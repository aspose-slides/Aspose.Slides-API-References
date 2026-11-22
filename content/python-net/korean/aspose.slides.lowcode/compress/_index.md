---
title: Compress class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.lowcode/compress/
---
## Compress 클래스

[`Presentation`](/slides/python-net/ko/aspose.slides/presentation)를 압축하도록 설계된 메서드 그룹을 나타냅니다.

Compress 유형은 다음 멤버를 노출합니다:

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`compress_presentation(presentation)`](/slides/python-net/ko/aspose.slides.lowcode/compress/compress_presentation/#presentation) | 발표 파일의 크기를 모든 사용 가능한 압축 단계를 적용하여 줄입니다:<br/>            <br/>* 사용되지 않는 마스터 슬라이드를 제거합니다 **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.<br/>* 사용되지 않는 레이아웃 슬라이드를 제거합니다 **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.<br/>* 포함된 폰트에서 실제로 사용되는 글리프만을 유지합니다 **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.<br/>* 그림 해상도를 150 DPI로 낮추고 그림의 잘린 영역을 삭제합니다 **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**. |
| [`remove_unused_master_slides(pres)`](/slides/python-net/ko/aspose.slides.lowcode/compress/remove_unused_master_slides/#presentation) | 사용되지 않는 마스터 슬라이드를 제거하여 [`Presentation`](/slides/python-net/ko/aspose.slides/presentation)를 압축합니다. |
| [`remove_unused_layout_slides(pres)`](/slides/python-net/ko/aspose.slides.lowcode/compress/remove_unused_layout_slides/#presentation) | 사용되지 않는 레이아웃 슬라이드를 제거하여 [`Presentation`](/slides/python-net/ko/aspose.slides/presentation)를 압축합니다. |
| [`compress_embedded_fonts(pres)`](/slides/python-net/ko/aspose.slides.lowcode/compress/compress_embedded_fonts/#presentation) | 포함된 폰트에서 사용되지 않는 문자를 제거하여 [`Presentation`](/slides/python-net/ko/aspose.slides/presentation)를 압축합니다. |
| [`compress_images(presentation, resolution)`](/slides/python-net/ko/aspose.slides.lowcode/compress/compress_images/#ipresentation-asposeslidesexportpicturescompression) | 프레젠테이션의 그림 해상도를 낮추고 잘린 영역을 삭제합니다,<br/>            PowerPoint의 "Compress Pictures"와 유사하게 모든 그림에 적용합니다.<br/>            슬라이드, 레이아웃 슬라이드 및 마스터 슬라이드의 그림이 처리되며, 그룹 도형 내부의 그림 및 도형의 그림 채우기도 포함됩니다. |

### 관련 항목
* 클래스 [`Presentation`](/slides/python-net/ko/aspose.slides/presentation)
* 모듈 [`aspose.slides.lowcode`](/slides/python-net/ko/aspose.slides.lowcode)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)