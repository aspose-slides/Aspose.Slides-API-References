---
title: insert_from_html method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/slidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

### 반환값

Added slides



```python
def insert_from_html(self, index, html_text):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | 삽입 위치. |
| html_text | **str** | 추가할 HTML. |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

### 반환값

Added slides



```python
def insert_from_html(self, index, html_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | 삽입 위치. |
| html_stream | **io.RawIOBase** | HTML 파일의 소스로 사용될 스트림 객체. |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

### 반환값

Added slides



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | 삽입 위치. |
| html_text | **str** | 추가할 HTML. |
| use_slide_with_index_as_start | **bool** | 이 플래그는 삽입 시작 방식을 결정합니다: 새 슬라이드에서 시작하거나 지정된 인덱스의 슬라이드에서 시작합니다.<br/><br/>            **true**인 경우, 데이터 삽입은 지정된 인덱스의 슬라이드의 빈 공간에서 시작됩니다.<br/><br/>            **false**인 경우, 데이터가 생성된 슬라이드에 추가됩니다. |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

### 반환값

Added slides



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | 삽입 위치. |
| html_stream | **io.RawIOBase** | HTML 파일의 소스로 사용될 스트림 객체. |
| use_slide_with_index_as_start | **bool** | 이 플래그는 삽입 시작 방식을 결정합니다: 새 슬라이드에서 시작하거나 지정된 인덱스의 슬라이드에서 시작합니다.<br/><br/>            **true**인 경우, 데이터 삽입은 지정된 인덱스의 슬라이드의 빈 공간에서 시작됩니다.<br/><br/>            **false**인 경우, 데이터가 생성된 슬라이드에 추가됩니다. |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

### 반환값

Added slides.



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | 삽입 위치. |
| html_text | **str** | 추가할 HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ko/aspose.slides.importing/iexternalresourceresolver) | 외부 객체를 가져오는 데 사용되는 콜백 객체입니다. 이 매개변수가 None이면 모든 외부 객체가 무시됩니다. |
| uri | **str** | 지정된 HTML의 URI입니다. 상대 링크를 해결하는 데 사용됩니다. |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

### 반환값

Added slides.



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | 삽입 위치. |
| html_stream | **io.RawIOBase** | HTML 파일의 소스로 사용될 스트림 객체. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ko/aspose.slides.importing/iexternalresourceresolver) | 외부 객체를 가져오는 데 사용되는 콜백 객체입니다. 이 매개변수가 None이면 모든 외부 객체가 무시됩니다. |
| uri | **str** | 지정된 HTML의 URI입니다. 상대 링크를 해결하는 데 사용됩니다. |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

### 반환값

Added slides.



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | 삽입 위치. |
| html_text | **str** | 추가할 HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ko/aspose.slides.importing/iexternalresourceresolver) | 외부 객체를 가져오는 데 사용되는 콜백 객체입니다. 이 매개변수가 None이면 모든 외부 객체가 무시됩니다. |
| uri | **str** | 지정된 HTML의 URI입니다. 상대 링크를 해결하는 데 사용됩니다. |
| use_slide_with_index_as_start | **bool** | 이 플래그는 삽입 시작 방식을 결정합니다: 새 슬라이드에서 시작하거나 지정된 인덱스의 슬라이드에서 시작합니다.<br/><br/>            **true**인 경우, 데이터 삽입은 지정된 인덱스의 슬라이드의 빈 공간에서 시작됩니다.<br/><br/>            **false**인 경우, 데이터가 생성된 슬라이드에 추가됩니다. |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다.

### 반환값

Added slides.



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | 삽입 위치. |
| html_stream | **io.RawIOBase** | HTML 파일의 소스로 사용될 스트림 객체. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ko/aspose.slides.importing/iexternalresourceresolver) | 외부 객체를 가져오는 데 사용되는 콜백 객체입니다. 이 매개변수가 None이면 모든 외부 객체가 무시됩니다. |
| uri | **str** | 지정된 HTML의 URI입니다. 상대 링크를 해결하는 데 사용됩니다. |
| use_slide_with_index_as_start | **bool** | 이 플래그는 삽입 시작 방식을 결정합니다: 새 슬라이드에서 시작하거나 지정된 인덱스의 슬라이드에서 시작합니다.<br/><br/>            **true**인 경우, 데이터 삽입은 지정된 인덱스의 슬라이드의 빈 공간에서 시작됩니다.<br/><br/>            **false**인 경우, 데이터가 생성된 슬라이드에 추가됩니다. |



### 참조
* 클래스 [`IExternalResourceResolver`](/slides/python-net/ko/aspose.slides.importing/iexternalresourceresolver)
* 클래스 [`SlideCollection`](/slides/python-net/ko/aspose.slides/slidecollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)