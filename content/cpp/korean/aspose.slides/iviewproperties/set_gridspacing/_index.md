---
title: set_GridSpacing()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션 문서의 기본 그리드에 사용해야 하는 그리드 간격을 포인트 단위로 설정합니다. float를 씁니다.
type: docs
weight: 105
url: /ko/aspose.slides/iviewproperties/set_gridspacing/
---
## IViewProperties::set_GridSpacing(float) 메서드

프레젠테이션 문서의 기본 그리드에 사용해야 하는 그리드 간격을 포인트 단위로 설정합니다. **float**를 씁니다.

```cpp
virtual void Aspose::Slides::IViewProperties::set_GridSpacing(float value)=0
```

## 비고

그리드 간격 값은 양수여야 합니다. 일반적인 값 범위는 1 mm (2.8349607 포인트)에서 2 인치 (144 포인트)까지입니다.

다음 샘플 코드는 PowerPoint 프레젠테이션에서 그리드 간격을 변경하는 방법을 보여줍니다.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## 참조

* 클래스 [IViewProperties](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)