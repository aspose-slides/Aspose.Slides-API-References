---
title: get_DetectTables()
second_title: Aspose.Slides for C++ API 參考
description: 判斷在匯入 PDF 檔案時是否偵測表格。
type: docs
weight: 1
url: /zh-hant/aspose.slides.import/pdfimportoptions/get_detecttables/
---
## PdfImportOptions::get_DetectTables() const 方法


判斷在匯入 pdf 檔案時是否偵測表格。

```cpp
bool Aspose::Slides::Import::PdfImportOptions::get_DetectTables() const
```

## 備註


範例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(stream, options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## 參見

* 類別 [PdfImportOptions](../)
* 命名空間 [Aspose::Slides::Import](../../)
* 函式庫 [Aspose.Slides](../../../)