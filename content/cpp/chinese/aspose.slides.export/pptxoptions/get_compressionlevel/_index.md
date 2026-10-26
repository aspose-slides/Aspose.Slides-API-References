---
title: get_CompressionLevel()
second_title: Aspose.Slides C++ API 参考
description: "指定在保存演示文稿时使用的压缩级别。默认值为 CompressionLevel::Level6."
type: docs
weight: 79
url: /zh/aspose.slides.export/pptxoptions/get_compressionlevel/
---
## PptxOptions::get_CompressionLevel() 方法

指定保存演示文稿时使用的压缩级别。默认值为 [CompressionLevel::Level6](../../compressionlevel/)。

```cpp
Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::PptxOptions::get_CompressionLevel() override
```

## 备注

更高的压缩级别会产生更小的文件，但需要更多的处理时间。实际的压缩比取决于演示文稿的内容。

示例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## 另见

* 枚举 [CompressionLevel](../../compressionlevel/)
* 类 [PptxOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)