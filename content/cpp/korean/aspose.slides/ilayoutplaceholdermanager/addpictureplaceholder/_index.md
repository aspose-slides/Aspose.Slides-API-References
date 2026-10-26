---
title: AddPicturePlaceholder()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 레이아웃 슬라이드에 그림을 담을 새로운 자리표시자 도형을 추가합니다.
type: docs
weight: 53
url: /ko/aspose.slides/ilayoutplaceholdermanager/addpictureplaceholder/
---
## ILayoutPlaceholderManager::AddPicturePlaceholder(float, float, float, float) 메서드

레이아웃 슬라이드에 그림을 담을 새로운 자리표시자 도형을 추가합니다.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddPicturePlaceholder(float x, float y, float width, float height)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 새 자리표시자 도형의 X 좌표입니다. |
| y | **float** | 새 자리표시자 도형의 Y 좌표입니다. |
| width | **float** | 새 자리표시자 도형의 너비입니다. |
| height | **float** | 새 자리표시자 도형의 높이입니다. |

### 반환값

생성된 [IAutoShape](../../iautoshape/)에 [Picture](../../picture/) 자리표시자가 포함됩니다.

## 비고

다음 예제는 레이아웃 슬라이드에 [Picture](../../picture/) 자리표시자 도형을 추가하는 방법을 보여줍니다.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddPicturePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## 또 보기

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAutoShape](../../iautoshape/)
* 클래스 [ILayoutPlaceholderManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)