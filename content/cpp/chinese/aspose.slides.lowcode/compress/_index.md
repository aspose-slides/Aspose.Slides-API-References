---
title: Compress
second_title: Aspose.Slides for C++ API 参考
description: 表示一组旨在压缩 Presentation 的方法。
type: docs
weight: 14
url: /zh/aspose.slides.lowcode/compress/
---
## Compress 类

Represents a group of methods intended to compress [Presentation](../../aspose.slides/presentation/).

```cpp
class Compress
```

## 方法

| 方法 | 描述 |
| --- | --- |
|  [Compress](./compress/)() |  |
| static void [CompressEmbeddedFonts](./compressembeddedfonts/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | 通过删除嵌入字体中未使用的字符，对 [Presentation](../../aspose.slides/presentation/) 进行压缩。 |
| static void [RemoveUnusedLayoutSlides](./removeunusedlayoutslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | 通过删除未使用的布局幻灯片，对 [Presentation](../../aspose.slides/presentation/) 进行压缩。 |
| static void [RemoveUnusedMasterSlides](./removeunusedmasterslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | 通过删除未使用的母版幻灯片，对 [Presentation](../../aspose.slides/presentation/) 进行压缩。 |
## 备注



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## 另见

* 命名空间 [Aspose::Slides::LowCode](../)
* 库 [Aspose.Slides](../../)