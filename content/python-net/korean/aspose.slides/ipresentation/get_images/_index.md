---
title: get_images method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ipresentation/get_images/
weight: 10
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
프레젠테이션의 모든 슬라이드에 대한 썸네일 이미지 객체를 반환합니다.

### Returns
Bitmap objects.



```python
def get_images(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | 렌더링 옵션. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
지정된 슬라이드에 대한 썸네일 Bitmap 객체를 반환합니다.

### Returns
Bitmap objects.



```python
def get_images(self, options, slides):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | 렌더링 옵션. |
| slides | **List[int]** | 1부터 시작하는 슬라이드 위치 배열. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
지정된 크기로 프레젠테이션의 모든 슬라이드에 대한 썸네일 이미지 객체를 반환합니다.

### Returns
Bitmap objects.



```python
def get_images(self, options, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | 렌더링 옵션. |
| image_size | **aspose.slides.Size** | 생성할 이미지의 크기. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
사용자 정의 스케일링으로 프레젠테이션의 모든 슬라이드에 대한 썸네일 이미지 객체를 반환합니다.

### Returns
Bitmap objects.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | 렌더링 옵션. |
| scale_x | **float** | x축 방향으로 이 썸네일을 스케일링하는 값. |
| scale_y | **float** | y축 방향으로 이 썸네일을 스케일링하는 값. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
지정된 크기로 지정된 슬라이드에 대한 썸네일 이미지 객체를 반환합니다.

### Returns
Bitmap objects.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | 렌더링 옵션. |
| slides | **List[int]** | 1부터 시작하는 슬라이드 위치 배열. |
| image_size | **aspose.slides.Size** | 생성할 이미지의 크기. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
사용자 정의 스케일링으로 지정된 슬라이드에 대한 썸네일 이미지 객체를 반환합니다.

### Returns
Bitmap objects.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | 렌더링 옵션. |
| slides | **List[int]** | 1부터 시작하는 슬라이드 위치 배열. |
| scale_x | **float** | x축 방향으로 이 썸네일을 스케일링하는 값. |
| scale_y | **float** | y축 방향으로 이 썸네일을 스케일링하는 값. |



### See Also
* 클래스 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation)
* 클래스 [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)