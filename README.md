# Java FileCloud (示例)

这是一个最小可运行的 Spring Boot 网盘示例，包含：
- 用户注册/登录（Spring Security + H2 内存数据库）
- 文件上传/下载
- 在线查看图片与视频（浏览器直接请求 /file/{id}/view）
- 简单的 Thymeleaf 前端

运行:
1. 需要 JDK 17+ 与 Maven
2. 在项目根目录运行 `mvn spring-boot:run`
3. 访问 http://localhost:8080

注意:
- 这是演示项目，不建议用于生产环境（安全性、存储策略需增强）
