---
title: SetEmbeddedData()
second_title: Aspose.Slides C++ API 參考
description: 設定有關 OLE 嵌入資料的資訊。
type: docs
weight: 248
url: /zh-hant/aspose.slides/oleobjectframe/setembeddeddata/
---
## OleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) 方法


Sets information about OLE embedded data.

```cpp
void Aspose::Slides::OleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData) override
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | 嵌入資料 [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |
## 備註


此方法會變更物件的屬性以反映新資料，並將 IsObjectLink 標誌設為 false，表示 OLE 物件是嵌入的。 



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* 類別 [OleObjectFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)