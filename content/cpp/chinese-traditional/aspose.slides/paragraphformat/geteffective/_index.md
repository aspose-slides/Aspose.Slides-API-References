---
title: GetEffective()
second_title: Aspose.Slides for C++ API 參考手冊
description: 取得套用繼承後的有效段落格式資料。
type: docs
weight: 365
url: /zh-hant/aspose.slides/paragraphformat/geteffective/
---
## ParagraphFormat::GetEffective() 方法


取得套用繼承後的有效段落格式資料。

```cpp
System::SharedPtr<IParagraphFormatEffectiveData> Aspose::Slides::ParagraphFormat::GetEffective() override
```


### 返回值

一個 [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/)。
## 備註



此範例說明如何取得某些有效的段落格式屬性。
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveParagraphFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->GetEffective();

Console::WriteLine(String(u"Text alignment: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Alignment()));
Console::WriteLine(String(u"Indent: ") + effectiveParagraphFormat->get_Indent());
Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Bullet()->get_Type()));
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/)
* Class [ParagraphFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)