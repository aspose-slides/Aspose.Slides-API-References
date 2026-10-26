---
title: set_TileAlignment()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 텍스처가 도형 내부에서 어떻게 정렬되는지를 설정합니다. 이 설정은 텍스처 패턴의 시작점과 도형 전체에 반복되는 방식을 제어합니다. RectangleAlignment을 작성하십시오.
type: docs
weight: 391
url: /ko/aspose.slides/picturefillformat/set_tilealignment/
---
## PictureFillFormat::set_TileAlignment(RectangleAlignment) 메서드

텍스처가 도형 내부에서 정렬되는 방식을 설정합니다. 이 설정은 텍스처 패턴의 시작점을 제어하고 도형 전체에 어떻게 반복되는지를 결정합니다. [RectangleAlignment](../../rectanglealignment/)를 작성하십시오.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileAlignment(RectangleAlignment value) override
```

## 비고

기본값은 [RectangleAlignment::TopLeft](../../rectanglealignment/)입니다. 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 형태의 그림 채우기 형식을 가져옵니다
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 그림 채우기 모드를 Tile로 설정합니다
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 타일링 정렬을 오른쪽 아래로 설정합니다
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## 참고

* Enum [RectangleAlignment](../../rectanglealignment/)
* 클래스 [PictureFillFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)