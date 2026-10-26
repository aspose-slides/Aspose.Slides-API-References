---
title: AddChartPlaceholder()
second_title: Aspose.Slides for C++ API 참조
description: 차트를 포함하기 위해 레이아웃 슬라이드에 새로운 자리 표시자 도형을 추가합니다.
type: docs
weight: 66
url: /ko/aspose.slides/layoutplaceholdermanager/addchartplaceholder/
---
## LayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) 메서드

새 차트를 포함하기 위해 레이아웃 슬라이드에 새로운 자리 표시자 도형을 추가합니다.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 새로운 자리 표시자 도형의 X 좌표입니다. |
| y | **float** | 새로운 자리 표시자 도형의 Y 좌표입니다. |
| width | **float** | 새로운 자리 표시자 도형의 너비입니다. |
| height | **float** | 새로운 자리 표시자 도형의 높이입니다. |

### 반환값

[IAutoShape](../../iautoshape/)을(를) Chart 자리 표시자와 함께 생성했습니다.

## 비고

다음 예제는 레이아웃 슬라이드에 Chart 자리 표시자 도형을 추가하는 방법을 보여줍니다.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## 또 보기

* typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAutoShape](../../iautoshape/)
* 클래스 [LayoutPlaceholderManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)