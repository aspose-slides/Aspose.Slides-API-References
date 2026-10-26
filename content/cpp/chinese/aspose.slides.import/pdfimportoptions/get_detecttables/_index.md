---
title: get_DetectTables()
second_title: Aspose.Slides for C++ API 参考
description: 确定在导入 pdf 文件时是否检测表格。
type: docs
weight: 1
url: /zh/aspose.slides.import/pdfimportoptions/get_detecttables/
---
## PdfImportOptions::get_DetectTables() const 方法


确定在导入 pdf 文件时是否检测表格。

```cpp
bool Aspose::Slides::Import::PdfImportOptions::get_DetectTables() const
```

## 备注


示例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(stream, options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## 另请参见

* 类 [PdfImportOptions](../)
* 命名空间 [Aspose::Slides::Import](../../)
* 库 [Aspose.Slides](../../../)