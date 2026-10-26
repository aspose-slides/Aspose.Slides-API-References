---
title: AddOnlineImagePlaceholder()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 온라인 이미지를 포함하기 위해 레이아웃 슬라이드에 새로운 자리표시자 모양을 추가합니다.
type: docs
weight: 118
url: /ko/aspose.slides/ilayoutplaceholdermanager/addonlineimageplaceholder/
---
## ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) 메서드


새로운 온라인 이미지를 포함하기 위해 레이아웃 슬라이드에 새로운 자리표시자 모양을 추가합니다.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 새 자리표시자 모양의 X 좌표입니다. |
| y | **float** | 새 자리표시자 모양의 Y 좌표입니다. |
| width | **float** | 새 자리표시자 모양의 너비입니다. |
| height | **float** | 새 자리표시자 모양의 높이입니다. |

### 반환 값

[IAutoShape](../../iautoshape/)가 온라인 이미지 자리표시자와 함께 생성되었습니다.
## 비고

다음 예제는 레이아웃 슬라이드에 온라인 이미지 자리표시자 모양을 추가하는 방법을 보여줍니다.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAutoShape](../../iautoshape/)
* 클래스 [ILayoutPlaceholderManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)