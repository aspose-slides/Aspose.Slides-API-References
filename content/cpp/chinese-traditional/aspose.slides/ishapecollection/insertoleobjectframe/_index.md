---
title: InsertOleObjectFrame()
second_title: Aspose.Slides for C++ API 參考
description: 在指定索引處建立新的 OLE 物件框架，並將其插入至 shape 集合中。
type: docs
weight: 79
url: /zh-hant/aspose.slides/ishapecollection/insertoleobjectframe/
---
## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) 方法

建立一個新的 OLE 物件框架，並將其插入至指定索引的 shape 集合中。

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 要插入 OLE 物件框架的零基索引。 |
| x | **float** | 新 OLE 框架的 x 座標（單位為點）。 |
| y | **float** | 新 OLE 框架的 y 座標（單位為點）。 |
| width | **float** | 新 OLE 框架的寬度（單位為點）。 |
| height | **float** | 新 OLE 框架的高度（單位為點）。 |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | 內嵌 OLE 資料資訊（[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)）。 |

### 回傳值

新建立的 [IOleObjectFrame](../../ioleobjectframe/)。

## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) 方法

建立一個新的 OLE 物件框架，並將其插入至指定索引的 shape 集合中。

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 要插入 OLE 物件框架的零基索引。 |
| x | **float** | 新 OLE 框架的 x 座標（單位為點）。 |
| y | **float** | 新 OLE 框架的 y 座標（單位為點）。 |
| width | **float** | 新 OLE 框架的寬度（單位為點）。 |
| height | **float** | 新 OLE 框架的高度（單位為點）。 |
| className | [System::String](../../../system/string/) | OLE 物件的類別名稱。 |
| path | [System::String](../../../system/string/) | 連結檔案的路徑。 |

### 回傳值

新建立的 [IOleObjectFrame](../../ioleobjectframe/)。

## 備註

此路徑會以原始文字儲存在簡報中。若指定相對路徑，於從不同目錄開啟簡報時，檔案將無法存取。

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IOleObjectFrame](../../ioleobjectframe/)
* 類別 [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* 類別 [IShapeCollection](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)