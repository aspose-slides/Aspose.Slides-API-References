---
title: get_RefreshThumbnail()
second_title: Aspose.Slides for C++ API 参考
description: 指定是否刷新演示文稿的缩略图。读取 bool。默认值为 true。
type: docs
weight: 53
url: /zh/aspose.slides.export/ipptxoptions/get_refreshthumbnail/
---
## IPptxOptions::get_RefreshThumbnail() method


指定是否刷新演示文稿的缩略图。读取 **bool**。默认值为 **true**。

```cpp
virtual bool Aspose::Slides::Export::IPptxOptions::get_RefreshThumbnail()=0
```

## 备注


当选项值为 **true** 时，将生成新的缩略图。

当选项值为 **false** 时，当前缩略图将保持不变。

示例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## 另请参见

* 类 [IPptxOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)