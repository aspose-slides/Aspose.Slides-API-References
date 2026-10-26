---
title: SslStream()
second_title: Aspose.Slides for C++ API 參考
description: 建立新的實例。
type: docs
weight: 326
url: /zh-hant/system.net.security/sslstream/sslstream/
---
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>) 建構函式


建立新的實例。

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 用於傳送和接收資料的串流。 |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool) 建構函式


建立新的實例。

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 用於傳送和接收資料的串流。 |
| leaveInnerStreamOpen | **bool** | 如果為 true，關閉目前實例不會影響 'InnerStream'。 |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) 建構函式


建立新的實例。

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 用於傳送和接收資料的串流。 |
| leaveInnerStreamOpen | **bool** | 如果為 true，關閉目前實例不會影響 'InnerStream'。 |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | 用於驗證遠端提供之憑證的委派。 |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) 建構函式


建立新的實例。

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 用於傳送和接收資料的串流。 |
| leaveInnerStreamOpen | **bool** | 如果為 true，關閉目前實例不會影響 'InnerStream'。 |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | 用於驗證遠端提供之憑證的委派。 |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | 用於選取用於驗證的憑證的委派。 |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) 建構函式


建立新的實例。

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback, EncryptionPolicy encryptionPolicy)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 用於傳送和接收資料的串流。 |
| leaveInnerStreamOpen | **bool** | 如果為 true，關閉目前實例不會影響 'InnerStream'。 |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | 用於驗證遠端提供之憑證的委派。 |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | 用於選取用於驗證的憑證的委派。 |
| encryptionPolicy | [EncryptionPolicy](../../encryptionpolicy/) | 加密政策。 |

## 另請參閱

* 列舉 [EncryptionPolicy](../../encryptionpolicy/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 型別別名 [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* 型別別名 [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* 類別 [Stream](../../../system.io/stream/)
* 類別 [SslStream](../)
* 命名空間 [System::Net::Security](../../)
* 函式庫 [Aspose.Slides](../../../)