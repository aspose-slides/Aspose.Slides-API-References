---
title: InsertSectionZoomFrame()
second_title: Aspose.Slides for C++ API 참조
description: 새로운 Section Zoom 프레임을 만들고 지정된 인덱스에 형상 컬렉션에 삽입합니다.
type: docs
weight: 131
url: /ko/aspose.slides/ishapecollection/insertsectionzoomframe/
---
## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) 메서드

새로운 [Section](../../section/) Zoom 프레임을 만들고 지정된 인덱스에 형상 컬렉션에 삽입합니다.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | [Section](../../section/) Zoom 프레임을 삽입할 0 기반 인덱스입니다. |
| x | **float** | 새로운 [Section](../../section/) Zoom 프레임의 x 좌표(포인트)입니다. |
| y | **float** | 새로운 [Section](../../section/) Zoom 프레임의 y 좌표(포인트)입니다. |
| width | **float** | 새로운 [Section](../../section/) Zoom 프레임의 너비(포인트)입니다. |
| height | **float** | 새로운 [Section](../../section/) Zoom 프레임의 높이(포인트)입니다. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) Zoom 프레임이 참조하는 [ISection](../../isection/); 이 프레젠테이션에 속하고 최소 하나의 슬라이드를 포함해야 합니다. |

### 반환 값

새로 만든 [ISectionZoomFrame](../../isectionzoomframe/).

## 비고

이 예제는 컬렉션의 지정된 인덱스에 [Section](../../section/) Zoom 객체를 생성하고 삽입하는 방법을 보여줍니다(예: \"Presentation.pptx\" 프레젠테이션에 섹션이 두 개 이상 있다고 가정). 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) 메서드

새로운 [Section](../../section/) Zoom 프레임을 미리 정의된 이미지와 함께 만들고 지정된 인덱스에 형상 컬렉션에 삽입합니다.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | [Section](../../section/) Zoom 프레임을 삽입할 0 기반 인덱스입니다. |
| x | **float** | 새로운 [Section](../../section/) Zoom 프레임의 x 좌표(포인트)입니다. |
| y | **float** | 새로운 [Section](../../section/) Zoom 프레임의 y 좌표(포인트)입니다. |
| width | **float** | 새로운 [Section](../../section/) Zoom 프레임의 너비(포인트)입니다. |
| height | **float** | 새로운 [Section](../../section/) Zoom 프레임의 높이(포인트)입니다. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) Zoom 프레임이 참조하는 [ISection](../../isection/); 이 프레젠테이션에 속하고 최소 하나의 슬라이드를 포함해야 합니다. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [Section](../../section/) Zoom 프레임 내에 표시할 이미지입니다. |

### 반환 값

새로 만든 [ISectionZoomFrame](../../isectionzoomframe/).

## 비고

이 예제는 컬렉션의 지정된 인덱스에 [Section](../../section/) Zoom 객체를 생성하고 삽입하는 방법을 보여줍니다(예: \"Presentation.pptx\" 프레젠테이션에 섹션이 두 개 이상 있다고 가정). 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## 또한 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISectionZoomFrame](../../isectionzoomframe/)
* Class [ISection](../../isection/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)