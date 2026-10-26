---
title: set_SpellCheck()
second_title: Aspose.Slides for C++ API 參考
description: 設定一個值以指示文字區段是否啟用拼寫檢查。當此屬性設為 false 時，文字元素的拼寫檢查會被抑制。設為 true 時，允許拼寫檢查。預設值為 false。
type: docs
weight: 612
url: /zh-hant/aspose.slides/ibaseportionformat/set_spellcheck/
---
## IBasePortionFormat::set_SpellCheck(bool) 方法

設定一個值以指示文字區段是否啟用拼寫檢查。當此屬性設為 false 時，文字元素的拼寫檢查會被抑制。設為 true 時，允許拼寫檢查。預設值為 **false**。

```cpp
virtual void Aspose::Slides::IBasePortionFormat::set_SpellCheck(bool value)=0
```

## 備註

以下範例示範在儲存簡報之前啟用 SpellCheck 標誌：
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// 存取第一張投影片上第一個圖形內的第一段文字
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// 為此文字區段啟用拼寫檢查
portion->get_PortionFormat()->set_SpellCheck(true);
// 儲存已修改的簡報
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## 另請參閱

* 類別 [IBasePortionFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)