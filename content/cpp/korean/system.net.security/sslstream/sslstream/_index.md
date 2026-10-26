---
title: SslStream()
second_title: Aspose.Slides for C++ API 참조
description: 새 인스턴스를 생성합니다.
type: docs
weight: 326
url: /ko/system.net.security/sslstream/sslstream/
---
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 데이터를 송수신하는 데 사용되는 스트림입니다. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 데이터를 송수신하는 데 사용되는 스트림입니다. |
| leaveInnerStreamOpen | **bool** | true이면 현재 인스턴스를 닫아도 'InnerStream'에 영향을 주지 않습니다. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 데이터를 송수신하는 데 사용되는 스트림입니다. |
| leaveInnerStreamOpen | **bool** | true이면 현재 인스턴스를 닫아도 'InnerStream'에 영향을 주지 않습니다. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | 원격 파티가 제공한 인증서를 검증하는 데 사용되는 대리자입니다. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 데이터를 송수신하는 데 사용되는 스트림입니다. |
| leaveInnerStreamOpen | **bool** | true이면 현재 인스턴스를 닫아도 'InnerStream'에 영향을 주지 않습니다. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | 원격 파티가 제공한 인증서를 검증하는 데 사용되는 대리자입니다. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | 인증에 사용되는 인증서를 선택하는 데 사용되는 대리자입니다. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback, EncryptionPolicy encryptionPolicy)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 데이터를 송수신하는 데 사용되는 스트림입니다. |
| leaveInnerStreamOpen | **bool** | true이면 현재 인스턴스를 닫아도 'InnerStream'에 영향을 주지 않습니다. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | 원격 파티가 제공한 인증서를 검증하는 데 사용되는 대리자입니다. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | 인증에 사용되는 인증서를 선택하는 데 사용되는 대리자입니다. |
| encryptionPolicy | [EncryptionPolicy](../../encryptionpolicy/) | 암호화 정책입니다. |

## 참고

* Enum [EncryptionPolicy](../../encryptionpolicy/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Typedef [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [SslStream](../)
* 네임스페이스 [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)