---
title: set_IncludeOleData()
second_title: Aspose.Slides for C++ API 参考
description: 将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。写入 bool.
type: docs
weight: 469
url: /zh/aspose.slides.export/pdfoptions/set_includeoledata/
---
## PdfOptions::set_IncludeOleData(bool) 方法


True to convert all OLE data from the presentation to embedded files in the resulting PDF. Write **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_IncludeOleData(bool value) override
```

## 备注


Default is **false**. 

Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## 另请参见

* 类 [PdfOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)