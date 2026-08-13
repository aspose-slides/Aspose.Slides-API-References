---
title: AddSmartArt()
second_title: Aspose.Slides for C++ API 레퍼런스
description: SmartArt 다이어그램을 생성하고 shape 컬렉션의 끝에 추가합니다.
type: docs
weight: 79
url: /ko/aspose.slides/shapecollection/addsmartart/
---
## ShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) method


[SmartArt](../../../aspose.slides.smartart/) 다이어그램을 생성하고 shape 컬렉션의 끝에 추가합니다.

```cpp
System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::ShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType) override
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | diagram\\u2019s 프레임의 x좌표, 포인트 단위. |
| y | **float** | diagram\\u2019s 프레임의 y좌표, 포인트 단위. |
| width | **float** | diagram\\u2019s 프레임의 너비, 포인트 단위. |
| height | **float** | diagram\\u2019s 프레임의 높이, 포인트 단위. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | [SmartArt](../../../aspose.slides.smartart/) 레이아웃 유형. |

### 반환값

새로 생성된 [SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/).

## 비고



```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```


## 참조

* Enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)