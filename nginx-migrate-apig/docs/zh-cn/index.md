# 概述


### 场景描述
前端应用的`nginx` 配置如下：
```
location ^~/chat/ {
  proxy_pass http://example.com:8080/;
  proxy_set_header   Host     $host;
  proxy_set_header   X-Real-IP    $remote_addr;
}
```
访问 `localhost:8080/chat/` 以及 `localhost:8080/chat` 是同样的效果
迁移到api网关后需要支持同样的能力

### 应用场景


### 解决问题


## 架构


## 部署

## 使用
