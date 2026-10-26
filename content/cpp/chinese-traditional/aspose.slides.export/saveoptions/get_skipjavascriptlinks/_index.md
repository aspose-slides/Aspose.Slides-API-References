---
title: get_SkipJavaScriptLinks()
second_title: Aspose.Slides for C++ API 參考文件
description: 指定在儲存簡報時是否跳過包含 JavaScript 呼叫的超連結。讀取 bool。預設值為 false.
type: docs
weight: 105
url: /zh-hant/aspose.slides.export/saveoptions/get_skipjavascriptlinks/
---
## SaveOptions::get_SkipJavaScriptLinks() 方法


指定在儲存簡報時是否跳過包含 JavaScript 呼叫的超連結。讀取 **bool**。預設值為 **false**。

```cpp
bool Aspose::Slides::Export::SaveOptions::get_SkipJavaScriptLinks() override
```

## 備註


當此屬性設為 **true** 時，包含 JavaScript 呼叫的超連結將在儲存時被忽略。

當此屬性設為 **false** 時，所有超連結將被儲存。

範例:
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