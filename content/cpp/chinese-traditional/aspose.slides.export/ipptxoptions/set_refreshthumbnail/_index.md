---
title: set_RefreshThumbnail()
second_title: Aspose.Slides for C++ API 參考文件
description: 指定是否要重新整理簡報的縮圖。寫入 bool。預設值為 true。
type: docs
weight: 66
url: /zh-hant/aspose.slides.export/ipptxoptions/set_refreshthumbnail/
---
## IPptxOptions::set_RefreshThumbnail(bool) 方法


指定是否要重新整理簡報的縮圖。寫入 **bool**。預設值為 **true**。

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_RefreshThumbnail(bool value)=0
```

## 備註


當選項值為 **true** 時，將產生新的縮圖。

當選項值為 **false** 時，當前的縮圖將原樣保存。

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