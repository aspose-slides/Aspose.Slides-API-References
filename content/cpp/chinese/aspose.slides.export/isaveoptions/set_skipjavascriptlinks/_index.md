---
title: set_SkipJavaScriptLinks()
second_title: Aspose.Slides C++ API 参考
description: 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。写入 bool。默认值为 false.
type: docs
weight: 118
url: /zh/aspose.slides.export/isaveoptions/set_skipjavascriptlinks/
---
## ISaveOptions::set_SkipJavaScriptLinks(bool) 方法


指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。写入 **bool**。默认值为 **false**。

```cpp
virtual void Aspose::Slides::Export::ISaveOptions::set_SkipJavaScriptLinks(bool value)=0
```

## 备注


当此属性设置为 **true** 时，带有 JavaScript 调用的超链接将在保存时被忽略。

当此属性设置为 **false** 时，所有超链接将被保存。

示例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## 另见

* 类 [ISaveOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)