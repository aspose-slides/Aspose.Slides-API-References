---
title: SvgImage constructor
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/svgimage/__init__/
weight: 10
---
## __init__(self, data) {#bytes}
새 SvgImage 객체를 생성합니다.

```python
def __init__(self, data):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| data | **bytes** | Svg 데이터. |


## __init__(self, svg_content) {#str}
새 SvgImage 객체를 생성합니다.

```python
def __init__(self, svg_content):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| svg_content | **str** | Svg 내용. |


## __init__(self, stream) {#iorawiobase}
새 SvgImage 객체를 생성합니다.

```python
def __init__(self, stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| stream | **io.RawIOBase** | Svg 스트림. |


## __init__(self, data, external_res_resolver, base_uri) {#bytes-asposeslidesimportingiexternalresourceresolver-str}
새 SvgImage 객체를 생성합니다.

```python
def __init__(self, data, external_res_resolver, base_uri):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| data | **bytes** | Svg 데이터. |
| external_res_resolver | [`IExternalResourceResolver`](/slides/python-net/ko/aspose.slides.importing/iexternalresourceresolver) | 외부 객체를 가져오는 콜백 객체입니다. 이 매개변수가 None이면 모든 외부 객체가 무시됩니다. |
| base_uri | **str** | 지정된 Svg의 기본 URI입니다. 상대 링크를 해결하는 데 사용됩니다. |


## __init__(self, svg_content, external_res_resolver, base_uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
새 SvgImage 객체를 생성합니다.

```python
def __init__(self, svg_content, external_res_resolver, base_uri):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| svg_content | **str** | Svg 내용. |
| external_res_resolver | [`IExternalResourceResolver`](/slides/python-net/ko/aspose.slides.importing/iexternalresourceresolver) | 외부 객체를 가져오는 콜백 객체입니다. 이 매개변수가 None이면 모든 외부 객체가 무시됩니다. |
| base_uri | **str** | 지정된 Svg의 기본 URI입니다. 상대 링크를 해결하는 데 사용됩니다. |


## __init__(self, stream, external_res_resolver, base_uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
새 SvgImage 객체를 생성합니다.

```python
def __init__(self, stream, external_res_resolver, base_uri):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| stream | **io.RawIOBase** | Svg 스트림. |
| external_res_resolver | [`IExternalResourceResolver`](/slides/python-net/ko/aspose.slides.importing/iexternalresourceresolver) | 외부 객체를 가져오는 콜백 객체입니다. 이 매개변수가 None이면 모든 외부 객체가 무시됩니다. |
| base_uri | **str** | 지정된 Svg의 기본 URI입니다. 상대 링크를 해결하는 데 사용됩니다. |



### 참고
* 클래스 [`IExternalResourceResolver`](/slides/python-net/ko/aspose.slides.importing/iexternalresourceresolver)
* 클래스 [`SvgImage`](/slides/python-net/ko/aspose.slides/svgimage)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)