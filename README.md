# wx-miniprogram-learning
# 记录下小程序的知识点<br>
## 1. res =>可以理解为function(res)  
>> res =>里可以直接使用this.setData()  
function(res)里，this的对象可能发生改变，需要提前保存this  
