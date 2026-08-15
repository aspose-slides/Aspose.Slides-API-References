---
title: set_RefreshThumbnail()
second_title: Aspose.Slides for C++ API 參考
description: 指定是否要重新整理簡報縮圖。寫入 bool。預設值為 true。
type: docs
weight: 66
url: /zh-hant/aspose.slides.export/pptxoptions/set_refreshthumbnail/
---
## PptxOptions::set_RefreshThumbnail(bool) 方法

指定是否要重新整理簡報縮圖。寫入 **bool**。預設值為 **true**。

```cpp
void Aspose::Slides::Export::PptxOptions::set_RefreshThumbnail(bool value) override
```

## 備註

當選項值為 **true** 時，將產生新的縮圖。

當選項值為 **false** 時，現有的縮圖將照原樣儲存。

範例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## 另請參閱

* 類別 [PptxOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)