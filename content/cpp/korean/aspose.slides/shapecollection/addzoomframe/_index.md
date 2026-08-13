---
title: AddZoomFrame()
second_title: Aspose.Slides for C++ API 참조
description: 새 Zoom 프레임을 생성하고 이를 shape 컬렉션의 끝에 추가합니다.
type: docs
weight: 105
url: /ko/aspose.slides/shapecollection/addzoomframe/
---
## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) 메서드

새 Zoom 프레임을 생성하고 이를 shape 컬렉션의 끝에 추가합니다.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 새 Zoom 프레임의 x 좌표(포인트 단위)입니다. |
| y | **float** | 새 Zoom 프레임의 y 좌표(포인트 단위)입니다. |
| width | **float** | 새 Zoom 프레임의 너비(포인트 단위)입니다. |
| height | **float** | 새 Zoom 프레임의 높이(포인트 단위)입니다. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom 프레임이 참조하는 [ISlide](../../islide/); 현재 프레젠테이션에 속해야 합니다. |

### 반환 값

새로 생성된 [IZoomFrame](../../izoomframe/)입니다.

## 비고

이 예제는 컬렉션의 끝에 Zoom 객체를 추가하는 방법을 보여줍니다 (\"Presentation.pptx\" 프레젠테이션에 슬라이드가 최소 두 개 있다고 가정합니다):
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) 메서드

새 Zoom 프레임을 생성하고 이를 shape 컬렉션의 끝에 추가합니다.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 새 Zoom 프레임의 x 좌표(포인트 단위)입니다. |
| y | **float** | 새 Zoom 프레임의 y 좌표(포인트 단위)입니다. |
| width | **float** | 새 Zoom 프레임의 너비(포인트 단위)입니다. |
| height | **float** | 새 Zoom 프레임의 높이(포인트 단위)입니다. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom 프레임이 참조하는 [ISlide](../../islide/); 현재 프레젠테이션에 속해야 합니다. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 참조된 슬라이드 [IPPImage](../../ippimage/)에 대한 이미지입니다. |

### 반환 값

새로 생성된 [IZoomFrame](../../izoomframe/)입니다.

## 비고

이 예제는 컬렉션의 끝에 Zoom 객체를 추가하는 방법을 보여줍니다 (\"Presentation.pptx\" 프레젠테이션에 슬라이드가 최소 두 개 있다고 가정합니다):
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IZoomFrame](../../izoomframe/)
* 클래스 [ISlide](../../islide/)
* 클래스 [ShapeCollection](../)
* 클래스 [IPPImage](../../ippimage/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)