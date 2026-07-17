---
title: AddOleObjectFrame()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个新的 OLE 对象框架并将其添加到形状集合的末尾。
type: docs
weight: 66
url: /zh/aspose.slides/ishapecollection/addoleobjectframe/
---
## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) 方法

创建一个新的 OLE 对象框架并将其添加到形状集合的末尾。

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 新 OLE 框架的 x 坐标，单位为点。 |
| y | **float** | 新 OLE 框架的 y 坐标，单位为点。 |
| width | **float** | 新 OLE 框架的宽度，单位为点。 |
| height | **float** | 新 OLE 框架的高度，单位为点。 |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | 嵌入的 OLE 数据信息（[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)）。 |

### 返回值

新创建的 [IOleObjectFrame](../../ioleobjectframe/)。

## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) 方法

创建一个新的 OLE 对象框架并将其添加到形状集合的末尾。

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 新 OLE 框架的 x 坐标，单位为点。 |
| y | **float** | 新 OLE 框架的 y 坐标，单位为点。 |
| width | **float** | 新 OLE 框架的宽度，单位为点。 |
| height | **float** | 新 OLE 框架的高度，单位为点。 |
| className | [System::String](../../../system/string/) | OLE 对象的类名。 |
| path | [System::String](../../../system/string/) | 链接文件的路径。 |

### 返回值

新创建的 [IOleObjectFrame](../../ioleobjectframe/)。

## 备注

此路径在演示文稿中原样保存。如果指定了相对路径，在从不同目录打开演示文稿时文件将不可访问。

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IOleObjectFrame](../../ioleobjectframe/)
* 类 [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* 类 [IShapeCollection](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)