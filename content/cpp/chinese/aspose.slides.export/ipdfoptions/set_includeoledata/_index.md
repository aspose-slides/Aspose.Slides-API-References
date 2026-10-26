---
title: set_IncludeOleData()
second_title: Aspose.Slides C++ API 参考
description: True 表示将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。写入 bool。
type: docs
weight: 469
url: /zh/aspose.slides.export/ipdfoptions/set_includeoledata/
---
## IPdfOptions::set_IncludeOleData(bool) 方法

True 将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。写入 **bool**。

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_IncludeOleData(bool value)=0
```

## 备注

默认为 **false**。

示例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## 另见

* 类 [IPdfOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)