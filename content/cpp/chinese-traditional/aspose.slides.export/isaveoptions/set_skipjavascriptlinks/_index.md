---
title: set_SkipJavaScriptLinks()
second_title: Aspose.Slides for C++ API 參考
description: 指定在儲存簡報時是否跳過帶有 JavaScript 呼叫的超連結。寫入 bool。預設值為 false.
type: docs
weight: 118
url: /zh-hant/aspose.slides.export/isaveoptions/set_skipjavascriptlinks/
---
## ISaveOptions::set_SkipJavaScriptLinks(bool) 方法

指定在儲存簡報時是否跳過帶有 JavaScript 呼叫的超連結。寫入 **bool**。預設值為 **false**。

```cpp
virtual void Aspose::Slides::Export::ISaveOptions::set_SkipJavaScriptLinks(bool value)=0
```

## 備註

當此屬性設定為 **true** 時，帶有 JavaScript 呼叫的超連結在儲存時將被忽略。

當此屬性設定為 **false** 時，所有超連結都會被儲存。

範例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## 參見

* 類別 [ISaveOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)