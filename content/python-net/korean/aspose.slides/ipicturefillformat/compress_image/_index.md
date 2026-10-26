---
title: compress_image method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ipicturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
이미지를 형태 크기와 지정된 해상도에 따라 크기를 줄여 압축합니다. 선택적으로 자른 영역을 삭제할 수도 있습니다.

### 반환값

이미지가 성공적으로 압축되었는지 여부를 나타내는 **bool**입니다. 이미지가 크기가 조정되었거나 자른 경우 **True**를 반환하고, 그렇지 않으면 **False**를 반환합니다.

```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | true이면, 메서드는 이미지의 잘린 영역을 제거하여 크기를 더 줄일 수 있습니다. |
| resolution | [`PicturesCompression`](/slides/python-net/ko/aspose.slides.export/picturescompression) | 압축을 위한 목표 해상도로, [`PicturesCompression`](/slides/python-net/ko/aspose.slides.export/picturescompression) 열거형 값으로 지정됩니다. |

### 비고

이 메서드는 PowerPoint의 "Picture Format -> Compress Pictures" 기능과 유사하게 이미지의 크기와 해상도를 변경합니다.

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 해상도가 유효한 값이 아닐 때 발생합니다. |

## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
이미지를 형태 크기와 지정된 해상도에 따라 크기를 줄여 압축합니다. 선택적으로 자른 영역을 삭제할 수도 있습니다.

### 반환값

이미지가 성공적으로 압축되었는지 여부를 나타내는 **bool**입니다. 이미지가 크기가 조정되었거나 자른 경우 **True**를 반환하고, 그렇지 않으면 **False**를 반환합니다.

```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | true이면, 메서드는 이미지의 잘린 영역을 제거하여 크기를 더 줄일 수 있습니다. |
| resolution | **float** | 압축을 위한 목표 DPI 해상도입니다. 이 값은 양수이어야 하며 이미지가 어떻게 크기 조정되는지를 정의합니다. |

### 비고

이 메서드는 PowerPoint의 "Picture Format -> Compress Pictures" 기능과 유사하게 이미지의 크기와 해상도를 변경합니다.

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 해상도가 양수가 아닐 때 발생합니다. |

### 참조
* 클래스 [`IPictureFillFormat`](/slides/python-net/ko/aspose.slides/ipicturefillformat)
* 열거형 [`PicturesCompression`](/slides/python-net/ko/aspose.slides.export/picturescompression)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)