---
title: GetEffective()
second_title: Aspose.Slides for C++ API リファレンス
description: 継承が適用された有効なテキストフレームの書式設定データを取得します。
type: docs
weight: 391
url: /ja/aspose.slides/textframeformat/geteffective/
---
## TextFrameFormat::GetEffective() メソッド

継承が適用された有効なテキストフレームの書式設定データを取得します。

```cpp
System::SharedPtr<ITextFrameFormatEffectiveData> Aspose::Slides::TextFrameFormat::GetEffective() override
```

### 戻り値

A [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/).

## 備考

この例は、有効なテキストフレーム書式設定プロパティのいくつかを取得する方法を示しています。

```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveTextFrameFormat = shape->get_TextFrame()->get_TextFrameFormat()->GetEffective();

Console::WriteLine(String(u"Anchoring type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_AnchoringType()));
Console::WriteLine(String(u"Autofit type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_AutofitType()));
Console::WriteLine(String(u"Text vertical type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_TextVerticalType()));
Console::WriteLine(u"Margins");
Console::WriteLine(String(u"   Left: ") + effectiveTextFrameFormat->get_MarginLeft());
Console::WriteLine(String(u"   Top: ") + effectiveTextFrameFormat->get_MarginTop());
Console::WriteLine(String(u"   Right: ") + effectiveTextFrameFormat->get_MarginRight());
Console::WriteLine(String(u"   Bottom: ") + effectiveTextFrameFormat->get_MarginBottom());
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/)
* クラス [TextFrameFormat](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)