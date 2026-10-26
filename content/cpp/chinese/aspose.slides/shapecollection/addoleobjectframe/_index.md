---
title: AddOleObjectFrame()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个新的 OLE 对象框架并将其添加到形状集合的末尾。
type: docs
weight: 183
url: /zh/aspose.slides/shapecollection/addoleobjectframe/
---
## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) method

创建一个新的 OLE 对象框架并将其添加到形状集合的末尾。

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 新 OLE 框架的 x 坐标，单位为点。 |
| y | **float** | 新 OLE 框架的 y 坐标，单位为点。 |
| width | **float** | 新 OLE 框架的宽度，单位为点。 |
| height | **float** | 新 OLE 框架的高度，单位为点。 |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | 嵌入的 OLE 数据的信息（[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)）。 |

### 返回值

新创建的 [IOleObjectFrame](../../ioleobjectframe/)。

## 备注

以下示例演示如何向 PowerPoint [Presentation](../../presentation/) 的 [Slides](../../) 添加 OLE 对象框架。

```cpp
auto pres = System::MakeObject<Presentation>();

// 访问第一张幻灯片
auto slide = pres->get_Slides()->idx_get(0);
// 将 Excel 文件加载到流中
System::SharedPtr<System::IO::MemoryStream> mstream = System::MakeObject<System::IO::MemoryStream>();
auto fs = System::MakeObject<System::IO::FileStream>(u"book1.xlsx", System::IO::FileMode::Open, System::IO::FileAccess::Read);

System::ArrayPtr<uint8_t> buf = System::MakeArray<uint8_t>(4096, 0);
while (true)
{
    int32_t bytesRead = fs->Read(buf, 0, buf->get_Length());
    if (bytesRead <= 0)
    {
        break;
    }
    mstream->Write(buf, 0, bytesRead);
}

// 创建用于嵌入的数据对象
auto dataInfo = System::MakeObject<OleEmbeddedDataInfo>(mstream->ToArray(), u"xlsx");
// 添加 Ole 对象框架形状
auto slideSize = pres->get_SlideSize()->get_Size();
auto oleObjectFrame = slide->get_Shapes()->AddOleObjectFrame(0.0f, 0.0f, slideSize.get_Width(), slideSize.get_Height(), dataInfo);
//将 PPTX 文件写入磁盘
pres->Save(u"OleEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) method

创建一个新的 OLE 对象框架并将其添加到形状集合的末尾。

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path) override
```

### 参数

| Parameter | Type | Description |
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

此路径在演示文稿中原样存储。如果指定了相对路径，在从其他目录打开演示文稿时将无法访问该文件。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleObjectFrame](../../ioleobjectframe/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [ShapeCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)