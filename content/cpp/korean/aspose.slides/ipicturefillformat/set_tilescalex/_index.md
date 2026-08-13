---
title: set_TileScaleX()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 텍스처 채우기의 수평 스케일을 백분율로 설정합니다. float을 씁니다.
type: docs
weight: 339
url: /ko/aspose.slides/ipicturefillformat/set_tilescalex/
---
## IPictureFillFormat::set_TileScaleX(float) 메서드

텍스처 채우기의 수평 스케일을 백분율로 설정합니다. **float**을 씁니다.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleX(float value)=0
```

## 비고


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 모양의 그림 채우기 형식을 가져옵니다
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 그림 채우기 모드를 Tile로 설정합니다
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 텍스처의 수평 스케일을 120 퍼센트로 설정합니다
pictureFillFormat->set_TileScaleX(120.0f);
```

## 참고

* 클래스 [IPictureFillFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)