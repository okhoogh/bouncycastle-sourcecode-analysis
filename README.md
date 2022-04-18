# bouncycastle-sourcecode-analysis

## 项目介绍

对开源的加解密第三方库[BouncyCastle](https://www.bouncycastle.org/)源码进行分析，基于[bcprov-jdk18on-171](https://www.bouncycastle.org/download/bcprov-jdk18on-171.zip)版本。

## 源码结构

```
├── org.bouncycastle
    ├── asn1					# 密码算法涉及的数据结构及编码
    ├── crypto					# 密码算法
    ├── i18n					# 国际化
    ├── iana					# 互联网数字分配机构(给互联网标准下的密码算法标号)
    ├── internal.asn1			        # 互联网标准中定义的数据结构
    ├── jcajce					# Java密码学体系结构及扩展包
    ├── jce					# 使用Java密码学扩展包的工具类
    ├── math					# 数学相关
    ├── ocsp					# 在线证书状态协议(空)
    ├── pqc					# 后量子密码学
    ├── util					# 操作数据的工具类
    ├── x509					# x509证书相关
    └── LICENSE					# 许可证
```
