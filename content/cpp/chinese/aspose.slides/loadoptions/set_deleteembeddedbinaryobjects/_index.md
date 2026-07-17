---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides for C++ API 参考
description: 确定在加载演示文稿时 Aspose.Slides 是否会删除所有嵌入的二进制对象。
type: docs
weight: 352
url: /zh/aspose.slides/loadoptions/set_deleteembeddedbinaryobjects/
---
## LoadOptions::set_DeleteEmbeddedBinaryObjects(bool) 方法

确定在加载演示文稿时 [Aspose.Slides](../../) 是否会删除所有嵌入的二进制对象。

```cpp
void Aspose::Slides::LoadOptions::set_DeleteEmbeddedBinaryObjects(bool value) override
```

## 备注

嵌入的二进制对象类型有：

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) 二进制数据 [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

写入 **bool**。

默认值为 **false**。

下面的示例展示了如何在不包含任何嵌入二进制对象的情况下加载演示文稿。

```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## 另请参见

* 类 [LoadOptions](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)