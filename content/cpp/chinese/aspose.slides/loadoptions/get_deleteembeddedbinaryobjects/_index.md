---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides C++ API 参考
description: 确定在加载演示文稿时 Aspose.Slides 是否会删除所有嵌入的二进制对象。
type: docs
weight: 339
url: /zh/aspose.slides/loadoptions/get_deleteembeddedbinaryobjects/
---
## LoadOptions::get_DeleteEmbeddedBinaryObjects() 方法

确定在加载演示文稿时 [Aspose.Slides](../../) 是否会删除所有嵌入的二进制对象。

```cpp
bool Aspose::Slides::LoadOptions::get_DeleteEmbeddedBinaryObjects() override
```

## 备注

嵌入的二进制对象类型：

* VBA 项目 [IPresentation::VbaProject](../)
* OLE 对象嵌入数据 [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX 二进制数据 [Control](../../control/) [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

读取 **bool**。 

默认值为 **false**。 

以下示例展示了如何在不加载任何嵌入二进制对象的情况下加载演示文稿。 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## 另见

* 类 [LoadOptions](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)