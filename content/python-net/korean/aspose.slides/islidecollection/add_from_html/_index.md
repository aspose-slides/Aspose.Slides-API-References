---
title: add_from_html method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/islidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
HTML 텍스트에서 슬라이드를 만들고 컬렉션 끝에 추가합니다.

### 반환

추가된 슬라이드



```python
def add_from_html(self, html_text):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| html_text | **str** | 추가할 Html. |


## add_from_html(self, html_stream) {#iorawiobase}
HTML 텍스트에서 슬라이드를 만들고 컬렉션 끝에 추가합니다.

### 반환

추가된 슬라이드



```python
def add_from_html(self, html_stream):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | HTML 파일의 소스로 사용될 Stream 객체. |


## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
HTML 텍스트에서 슬라이드를 만들고 컬렉션 끝에 추가합니다.

### 반환

추가된 슬라이드.



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| html_text | **str** | 추가할 Html. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ko/aspose.slides.importing/iexternalresourceresolver) | 외부 객체를 가져오는 데 사용되는 콜백 객체. 이 매개변수가 None이면 모든 외부 객체가 무시됩니다. |
| uri | **str** | 지정된 HTML의 URI. 상대 링크를 확인하는 데 사용됩니다. |


## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
HTML 텍스트에서 슬라이드를 만들고 컬렉션 끝에 추가합니다.

### 반환

추가된 슬라이드.



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | HTML 파일의 소스로 사용될 Stream 객체. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ko/aspose.slides.importing/iexternalresourceresolver) | 외부 객체를 가져오는 데 사용되는 콜백 객체. 이 매개변수가 None이면 모든 외부 객체가 무시됩니다. |
| uri | **str** | 지정된 HTML의 URI. 상대 링크를 확인하는 데 사용됩니다. |



### 참고
* 클래스 [`IExternalResourceResolver`](/slides/python-net/ko/aspose.slides.importing/iexternalresourceresolver)
* 클래스 [`ISlideCollection`](/slides/python-net/ko/aspose.slides/islidecollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)