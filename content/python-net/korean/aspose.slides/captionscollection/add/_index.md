---
title: add method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/captionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
컬렉션 끝에 WebVTT 폐쇄 캡션을 추가합니다.

### 반환

추가된 [`ICaptions`](/slides/python-net/ko/aspose.slides/icaptions) 인스턴스입니다.



```python
def add(self, label, file_path):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| label | **str** | 폐쇄 캡션의 레이블입니다. |
| file_path | **str** | WebVTT 파일의 경로입니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `file_path`가 `None`인 경우 발생합니다. |
| **RuntimeError(Proxy error(ArgumentException))** | `file_path`가 비어 있는 경우 발생합니다. |


## add(self, label, stream) {#str-iorawiobase}
스트림에서 컬렉션 끝에 WebVTT 폐쇄 캡션을 추가합니다.

### 반환

추가된 [`ICaptions`](/slides/python-net/ko/aspose.slides/icaptions) 인스턴스입니다.



```python
def add(self, label, stream):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| label | **str** | 폐쇄 캡션의 레이블입니다. |
| stream | **io.RawIOBase** | WebVTT 형식의 데이터를 포함하는 입력 스트림입니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `stream`이 `None`인 경우 발생합니다. |
| **RuntimeError(Proxy error(ArgumentException))** | 입력 데이터가 WebVTT 형식이 아닌 경우 발생합니다. |



### 참조
* 클래스 [`CaptionsCollection`](/slides/python-net/ko/aspose.slides/captionscollection)
* 클래스 [`ICaptions`](/slides/python-net/ko/aspose.slides/icaptions)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)