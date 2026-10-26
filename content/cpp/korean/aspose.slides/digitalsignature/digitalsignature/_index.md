---
title: DigitalSignature()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 인증서로 새 DigitalSignature 객체를 생성합니다.
type: docs
weight: 66
url: /ko/aspose.slides/digitalsignature/digitalsignature/
---
## DigitalSignature::DigitalSignature(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>) 생성자

지정된 인증서로 새 [DigitalSignature](../) 객체를 생성합니다.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> certificate)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| certificate | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)\> | 프레젠테이션 서명에 사용할 인증서입니다. |

## DigitalSignature::DigitalSignature(System::String, System::String) 생성자

지정된 인증서 파일 경로와 비밀번호로 새 [DigitalSignature](../) 객체를 생성합니다.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::String filePath, System::String password)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | [System::String](../../../system/string/) | 인증서 파일 경로입니다. |
| password | [System::String](../../../system/string/) | 인증서에 접근하기 위해 필요한 비밀번호입니다. |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* 클래스 [DigitalSignature](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)