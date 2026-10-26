---
title: get_images method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/presentation/get_images/
weight: 20
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Returns a Image objects for all slides of a presentation.

### 반환값

Image 객체.



```python
def get_images(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | Tiff 옵션. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Returns a Thumbnail Image objects for specified slides of a presentation.

### 반환값

Image 객체.



```python
def get_images(self, options, slides):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | Tiff 옵션. |
| slides | **List[int]** | 슬라이드 위치 배열, 1부터 시작합니다. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Returns a Thumbnail Image objects for all slides of a presentation with specified size.

### 반환값

Image 객체.



```python
def get_images(self, options, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | Tiff 옵션. |
| image_size | [`Size`](/slides/python-net/ko/aspose.slides/size) | 생성할 이미지의 크기. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Returns a Thumbnail Image objects for all slides of a presentation with custom scaling.

### 반환값

Image 객체.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | Tiff 옵션. |
| scale_x | **float** | x축 방향으로 이 Thumbnail을 확대하는 값. |
| scale_y | **float** | y축 방향으로 이 Thumbnail을 확대하는 값. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposeslidessize}
Returns a Thumbnail Image objects for specified slides of a presentation with specified size.

### 반환값

Image 객체.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | Tiff 옵션. |
| slides | **List[int]** | 슬라이드 위치 배열, 1부터 시작합니다. |
| image_size | [`Size`](/slides/python-net/ko/aspose.slides/size) | 생성할 이미지의 크기. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Returns a Thumbnail Image objects for specified slides of a presentation with custom scaling.

### 반환값

Image 객체.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | Tiff 옵션. |
| slides | **List[int]** | 슬라이드 위치 배열, 1부터 시작합니다. |
| scale_x | **float** | x축 방향으로 이 Thumbnail을 확대하는 값. |
| scale_y | **float** | y축 방향으로 이 Thumbnail을 확대하는 값. |



### 추가 정보
* 클래스 [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions)
* 클래스 [`Presentation`](/slides/python-net/ko/aspose.slides/presentation)
* 클래스 [`Size`](/slides/python-net/ko/aspose.slides/size)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)