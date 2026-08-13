---
title: AddSmartArtPlaceholder()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 레이아웃 슬라이드에 새로운 자리 표시자 모양을 추가하여 SmartArt 다이어그램을 보관합니다.
type: docs
weight: 92
url: /ko/aspose.slides/layoutplaceholdermanager/addsmartartplaceholder/
---
## LayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) 메서드

새로운 자리 표시자 모양을 레이아웃 슬라이드에 추가하여 [SmartArt](../../../aspose.slides.smartart/) 다이어그램을 보관합니다.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height) override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 새로운 자리 표시자 모양의 X 좌표입니다. |
| y | **float** | 새로운 자리 표시자 모양의 Y 좌표입니다. |
| width | **float** | 새로운 자리 표시자 모양의 너비입니다. |
| height | **float** | 새로운 자리 표시자 모양의 높이입니다. |

### 반환 값

[IAutoShape](../../iautoshape/)를 [SmartArt](../../../aspose.slides.smartart/) 자리 표시자와 함께 생성했습니다.

## 비고

다음 예제는 [SmartArt](../../../aspose.slides.smartart/) 자리 표시자 모양을 레이아웃 슬라이드에 추가하는 방법을 보여줍니다. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAutoShape](../../iautoshape/)
* 클래스 [LayoutPlaceholderManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)