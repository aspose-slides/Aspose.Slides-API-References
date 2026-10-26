---
title: GetEffective()
second_title: Aspose.Slides の C++ 用 API リファレンス
description: 継承が適用された有効な箇条書き書式データを取得します。
type: docs
weight: 248
url: /ja/aspose.slides/bulletformat/geteffective/
---
## BulletFormat::GetEffective() メソッド


Gets effective bullet formatting data with the inheritance applied.

```cpp
System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::BulletFormat::GetEffective() override
```


### 戻り値

A [IBulletFormatEffectiveData](../../ibulletformateffectivedata/).
## 備考



This example demonstrates getting some effective bullet format properties. 
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

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* クラス [BulletFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)