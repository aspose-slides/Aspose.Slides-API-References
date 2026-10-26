---
title: get_IncludeOleData()
second_title: Aspose.Slides for C++ API 參考文件
description: True 用於將簡報中的所有 OLE 資料轉換為產生的 PDF 中的嵌入檔案。讀取 bool.
type: docs
weight: 456
url: /zh-hant/aspose.slides.export/ipdfoptions/get_includeoledata/
---
## IPdfOptions::get_IncludeOleData() 方法

True 用於將簡報中的所有 OLE 資料轉換為產生的 PDF 中的嵌入檔案。讀取 **bool**。

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_IncludeOleData()=0
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

* 類別 [IPdfOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)