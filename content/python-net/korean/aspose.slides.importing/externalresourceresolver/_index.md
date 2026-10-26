---
title: ExternalResourceResolver class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.importing/externalresourceresolver/
---
## ExternalResourceResolver 클래스

Callback 클래스는 Html, Svg 문서 가져오기 중 외부 리소스를 해결하는 데 사용됩니다.
이 리졸버를 사용하면 클라이언트가 제공한 HTML 또는 SVG 파일이 서버 소프트웨어가 로컬 또는 네트워크 파일을 획득하도록 만들어 취약점을 초래할 수 있습니다.
조심해서 사용하세요.
ExternalResourceResolver를 전혀 지정하지 않는 것이 권장됩니다(임베디드 객체만 읽힙니다) 또는 지정된 uri가 유효한지 검사하는 서브클래스를 생성하세요.

ExternalResourceResolver 타입은 다음 멤버를 노출합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ko/aspose.slides.importing/externalresourceresolver/__init__/#) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/ko/aspose.slides.importing/externalresourceresolver/resolve_uri/#str-str) | 기본 및 상대 URI에서 절대 URI를 해결합니다. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/ko/aspose.slides.importing/externalresourceresolver/get_entity/#str) | URI를 실제 리소스를 포함하는 객체에 매핑합니다. |

### 참고
* 모듈 [`aspose.slides.importing`](/slides/python-net/ko/aspose.slides.importing)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)