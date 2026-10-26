---
title: set_CompressionLevel()
second_title: Aspose.Slides for C++ API 參考文件
description: "指定在儲存簡報文件時使用的壓縮等級。預設值為 CompressionLevel::Level6."
type: docs
weight: 92
url: /zh-hant/aspose.slides.export/ipptxoptions/set_compressionlevel/
---
## IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) 方法


指定儲存簡報文件時使用的壓縮等級。預設值為 [CompressionLevel::Level6](../../compressionlevel/)。

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value)=0
```

## 備註


較高的壓縮等級會產生較小的檔案，但需要較多的處理時間。實際的壓縮比例取決於簡報的內容。 

範例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## 另見

* 列舉 [CompressionLevel](../../compressionlevel/)
* 類別 [IPptxOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)