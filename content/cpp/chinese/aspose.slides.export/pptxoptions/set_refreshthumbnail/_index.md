---
title: set_RefreshThumbnail()
second_title: Aspose.Slides C++ API 参考
description: 指定是否刷新演示文稿缩略图。写入 bool。默认值为 true。
type: docs
weight: 66
url: /zh/aspose.slides.export/pptxoptions/set_refreshthumbnail/
---
## PptxOptions::set_RefreshThumbnail(bool) 方法

指定是否刷新演示文稿缩略图。写入 **bool**。默认值为 **true**。

```cpp
void Aspose::Slides::Export::PptxOptions::set_RefreshThumbnail(bool value) override
```

## 备注

当选项值为 **true** 时，将生成新的缩略图。

当选项值为 **false** 时，当前缩略图将保持不变保存。

示例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## 另见

* 类 [PptxOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)