---
title: set_SpellCheck()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定一個值，用於指示文字部分是否啟用拼寫檢查。當此屬性設定為 false 時，文字元素的拼寫檢查將被抑制。當設定為 true 時，允許拼寫檢查。預設值為 false。
type: docs
weight: 612
url: /zh-hant/aspose.slides/baseportionformat/set_spellcheck/
---
## BasePortionFormat::set_SpellCheck(bool) 方法


設定一個值，用來指示文字部分是否啟用拼寫檢查。當此屬性設為 false 時，文字元素的拼寫檢查將被抑制。當設為 true 時，允許拼寫檢查。預設值為 **false**。

```cpp
void Aspose::Slides::BasePortionFormat::set_SpellCheck(bool value) override
```

## 備註


以下範例示範在儲存簡報之前啟用 SpellCheck 旗標： 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// 存取第一張投影片上第一個圖形內的第一段文字
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// 為此文字段落啟用拼寫檢查
portion->get_PortionFormat()->set_SpellCheck(true);
// 儲存已修改的簡報
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## 另請參閱

* 類別 [BasePortionFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)