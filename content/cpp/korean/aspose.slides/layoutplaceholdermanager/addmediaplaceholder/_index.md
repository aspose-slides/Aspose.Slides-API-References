---
title: AddMediaPlaceholder()
second_title: Aspose.Slides for C++ API 참조
description: 레이아웃 슬라이드에 미디어 개체를 보관하기 위한 새 자리 표시자 모양을 추가합니다.
type: docs
weight: 105
url: /ko/aspose.slides/layoutplaceholdermanager/addmediaplaceholder/
---
## LayoutPlaceholderManager::AddMediaPlaceholder(float, float, float, float) 메서드

레이아웃 슬라이드에 미디어 개체를 보관하기 위한 새 자리 표시자 모양을 추가합니다.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddMediaPlaceholder(float x, float y, float width, float height) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 새 자리 표시자 모양의 X 좌표입니다. |
| y | **float** | 새 자리 표시자 모양의 Y 좌표입니다. |
| width | **float** | 새 자리 표시자 모양의 너비입니다. |
| height | **float** | 새 자리 표시자 모양의 높이입니다. |

### 반환값

[IAutoShape](../../iautoshape/)가 미디어 자리 표시자와 함께 생성되었습니다.
## 비고

다음 예제는 레이아웃 슬라이드에 미디어 자리 표시자 모양을 추가하는 방법을 보여줍니다.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddMediaPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAutoShape](../../iautoshape/)
* 클래스 [LayoutPlaceholderManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)