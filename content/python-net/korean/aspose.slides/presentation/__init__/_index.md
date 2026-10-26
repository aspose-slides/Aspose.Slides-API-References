---
title: Presentation constructor
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/presentation/__init__/
weight: 10
---
## __init__(self) {#}
이 생성자는 새로운 프레젠테이션을 처음부터 생성합니다.
            생성된 프레젠테이션에는 빈 슬라이드가 하나 있습니다.


```python
def __init__(self):
    ...
```



## __init__(self, load_options) {#loadoptions}
이 생성자는 새로운 프레젠테이션을 처음부터 생성합니다.
            생성된 프레젠테이션에는 빈 슬라이드가 하나 있습니다.


```python
def __init__(self, load_options):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| load_options | [`LoadOptions`](/slides/python-net/ko/aspose.slides/loadoptions) | 추가 로드 옵션. |


## __init__(self, stream) {#iorawiobase}
이 생성자는 기존 프레젠테이션을 읽기 위한 주요 메커니즘입니다.


```python
def __init__(self, stream):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 입력 스트림. |


## __init__(self, file) {#str}
이 생성자는 프레젠테이션 내용을 읽어들이는 소스 파일 경로를 가져옵니다.


```python
def __init__(self, file):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file | **str** | 입력 파일. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 입력 파일의 길이가 0인 경우 발생합니다. |


## __init__(self, stream, load_options) {#iorawiobase-loadoptions}
이 생성자는 기존 프레젠테이션을 읽기 위한 주요 메커니즘입니다.


```python
def __init__(self, stream, load_options):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 입력 스트림. |
| load_options | [`LoadOptions`](/slides/python-net/ko/aspose.slides/loadoptions) | 추가 로드 옵션. |


## __init__(self, file, load_options) {#str-loadoptions}
이 생성자는 프레젠테이션 내용을 읽어들이는 소스 파일 경로를 가져옵니다.


```python
def __init__(self, file, load_options):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file | **str** | 입력 파일. |
| load_options | [`LoadOptions`](/slides/python-net/ko/aspose.slides/loadoptions) | 추가 로드 옵션. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 입력 파일의 길이가 0인 경우 발생합니다. |



### 참고
* 클래스 [`LoadOptions`](/slides/python-net/ko/aspose.slides/loadoptions)
* 클래스 [`Presentation`](/slides/python-net/ko/aspose.slides/presentation)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)