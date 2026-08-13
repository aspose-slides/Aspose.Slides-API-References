---
title: set_TileOffsetY()
second_title: Aspose.Slides for C++ API 참조
description: 텍스처를 형태의 원점에서 포인트 단위로 수직 오프셋합니다. 양수 값은 텍스처를 아래로 이동시키고, 음수 값은 위로 이동시킵니다. float 형식으로 기록합니다.
type: docs
weight: 313
url: /ko/aspose.slides/picturefillformat/set_tileoffsety/
---
## PictureFillFormat::set_TileOffsetY(float) 메서드

텍스처를 형태의 원점에서 포인트 단위로 수직 오프셋합니다. 양수 값은 텍스처를 아래로 이동시키고, 음수 값은 위로 이동시킵니다. **float** 형식으로 기록합니다.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetY(float value) override
```

## 비고



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 도형의 그림 채우기 형식을 가져옵니다
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// 그림 채우기 모드를 Tile로 설정합니다
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// 텍스처의 수직 오프셋을 -50 포인트로 설정합니다
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## 참고

* 클래스 [PictureFillFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)