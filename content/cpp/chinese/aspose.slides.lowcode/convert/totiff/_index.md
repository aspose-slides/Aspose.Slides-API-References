---
title: ToTiff()
second_title: Aspose.Slides for C++ API 参考
description: 将输入的演示文稿转换为一组 TIFF 格式的图像。  如果输出文件名为 \"myPath/myFilename.tiff\"，结果将保存为一组 \"myPath/myFilename_N.tiff\" 文件，其中 N 为幻灯片编号。
type: docs
weight: 66
url: /zh/aspose.slides.lowcode/convert/totiff/
---
## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String) 方法


将输入的演示文稿转换为一组 TIFF 格式的图像。 

如果输出文件名指定为 \"myPath/myFilename.tiff\"，结果将保存为一组 \"myPath/myFilename_N.tiff\" 文件，其中 N 为幻灯片编号。

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 输入的演示文稿。 |
| outputFileName | [System::String](../../../system/string/) | 输出文件名。 |
## 备注




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"presImage.tiff");
```

## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ITiffOptions\>, bool) 方法


将输入的演示文稿转换为带有自定义选项的 TIFF 格式。 如果输出文件名指定为 \"myPath/myFilename.tiff\" 且 *multipage* 为 **false**，结果将保存为一组 \"myPath/myFilename_N.tiff\" 文件，其中 N 为幻灯片编号。否则，如果 *multipage* 为 **true**，结果将是一个多页的 \"myPath/myFilename.tiff\" 文档。

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ITiffOptions> options, bool multipage)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 输入的演示文稿。 |
| outputFileName | [System::String](../../../system/string/) | 输出文件名。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | TIFF 保存选项。 |
| multipage | **bool** | 指定生成的 TIFF 文档是否应为多页。 |
## 备注




```cpp
System::SharedPtr<ITiffOptions> options = System::MakeObject<TiffOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);
options->set_CompressionType(TiffCompressionTypes::CCITT3);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"pres.tiff", options, false);
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Presentation](../../../aspose.slides/presentation/)
* 类 [String](../../../system/string/)
* 类 [Convert](../)
* 类 [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* 命名空间 [Aspose::Slides::LowCode](../../)
* 库 [Aspose.Slides](../../../)