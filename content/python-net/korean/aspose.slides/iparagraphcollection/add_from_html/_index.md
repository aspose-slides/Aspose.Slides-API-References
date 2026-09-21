---
title: add_from_html method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/iparagraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
지정된 html 문자열에서 텍스트를 컬렉션에 추가합니다.

```python
def add_from_html(self, text):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| text | **str** | HTML 텍스트. |

## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
지정된 html 문자열에서 텍스트를 컬렉션에 추가합니다.

```python
def add_from_html(self, text, resolver, uri):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| text | **str** | HTML 텍스트. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ko/aspose.slides.importing/iexternalresourceresolver) | URI를 해석하고 참조된 객체를 가져오는 Resolver 콜백 객체. |
| uri | **str** | HTML 문서를 추가하기 위한 URI. 상대 링크 해석에 사용됩니다. |

### 비고

resolver를 지정하면 잠재적인 취약점이 발생할 수 있습니다. 주의해서 사용하십시오.

### 참고
* 클래스 [`IExternalResourceResolver`](/slides/python-net/ko/aspose.slides.importing/iexternalresourceresolver)
* 클래스 [`IParagraphCollection`](/slides/python-net/ko/aspose.slides/iparagraphcollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)