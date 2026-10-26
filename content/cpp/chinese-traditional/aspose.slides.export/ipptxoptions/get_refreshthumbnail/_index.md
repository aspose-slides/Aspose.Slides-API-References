---
title: get_RefreshThumbnail()
second_title: Aspose.Slides for C++ API 參考文件
description: 指定是否要刷新簡報縮圖。讀取 bool。預設值為 true。
type: docs
weight: 53
url: /zh-hant/aspose.slides.export/ipptxoptions/get_refreshthumbnail/
---
## IPptxOptions::get_RefreshThumbnail() method

指定是否要刷新簡報縮圖。讀取 **bool**。預設值為 **true**。

```cpp
virtual bool Aspose::Slides::Export::IPptxOptions::get_RefreshThumbnail()=0
```

## 備註

當選項值為 **true** 時，將產生新的縮圖。

當選項值為 **false** 時，當前的縮圖將保持原樣保存。

範例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## 另請參閱

* 類別 [IPptxOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)