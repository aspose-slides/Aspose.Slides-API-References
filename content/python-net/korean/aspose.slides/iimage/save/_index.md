---
title: save method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/iimage/save/
weight: 10
---
## save(self, filename) {#str}
이미지를 파일에 저장합니다.


```python
def save(self, filename):
    ...
```


| 매개변수 | 타입 | 설명 |
| :- | :- | :- |
| filename | **str** | 이미지가 저장될 파일의 경로. |


## save(self, filename, format) {#str-imageformat}
이미지를 지정된 형식으로 파일에 저장합니다.


```python
def save(self, filename, format):
    ...
```


| 매개변수 | 타입 | 설명 |
| :- | :- | :- |
| filename | **str** | 이미지가 저장될 파일의 경로. |
| format | [`ImageFormat`](/slides/python-net/ko/aspose.slides/imageformat) | 이미지 형식. |


## save(self, stream, format) {#iorawiobase-imageformat}
이미지를 지정된 형식으로 스트림에 저장합니다.


```python
def save(self, stream, format):
    ...
```


| 매개변수 | 타입 | 설명 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 이미지가 저장될 스트림. |
| format | [`ImageFormat`](/slides/python-net/ko/aspose.slides/imageformat) | 이미지 형식. |


## save(self, filename, format, quality) {#str-imageformat-int}
이미지를 지정된 형식과 품질로 파일에 저장합니다.


```python
def save(self, filename, format, quality):
    ...
```


| 매개변수 | 타입 | 설명 |
| :- | :- | :- |
| filename | **str** | 이미지가 저장될 파일의 경로. |
| format | [`ImageFormat`](/slides/python-net/ko/aspose.slides/imageformat) | 이미지 형식. |
| quality | **int** | 저장된 이미지의 품질 (0~100).  <br/><br/>            이 매개변수는 [`ImageFormat.JPEG`](/slides/python-net/ko/aspose.slides/imageformat/JPEG) 저장에만 영향을 미치며, 다른 모든 형식에서는 무시됩니다. |


## save(self, stream, format, quality) {#iorawiobase-imageformat-int}
이미지를 지정된 형식과 품질로 스트림에 저장합니다.


```python
def save(self, stream, format, quality):
    ...
```


| 매개변수 | 타입 | 설명 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 이미지가 저장될 스트림. |
| format | [`ImageFormat`](/slides/python-net/ko/aspose.slides/imageformat) | 이미지 형식. |
| quality | **int** | 저장된 이미지의 품질 (0~100).  <br/><br/>            이 매개변수는 [`ImageFormat.JPEG`](/slides/python-net/ko/aspose.slides/imageformat/JPEG) 저장에만 영향을 미치며, 다른 모든 형식에서는 무시됩니다. |



### 참고
* 클래스 [`IImage`](/slides/python-net/ko/aspose.slides/iimage)
* 열거형 [`ImageFormat`](/slides/python-net/ko/aspose.slides/imageformat)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)