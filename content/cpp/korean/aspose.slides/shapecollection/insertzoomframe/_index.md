---
title: InsertZoomFrame()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 Zoom 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.
type: docs
weight: 118
url: /ko/aspose.slides/shapecollection/insertzoomframe/
---
## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) 메서드

새로운 Zoom 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Zoom 프레임을 삽입할 0부터 시작하는 인덱스입니다. |
| x | **float** | 새 Zoom 프레임의 x 좌표(포인트 단위)입니다. |
| y | **float** | 새 Zoom 프레임의 y 좌표(포인트 단위)입니다. |
| width | **float** | 새 Zoom 프레임의 너비(포인트 단위)입니다. |
| height | **float** | 새 Zoom 프레임의 높이(포인트 단위)입니다. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom 프레임이 참조하는 [ISlide](../../islide/)입니다. |

### 반환 값

새로 생성된 [IZoomFrame](../../izoomframe/).

## 비고

이 예제는 컬렉션의 지정된 인덱스에 Zoom 객체를 생성하고 삽입하는 방법을 보여줍니다(예: \"Presentation.pptx\" 프레젠테이션에 슬라이드가 최소 두 개 있다고 가정). 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) 메서드

새로운 Zoom 프레임을 미리 정의된 이미지와 함께 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Zoom 프레임을 삽입할 0부터 시작하는 인덱스입니다. |
| x | **float** | 새 Zoom 프레임의 x 좌표(포인트 단위)입니다. |
| y | **float** | 새 Zoom 프레임의 y 좌표(포인트 단위)입니다. |
| width | **float** | 새 Zoom 프레임의 너비(포인트 단위)입니다. |
| height | **float** | 새 Zoom 프레임의 높이(포인트 단위)입니다. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom 프레임이 참조하는 [ISlide](../../islide/)입니다. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 참조된 슬라이드 [IPPImage](../../ippimage/)에 대한 이미지입니다. |

### 반환 값

새로 생성된 [IZoomFrame](../../izoomframe/).

## 비고

이 예제는 컬렉션의 지정된 인덱스에 Zoom 객체를 생성하고 삽입하는 방법을 보여줍니다(예: \"Presentation.pptx\" 프레젠테이션에 슬라이드가 최소 두 개 있다고 가정). 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IZoomFrame](../../izoomframe/)
* Class [ISlide](../../islide/)
* Class [ShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)