---
title: compress_images method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.lowcode/compress/compress_images/
weight: 20
---
## compress_images(presentation, resolution) {#ipresentation-asposeslidesexportpicturescompression}
프레젠테이션의 그림 해상도를 낮추고 잘라낸 영역을 삭제합니다,
            PowerPoint의 "Compress Pictures"와 유사하게 모든 그림에 적용됩니다.
            슬라이드, 레이아웃 슬라이드 및 마스터 슬라이드의 그림이 처리되며, 그룹 도형 내부의 그림과 도형의 그림 채우기도 포함됩니다.


```python
@staticmethod
def compress_images(presentation, resolution):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation) | 처리할 프레젠테이션입니다. |
| resolution | [`PicturesCompression`](/slides/python-net/ko/aspose.slides.export/picturescompression) | 각 그림이 표시되는 크기에 대한 목표 해상도입니다.<br/><br/>[`PicturesCompression.DOCUMENT_RESOLUTION`](/slides/python-net/ko/aspose.slides.export/picturescompression/DOCUMENT_RESOLUTION)는 그림을 변경하지 않습니다. |

### 비고

목표 해상도 이하이거나 같은 그림은 그대로 유지되며, 그림이 확대되는 일은 없습니다.


처리되지 않음: 슬라이드 배경, 표 셀 채우기, 차트, SmartArt, GIF 이미지(애니메이션 보존을 위해),
            SVG 및 메타파일(EMF/WMF) 이미지.


잘라낸 영역은 영구적으로 제거되며 PowerPoint에서 복원할 수 없습니다.

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` is `None`. |



### 참조
* 클래스 [`Compress`](/slides/python-net/ko/aspose.slides.lowcode/compress)
* 클래스 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation)
* 열거형 [`PicturesCompression`](/slides/python-net/ko/aspose.slides.export/picturescompression)
* 모듈 [`aspose.slides.lowcode`](/slides/python-net/ko/aspose.slides.lowcode)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)