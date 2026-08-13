---
title: AddSectionZoomFrame()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 섹션 줌 프레임을 만들고 이를 shape 컬렉션의 끝에 추가합니다.
type: docs
weight: 131
url: /ko/aspose.slides/shapecollection/addsectionzoomframe/
---
## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) 메서드

새로운 [Section](../../section/) 줌 프레임을 만들고 형태 컬렉션 끝에 추가합니다.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 새 [Section](../../section/) 줌 프레임의 x 좌표(포인트). |
| y | **float** | 새 [Section](../../section/) 줌 프레임의 y 좌표(포인트). |
| width | **float** | 새 [Section](../../section/) 줌 프레임의 너비(포인트). |
| height | **float** | 새 [Section](../../section/) 줌 프레임의 높이(포인트). |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) 줌 프레임이 참조하는 [ISection](../../isection/); 이 프레젠테이션에 속하고 최소 하나의 슬라이드를 포함해야 합니다. |

### 반환값

새로 만든 [ISectionZoomFrame](../../isectionzoomframe/).

## 비고

이 예제는 컬렉션 끝에 [Section](../../section/) 줌 객체를 추가하는 방법을 보여줍니다(예: \"Presentation.pptx\" 프레젠테이션에 섹션이 최소 두 개 있다고 가정). 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) 메서드

미리 정의된 이미지를 사용해 새로운 [Section](../../section/) 줌 프레임을 만들고 형태 컬렉션 끝에 추가합니다.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 새 [Section](../../section/) 줌 프레임의 x 좌표(포인트). |
| y | **float** | 새 [Section](../../section/) 줌 프레임의 y 좌표(포인트). |
| width | **float** | 새 [Section](../../section/) 줌 프레임의 너비(포인트). |
| height | **float** | 새 [Section](../../section/) 줌 프레임의 높이(포인트). |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) 줌 프레임이 참조하는 [ISection](../../isection/); 이 프레젠테이션에 속하고 최소 하나의 슬라이드를 포함해야 합니다. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [Section](../../section/) 줌 프레임 내에 표시할 [IPPImage](../../ippimage/). |

### 반환값

새로 만든 [ISectionZoomFrame](../../isectionzoomframe/).

## 비고

이 예제는 컬렉션 끝에 [Section](../../section/) 줌 객체를 추가하는 방법을 보여줍니다(예: \"Presentation.pptx\" 프레젠테이션에 섹션이 최소 두 개 있다고 가정). 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## 또한 보기

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISectionZoomFrame](../../isectionzoomframe/)
* 클래스 [ISection](../../isection/)
* 클래스 [ShapeCollection](../)
* 클래스 [IPPImage](../../ippimage/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)