---
title: AddTextPlaceholder()
second_title: Aspose.Slides for C++ API 참조
description: 레이아웃 슬라이드에 텍스트 내용을 담을 새로운 플레이스홀더 도형을 추가합니다.
type: docs
weight: 27
url: /ko/aspose.slides/ilayoutplaceholdermanager/addtextplaceholder/
---
## ILayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) 메서드

텍스트 콘텐츠를 보관하기 위해 레이아웃 슬라이드에 새 플레이스홀더 도형을 추가합니다.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 새 플레이스홀더 도형의 X 좌표입니다. |
| y | **float** | 새 플레이스홀더 도형의 Y 좌표입니다. |
| width | **float** | 새 플레이스홀더 도형의 너비입니다. |
| height | **float** | 새 플레이스홀더 도형의 높이입니다. |

### 반환 값

[IAutoShape](../../iautoshape/)를 텍스트 플레이스홀더와 함께 생성했습니다.

## 비고

다음 예제는 레이아웃 슬라이드에 텍스트 플레이스홀더 도형을 추가하는 방법을 보여줍니다. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAutoShape](../../iautoshape/)
* 클래스 [ILayoutPlaceholderManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)