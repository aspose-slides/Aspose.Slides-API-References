---
title: get_InkEffect()
second_title: Aspose.Slides for C++ API 參考
description: "取得定義墨跡視覺樣式的墨水效果類型（例如，Galaxy、Gold、Silver）。該值會從筆刷屬性 \"inkEffects\" 解析。如果未指定已識別的效果，InkEffectType::NotDefined 將被返回。"
type: docs
weight: 53
url: /zh-hant/aspose.slides.ink/iinkbrush/get_inkeffect/
---
## IInkBrush::get_InkEffect() 方法

取得定義墨跡視覺樣式的墨水效果類型（例如，Galaxy、Gold、Silver）。該值是從筆刷屬性 "inkEffects" 解析的。如果未指定已識別的效果，[InkEffectType::NotDefined](../../inkeffecttype/) 將被返回。

```cpp
virtual InkEffectType Aspose::Slides::Ink::IInkBrush::get_InkEffect()=0
```

## 備註

範例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<Ink> ink = System::AsCast<Ink>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IInkBrush> brush = ink->get_Traces()->idx_get(0)->get_Brush();
System::Console::WriteLine(u"InkEffects = {0}", brush->get_InkEffect());
```

## 另見

* 列舉 [InkEffectType](../../inkeffecttype/)
* 類別 [IInkBrush](../)
* 命名空間 [Aspose::Slides::Ink](../../)
* 函式庫 [Aspose.Slides](../../../)