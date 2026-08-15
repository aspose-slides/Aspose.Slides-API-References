---
title: set_IncludeOleData()
second_title: Aspose.Slides for C++ API 參考
description: True 代表將簡報中的所有 OLE 資料轉換為最終 PDF 中的嵌入檔案。寫入 bool.
type: docs
weight: 469
url: /zh-hant/aspose.slides.export/ipdfoptions/set_includeoledata/
---
## IPdfOptions::set_IncludeOleData(bool) 方法


True 代表將簡報中的所有 OLE 資料轉換為最終 PDF 中的嵌入檔案。寫入 **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_IncludeOleData(bool value)=0
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

## 參見

* 類別 [IPdfOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 程式庫 [Aspose.Slides](../../../)