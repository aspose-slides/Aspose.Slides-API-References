---
title: GetEffective()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 상속이 적용된 실제 글머리표 서식 데이터를 가져옵니다.
type: docs
weight: 248
url: /ko/aspose.slides/bulletformat/geteffective/
---
## BulletFormat::GetEffective() 메서드

상속이 적용된 실제 글머리표 서식 데이터를 가져옵니다.

```cpp
System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::BulletFormat::GetEffective() override
```

### Return Value

다음은 [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)이다.

## Remarks

이 예제는 일부 실제 글머리표 서식 속성을 가져오는 방법을 보여줍니다.
```cpp
using namespace System;
using namespace Aspose::Slides;

auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<Aspose::Slides::IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveBulletFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->get_Bullet()->GetEffective();

Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveBulletFormat->get_Type()));
if (effectiveBulletFormat->get_Type() == Aspose::Slides::BulletType::Numbered)
{
    Console::WriteLine(String(u"Numbered style: ") + ObjectExt::ToString(effectiveBulletFormat->get_NumberedBulletStyle()));
    Console::WriteLine(String(u"Starting number: ") + effectiveBulletFormat->get_NumberedBulletStartWith());
}
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* Class [BulletFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)