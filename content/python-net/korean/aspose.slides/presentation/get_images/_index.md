---
title: get_images method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/presentation/get_images/
weight: 20
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
프레젠테이션의 모든 슬라이드에 대한 Image 객체를 반환합니다.

### 반환값

Image objects.



```python
def get_images(self, options):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | Tiff 옵션. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
프레젠테이션의 지정된 슬라이드에 대한 썸네일 Image 객체를 반환합니다.

### 반환값

Image objects.



```python
def get_images(self, options, slides):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | Tiff 옵션. |
| slides | **List[int]** | 슬라이드 위치 배열, 1부터 시작합니다. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
지정된 크기로 프레젠테이션의 모든 슬라이드에 대한 썸네일 Image 객체를 반환합니다.

### 반환값

Image objects.



```python
def get_images(self, options, image_size):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | Tiff 옵션. |
| image_size | **aspose.slides.Size** | 생성할 이미지의 크기. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
사용자 지정 스케일링을 사용하여 프레젠테이션의 모든 슬라이드에 대한 썸네일 Image 객체를 반환합니다.

### 반환값

Image objects.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | Tiff 옵션. |
| scale_x | **float** | x축 방향으로 이 썸네일을 스케일링할 값. |
| scale_y | **float** | y축 방향으로 이 썸네일을 스케일링할 값. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
지정된 크기로 프레젠테이션의 지정된 슬라이드에 대한 썸네일 Image 객체를 반환합니다.

### 반환값

Image objects.



```python
def get_images(self, options, slides, image_size):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | Tiff 옵션. |
| slides | **List[int]** | 슬라이드 위치 배열, 1부터 시작합니다. |
| image_size | **aspose.slides.Size** | 생성할 이미지의 크기. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
사용자 지정 스케일링을 사용하여 프레젠테이션의 지정된 슬라이드에 대한 썸네일 Image 객체를 반환합니다.

### 반환값

Image objects.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | Tiff 옵션. |
| slides | **List[int]** | 슬라이드 위치 배열, 1부터 시작합니다. |
| scale_x | **float** | x축 방향으로 이 썸네일을 스케일링할 값. |
| scale_y | **float** | y축 방향으로 이 썸네일을 스케일링할 값. |



### 또 보기
* 클래스 [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions)
* 클래스 [`Presentation`](/slides/python-net/ko/aspose.slides/presentation)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)