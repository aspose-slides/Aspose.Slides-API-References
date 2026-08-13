---
title: GetEffective()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 상속이 적용된 효과적인 글머리표 서식 데이터를 가져옵니다.
type: docs
weight: 248
url: /ko/aspose.slides/ibulletformat/geteffective/
---
## IBulletFormat::GetEffective() 메서드


상속이 적용된 효과적인 글머리표 서식 데이터를 가져옵니다.

```cpp
virtual System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::IBulletFormat::GetEffective()=0
```


### 반환 값

하나의 [IBulletFormatEffectiveData](../../ibulletformateffectivedata/).
## 비고



이 예제는 일부 효과적인 글머리표 형식 속성을 가져오는 방법을 보여줍니다. 
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

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* 클래스 [IBulletFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)