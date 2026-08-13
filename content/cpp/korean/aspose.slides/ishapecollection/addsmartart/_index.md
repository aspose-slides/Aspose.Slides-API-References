---
title: AddSmartArt()
second_title: Aspose.Slides for C++ API 레퍼런스
description: SmartArt 다이어그램을 생성하고 도형 컬렉션의 끝에 추가합니다.
type: docs
weight: 40
url: /ko/aspose.slides/ishapecollection/addsmartart/
---
## IShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) 메서드


[SmartArt](../../../aspose.slides.smartart/) 다이어그램을 생성하고 도형 컬렉션의 끝에 추가합니다.

```cpp
virtual System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::IShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType)=0
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 다이어그램 프레임의 x좌표(포인트 단위). |
| y | **float** | 다이어그램 프레임의 y좌표(포인트 단위). |
| width | **float** | 다이어그램 프레임의 너비(포인트 단위). |
| height | **float** | 다이어그램 프레임의 높이(포인트 단위). |
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

* 열거형 [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* 클래스 [IShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)