---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
실제 크기의 20%인 섬네일 이미지 객체를 반환합니다.


```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposeslidessize}
지정된 크기의 섬네일 이미지 객체를 반환합니다.

### 반환

이미지 객체.



```python
def get_image(self, image_size):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/ko/aspose.slides/size) | 생성할 이미지의 크기. |


## get_image(self, options) {#asposeslidesexportitiffoptions}
지정된 매개변수로 섬네일 TIFF 이미지 객체를 반환합니다.

### 반환

이미지 객체.



```python
def get_image(self, options):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/ko/aspose.slides.export/itiffoptions) | TIFF 옵션. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | options.SlideLayoutOption이 NotesCommentsLayoutingOptions이고 그 속성 NotesPosition이 NotesPositions.BottomFull 값을 가질 때 발생합니다. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
섬네일 이미지 객체를 반환합니다.

### 반환

이미지 객체.



```python
def get_image(self, options):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | 렌더링 옵션. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | notesCommentsLayouting.NotesPosition이 NotesPositions.BottomFull 값을 가질 때 발생합니다. |


## get_image(self, scale_x, scale_y) {#float-float}
맞춤 스케일링으로 섬네일 이미지 객체를 반환합니다.

### 반환

IImage 객체.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| scale_x | **float** | x축 방향으로 이 섬네일을 스케일링하는 값. |
| scale_y | **float** | y축 방향으로 이 섬네일을 스케일링하는 값. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
지정된 크기의 섬네일 이미지 객체를 반환합니다.

### 반환

이미지 객체.



```python
def get_image(self, options, image_size):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | 렌더링 옵션. |
| image_size | [`Size`](/slides/python-net/ko/aspose.slides/size) | 생성할 이미지의 크기. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | options.SlideLayoutOption이 NotesCommentsLayoutingOptions이고 그 속성 NotesPosition이 NotesPositions.BottomFull 값을 가질 때 발생합니다. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
맞춤 스케일링으로 섬네일 이미지 객체를 반환합니다.

### 반환

비트맵 객체.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | 렌더링 옵션. |
| scale_x | **float** | x축 방향으로 이 섬네일을 스케일링하는 값. |
| scale_y | **float** | y축 방향으로 이 섬네일을 스케일링하는 값. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | notesCommentsLayouting.NotesPosition이 NotesPositions.BottomFull 값을 가질 때 발생합니다. |



### 참고
* 클래스 [`IImage`](/slides/python-net/ko/aspose.slides/iimage)
* 클래스 [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions)
* 클래스 [`ITiffOptions`](/slides/python-net/ko/aspose.slides.export/itiffoptions)
* 클래스 [`Slide`](/slides/python-net/ko/aspose.slides/slide)
* 클래스 [`Size`](/slides/python-net/ko/aspose.slides/size)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)