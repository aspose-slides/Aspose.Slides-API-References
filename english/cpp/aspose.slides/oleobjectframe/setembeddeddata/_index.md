---
title: SetEmbeddedData()
second_title: Aspose.Slides for C++ API Reference
description: Sets information about OLE embedded data.
type: docs
weight: 248
url: /cpp/aspose.slides/oleobjectframe/setembeddeddata/
---
## OleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) method


Sets information about OLE embedded data.

```cpp
void Aspose::Slides::OleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Embedded data [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |
## Remarks


This method changes the properties of the object to reflect the new data and sets the IsObjectLink flag to false, indicating that the OLE object is embedded. 



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [OleObjectFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)