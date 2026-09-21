---
title: DigitalSignature class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/digitalsignature/
---
## DigitalSignature 클래스

서명된 파일의 디지털 서명.

DigitalSignature 형식은 다음 멤버를 노출합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self, certificate)`](/slides/python-net/ko/aspose.slides/digitalsignature/__init__/#systemsecuritycryptographyx509certificatesx509certificate2) | 지정된 인증서를 사용하여 새 DigitalSignature 개체를 생성합니다. |
| [`__init__(self, file_path, password)`](/slides/python-net/ko/aspose.slides/digitalsignature/__init__/#str-str) | 지정된 인증서 파일 경로와 비밀번호를 사용하여 새 DigitalSignature 개체를 생성합니다. |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`certificate`](/slides/python-net/ko/aspose.slides/digitalsignature/certificate/) | 문서를 서명하는 데 사용된 인증서 개체.<br/>            읽기 전용 **System.Security.Cryptography.X509Certificates.X509Certificate2**. |
| [`is_valid`](/slides/python-net/ko/aspose.slides/digitalsignature/is_valid/) | 이 디지털 서명이 유효하고 문서가 변조되지 않은 경우, 이 값은 true가 됩니다.<br/>            읽기 전용 **bool**. |
| [`sign_time`](/slides/python-net/ko/aspose.slides/digitalsignature/sign_time/) | 문서가 서명된 시간.<br/>            읽기 전용 **System.DateTime**. |
| [`comments`](/slides/python-net/ko/aspose.slides/digitalsignature/comments/) | 서명의 목적.<br/>            읽기/쓰기 **str**. |


### 참고
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)