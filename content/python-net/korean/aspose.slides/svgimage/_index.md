---
title: SvgImage class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/svgimage/
---
## SvgImage 클래스

SVG 이미지를 나타냅니다.

SvgImage 형식은 다음 멤버를 노출합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self, data)`](/slides/python-net/ko/aspose.slides/svgimage/__init__/#bytes) | 새 SvgImage 객체를 만듭니다. |
| [`__init__(self, svg_content)`](/slides/python-net/ko/aspose.slides/svgimage/__init__/#str) | 새 SvgImage 객체를 만듭니다. |
| [`__init__(self, stream)`](/slides/python-net/ko/aspose.slides/svgimage/__init__/#iorawiobase) | 새 SvgImage 객체를 만듭니다. |
| [`__init__(self, data, external_res_resolver, base_uri)`](/slides/python-net/ko/aspose.slides/svgimage/__init__/#bytes-asposeslidesimportingiexternalresourceresolver-str) | 새 SvgImage 객체를 만듭니다. |
| [`__init__(self, svg_content, external_res_resolver, base_uri)`](/slides/python-net/ko/aspose.slides/svgimage/__init__/#str-asposeslidesimportingiexternalresourceresolver-str) | 새 SvgImage 객체를 만듭니다. |
| [`__init__(self, stream, external_res_resolver, base_uri)`](/slides/python-net/ko/aspose.slides/svgimage/__init__/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | 새 SvgImage 객체를 만듭니다. |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`svg_data`](/slides/python-net/ko/aspose.slides/svgimage/svg_data/) | SVG 데이터를 반환합니다.<br/>            읽기 전용 **int**[]. |
| [`external_resource_resolver`](/slides/python-net/ko/aspose.slides/svgimage/external_resource_resolver/) | Svg 문서 가져오기 중 외부 리소스를 해결하는 데 사용되는 콜백 인터페이스를 반환합니다.<br/>            읽기 전용 **IExternalResourceResolver**. |
| [`base_uri`](/slides/python-net/ko/aspose.slides/svgimage/base_uri/) | 지정된 Svg의 기본 URI를 반환합니다. 상대 링크를 해결하는 데 사용됩니다.<br/>            읽기 전용 **str**. |
| [`svg_content`](/slides/python-net/ko/aspose.slides/svgimage/svg_content/) | SVG 콘텐츠를 반환합니다.<br/>            읽기 전용 **str**. |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`write_as_emf(self, stream)`](/slides/python-net/ko/aspose.slides/svgimage/write_as_emf/#iorawiobase) | SVG 이미지를 EMF 파일로 저장합니다. |

### 참고
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)