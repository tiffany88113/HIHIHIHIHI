# HIHIHIHIHI
nononono
product = {'1':'香蕉', '2':'蘋果', '3':'橘子', '4':'鳳梨', '5':'柳橙'}
cart = {}
print('可購買商品清單：1.香蕉,2.蘋果,3.橘子,4.鳳梨,5.柳橙')
while 1:
x = input('請輸入對應操作-1.添加商品,2.移除商品,q.離開,b.結帳: ')
if x == '1':
product_num = input('The new product number: ')
if product_num in product:
cart[product_num] = product[product_num]
print('添加商品成功！購物車現有商品 ', cart)
elif x == '2':
product_num = input('To delete product number: ')
if product_num in cart:
cart.pop(product_num, None)
print('移除商品成功！購物車現有商品 ', cart)
elif x == 'q':
break
elif x == 'b':
print('結帳完成！購買商品', cart)
break
else:
pass
