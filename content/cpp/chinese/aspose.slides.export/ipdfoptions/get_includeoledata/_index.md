---
title: get_IncludeOleData()
second_title: Aspose.Slides C++ API 参考
description: True 表示将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。读取 bool。
type: docs
weight: 456
url: /zh/aspose.slides.export/ipdfoptions/get_includeoledata/
---
## IPdfOptions::get_IncludeOleData() 方法


True 表示将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。读取 **bool**。

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_IncludeOleData()=0
```

## 备注


默认是 **false**。 

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