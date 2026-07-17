---
title: get_IncludeOleData()
second_title: Aspose.Slides for C++ API 参考
description: True 表示将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。读取 bool.
type: docs
weight: 456
url: /zh/aspose.slides.export/pdfoptions/get_includeoledata/
---
## PdfOptions::get_IncludeOleData() 方法


返回 true，将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。读取 **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_IncludeOleData() override
```

## 备注


默认是 **false**。 

示例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## 另见

* 类 [PdfOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)