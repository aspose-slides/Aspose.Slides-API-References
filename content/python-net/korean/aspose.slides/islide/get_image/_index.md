---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/islide/get_image/
weight: 40
---
## get_image(self) {#}
실제 크기의 20%인 썸네일 이미지 객체를 반환합니다.

### 반환값

Image object **aspose.slides.Bitmap**



```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposepydrawingsize}
지정된 크기의 이미지 객체를 반환합니다.

### 반환값

Bitmap object.



```python
def get_image(self, image_size):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| image_size | **aspose.slides.Size** | 생성할 이미지의 크기. |


## get_image(self, options) {#asposeslidesexportitiffoptions}
지정된 매개변수로 썸네일 TIFF 비트맵 객체를 반환합니다.

### 반환값

Image object.



```python
def get_image(self, options):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/ko/aspose.slides.export/itiffoptions) | TIFF 옵션. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
썸네일 비트맵 객체를 반환합니다.

### 반환값

Bitmap objects.



```python
def get_image(self, options):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | 렌더링 옵션. |


## get_image(self, scale_x, scale_y) {#float-float}
사용자 지정 스케일링을 적용한 이미지 객체를 반환합니다.

### 반환값

Image object **aspose.slides.Bitmap**



```python
def get_image(self, scale_x, scale_y):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| scale_x | **float** | x축 방향으로 이 썸네일을 스케일링할 값. |
| scale_y | **float** | y축 방향으로 이 썸네일을 스케일링할 값. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
지정된 크기의 썸네일 비트맵 객체를 반환합니다.

### 반환값

Bitmap objects.



```python
def get_image(self, options, image_size):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | 렌더링 옵션. |
| image_size | **aspose.slides.Size** | 생성할 이미지의 크기. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
사용자 지정 스케일링을 적용한 썸네일 비트맵 객체를 반환합니다.

### 반환값

Bitmap objects.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | 렌더링 옵션. |
| scale_x | **float** | x축 방향으로 이 썸네일을 스케일링할 값. |
| scale_y | **float** | y축 방향으로 이 썸네일을 스케일링할 값. |



### 참조
* 클래스 [`IImage`](/slides/python-net/ko/aspose.slides/iimage)
* 클래스 [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions)
* 클래스 [`ISlide`](/slides/python-net/ko/aspose.slides/islide)
* 클래스 [`ITiffOptions`](/slides/python-net/ko/aspose.slides.export/itiffoptions)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)