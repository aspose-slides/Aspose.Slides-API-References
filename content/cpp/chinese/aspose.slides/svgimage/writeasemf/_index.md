---
title: WriteAsEmf()
second_title: Aspose.Slides C++ API 参考
description: 将 SVG 图像保存为 EMF 文件。
type: docs
weight: 66
url: /zh/aspose.slides/svgimage/writeasemf/
---
## SvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) 方法


将 SVG 图像保存为 EMF 文件。

```cpp
void Aspose::Slides::SvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 目标流 |
## 备注



下面的示例演示了如何将 SVG 图像保存为元文件。 
```cpp
// 创建新的 SVG 图像
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// 将 SVG 图像保存为元文件
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 此示例演示了如何将 SVG 图像作为元文件添加到演示文稿的图像集合中。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 创建新的 SVG 图像
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// 将 SVG 图像保存为元文件
svgImage->WriteAsEmf(memStream);
// 将元文件添加到图像集合
pres->get_Images()->AddImage(memStream->ToArray());
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Stream](../../../system.io/stream/)
* 类 [SvgImage](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)