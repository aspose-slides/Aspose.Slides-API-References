---
title: GetEffective()
second_title: Aspose.Slides for C++ API 參考
description: 取得套用繼承後的有效線條格式資料。
type: docs
weight: 417
url: /zh-hant/aspose.slides/lineformat/geteffective/
---
## LineFormat::GetEffective() 方法

取得套用繼承後的有效線條格式資料。

```cpp
System::SharedPtr<ILineFormatEffectiveData> Aspose::Slides::LineFormat::GetEffective() override
```

### 傳回值

一個 [ILineFormatEffectiveData](../../ilineformateffectivedata/).

## 備註

本範例示範取得圖形的有效線條格式屬性。
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveLineFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_LineFormat()->GetEffective();

Console::WriteLine(String(u"Style: ") + ObjectExt::ToString(effectiveLineFormat->get_Style()));
Console::WriteLine(String(u"Width: ") + effectiveLineFormat->get_Width());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectiveLineFormat->get_FillFormat()->get_FillType()));
```

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [ILineFormatEffectiveData](../../ilineformateffectivedata/)
* 類別 [LineFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)