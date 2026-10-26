---
title: set_IncludeOleData()
second_title: Aspose.Slides for C++ API 參考文件
description: True 表示將簡報中的所有 OLE 資料轉換為產生的 PDF 中的嵌入檔案。寫入 bool.
type: docs
weight: 469
url: /zh-hant/aspose.slides.export/pdfoptions/set_includeoledata/
---
## PdfOptions::set_IncludeOleData(bool) 方法


True 代表將所有 OLE 資料從簡報轉換為產生的 PDF 中的嵌入檔案。寫入 **bool**。

```cpp
void Aspose::Slides::Export::PdfOptions::set_IncludeOleData(bool value) override
```

## 備註


預設為 **false**。 

範例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## 另見

* 類別 [PdfOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)