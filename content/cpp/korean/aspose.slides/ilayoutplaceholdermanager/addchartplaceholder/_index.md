---
title: AddChartPlaceholder()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 차트를 보관하기 위해 레이아웃 슬라이드에 새로운 플레이스홀더 도형을 추가합니다.
type: docs
weight: 66
url: /ko/aspose.slides/ilayoutplaceholdermanager/addchartplaceholder/
---
## ILayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) 메서드

차트를 보관하기 위해 레이아웃 슬라이드에 새로운 플레이스홀더 도형을 추가합니다.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | **float** | 새로운 플레이스홀더 도형의 X 좌표입니다. |
| y | **float** | 새로운 플레이스홀더 도형의 Y 좌표입니다. |
| width | **float** | 새로운 플레이스홀더 도형의 너비입니다. |
| height | **float** | 새로운 플레이스홀더 도형의 높이입니다. |

### 반환 값

Chart 플레이스홀더가 포함된 [IAutoShape](../../iautoshape/)를 생성했습니다.

## 비고

다음 예제는 레이아웃 슬라이드에 차트 플레이스홀더 도형을 추가하는 방법을 보여줍니다. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAutoShape](../../iautoshape/)
* 클래스 [ILayoutPlaceholderManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)