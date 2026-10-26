---
title: set_SkipJavaScriptLinks()
second_title: Aspose.Slides for C++ API 参考
description: 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。写入 bool。默认值为 false。
type: docs
weight: 118
url: /zh/aspose.slides.export/saveoptions/set_skipjavascriptlinks/
---
## SaveOptions::set_SkipJavaScriptLinks(bool) 方法

指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。写入 **bool**。默认值为 **false**。

```cpp
void Aspose::Slides::Export::SaveOptions::set_SkipJavaScriptLinks(bool value) override
```

## 备注

当此属性设置为 **true** 时，保存时会忽略带有 JavaScript 调用的超链接。

当此属性设置为 **false** 时，所有超链接都会被保存。

示例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## 另见

* 类 [SaveOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)