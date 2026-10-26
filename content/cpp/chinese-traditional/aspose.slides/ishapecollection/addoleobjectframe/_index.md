---
title: AddOleObjectFrame()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立新的 OLE 物件框架，並將其新增至形狀集合的末端。
type: docs
weight: 66
url: /zh-hant/aspose.slides/ishapecollection/addoleobjectframe/
---
## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) method

建立新的 OLE 物件框架，並將其新增至形狀集合的末端。

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 新 OLE 框架的 x 座標（單位為點）。 |
| y | **float** | 新 OLE 框架的 y 座標（單位為點）。 |
| width | **float** | 新 OLE 框架的寬度（單位為點）。 |
| height | **float** | 新 OLE 框架的高度（單位為點）。 |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | 嵌入的 OLE 資料資訊（[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)）。 |

### 傳回值

新建立的 [IOleObjectFrame](../../ioleobjectframe/)。

## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) method

建立新的 OLE 物件框架，並將其新增至形狀集合的末端。

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 新 OLE 框架的 x 座標（單位為點）。 |
| y | **float** | 新 OLE 框架的 y 座標（單位為點）。 |
| width | **float** | 新 OLE 框架的寬度（單位為點）。 |
| height | **float** | 新 OLE 框架的高度（單位為點）。 |
| className | [System::String](../../../system/string/) | OLE 物件的類別名稱。 |
| path | [System::String](../../../system/string/) | 連結檔案的路徑。 |

### 傳回值

新建立的 [IOleObjectFrame](../../ioleobjectframe/)。

## 備註

此路徑會以原樣儲存在簡報中。若指定相對路徑，於從不同目錄開啟簡報時，檔案將無法存取。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IOleObjectFrame](../../ioleobjectframe/)
* 類別 [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* 類別 [IShapeCollection](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)