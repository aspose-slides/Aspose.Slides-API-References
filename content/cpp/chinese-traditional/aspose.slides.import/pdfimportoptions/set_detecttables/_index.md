---
title: set_DetectTables()
second_title: Aspose.Slides for C++ API 參考文件
description: 決定在匯入 pdf 檔案時是否偵測表格。
type: docs
weight: 14
url: /zh-hant/aspose.slides.import/pdfimportoptions/set_detecttables/
---
## PdfImportOptions::set_DetectTables(bool) 方法


判斷在匯入 pdf 檔案時是否偵測表格。

```cpp
void Aspose::Slides::Import::PdfImportOptions::set_DetectTables(bool value)
```

## 備註


範例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(stream, options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## 另見

* 類別 [PdfImportOptions](../)
* 命名空間 [Aspose::Slides::Import](../../)
* 函式庫 [Aspose.Slides](../../../)