---
title: set_TileFlip()
second_title: "Aspose.Slides for C++ API 레퍼런스"
description: "텍스처 타일을 수평, 수직 또는 두 축 모두를 기준으로 뒤집습니다. Slides::TileFlip을 작성하십시오."
type: docs
weight: 417
url: /ko/aspose.slides/picturefillformat/set_tileflip/
---
## PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) 메서드

텍스처 타일을 수평, 수직 또는 두 축 모두를 기준으로 뒤집습니다. [Slides::TileFlip](../../tileflip/)를 작성하십시오.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value) override
```

## 비고

기본값은 [TileFlip::NoFlip](../../tileflip/)입니다.

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 도형의 picture fill 형식을 가져옵니다.
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// picture fill 모드를 Tile로 설정합니다.
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 텍스처 타일을 수직 축을 기준으로 뒤집습니다.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## 참고

* Enum [TileFlip](../../tileflip/)
* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)