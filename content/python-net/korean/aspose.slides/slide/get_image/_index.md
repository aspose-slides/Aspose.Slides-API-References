---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
Thumbnail Image 객체를 반환합니다 (실제 크기의 20%).

```python
def get_image(self):
    ...
```

## get_image(self, image_size) {#asposepydrawingsize}
지정된 크기의 Thumbnail Image 객체를 반환합니다.

### 반환값

Image 객체.

```python
def get_image(self, image_size):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| image_size | **aspose.slides.Size** | 생성할 이미지의 크기. |

## get_image(self, options) {#asposeslidesexportitiffoptions}
지정된 매개변수로 Thumbnail tiff 이미지 객체를 반환합니다.

### 반환값

Image 객체.

```python
def get_image(self, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/ko/aspose.slides.export/itiffoptions) | Tiff 옵션. |

### 예외

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | options.SlideLayoutOption이 NotesCommentsLayoutingOptions이고 해당 속성 NotesPosition이 NotesPositions.BottomFull 값을 가질 때 발생합니다. |

## get_image(self, options) {#asposeslidesexportirenderingoptions}
Thumbnail Image 객체를 반환합니다.

### 반환값

Image 객체.

```python
def get_image(self, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | 렌더링 옵션. |

### 예외

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | notesCommentsLayouting.NotesPosition이 NotesPositions.BottomFull 값을 가질 때 발생합니다. |

## get_image(self, scale_x, scale_y) {#float-float}
사용자 정의 스케일링으로 Thumbnail Image 객체를 반환합니다.

### 반환값

IImage 객체.

```python
def get_image(self, scale_x, scale_y):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| scale_x | **float** | x축 방향으로 이 Thumbnail을 스케일링할 값. |
| scale_y | **float** | y축 방향으로 이 Thumbnail을 스케일링할 값. |

## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
지정된 크기의 Thumbnail Image 객체를 반환합니다.

### 반환값

Image 객체.

```python
def get_image(self, options, image_size):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | 렌더링 옵션. |
| image_size | **aspose.slides.Size** | 생성할 이미지의 크기. |

### 예외

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | options.SlideLayoutOption이 NotesCommentsLayoutingOptions이고 해당 속성 NotesPosition이 NotesPositions.BottomFull 값을 가질 때 발생합니다. |

## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
사용자 정의 스케일링으로 Thumbnail Image 객체를 반환합니다.

### 반환값

Bitmap 객체들.

```python
def get_image(self, options, scale_x, scale_y):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | 렌더링 옵션. |
| scale_x | **float** | x축 방향으로 이 Thumbnail을 스케일링할 값. |
| scale_y | **float** | y축 방향으로 이 Thumbnail을 스케일링할 값. |

### 예외

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | notesCommentsLayouting.NotesPosition이 NotesPositions.BottomFull 값을 가질 때 발생합니다. |

### 참조
* 클래스 [`IImage`](/slides/python-net/ko/aspose.slides/iimage)
* 클래스 [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions)
* 클래스 [`ITiffOptions`](/slides/python-net/ko/aspose.slides.export/itiffoptions)
* 클래스 [`Slide`](/slides/python-net/ko/aspose.slides/slide)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)