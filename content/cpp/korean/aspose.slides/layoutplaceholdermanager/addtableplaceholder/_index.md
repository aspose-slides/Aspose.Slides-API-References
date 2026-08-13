---
title: AddTablePlaceholder()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 레이아웃 슬라이드에 표를 담기 위해 새로운 자리 표시자 모양을 추가합니다.
type: docs
weight: 79
url: /ko/aspose.slides/layoutplaceholdermanager/addtableplaceholder/
---
## LayoutPlaceholderManager::AddTablePlaceholder(float, float, float, float) method


레이아웃 슬라이드에 표를 담을 새로운 자리 표시자 모양을 추가합니다.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTablePlaceholder(float x, float y, float width, float height) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 새 자리 표시자 모양의 X 좌표입니다. |
| y | **float** | 새 자리 표시자 모양의 Y 좌표입니다. |
| width | **float** | 새 자리 표시자 모양의 너비입니다. |
| height | **float** | 새 자리 표시자 모양의 높이입니다. |

### 반환값

[IAutoShape](../../iautoshape/)를 [Table](../../table/) 자리 표시자로 생성했습니다.
## 비고



다음 예제는 레이아웃 슬라이드에 [Table](../../table/) 자리 표시자 모양을 추가하는 방법을 보여줍니다. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTablePlaceholder(20.0f, 20.0f, 500.0f, 200.0f);
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)