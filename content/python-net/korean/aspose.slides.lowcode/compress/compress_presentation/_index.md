---
title: compress_presentation method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.lowcode/compress/compress_presentation/
weight: 30
---
## compress_presentation(presentation) {#presentation}
프레젠테이션의 크기를 모든 사용 가능한 압축 단계를 적용하여 감소시킵니다:

* 사용되지 않는 마스터 슬라이드를 제거합니다 **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.
* 사용되지 않는 레이아웃 슬라이드를 제거합니다 **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.
* 임베디드 폰트에 실제로 사용된 글리프만 유지합니다 **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.
* 이미지 해상도를 150 DPI로 낮추고 이미지의 잘린 영역을 삭제합니다 **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**.

```python
@staticmethod
def compress_presentation(presentation):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| presentation | [`Presentation`](/slides/python-net/ko/aspose.slides/presentation) | 압축할 프레젠테이션. |

### 비고

압축을 사용자 정의하려면, 예를 들어 다른 이미지 해상도를 사용하거나 단계를 건너뛰려면,
위에 나열된 메서드를 이 메서드 대신 개별적으로 호출하십시오.
이미지의 잘린 영역은 영구적으로 제거되며 PowerPoint에서 복원할 수 없습니다.

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` 은 `None` 입니다. |

### 참조
* 클래스 [`Compress`](/slides/python-net/ko/aspose.slides.lowcode/compress)
* 클래스 [`Presentation`](/slides/python-net/ko/aspose.slides/presentation)
* 모듈 [`aspose.slides.lowcode`](/slides/python-net/ko/aspose.slides.lowcode)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)