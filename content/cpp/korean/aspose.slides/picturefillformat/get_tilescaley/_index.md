---
title: get_TileScaleY()
second_title: Aspose.Slides C++ API 레퍼런스
description: 텍스처 채우기의 수직 스케일을 백분율로 반환합니다. 읽기 float.
type: docs
weight: 352
url: /ko/aspose.slides/picturefillformat/get_tilescaley/
---
## PictureFillFormat::get_TileScaleY() 메서드


텍스처 채우기의 수직 스케일을 백분율로 반환합니다. 읽기 **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleY() override
```

## 비고



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 형상의 그림 채우기 형식을 가져옵니다
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 그림 채우기 모드를 타일로 설정합니다
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 텍스처의 수직 스케일을 120%로 설정합니다
pictureFillFormat->set_TileScaleY(120.0f);
```

## 참고

* 클래스 [PictureFillFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)