---
title: AddContentPlaceholder()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 레이아웃 슬라이드에 새 플레이스홀더 모양을 추가하여 그림, 표, 미디어 또는 텍스트와 같은 콘텐츠를 보관합니다.
type: docs
weight: 1
url: /ko/aspose.slides/layoutplaceholdermanager/addcontentplaceholder/
---
## LayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) method

새로운 플레이스홀더 모양을 레이아웃 슬라이드에 추가하여 그림, 표, 미디어 또는 텍스트와 같은 콘텐츠를 보관합니다.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 새 플레이스홀더 모양의 X 좌표입니다. |
| y | **float** | 새 플레이스홀더 모양의 Y 좌표입니다. |
| width | **float** | 새 플레이스홀더 모양의 너비입니다. |
| height | **float** | 새 플레이스홀더 모양의 높이입니다. |

### 반환 값

[IAutoShape](../../iautoshape/)을(를) Content 자리표시자로 생성했습니다.

## 비고

다음 예제는 레이아웃 슬라이드에 Content 플레이스홀더 모양을 추가하는 방법을 보여줍니다. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)