---
title: GetEffective()
second_title: Aspose.Slides for C++ API リファレンス
description: 継承が適用された有効な背景データを取得します。
type: docs
weight: 118
url: /ja/aspose.slides/background/geteffective/
---
## Background::GetEffective() メソッド

継承が適用された有効な背景データを取得します。

```cpp
System::SharedPtr<IBackgroundEffectiveData> Aspose::Slides::Background::GetEffective() override
```

### Return Value

A [IBackgroundEffectiveData](../../ibackgroundeffectivedata/).

## 備考

この例は、有効な背景プロパティの取得方法を示しています。
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveBackground = pres->get_Slides()->idx_get(0)->get_Background()->GetEffective();
Console::WriteLine(String(u"Background fill type: ") + ObjectExt::ToString(effectiveBackground->get_FillFormat()->get_FillType()));
Console::WriteLine(String(u"Any effects applied: ") + !effectiveBackground->get_EffectFormat()->get_IsNoEffects());
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IBackgroundEffectiveData](../../ibackgroundeffectivedata/)
* クラス [Background](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)