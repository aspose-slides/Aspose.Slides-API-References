---
title: SslStream()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个新实例。
type: docs
weight: 326
url: /zh/system.net.security/sslstream/sslstream/
---
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>) 构造函数

构造一个新实例。

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream)
```


### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 用于发送和接收数据的流。 |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool) 构造函数

构造一个新实例。

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen)
```


### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 用于发送和接收数据的流。 |
| leaveInnerStreamOpen | **bool** | 如果为 true，关闭当前实例不会影响 'InnerStream'。 |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) 构造函数

构造一个新实例。

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback)
```


### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 用于发送和接收数据的流。 |
| leaveInnerStreamOpen | **bool** | 如果为 true，关闭当前实例不会影响 'InnerStream'。 |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | 用于验证远程方提供的证书的委托。 |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) 构造函数

构造一个新实例。

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback)
```


### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 用于发送和接收数据的流。 |
| leaveInnerStreamOpen | **bool** | 如果为 true，关闭当前实例不会影响 'InnerStream'。 |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | 用于验证远程方提供的证书的委托。 |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | 用于选择用于身份验证的证书的委托。 |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) 构造函数

构造一个新实例。

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback, EncryptionPolicy encryptionPolicy)
```


### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 用于发送和接收数据的流。 |
| leaveInnerStreamOpen | **bool** | 如果为 true，关闭当前实例不会影响 'InnerStream'。 |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | 用于验证远程方提供的证书的委托。 |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | 用于选择用于身份验证的证书的委托。 |
| encryptionPolicy | [EncryptionPolicy](../../encryptionpolicy/) | 加密策略。 |

## 另请参见

* 枚举 [EncryptionPolicy](../../encryptionpolicy/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* 类型定义 [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* 类 [Stream](../../../system.io/stream/)
* 类 [SslStream](../)
* 命名空间 [System::Net::Security](../../)
* 库 [Aspose.Slides](../../../)