---
title: Shapes()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Presentation에서 Shape의 모든 인스턴스를 수집합니다.
type: docs
weight: 1
url: /ko/aspose.slides.lowcode/collect/shapes/
---
## Collect::Shapes(System::SharedPtr\<Presentation\>) 메서드


[Shape](../../../aspose.slides/shape/)의 모든 인스턴스를 [Presentation](../../../aspose.slides/presentation/)에서 수집합니다.

```cpp
static System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Shape>>> Aspose::Slides::LowCode::Collect::Shapes(System::SharedPtr<Presentation> pres)
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/)를 사용하여 도형을 수집합니다. |

### 반환값

프레젠테이션에 포함된 모든 도형의 컬렉션
## 비고




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // shape가 AutoShape인 경우, 검은색 실선 테두리를 추가합니다
    if (System::ObjectExt::Is<AutoShape>(shape))
    {
        auto autoShape = System::AsCast<AutoShape>(shape);
        autoShape->get_LineFormat()->set_Style(LineStyle::Single);
        autoShape->get_LineFormat()->set_Width(10.0f);
        autoShape->get_LineFormat()->get_FillFormat()->set_FillType(FillType::Solid);
        autoShape->get_LineFormat()->get_FillFormat()->get_SolidFillColor()->set_Color(Color::get_Black());
    }
}

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```




## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 클래스 [Shape](../../../aspose.slides/shape/)
* 클래스 [Presentation](../../../aspose.slides/presentation/)
* 클래스 [Collect](../)
* 네임스페이스 [Aspose::Slides::LowCode](../../)
* 라이브러리 [Aspose.Slides](../../../)