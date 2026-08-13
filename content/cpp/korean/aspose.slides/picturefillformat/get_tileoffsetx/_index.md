---
title: get_TileOffsetX()
second_title: Aspose.Slides C++ API 레퍼런스
description: 텍스처가 도형의 원점에서 포인트 단위로 갖는 수평 오프셋을 반환합니다. 양수 값은 텍스처를 오른쪽으로 이동시키고, 음수 값은 왼쪽으로 이동시킵니다. 읽기 전용 float.
type: docs
weight: 274
url: /ko/aspose.slides/picturefillformat/get_tileoffsetx/
---
## PictureFillFormat::get_TileOffsetX() 메서드

텍스처의 수평 오프셋을 도형의 원점에서 포인트 단위로 반환합니다. 양수 값은 텍스처를 오른쪽으로 이동시키고, 음수 값은 왼쪽으로 이동시킵니다. 읽기 전용 **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetX() override
```

## 비고

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 도형의 그림 채우기 형식을 가져옵니다
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 그림 채우기 모드를 타일로 설정합니다
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 텍스처의 수평 오프셋을 20 포인트로 설정합니다
pictureFillFormat->set_TileOffsetX(20.0f);
```

## 참조

* 클래스 [PictureFillFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)