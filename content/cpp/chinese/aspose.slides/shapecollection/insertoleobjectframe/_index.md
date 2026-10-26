---
title: InsertOleObjectFrame()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个新的 OLE 对象框架并将其插入到指定索引的形状集合中。
type: docs
weight: 196
url: /zh/aspose.slides/shapecollection/insertoleobjectframe/
---
## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) 方法

创建一个新的 OLE 对象框架并将其插入到指定索引的形状集合中。

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 要插入 OLE 对象框架的基于零的索引。 |
| x | **float** | 新 OLE 框架的 x 坐标，单位为点。 |
| y | **float** | 新 OLE 框架的 y 坐标，单位为点。 |
| width | **float** | 新 OLE 框架的宽度，单位为点。 |
| height | **float** | 新 OLE 框架的高度，单位为点。 |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | 嵌入的 OLE 数据信息（[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)）。 |

### 返回值

新创建的 [IOleObjectFrame](../../ioleobjectframe/)。

## 备注

此示例演示在第二个索引处插入 OLE 对象：
```cpp
ArrayPtr<uint8_t> fileData = IO::File::ReadAllBytes(u"test.zip");
auto dataInfo = MakeObject<OleEmbeddedDataInfo>(fileData, u"zip");
auto oleObjectFrame = slide->get_Shapes()->InsertOleObjectFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, dataInfo);
```

## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) 方法

创建一个新的 OLE 对象框架并将其插入到指定索引的形状集合中。

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 要插入 OLE 对象框架的基于零的索引。 |
| x | **float** | 新 OLE 框架的 x 坐标，单位为点。 |
| y | **float** | 新 OLE 框架的 y 坐标，单位为点。 |
| width | **float** | 新 OLE 框架的宽度，单位为点。 |
| height | **float** | 新 OLE 框架的高度，单位为点。 |
| className | [System::String](../../../system/string/) | OLE 对象的类名。 |
| path | [System::String](../../../system/string/) | 链接文件的路径。 |

### 返回值

新创建的 OLE 对象框架。

## 备注

此路径以原样存储在演示文稿中。如果指定相对路径，则在从不同目录打开演示文稿时，该文件将无法访问。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IOleObjectFrame](../../ioleobjectframe/)
* 类 [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* 类 [ShapeCollection](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)