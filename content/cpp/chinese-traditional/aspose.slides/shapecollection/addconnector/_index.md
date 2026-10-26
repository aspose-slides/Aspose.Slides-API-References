---
title: AddConnector()
second_title: Aspose.Slides for C++ API 參考
description: 建立具有預設範本樣式的新連接線形狀，並將其加入形狀集合的末端。
type: docs
weight: 417
url: /zh-hant/aspose.slides/shapecollection/addconnector/
---
## ShapeCollection::AddConnector(ShapeType, float, float, float, float) 方法

建立一個具有預設範本樣式的新連接線形狀，並將其加入形狀集合的末端。

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 要新增之連接線形狀的 [ShapeType](../../shapetype/)。 |
| x | **float** | 連接線框架的 x 座標（單位：點）。 |
| y | **float** | 連接線框架的 y 座標（單位：點）。 |
| width | **float** | 連接線框架的寬度（單位：點）。 |
| height | **float** | 連接線框架的高度（單位：點）。 |

### 回傳值

新建立的 [IConnector](../../iconnector/)。
## 備註

以下範例示範如何在 PowerPoint [Presentation](../../presentation/) 中於兩個形狀（橢圓和矩形）之間加入連接線（彎曲連接線）。

```cpp
// 實例化表示 PPTX 檔案的簡報類別
auto input = System::MakeObject<Presentation>();

// 存取特定投影片的形狀集合
auto shapes = input->get_Slides()->idx_get(0)->get_Shapes();
// 新增一個橢圓自動圖形
System::SharedPtr<IAutoShape> ellipse = shapes->AddAutoShape(ShapeType::Ellipse, 0.0f, 100.0f, 100.0f, 100.0f);
// 新增一個矩形自動圖形
System::SharedPtr<IAutoShape> rectangle = shapes->AddAutoShape(ShapeType::Rectangle, 100.0f, 300.0f, 100.0f, 100.0f);

// 將連接線形狀新增至投影片的形狀集合
System::SharedPtr<IConnector> connector = shapes->AddConnector(ShapeType::BentConnector2, 0.0f, 0.0f, 10.0f, 10.0f);
// 使用連接線將形狀連接起來
connector->set_StartShapeConnectedTo(ellipse);
connector->set_EndShapeConnectedTo(rectangle);
// 呼叫 reroute，設定形狀之間的自動最短路徑
connector->Reroute();

// 儲存簡報
input->Save(u"Shapes-connector.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) 方法

建立一個新的連接線形狀，並將其加入形狀集合的末端，可選擇套用預設範本樣式。

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 要建立之連接線形狀的 [ShapeType](../../shapetype/)。 |
| x | **float** | 連接線框架的 x 座標（單位：點）。 |
| y | **float** | 連接線框架的 y 座標（單位：點）。 |
| width | **float** | 連接線框架的寬度（單位：點）。 |
| height | **float** | 連接線框架的高度（單位：點）。 |
| createFromTemplate | **bool** | True 表示套用預設範本樣式（非空名稱，簡易樣式）；false 表示以預設屬性值建立連接線。 |

### 回傳值

新建立的 [IConnector](../../iconnector/)。

## 另見

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)