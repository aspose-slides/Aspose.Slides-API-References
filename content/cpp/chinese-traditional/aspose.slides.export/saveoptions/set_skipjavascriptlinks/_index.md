---
title: set_SkipJavaScriptLinks()
second_title: Aspose.Slides for C++ API 參考
description: 指定在保存簡報時是否跳過帶有 JavaScript 呼叫的超連結。寫入 bool。預設值為 false.
type: docs
weight: 118
url: /zh-hant/aspose.slides.export/saveoptions/set_skipjavascriptlinks/
---
## SaveOptions::set_SkipJavaScriptLinks(bool) 方法


指定在保存簡報時是否跳過帶有 JavaScript 呼叫的超連結。寫入 **bool**。預設值為 **false**。

```cpp
void Aspose::Slides::Export::SaveOptions::set_SkipJavaScriptLinks(bool value) override
```

## 備註


當此屬性設為 **true** 時，保存過程中將忽略帶有 JavaScript 呼叫的超連結。

當此屬性設為 **false** 時，所有超連結都將被保存。

範例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## 另請參閱

* 類別 [SaveOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)