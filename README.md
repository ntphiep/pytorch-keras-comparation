# PyTorch Learning


## Autograd cơ bản

### torch.Tensor
- .require_grad(): enable luu trữ thong tin gradien, luu cac he so
- .grad()
- .grad_fn() luu ham so da su dung cho tensor
- .backward()




```python
x = torch.tensor(2.0, requires_grad=True)
x
# tensor(2., requires_grad=True)


y = torch.exp(x)
y
# tensor(7.3891, grad_fn=<ExpBackward0>)





```