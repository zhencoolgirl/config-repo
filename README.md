# config-repo


**注意本主分支名称为——main**  
这两个是自己原本环境的配置项application.yml(可用),其他dev,prod,test版本不一定可用  
order-service.yml  
product-service.yml  

### 自动更新配置类,不需要重启的项目  
通过发送 POST 请求http://localhost:9090/actuator/refresh ,可以使用postman等工具
但是很多项目需要更新的时候,就很麻烦,Github 提供了一种 Webhook 的方式,但是需要环境是github可访问地址,像上面的本地地址就不适用
