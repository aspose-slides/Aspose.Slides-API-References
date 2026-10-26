---
title: AddTablePlaceholder()
second_title: Aspose.Slides for C++ API 참조
description: 레이아웃 슬라이드에 테이블을 보관하기 위한 새로운 플레이스홀더 형태를 추가합니다.
type: docs
weight: 79
url: /ko/aspose.slides/ilayoutplaceholdermanager/addtableplaceholder/
---
## ILayoutPlaceholderManager::AddTablePlaceholder(float, float, float, float) 메서드

레이아웃 슬라이드에 테이블을 보관하기 위한 새로운 플레이스홀더 형태를 추가합니다.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddTablePlaceholder(float x, float y, float width, float height)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 새 플레이스홀더 형태의 X 좌표. |
| y | **float** | 새 플레이스홀더 형태의 Y 좌표. |
| width | **float** | 새 플레이스홀더 형태의 너비. |
| height | **float** | 새 플레이스홀더 형태의 높이. |

### 반환 값

[IAutoShape](../../iautoshape/)이(가) [Table](../../table/) 플레이스홀더와 함께 생성되었습니다.

## 비고

다음 예제는 [Table](../../table/) 플레이스홀더 형태를 레이아웃 슬라이드에 추가하는 방법을 보여줍니다.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTablePlaceholder(20.0f, 20.0f, 500.0f, 200.0f);
```

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAutoShape](../../iautoshape/)
* 클래스 [ILayoutPlaceholderManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)