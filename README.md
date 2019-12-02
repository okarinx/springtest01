## 第一个Spring框架项目

##知识点
Cookie和Session Session类似银行账户，Cookie类似银行卡，有银行卡才能查到账户。浏览器相当于用户，服务器相当于银行。因为HTTP是无状态的，要让服务器记住状态，每次携带一张“银行卡”即可。

## 资料
Thymeleaf https://www.thymeleaf.org/

Spring文档 https://spring.io/guides

Controller那些 https://spring.io/guides/gs/serving-web-content/

参考网站 https://elasticsearch.cn/

Github OAuth https://developer.github.com/apps/building-oauth-apps/creating-an-oauth-app/
## 工具
Visual Diagram https://www.visual-paradigm.com/cn/

OkHTTP https://square.github.io/okhttp/

maven仓库 https://mvnrepository.com/

##脚本
```sql
create table USER
(
    ID           INTEGER auto_increment,
    ACCOUNT_ID   VARCHAR(100),
    NAME         VARCHAR(50),
    TOKEN        CHAR(36),
    GMT_CREATE   BIGINT,
    GMT_MODIFIED BIGINT,
    constraint USER_PK
        primary key (ID)
);
```