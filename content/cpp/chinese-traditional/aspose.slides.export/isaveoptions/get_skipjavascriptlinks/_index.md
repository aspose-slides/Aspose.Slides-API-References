---
title: get_SkipJavaScriptLinks()
second_title: Aspose.Slides for C++ API 參考
description: 指定在儲存簡報時是否跳過帶有 JavaScript 呼叫的超連結。讀取 bool。預設值為 false.
type: docs
weight: 105
url: /zh-hant/aspose.slides.export/isaveoptions/get_skipjavascriptlinks/
---
## ISaveOptions::get_SkipJavaScriptLinks() 方法


指定在儲存簡報時是否跳過帶有 JavaScript 呼叫的超連結。讀取 **bool**。預設值為 **false**。

```cpp
virtual bool Aspose::Slides::Export::ISaveOptions::get_SkipJavaScriptLinks()=0
```

## 備註


當此屬性設定為 **true** 時，儲存時會忽略帶有 JavaScript 呼叫的超連結。

當此屬性設定為 **false** 時，所有超連結皆會被儲存。

範例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## 另請參閱

* 類別 [ISaveOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 程式庫 [Aspose.Slides](../../../)