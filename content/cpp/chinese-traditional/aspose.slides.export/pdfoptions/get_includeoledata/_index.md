---
title: get_IncludeOleData()
second_title: Aspose.Slides for C++ API 參考文件
description: True 表示將簡報中的所有 OLE 資料轉換為結果 PDF 中的嵌入檔案。讀取 bool.
type: docs
weight: 456
url: /zh-hant/aspose.slides.export/pdfoptions/get_includeoledata/
---
## PdfOptions::get_IncludeOleData() 方法

True 表示將簡報中的所有 OLE 資料轉換為結果 PDF 中的嵌入檔案。讀取 **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_IncludeOleData() override
```

## 備註

預設為 **false**。 

範例： 
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