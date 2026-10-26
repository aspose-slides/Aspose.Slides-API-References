---
title: AddPicturePlaceholder()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 레이아웃 슬라이드에 그림을 보관하기 위한 새로운 플레이스홀더 도형을 추가합니다.
type: docs
weight: 53
url: /ko/aspose.slides/layoutplaceholdermanager/addpictureplaceholder/
---
## LayoutPlaceholderManager::AddPicturePlaceholder(float, float, float, float) 메서드

레이아웃 슬라이드에 그림을 보관하기 위한 새로운 플레이스홀더 도형을 추가합니다.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddPicturePlaceholder(float x, float y, float width, float height) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 새 플레이스홀더 도형의 X 좌표입니다. |
| y | **float** | 새 플레이스홀더 도형의 Y 좌표입니다. |
| width | **float** | 새 플레이스홀더 도형의 너비입니다. |
| height | **float** | 새 플레이스홀더 도형의 높이입니다. |

### 반환값

[IAutoShape](../../iautoshape/)를 생성하고 [Picture](../../picture/) 플레이스홀더를 포함합니다.

## 비고

다음 예제는 레이아웃 슬라이드에 [Picture](../../picture/) 플레이스홀더 도형을 추가하는 방법을 보여줍니다.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddPicturePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAutoShape](../../iautoshape/)
* 클래스 [LayoutPlaceholderManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)