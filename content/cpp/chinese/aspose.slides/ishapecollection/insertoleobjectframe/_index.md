---
title: InsertOleObjectFrame()
second_title: Aspose.Slides C++ API 参考
description: 在指定索引处创建一个新的 OLE 对象帧并将其插入到形状集合中。
type: docs
weight: 79
url: /zh/aspose.slides/ishapecollection/insertoleobjectframe/
---
## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) 方法

创建一个新的 OLE 对象帧并将其插入到指定索引的形状集合中。

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 插入 OLE 对象帧的零基索引。 |
| x | **float** | 新 OLE 帧的 x 坐标，单位为点。 |
| y | **float** | 新 OLE 帧的 y 坐标，单位为点。 |
| width | **float** | 新 OLE 帧的宽度，单位为点。 |
| height | **float** | 新 OLE 帧的高度，单位为点。 |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | 嵌入的 OLE 数据信息（[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)）。 |

### 返回值

新创建的 [IOleObjectFrame](../../ioleobjectframe/)。

## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) 方法

创建一个新的 OLE 对象帧并将其插入到指定索引的形状集合中。

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 插入 OLE 对象帧的零基索引。 |
| x | **float** | 新 OLE 帧的 x 坐标，单位为点。 |
| y | **float** | 新 OLE 帧的 y 坐标，单位为点。 |
| width | **float** | 新 OLE 帧的宽度，单位为点。 |
| height | **float** | 新 OLE 帧的高度，单位为点。 |
| className | [System::String](../../../system/string/) | OLE 对象的类名。 |
| path | [System::String](../../../system/string/) | 链接文件的路径。 |

### 返回值

新创建的 [IOleObjectFrame](../../ioleobjectframe/)。

## 备注

此路径以原始形式存储在演示文稿中。如果指定相对路径，则在从不同目录打开演示文稿时文件将不可访问。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IOleObjectFrame](../../ioleobjectframe/)
* 类 [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* 类 [IShapeCollection](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)