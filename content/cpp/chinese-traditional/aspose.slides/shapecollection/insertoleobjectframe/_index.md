---
title: InsertOleObjectFrame()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個新的 OLE 物件框架，並將其插入至指定索引的圖形集合中。
type: docs
weight: 196
url: /zh-hant/aspose.slides/shapecollection/insertoleobjectframe/
---
## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) 方法

建立一個新的 OLE 物件框架，並將其插入至指定索引的圖形集合中。

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 要插入 OLE 物件框架的零基索引。 |
| x | **float** | 新 OLE 框架的 x 坐標，以點為單位。 |
| y | **float** | 新 OLE 框架的 y 坐標，以點為單位。 |
| width | **float** | 新 OLE 框架的寬度，以點為單位。 |
| height | **float** | 新 OLE 框架的高度，以點為單位。 |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | 嵌入的 OLE 資料資訊 ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/))。 |

### 返回值

新建立的 [IOleObjectFrame](../../ioleobjectframe/)。

## 備註



此範例示範在第二個索引插入 OLE 物件：

```cpp
ArrayPtr<uint8_t> fileData = IO::File::ReadAllBytes(u"test.zip");
auto dataInfo = MakeObject<OleEmbeddedDataInfo>(fileData, u"zip");
auto oleObjectFrame = slide->get_Shapes()->InsertOleObjectFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, dataInfo);
```

## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) 方法


建立一個新的 OLE 物件框架，並將其插入至指定索引的圖形集合中。

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 要插入 OLE 物件框架的零基索引。 |
| x | **float** | 新 OLE 框架的 x 坐標，以點為單位。 |
| y | **float** | 新 OLE 框架的 y 坐標，以點為單位。 |
| width | **float** | 新 OLE 框架的寬度，以點為單位。 |
| height | **float** | 新 OLE 框架的高度，以點為單位。 |
| className | [System::String](../../../system/string/) | OLE 物件的類別名稱。 |
| path | [System::String](../../../system/string/) | 連結檔案的路徑。 |

### 返回值

新建立的 OLE 物件框架。

## 備註



此路徑會以原始文字儲存在簡報中。若指定相對路徑，則在從不同目錄開啟簡報時，檔案將無法存取。

## 另請參見

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IOleObjectFrame](../../ioleobjectframe/)
* 類別 [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* 類別 [ShapeCollection](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)