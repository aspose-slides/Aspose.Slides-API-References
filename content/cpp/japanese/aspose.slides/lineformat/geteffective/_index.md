---
title: GetEffective()
second_title: Aspose.Slides for C++ API リファレンス
description: 継承が適用された有効な線書式データを取得します。
type: docs
weight: 417
url: /ja/aspose.slides/lineformat/geteffective/
---
## LineFormat::GetEffective() メソッド

継承が適用された有効な線の書式データを取得します。

```cpp
System::SharedPtr<ILineFormatEffectiveData> Aspose::Slides::LineFormat::GetEffective() override
```

### 戻り値

[ILineFormatEffectiveData](../../ilineformateffectivedata/)。

## 備考

この例は、シェイプの有効な線書式プロパティの取得方法を示しています。
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveLineFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_LineFormat()->GetEffective();

Console::WriteLine(String(u"Style: ") + ObjectExt::ToString(effectiveLineFormat->get_Style()));
Console::WriteLine(String(u"Width: ") + effectiveLineFormat->get_Width());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectiveLineFormat->get_FillFormat()->get_FillType()));
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ILineFormatEffectiveData](../../ilineformateffectivedata/)
* クラス [LineFormat](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)