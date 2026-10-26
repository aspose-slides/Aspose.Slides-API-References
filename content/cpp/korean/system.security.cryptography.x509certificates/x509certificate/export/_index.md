---
title: Export()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 형식을 사용하여 현재 객체를 바이트 배열로 내보냅니다. 구현되지 않음.
type: docs
weight: 287
url: /ko/system.security.cryptography.x509certificates/x509certificate/export/
---
## X509Certificate::Export(X509ContentType) const 메서드


지정된 형식을 사용하여 현재 개체를 바이트 배열로 내보냅니다. 구현되지 않음.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::Export(X509ContentType content_type) const
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| content_type | [X509ContentType](../../x509contenttype/) | 출력 데이터를 형식화하는 방법을 지정합니다. |

### 반환값

현재 개체를 나타내는 바이트 배열입니다.

## X509Certificate::Export(X509ContentType, const SecureStringPtr\&) const 메서드


지정된 형식을 사용하여 현재 개체를 바이트 배열로 내보냅니다. 구현되지 않음.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::Export(X509ContentType content_type, const SecureStringPtr &password) const
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| content_type | [X509ContentType](../../x509contenttype/) | 출력 데이터를 형식화하는 방법을 지정합니다. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 인증서 데이터에 액세스하기 위해 필요한 비밀번호입니다. |

### 반환값

현재 개체를 나타내는 바이트 배열입니다.

## X509Certificate::Export(X509ContentType, const String\&) const 메서드


지정된 형식을 사용하여 현재 개체를 바이트 배열로 내보냅니다. 구현되지 않음.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::Export(X509ContentType content_type, const String &password) const
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| content_type | [X509ContentType](../../x509contenttype/) | 출력 데이터를 형식화하는 방법을 지정합니다. |
| password | const [String](../../../system/string/)\& | 인증서 데이터에 액세스하기 위해 필요한 비밀번호입니다. |

### 반환값

현재 개체를 나타내는 바이트 배열입니다.

## 참조

* 열거형 [X509ContentType](../../x509contenttype/)
* 타입정의 [ByteArrayPtr](../../../system/bytearrayptr/)
* 타입정의 [SecureStringPtr](../../../system.security/securestringptr/)
* 클래스 [X509Certificate](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Security::Cryptography::X509Certificates](../../)
* 라이브러리 [Aspose.Slides](../../../)