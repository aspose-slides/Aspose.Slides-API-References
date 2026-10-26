---
title: get_SpellCheck()
second_title: Aspose.Slides for C++ API 參考
description: 取得一個值，用於指示文字段落的拼寫檢查是否已啟用。當此屬性設定為 false 時，文字元素的拼寫檢查會被抑制。當設定為 true 時，允許拼寫檢查。預設值為 false。
type: docs
weight: 599
url: /zh-hant/aspose.slides/baseportionformat/get_spellcheck/
---
## BasePortionFormat::get_SpellCheck() 方法

取得一個值，指示文字段落的拼寫檢查是否已啟用。當此屬性設定為 false 時，文字元素的拼寫檢查會被抑制。當設定為 true 時，允許拼寫檢查。預設值為 **false**。

```cpp
bool Aspose::Slides::BasePortionFormat::get_SpellCheck() override
```

## 備註

以下範例示範在保存簡報之前啟用 SpellCheck 旗標：

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Access the first portion of text inside the first shape on the first slide
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Enable spell checking for this text portion
portion->get_PortionFormat()->set_SpellCheck(true);
// Save the modified presentation
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## 另請參閱

* 類別 [BasePortionFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)