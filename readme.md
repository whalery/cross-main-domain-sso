# cross-main-domain-sso
基于 p3p 协议的跨一级域单点登录-php版
跨二级以上的域只需要session共享 + 设置session cookie的 domian 域为一级域名即可
但跨一级域时就需要使用 cookie 共享技术了，让 A 站点 和 B 站点设置相同 session cookie
