---
title: AddGroupShape()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個新的空白群組形狀，並將其新增至形狀集合的末端。群組的框架會自動調整以符合加入的任何形狀。
type: docs
weight: 391
url: /zh-hant/aspose.slides/shapecollection/addgroupshape/
---
## ShapeCollection::AddGroupShape() 方法

建立一個新的空白群組形狀，並將其新增至形狀集合的末端。群組的框架會自動調整以符合加入的任何形狀。

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape() override
```

### 返回值

新建立的 [IGroupShape](../../igroupshape/)。

## 備註

以下範例說明如何將群組形狀新增至 PowerPoint [Presentation](../../presentation/) 的投影片。
```cpp
// 建立 Presentation 類別實例
auto pres = System::MakeObject<Presentation>();

// 取得第一張投影片
auto slide = pres->get_Slides()->idx_get(0);
// 取得投影片的形狀集合
auto slideShapes = slide->get_Shapes();
// 在投影片中新增群組形狀
System::SharedPtr<IGroupShape> groupShape = slideShapes->AddGroupShape();

// 在已新增的群組形狀內加入形狀
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 300.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 300.0f, 100.0f, 100.0f);
// 為群組形狀新增框架
groupShape->set_Frame(System::MakeObject<ShapeFrame>(100.0f, 300.0f, 500.0f, 40.0f, NullableBool::False, NullableBool::False, 0.0f));

// 將 PPTX 檔寫入磁碟
pres->Save(u"GroupShape_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) 方法

建立一個新的群組形狀，將指定的 SVG 圖像轉換為個別形狀，並將產生的群組新增至形狀集合的末端。

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | [ISvgImage](../../isvgimage/) 包含要轉換成形狀的向量內容。 |
| x | **float** | 群組框架的 x 座標（以點為單位）。 |
| y | **float** | 群組框架的 y 座標（以點為單位）。 |
| width | **float** | 群組框架的寬度（以點為單位）。 |
| height | **float** | 群組框架的高度（以點為單位）。 |

### 返回值

新建立的 [IGroupShape](../../igroupshape/)。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IGroupShape](../../igroupshape/)
* 類別 [ShapeCollection](../)
* 類別 [ISvgImage](../../isvgimage/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)