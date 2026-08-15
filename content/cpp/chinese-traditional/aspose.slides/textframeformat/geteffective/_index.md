---
title: GetEffective()
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: 取得套用繼承後的有效文字框格式資料。
type: docs
weight: 391
url: /zh-hant/aspose.slides/textframeformat/geteffective/
---
## TextFrameFormat::GetEffective() 方法


取得套用繼承後的有效文字框格式資料。

```cpp
System::SharedPtr<ITextFrameFormatEffectiveData> Aspose::Slides::TextFrameFormat::GetEffective() override
```


### 傳回值

一個 [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/).


## 備註



此範例示範取得某些有效文字框格式屬性。
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

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/)
* 類別 [TextFrameFormat](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)