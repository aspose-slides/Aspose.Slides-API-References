---
title: get_SkipJavaScriptLinks()
second_title: Aspose.Slides C++ API 参考
description: 指定在保存演示文稿时是否跳过包含 JavaScript 调用的超链接。读取 bool。默认值为 false。
type: docs
weight: 105
url: /zh/aspose.slides.export/isaveoptions/get_skipjavascriptlinks/
---
## ISaveOptions::get_SkipJavaScriptLinks() 方法

指定在保存演示文稿时是否跳过包含 JavaScript 调用的超链接。读取 **bool**。默认值为 **false**。

```cpp
virtual bool Aspose::Slides::Export::ISaveOptions::get_SkipJavaScriptLinks()=0
```

## 备注

当此属性设置为 **true** 时，保存时将忽略包含 JavaScript 调用的超链接。

当此属性设置为 **false** 时，所有超链接都将被保存。

示例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## 另请参见

* 类 [ISaveOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)