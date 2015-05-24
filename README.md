# CFHealth
减肥助手

##服务器接口文档
注册接口
名称  RegistServlet
参数  userName  String
      userPwd   String
      userNick  String
      
登陆接口
名称  LoginServlet
参数  userName  String 
      userPwd   String
返回  userNick  String
      userIcon  String
      
录入用户信息接口
名称  BodyDataRecordServlet
参数  userName  String
      height  int 
      weight  int
      armLength  int
      
获取用户信息接口
名称  BodyDataGetServlet
参数  userName  String
      height  int 
      weight  int
      armLength  int

发布运动圈信息接口
名称  SportCircleServlet
参数  userNick  String 
      userIcon  String
      message   String 
      image     String
      tagInfo   String
      prop      String
      
获取运动圈消息接口
名称  GetSportMessageServlet
参数  pageIndex int (1,2,3.....)
返回  userNick  String 
      userIcon  String
      message   String 
      image     String
      timeStamp long
      tagInfo   String
      prop      String  (一次最多10个)

获取用户运动数据接口
名称  GetSportDataServelt
参数  无
返回  {"step":[{"step":134 , "heat":1345},{..},{..},{..},{..},{..},{..},{..}] ,"fuwo":[{..},{..},{..},{..},{..},{..},{..}]}

图片上传接口
名称  ImageUploadServlet
参数  
返回  imageUrl  String


##服务器相关bug

##客户端相关bug
