---
title: "System::Net::Security"
second_title: Aspose.Slides C++ API 参考
description: 
type: docs
weight: 716
url: /zh/system.net.security/
---
## 类

| 类 | 描述 |
| --- | --- |
| [AuthenticatedStream](./authenticatedstream/) | 包含用于在流中传递凭证的方法。此类的对象应仅使用 [System::MakeObject()](../system/makeobject/) 函数进行分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [SslStream](./sslstream/) | 使用 SSL 协议对服务器进行身份验证并可选地对客户端进行身份验证的流。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [AuthenticationLevel](./authenticationlevel/) | 特定于 WebRequest 的身份验证标志。 |
| [SslPolicyErrors](./sslpolicyerrors/) | 枚举 SSL 的策略错误。 |
| [EncryptionPolicy](./encryptionpolicy/) | 枚举加密策略。 |
## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [RemoteCertificateValidationCallback](./remotecertificatevalidationcallback/) | 用于验证远程 SSL 证书的用户委托。 |
| [LocalCertificateSelectionCallback](./localcertificateselectioncallback/) | 用于选择本地 SSL 证书的用户委托。 |