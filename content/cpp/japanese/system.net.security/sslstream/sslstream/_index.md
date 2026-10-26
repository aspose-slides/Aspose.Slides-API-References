---
title: SslStream()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいインスタンスを作成します。
type: docs
weight: 326
url: /ja/system.net.security/sslstream/sslstream/
---
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>) コンストラクター


新しいインスタンスを作成します。

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | データの送受信に使用されるストリームです。 |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool) コンストラクター


新しいインスタンスを作成します。

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | データの送受信に使用されるストリームです。 |
| leaveInnerStreamOpen | **bool** | true の場合、現在のインスタンスを閉じても 'InnerStream' には影響しません。 |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) コンストラクター


新しいインスタンスを作成します。

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | データの送受信に使用されるストリームです。 |
| leaveInnerStreamOpen | **bool** | true の場合、現在のインスタンスを閉じても 'InnerStream' には影響しません。 |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | リモート側が提供する証明書を検証するために使用されるデリゲートです。 |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) コンストラクター


新しいインスタンスを作成します。

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | データの送受信に使用されるストリームです。 |
| leaveInnerStreamOpen | **bool** | true の場合、現在のインスタンスを閉じても 'InnerStream' には影響しません。 |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | リモート側が提供する証明書を検証するために使用されるデリゲートです。 |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | 認証に使用される証明書を選択するために使用されるデリゲートです。 |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) コンストラクター


新しいインスタンスを作成します。

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback, EncryptionPolicy encryptionPolicy)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | データの送受信に使用されるストリームです。 |
| leaveInnerStreamOpen | **bool** | true の場合、現在のインスタンスを閉じても 'InnerStream' には影響しません。 |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | リモート側が提供する証明書を検証するために使用されるデリゲートです。 |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | 認証に使用される証明書を選択するために使用されるデリゲートです。 |
| encryptionPolicy | [EncryptionPolicy](../../encryptionpolicy/) | 暗号化ポリシーです。 |

## 参照

* 列挙体 [EncryptionPolicy](../../encryptionpolicy/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* 型定義 [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* クラス [Stream](../../../system.io/stream/)
* クラス [SslStream](../)
* 名前空間 [System::Net::Security](../../)
* ライブラリ [Aspose.Slides](../../../)