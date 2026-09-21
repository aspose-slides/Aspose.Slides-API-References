---
title: add_image method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/imagecollection/add_image/
weight: 10
---
## add_image(self, image_source) {#ippimage}
다른 프레젠테이션에서 이미지 복사본을 추가합니다.

### 반환값

추가된 이미지.



```python
def add_image(self, image_source):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/ko/aspose.slides/ippimage) | 원본 이미지. |


## add_image(self, image) {#iimage}
프레젠테이션에 이미지를 추가합니다.

### 반환값

추가된 이미지.



```python
def add_image(self, image):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/ko/aspose.slides/iimage) | 추가할 이미지. |

### 비고

이 메서드는 WMF/EMF 메타파일을 래스터 PNG 이미지로 변환한 후 프레젠테이션에 삽입합니다.


## add_image(self, stream) {#iorawiobase}
스트림에서 프레젠테이션에 이미지를 추가합니다.

### 반환값

추가된 이미지.



```python
def add_image(self, stream):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 이미지 추가에 사용할 스트림. |

### 비고

이 메서드는 WMF/EMF 메타파일을 래스터 PNG 이미지로 변환하지 않고도 프레젠테이션에 추가할 수 있습니다.


## add_image(self, buffer) {#bytes}
지정된 버퍼에서 프레젠테이션에 이미지를 추가합니다.

### 반환값

추가된 이미지.



```python
def add_image(self, buffer):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| buffer | **bytes** | 버퍼. |


## add_image(self, svg_image) {#isvgimage}
Svg 객체에서 프레젠테이션에 이미지를 추가합니다.

### 반환값

추가된 이미지.



```python
def add_image(self, svg_image):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/ko/aspose.slides/isvgimage) | Svg 이미지 객체 [`ISvgImage`](/slides/python-net/ko/aspose.slides/isvgimage) |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | svgImage 매개변수가 None인 경우. |


## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
스트림에서 프레젠테이션에 이미지를 생성하고 추가합니다.

### 반환값

추가된 [`IPPImage`](/slides/python-net/ko/aspose.slides/ippimage).



```python
def add_image(self, stream, loading_stream_behavior):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 이미지 파일을 추가할 스트림. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/ko/aspose.slides/loadingstreambehavior) | 스트림에 적용될 동작. |



### 또 보기
* 클래스 [`IImage`](/slides/python-net/ko/aspose.slides/iimage)
* 클래스 [`ImageCollection`](/slides/python-net/ko/aspose.slides/imagecollection)
* 클래스 [`IPPImage`](/slides/python-net/ko/aspose.slides/ippimage)
* 클래스 [`ISvgImage`](/slides/python-net/ko/aspose.slides/isvgimage)
* 열거형 [`LoadingStreamBehavior`](/slides/python-net/ko/aspose.slides/loadingstreambehavior)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)