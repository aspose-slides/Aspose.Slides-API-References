---
title: InsertSectionZoomFrame()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 Section Zoom 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다.
type: docs
weight: 144
url: /ko/aspose.slides/shapecollection/insertsectionzoomframe/
---
## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) 메서드

지정된 인덱스에 새 [Section](../../section/) Zoom 프레임을 생성하고 도형 컬렉션에 삽입합니다.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 새 [Section](../../section/) Zoom 프레임을 삽입할 0부터 시작하는 인덱스입니다. |
| x | **float** | 새 [Section](../../section/) Zoom 프레임의 x 좌표이며, 단위는 포인트입니다. |
| y | **float** | 새 [Section](../../section/) Zoom 프레임의 y 좌표이며, 단위는 포인트입니다. |
| width | **float** | 새 [Section](../../section/) Zoom 프레임의 너비이며, 단위는 포인트입니다. |
| height | **float** | 새 [Section](../../section/) Zoom 프레임의 높이며, 단위는 포인트입니다. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) Zoom 프레임이 참조하는 [ISection](../../isection/)이며, 이 프레젠테이션에 속하고 최소 한 개의 슬라이드를 포함해야 합니다. |

### 반환 값

새로 생성된 [ISectionZoomFrame](../../isectionzoomframe/).

## 비고

이 예제는 컬렉션의 지정된 인덱스에 [Section](../../section/) Zoom 객체를 생성하고 삽입하는 방법을 보여줍니다 (\"Presentation.pptx\" 프레젠테이션에 섹션이 최소 두 개 있다고 가정합니다):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) 메서드

지정된 인덱스에 미리 정의된 이미지가 포함된 새 [Section](../../section/) Zoom 프레임을 생성하고 도형 컬렉션에 삽입합니다.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 새 [Section](../../section/) Zoom 프레임을 삽입할 0부터 시작하는 인덱스입니다. |
| x | **float** | 새 [Section](../../section/) Zoom 프레임의 x 좌표이며, 단위는 포인트입니다. |
| y | **float** | 새 [Section](../../section/) Zoom 프레임의 y 좌표이며, 단위는 포인트입니다. |
| width | **float** | 새 [Section](../../section/) Zoom 프레임의 너비이며, 단위는 포인트입니다. |
| height | **float** | 새 [Section](../../section/) Zoom 프레임의 높이며, 단위는 포인트입니다. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) Zoom 프레임이 참조하는 [ISection](../../isection/)이며, 이 프레젠테이션에 속하고 최소 한 개의 슬라이드를 포함해야 합니다. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [Section](../../section/) Zoom 프레임 내에 표시할 이미지입니다. |

### 반환 값

새로 생성된 [ISectionZoomFrame](../../isectionzoomframe/).

## 비고

이 예제는 컬렉션의 지정된 인덱스에 [Section](../../section/) Zoom 객체를 생성하고 삽입하는 방법을 보여줍니다 (\"Presentation.pptx\" 프레젠테이션에 섹션이 최소 두 개 있다고 가정합니다):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISectionZoomFrame](../../isectionzoomframe/)
* 클래스 [ISection](../../isection/)
* 클래스 [ShapeCollection](../)
* 클래스 [IPPImage](../../ippimage/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)