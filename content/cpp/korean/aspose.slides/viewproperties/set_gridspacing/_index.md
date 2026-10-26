---
title: set_GridSpacing()
second_title: Aspose.Slides for C++ API 참조
description: 프레젠테이션 문서의 기본 그리드에 사용되어야 하는 그리드 간격을 포인트 단위로 설정합니다. float 형식으로 작성합니다.
type: docs
weight: 105
url: /ko/aspose.slides/viewproperties/set_gridspacing/
---
## ViewProperties::set_GridSpacing(float) method


프레젠테이션 문서의 기본이 되는 그리드에 사용되어야 하는 그리드 간격을 포인트 단위로 설정합니다. **float** 형식으로 씁니다.

```cpp
void Aspose::Slides::ViewProperties::set_GridSpacing(float value) override
```

## 비고


그리드 간격 값은 양수여야 합니다. 일반적인 값 범위는 1 mm (2.8349607 포인트)에서 2 인치 (144 포인트)까지입니다. 

다음 샘플 코드는 PowerPoint 프레젠테이션에서 그리드 간격을 변경하는 방법을 보여줍니다. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## 참고

* 클래스 [ViewProperties](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)