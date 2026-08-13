---
title: AddVerticalTextPlaceholder()
second_title: Aspose.Slides C++ API 참조
description: 레이아웃 슬라이드에 텍스트 내용을 수직 방향으로 보관하기 위한 새 자리 표시자 모양을 추가합니다.
type: docs
weight: 40
url: /ko/aspose.slides/ilayoutplaceholdermanager/addverticaltextplaceholder/
---
## ILayoutPlaceholderManager::AddVerticalTextPlaceholder(float, float, float, float) 메서드

레이아웃 슬라이드에 텍스트 내용을 수직 방향으로 보관하기 위한 새 자리 표시자 모양을 추가합니다.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddVerticalTextPlaceholder(float x, float y, float width, float height)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 새 자리 표시자 모양의 X 좌표입니다. |
| y | **float** | 새 자리 표시자 모양의 Y 좌표입니다. |
| width | **float** | 새 자리 표시자 모양의 너비입니다. |
| height | **float** | 새 자리 표시자 모양의 높이입니다. |

### 반환값

텍스트 (Vertical) 자리 표시자가 있는 [IAutoShape](../../iautoshape/)가 생성되었습니다.

## 비고

다음 예제는 레이아웃 슬라이드에 텍스트 (Vertical) 자리 표시자 모양을 추가하는 방법을 보여줍니다.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalTextPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## 추가 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ILayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)