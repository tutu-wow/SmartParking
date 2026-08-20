# SmartParking
停车小程序 亮点：车牌OCR智能识别、地图api、Echarts图形化分析、智能车位预约、自动计费与订单处理；
所有源码均本人开发，项目是前后端分离的，所有的项目都具备了完整的业务逻辑，不仅仅局限于基础的增删改查（CRUD）操作，系统亮点众多。

本文注重于计算机毕业设计选题指导，列出题目均有源码， 大家可以去【公众号】(毕业终点站)获取或者加我【qq】(2112698948)提意见(别忘记Star哟)。备注：git

声明：仅用于学习使用，请勿用于任何商业行为！

1.系统非商用，非开源，非无偿。

2.由本人开发，如需源码，请联系以下方式，qq:2112698948。

3.项目有很多，并未全部上传，如果未找到想要的，可直接咨询。


<font style="color:#117cee;">🎈</font><font style="color:#117cee;">系统亮点：车牌OCR智能识别、地图api、Echarts图形化分析、智能车位预约、自动计费与订单处理；</font>

# <font style="color:#48b378;">一.系统开发工具与环境搭建</font>
## <font style="color:#262626;">1.系统设计开发工具</font>
<font style="color:#262626;">后端使用Java编程语言的Spring boot框架</font>  
<font style="color:#262626;">项目架构：B/S架构</font>  
<font style="color:#262626;">运行环境：win10/win11、jdk17</font>



<font style="color:#48b378;">小程序：</font>

<font style="color:#262626;">技术：Uniapp；UI库：ColorUI； </font>

<font style="color:#262626;">开发工具：HBuilderX；</font>

---

<font style="color:#48b378;">前端：</font>  
<font style="color:#262626;">技术：框架Vue3 ；UI库：Element-Plus；</font>  
<font style="color:#262626;">开发工具：Visual Studio Code；</font>

---

<font style="color:#48b378;">后端:</font>  
<font style="color:#262626;">技术：Java语言、mybatis-plus、Spring boot框架；</font>  
<font style="color:#262626;">开发工具：IDEA 2025版本；</font>

---

<font style="color:#48b378;">数据库：</font>  
<font style="color:#262626;">数据库：mysql5.7/8.0 </font>  
<font style="color:#262626;">数据库工具：Navicat12版本；</font>

---

# <font style="color:#48b378;">二.系统实现（部分截图）</font>
## 2.1 用户
### 2.1.1 首页
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1787217258868-086c6b9b-748e-443b-9ea8-e32427a82c8d.png)

### 2.1.2 停车订单
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1787217256480-6c0bc564-39d9-4db2-8bb4-fd976d25ff02.png)

### 2.1.3 月卡管理
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1787217256504-ac789608-4e2d-4022-86a7-1cf20d3e5b53.png)

### 2.1.4 车位预约
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1787217256512-f42f042d-dff8-4c6e-8554-4ed5d05eee75.png)

### 2.1.5 个人中心
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1787217256477-8c718fcf-1d3f-459b-9ea6-c8e58acc5795.png)

## 2.2 管理员
### 2.2.1 数据分析
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1787217258439-31c7beff-0148-43e6-a042-c517c80ae090.png)

### 2.2.2 停车场列表
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1787217260871-71ff9073-c19c-4b8e-94a3-9e0d6b223b7b.png)

### 2.2.3 车位管理
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1787217261036-05682459-59eb-4ea0-9ea4-77c3e674b53e.png)

### 2.2.4 车位可视化
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1787217260828-b6a5465d-56d9-4e35-896c-37a1669617cf.png)

### 2.2.5 计费标准
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1787217261021-2bf9434f-e237-4e97-960c-6e6a76a8e266.png)

### 2.2.6 车辆列表
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1787217261156-5ca4a5db-09e2-42fc-8ead-74804c5edb17.png)

### 2.2.7 进出识别
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1787217261619-3d133d5c-d7dc-4f30-84cd-c1c22ce895db.png)

### 2.2.8 停车记录
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1787217261721-5caeb459-9122-491e-b4e7-f0bf8c99bd89.png)

### 2.2.9 订单数据分析
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1787217261765-24ca19e4-e828-46df-b421-c5c8d385d6e2.png)

### 2.2.10 月卡管理
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1787217261943-8ac82e95-5ef8-430c-b9b5-4ebfbc27e9f0.png)

### 2.2.11 优惠券管理
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1787217262018-99073dea-d4b6-4781-827c-63871caa7799.png)

### 2.2.12 意见反馈
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1787217262655-cafb6586-31d3-4312-947c-9ed671eb7012.png)

# <font style="color:#48b378;">三.数据库截图</font>
16张

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1787217262324-7856404f-6ce7-44f3-833e-a86b2d5dba5e.png)

