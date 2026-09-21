---
title: add_from_html method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/slidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다.

### 반환값

추가된 슬라이드



```python
def add_from_html(self, html_text):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| html_text | **str** | 추가할 HTML. |


## add_from_html(self, html_stream) {#iorawiobase}
HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다.

### 반환값

추가된 슬라이드



```python
def add_from_html(self, html_stream):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | HTML 파일의 소스로 사용되는 Stream 객체. |


## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다.

### 반환값

추가된 슬라이드.



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| html_text | **str** | 추가할 HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ko/aspose.slides.importing/iexternalresourceresolver) | 외부 객체를 가져오는 데 사용되는 콜백 객체입니다. 이 매개변수가 None이면 모든 외부 객체가 무시됩니다. |
| uri | **str** | 지정된 HTML의 URI입니다. 상대 링크를 해결하는 데 사용됩니다. |


## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다.

### 반환값

추가된 슬라이드.



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | HTML 파일의 소스로 사용되는 Stream 객체. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ko/aspose.slides.importing/iexternalresourceresolver) | 외부 객체를 가져오는 데 사용되는 콜백 객체입니다. 이 매개변수가 None이면 모든 외부 객체가 무시됩니다. |
| uri | **str** | 지정된 HTML의 URI입니다. 상대 링크를 해결하는 데 사용됩니다. |



### 참고
* 클래스 [`IExternalResourceResolver`](/slides/python-net/ko/aspose.slides.importing/iexternalresourceresolver)
* 클래스 [`SlideCollection`](/slides/python-net/ko/aspose.slides/slidecollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)