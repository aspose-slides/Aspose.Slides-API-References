---
title: set_CompressionLevel()
second_title: Aspose.Slides C++ API 参考
description: "指定在保存演示文稿时使用的压缩级别。默认值为 CompressionLevel::Level6."
type: docs
weight: 92
url: /zh/aspose.slides.export/ipptxoptions/set_compressionlevel/
---
## IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) 方法

指定在保存演示文稿时使用的压缩级别。默认值为 [CompressionLevel::Level6](../../compressionlevel/)。

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value)=0
```

## 备注

更高的压缩级别会生成更小的文件，但需要更多的处理时间。实际的压缩比取决于演示文稿的内容。 

示例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## 另请参见

* 枚举 [CompressionLevel](../../compressionlevel/)
* 类 [IPptxOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)