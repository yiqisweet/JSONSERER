# JSONSERER
本地JSON服务


<br>

## 访问方法

借助postman做尝试

//获取所有用户信息
http://localhost:3000/users

//获取用户id为1的信息
http://localhost:3000/users/1,

//获取公司的所有信息
http://localhost:3000/companies

//获取公司id为1的信息
http://localhost:3000/companies/1

//获取user里公司id为1的用户信息
http://localhost:3000/companies/1/users

//根据公司名字获取信息
http://localhost:3000/companies?name=BaiDu

//根据多个公司名字获取信息
http://localhost:3000/companies?name=BaiDu&name=Sina

//获取一页中，只有两条数据的
http://localhost:3000/companies?_page=1&_limit=2

//倒序排序    正序是（升序） asc  倒序（降序） desc
http://localhost:3000/companies?_sort=name&_order=desc

//获取年龄是30及30以上的用户信息
http://localhost:3000/users?age_gte=35

//获取年龄是30和40之间的用户信息
http://localhost:3000/users?age_gte=35&age_lte=40

//搜索用户信息，模糊搜索
http://localhost:3000/users?q=r