---
title: CompressEmbeddedFonts()
second_title: Aspose.Slides for C++ API 参考
description: 通过删除嵌入字体中未使用的字符来压缩 Presentation。
type: docs
weight: 27
url: /zh/aspose.slides.lowcode/compress/compressembeddedfonts/
---
## Compress::CompressEmbeddedFonts(System::SharedPtr\<Presentation\>) 方法


通过删除嵌入字体中未使用的字符来压缩 [Presentation](../../../aspose.slides/presentation/)。

```cpp
static void Aspose::Slides::LowCode::Compress::CompressEmbeddedFonts(System::SharedPtr<Presentation> pres)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 演示实例 |
## 备注




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::CompressEmbeddedFonts(pres);

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Presentation](../../../aspose.slides/presentation/)
* 类 [Compress](../)
* 命名空间 [Aspose::Slides::LowCode](../../)
* 库 [Aspose.Slides](../../../)