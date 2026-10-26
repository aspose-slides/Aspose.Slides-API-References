---
title: get_TileAlignment()
second_title: Aspose.Slides for C++ API 참조
description: 텍스처가 도형 내에서 어떻게 정렬되는지 반환합니다. 이 설정은 텍스처 패턴의 시작 지점과 도형 전체에 걸쳐 반복되는 방식을 제어합니다. RectangleAlignment를 읽어 보세요.
type: docs
weight: 378
url: /ko/aspose.slides/ipicturefillformat/get_tilealignment/
---
## IPictureFillFormat::get_TileAlignment() 메서드


텍스처가 도형 내에서 정렬되는 방식을 반환합니다. 이 설정은 텍스처 패턴의 시작 지점과 도형 전체에 걸쳐 반복되는 방식을 제어합니다. 읽어 보기 [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual RectangleAlignment Aspose::Slides::IPictureFillFormat::get_TileAlignment()=0
```

## 비고


기본값은 [RectangleAlignment::TopLeft](../../rectanglealignment/)입니다. 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 도형의 그림 채우기 형식을 가져옵니다
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 그림 채우기 모드를 타일로 설정합니다
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 타일링 정렬을 오른쪽 아래로 설정합니다
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## 참고

* 열거형 [RectangleAlignment](../../rectanglealignment/)
* 클래스 [IPictureFillFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)