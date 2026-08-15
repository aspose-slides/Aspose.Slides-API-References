---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides for C++ API 參考
description: 判斷在載入簡報時 Aspose.Slides 是否會刪除所有嵌入的二進位物件。
type: docs
weight: 352
url: /zh-hant/aspose.slides/loadoptions/set_deleteembeddedbinaryobjects/
---
## LoadOptions::set_DeleteEmbeddedBinaryObjects(bool) 方法


判斷在載入簡報時 [Aspose.Slides](../../) 是否會刪除所有嵌入的二進位物件。

```cpp
void Aspose::Slides::LoadOptions::set_DeleteEmbeddedBinaryObjects(bool value) override
```

## 備註


這些嵌入二進位物件的類型：

* VBA 專案 [IPresentation::VbaProject](../)
* OLE 物件嵌入資料 [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) 二進位資料 [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


寫入 **bool**。 

預設為 **false**。 

以下範例說明如何在不含任何嵌入二進位物件的情況下載入簡報。 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## 另見

* 類別 [LoadOptions](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)