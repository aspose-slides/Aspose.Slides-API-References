---
title: AddOleObjectFrame()
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: 建立一個新的 OLE 物件框架，並將其加入形狀集合的末端。
type: docs
weight: 183
url: /zh-hant/aspose.slides/shapecollection/addoleobjectframe/
---
## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) 方法

Creates a new OLE object frame and adds it to the end of the shape collection.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| x | **float** | 新 OLE 框架的 x 座標，以點為單位。 |
| y | **float** | 新 OLE 框架的 y 座標，以點為單位。 |
| width | **float** | 新 OLE 框架的寬度，以點為單位。 |
| height | **float** | 新 OLE 框架的高度，以點為單位。 |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | 嵌入式 OLE 資料的資訊（[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)）。 |

### 回傳值

新建立的 [IOleObjectFrame](../../ioleobjectframe/)。

## 備註

以下範例顯示如何將 OLE 物件框加入 [Slides](../../) 的 PowerPoint [Presentation](../../presentation/)。 
```cpp
auto pres = System::MakeObject<Presentation>();

// 存取第一張投影片
auto slide = pres->get_Slides()->idx_get(0);
// 將 Excel 檔案載入為串流
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

// 建立用於嵌入的資料物件
auto dataInfo = System::MakeObject<OleEmbeddedDataInfo>(mstream->ToArray(), u"xlsx");
// 新增 Ole 物件框形狀
auto slideSize = pres->get_SlideSize()->get_Size();
auto oleObjectFrame = slide->get_Shapes()->AddOleObjectFrame(0.0f, 0.0f, slideSize.get_Width(), slideSize.get_Height(), dataInfo);
// 將 PPTX 檔案寫入磁碟
pres->Save(u"OleEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) 方法

Creates a new OLE object frame and adds it to the end of the shape collection.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| x | **float** | 新 OLE 框架的 x 座標，以點為單位。 |
| y | **float** | 新 OLE 框架的 y 座標，以點為單位。 |
| width | **float** | 新 OLE 框架的寬度，以點為單位。 |
| height | **float** | 新 OLE 框架的高度，以點為單位。 |
| className | [System::String](../../../system/string/) | OLE 物件的類別名稱。 |
| path | [System::String](../../../system/string/) | 連結檔案的路徑。 |

### 回傳值

新建立的 [IOleObjectFrame](../../ioleobjectframe/)。

## 備註

此路徑會以原樣儲存在簡報中。若指定相對路徑，當從不同目錄開啟簡報時，檔案將無法存取。

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IOleObjectFrame](../../ioleobjectframe/)
* 類別 [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* 類別 [ShapeCollection](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)