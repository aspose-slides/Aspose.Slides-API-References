---
title: AddVerticalTextPlaceholder()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 레이아웃 슬라이드에 새로운 자리 표시자 모양을 추가하여 텍스트 내용을 수직 방향으로 보관합니다.
type: docs
weight: 40
url: /ko/aspose.slides/layoutplaceholdermanager/addverticaltextplaceholder/
---
## LayoutPlaceholderManager::AddVerticalTextPlaceholder(float, float, float, float) 메서드

새로운 자리 표시자 모양을 레이아웃 슬라이드에 추가하여 텍스트 내용을 수직 방향으로 보관합니다.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalTextPlaceholder(float x, float y, float width, float height) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 새 자리 표시자 모양의 X 좌표입니다. |
| y | **float** | 새 자리 표시자 모양의 Y 좌표입니다. |
| width | **float** | 새 자리 표시자 모양의 너비입니다. |
| height | **float** | 새 자리 표시자 모양의 높이입니다. |

### 반환값

[IAutoShape](../../iautoshape/)를 Text (Vertical) 자리 표시자와 함께 생성했습니다.

## 비고

다음 예제는 레이아웃 슬라이드에 Text (Vertical) 자리 표시자 모양을 추가하는 방법을 보여줍니다. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalTextPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## 또 보기

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAutoShape](../../iautoshape/)
* 클래스 [LayoutPlaceholderManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)