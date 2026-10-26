---
title: get_TileFlip()
second_title: Aspose.Slides C++용 API 레퍼런스
description: "텍스처 타일을 수평, 수직 또는 두 축 모두를 기준으로 뒤집습니다. Slides::TileFlip을 읽어보세요."
type: docs
weight: 404
url: /ko/aspose.slides/picturefillformat/get_tileflip/
---
## PictureFillFormat::get_TileFlip() 메서드


텍스처 타일을 수평, 수직 또는 두 축 모두를 기준으로 뒤집습니다. 읽어보세요 [Slides::TileFlip](../../tileflip/).

```cpp
Aspose::Slides::TileFlip Aspose::Slides::PictureFillFormat::get_TileFlip() override
```

## 비고


기본값은 [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 도형의 그림 채우기 형식을 가져옵니다.
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 그림 채우기 모드를 타일로 설정합니다.
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 텍스처 타일을 수직 축을 기준으로 뒤집습니다.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## 참조

* 열거형 [TileFlip](../../tileflip/)
* 클래스 [PictureFillFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)