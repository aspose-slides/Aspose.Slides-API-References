---
title: get_TileOffsetY()
second_title: Aspose.Slides C++ API 참조
description: 텍스처가 도형의 원점으로부터 포인트 단위로 갖는 수직 오프셋을 반환합니다. 양수 값은 텍스처를 아래쪽으로 이동시키고, 음수 값은 위쪽으로 이동시킵니다. 읽기 float.
type: docs
weight: 300
url: /ko/aspose.slides/ipicturefillformat/get_tileoffsety/
---
## IPictureFillFormat::get_TileOffsetY() 메서드


텍스처가 도형의 원점으로부터 포인트 단위로 갖는 수직 오프셋을 반환합니다. 양수 값은 텍스처를 아래로 이동시키고, 음수 값은 위로 이동시킵니다. 읽기 **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetY()=0
```

## 비고



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 도형의 이미지 채우기 형식을 가져옵니다
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 이미지 채우기 모드를 Tile로 설정합니다
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 텍스처의 수직 오프셋을 -50 포인트로 설정합니다
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## 참조

* 클래스 [IPictureFillFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)