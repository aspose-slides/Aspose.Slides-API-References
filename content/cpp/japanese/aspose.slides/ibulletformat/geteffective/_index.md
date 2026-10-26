---
title: GetEffective()
second_title: Aspose.Slides for C++ API リファレンス
description: 継承が適用された実際の箇条書き書式データを取得します。
type: docs
weight: 248
url: /ja/aspose.slides/ibulletformat/geteffective/
---
## IBulletFormat::GetEffective() method

継承が適用された実際の箇条書き書式データを取得します。

```cpp
virtual System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::IBulletFormat::GetEffective()=0
```

### 戻り値

[IBulletFormatEffectiveData](../../ibulletformateffectivedata/) を返します。

## 備考


この例では、実際の箇条書き書式プロパティの取得方法を示します。
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

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* クラス [IBulletFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)