---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides 的 C++ API 參考
description: 確定在載入簡報時，Aspose.Slides 是否會刪除所有嵌入的二進位物件。
type: docs
weight: 339
url: /zh-hant/aspose.slides/loadoptions/get_deleteembeddedbinaryobjects/
---
## LoadOptions::get_DeleteEmbeddedBinaryObjects() 方法


確定在載入簡報時，[Aspose.Slides](../../) 是否會刪除所有嵌入的二進位物件。

```cpp
bool Aspose::Slides::LoadOptions::get_DeleteEmbeddedBinaryObjects() override
```

## 備註


嵌入的二進位物件的類型：

* VBA Project [IPresentation::VbaProject](../)
* OLE Object 嵌入資料 [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) 二進位資料 [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


讀取 **bool**。 

預設為 **false**。 

以下範例示範如何在不包含任何嵌入二進位物件的情況下載入簡報。 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## 參見

* Class [LoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)