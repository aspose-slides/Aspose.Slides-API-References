---
title: get_RefreshThumbnail()
second_title: Aspose.Slides for C++ API 參考文件
description: 指定是否要重新整理簡報縮圖。讀取 bool。預設值為 true。
type: docs
weight: 53
url: /zh-hant/aspose.slides.export/pptxoptions/get_refreshthumbnail/
---
## PptxOptions::get_RefreshThumbnail() 方法


指定是否要重新整理簡報縮圖。讀取 **bool**。預設值為 **true**。

```cpp
bool Aspose::Slides::Export::PptxOptions::get_RefreshThumbnail() override
```

## 備註


當選項值為 **true** 時，將產生新縮圖。

當選項值為 **false** 時，當前縮圖將保持不變。

範例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## 參見

* 類別 [PptxOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 程式庫 [Aspose.Slides](../../../)