---
title: GetCertContentType()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 바이트 배열에 포함된 인증서의 유형을 가져옵니다.
type: docs
weight: 391
url: /ko/system.security.cryptography.x509certificates/x509certificate2/getcertcontenttype/
---
## X509Certificate2::GetCertContentType(const ByteArrayPtr\&) 메서드

지정된 바이트 배열에 포함된 인증서의 유형을 가져옵니다.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const ByteArrayPtr &raw_data)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 인증서 데이터. |

### 반환 값

X.509 인증서 유형.

## X509Certificate2::GetCertContentType(const String\&) 메서드

지정된 파일에 포함된 인증서의 유형을 가져옵니다.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const String &filename)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 인증서 파일 이름. |

### 반환 값

X.509 인증서 유형.

## 참고

* 열거형 [X509ContentType](../../x509contenttype/)
* 타입 정의 [ByteArrayPtr](../../../system/bytearrayptr/)
* 클래스 [X509Certificate2](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Security::Cryptography::X509Certificates](../../)
* 라이브러리 [Aspose.Slides](../../../)