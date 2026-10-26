---
title: add method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/icaptionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
컬렉션의 끝에 WebVTT 닫힌 캡션을 추가합니다.

### 반환

추가된 [`ICaptions`](/slides/python-net/ko/aspose.slides/icaptions) 인스턴스.



```python
def add(self, label, file_path):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| label | **str** | The label of the closed captions. |
| file_path | **str** | The path to the WebVTT file. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `file_path`가 `None`인 경우 발생합니다. |
| **RuntimeError(Proxy error(ArgumentException))** | `file_path`가 비어 있는 경우 발생합니다. |


## add(self, label, stream) {#str-iorawiobase}
스트림에서 컬렉션의 끝에 WebVTT 닫힌 캡션을 추가합니다.

### 반환

추가된 [`ICaptions`](/slides/python-net/ko/aspose.slides/icaptions) 인스턴스.



```python
def add(self, label, stream):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| label | **str** | The label of the closed captions. |
| stream | **io.RawIOBase** | The input stream containing data in WebVTT format. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `stream`이 `None`인 경우 발생합니다. |
| **RuntimeError(Proxy error(ArgumentException))** | 입력 데이터가 WebVTT 형식이 아닌 경우 발생합니다. |



### 참고
* 클래스 [`ICaptions`](/slides/python-net/ko/aspose.slides/icaptions)
* 클래스 [`ICaptionsCollection`](/slides/python-net/ko/aspose.slides/icaptionscollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)