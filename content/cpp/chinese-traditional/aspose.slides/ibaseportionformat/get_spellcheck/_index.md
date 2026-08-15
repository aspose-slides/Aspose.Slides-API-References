---
title: get_SpellCheck()
second_title: Aspose.Slides for C++ API 參考
description: 取得指示文字區段是否已啟用拼寫檢查的值。當此屬性設定為 false 時，文字元素的拼寫檢查會被抑制。設定為 true 時，允許拼寫檢查。預設值為 false。
type: docs
weight: 599
url: /zh-hant/aspose.slides/ibaseportionformat/get_spellcheck/
---
## IBasePortionFormat::get_SpellCheck() 方法


取得指示文字區段是否已啟用拼寫檢查的值。當此屬性設定為 false 時，文字元素的拼寫檢查會被抑制。設定為 true 時，允許拼寫檢查。預設值為 **false**。

```cpp
virtual bool Aspose::Slides::IBasePortionFormat::get_SpellCheck()=0
```

## 備註


下列範例示範在儲存簡報之前啟用 SpellCheck 標誌: 
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

* 類別 [IBasePortionFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)