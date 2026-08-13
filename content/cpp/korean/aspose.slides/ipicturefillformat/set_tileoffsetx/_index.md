---
title: set_TileOffsetX()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 텍스처의 수평 오프셋을 도형의 원점에서 포인트 단위로 설정합니다. 양수 값은 텍스처를 오른쪽으로 이동시키고, 음수 값은 왼쪽으로 이동시킵니다. float 형식으로 작성합니다.
type: docs
weight: 287
url: /ko/aspose.slides/ipicturefillformat/set_tileoffsetx/
---
## IPictureFillFormat::set_TileOffsetX(float) 메서드

텍스처의 수평 오프셋을 도형의 원점에서 포인트 단위로 설정합니다. 양수 값은 텍스처를 오른쪽으로 이동시키고, 음수 값은 왼쪽으로 이동시킵니다. **float** 형식으로 씁니다.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetX(float value)=0
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

## 참고

* 클래스 [IPictureFillFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)