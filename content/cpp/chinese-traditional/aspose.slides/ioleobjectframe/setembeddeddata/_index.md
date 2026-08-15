---
title: SetEmbeddedData()
second_title: Aspose.Slides C++ API 參考
description: 設定有關 OLE 嵌入資料的資訊。
type: docs
weight: 248
url: /zh-hant/aspose.slides/ioleobjectframe/setembeddeddata/
---
## IOleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) 方法

設定有關 OLE 嵌入資料的資訊。

```cpp
virtual void Aspose::Slides::IOleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | 嵌入資料 [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |
## 備註

此 方法 會變更 物件 的屬性，以 反映 新的資料，並將 IsObjectLink 旗標 設為 false，表示 OLE 物件 為 嵌入。

以下 範例 示範 如何 為 現有 [IOleObjectFrame](../) 物件 更改 OLE 嵌入資料 及 其 類型。
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

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* 類別 [IOleObjectFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)