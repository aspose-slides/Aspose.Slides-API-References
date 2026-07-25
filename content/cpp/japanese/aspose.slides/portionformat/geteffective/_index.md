---
title: GetEffective()
second_title: Aspose.Slides for C++ API リファレンス
description: 継承が適用された有効な部分書式データを取得します。
type: docs
weight: 131
url: /ja/aspose.slides/portionformat/geteffective/
---
## PortionFormat::GetEffective() メソッド

Gets effective portion formatting data with the inheritance applied.

```cpp
System::SharedPtr<IPortionFormatEffectiveData> Aspose::Slides::PortionFormat::GetEffective() override
```

### 戻り値

[IPortionFormatEffectiveData](../../iportionformateffectivedata/).
## 備考

This example demonstrates getting some effective portion format properties. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectivePortionFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)->get_PortionFormat()->GetEffective();

Console::WriteLine(String(u"Latin font: ") + effectivePortionFormat->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Font height: ") + effectivePortionFormat->get_FontHeight());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectivePortionFormat->get_FillFormat()->get_FillType()));
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IPortionFormatEffectiveData](../../iportionformateffectivedata/)
* クラス [PortionFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)