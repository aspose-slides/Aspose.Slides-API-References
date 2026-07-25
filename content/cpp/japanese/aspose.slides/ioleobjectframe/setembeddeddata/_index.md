---
title: SetEmbeddedData()
second_title: Aspose.Slides for C++ API リファレンス
description: OLE 埋め込みデータに関する情報を設定します。
type: docs
weight: 248
url: /ja/aspose.slides/ioleobjectframe/setembeddeddata/
---
## IOleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) メソッド

Sets information about OLE embedded data.

```cpp
virtual void Aspose::Slides::IOleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | 埋め込みデータ [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |
## 備考

This method changes the properties of the object to reflect the new data and sets the IsObjectLink flag to false, indicating that the OLE object is embedded.

Following example demonstrates how to change OLE embedded data and its type for existing [IOleObjectFrame](../) object
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* クラス [IOleObjectFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)