---
title: AddOnlineImagePlaceholder()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 온라인 이미지를 보관하기 위해 레이아웃 슬라이드에 새 자리 표시자 모양을 추가합니다.
type: docs
weight: 118
url: /ko/aspose.slides/layoutplaceholdermanager/addonlineimageplaceholder/
---
## LayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) 메서드

온라인 이미지를 보관하기 위해 레이아웃 슬라이드에 새 자리 표시자 모양을 추가합니다.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height) override
```

### Arguments

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | **float** | 새 자리 표시자 모양의 X 좌표입니다. |
| y | **float** | 새 자리 표시자 모양의 Y 좌표입니다. |
| width | **float** | 새 자리 표시자 모양의 너비입니다. |
| height | **float** | 새 자리 표시자 모양의 높이입니다. |

### Return Value

온라인 이미지 자리 표시자를 사용하여 [IAutoShape](../../iautoshape/)를 생성했습니다.

## Remarks

다음 예제에서는 레이아웃 슬라이드에 온라인 이미지 자리 표시자 모양을 추가하는 방법을 보여줍니다. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)