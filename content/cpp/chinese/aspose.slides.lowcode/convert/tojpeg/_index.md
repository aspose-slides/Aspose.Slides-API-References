---
title: ToJpeg()
second_title: Aspose.Slides C++ API 参考
description: 将输入的演示文稿转换为一组 JPEG 格式的图像。如果输出文件名指定为 \"myPath/myFilename.jpeg\"，则结果将保存为一组 \"myPath/myFilename_N.jpeg\" 文件，其中 N 为幻灯片编号。
type: docs
weight: 40
url: /zh/aspose.slides.lowcode/convert/tojpeg/
---
## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String) 方法

将输入的演示文稿转换为一组 JPEG 格式的图像。

如果输出文件名指定为 "myPath/myFilename.jpeg"，结果将保存为一组 "myPath/myFilename_N.jpeg" 文件，其中 N 为幻灯片编号。

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 输入的演示文稿。 |
| outputFileName | [System::String](../../../system/string/) | 输出文件名。 |

## 备注

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg");
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) 方法

将输入的演示文稿转换为一组 JPEG 格式的图像。

如果输出文件名指定为 "myPath/myFilename.jpeg"，结果将保存为一组 "myPath/myFilename_N.jpeg" 文件，其中 N 为幻灯片编号。

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 输入的演示文稿。 |
| outputFileName | [System::String](../../../system/string/) | 输出文件名。 |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 每个生成的图像的大小。 |

## 备注

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", System::Drawing::Size(720, 540));
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) 方法

将输入的演示文稿转换为一组 JPEG 格式的图像。

如果输出文件名指定为 "myPath/myFilename.jpeg"，结果将保存为一组 "myPath/myFilename_N.jpeg" 文件，其中 N 为幻灯片编号。

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 输入的演示文稿。 |
| outputFileName | [System::String](../../../system/string/) | 输出文件名。 |
| scale | **float** | 相对于原始幻灯片尺寸，输出图像的缩放因子。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 渲染选项。 |

## 备注

```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", 2.0f, options);
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Presentation](../../../aspose.slides/presentation/)
* 类 [String](../../../system/string/)
* 类 [Convert](../)
* 类 [Size](../../../system.drawing/size/)
* 类 [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* 命名空间 [Aspose::Slides::LowCode](../../)
* 库 [Aspose.Slides](../../../)