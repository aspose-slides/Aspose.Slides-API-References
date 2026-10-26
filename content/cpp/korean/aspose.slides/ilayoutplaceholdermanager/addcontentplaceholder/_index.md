---
title: AddContentPlaceholder()
second_title: Aspose.Slides for C++ API 참조
description: 레이아웃 슬라이드에 새로운 자리표시자 모양을 추가하여 사진, 표, 미디어 또는 텍스트와 같은 콘텐츠를 보관합니다.
type: docs
weight: 1
url: /ko/aspose.slides/ilayoutplaceholdermanager/addcontentplaceholder/
---
## ILayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) 메서드

새로운 자리표시자 모양을 레이아웃 슬라이드에 추가하여 사진, 표, 미디어 또는 텍스트와 같은 콘텐츠를 보관합니다.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 새로운 자리표시자 모양의 X 좌표. |
| y | **float** | 새로운 자리표시자 모양의 Y 좌표. |
| width | **float** | 새로운 자리표시자 모양의 너비. |
| height | **float** | 새로운 자리표시자 모양의 높이. |

### 반환 값

[IAutoShape](../../iautoshape/)가 콘텐츠 자리표시자와 함께 생성되었습니다.

## 비고

다음 예제는 레이아웃 슬라이드에 콘텐츠 자리표시자 모양을 추가하는 방법을 보여줍니다. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAutoShape](../../iautoshape/)
* 클래스 [ILayoutPlaceholderManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)