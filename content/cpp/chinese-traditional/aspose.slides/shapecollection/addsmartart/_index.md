---
title: AddSmartArt()
second_title: Aspose.Slides for C++ API 參考
description: 建立 SmartArt 圖表並將其新增至圖形集合的末尾。
type: docs
weight: 79
url: /zh-hant/aspose.slides/shapecollection/addsmartart/
---
## ShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) 方法

建立一個 [SmartArt](../../../aspose.slides.smartart/) 圖表並將其新增至圖形集合的末尾。

```cpp
System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::ShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 圖表框架的 x 座標（以點為單位）。 |
| y | **float** | 圖表框架的 y 座標（以點為單位）。 |
| width | **float** | 圖表框架的寬度（以點為單位）。 |
| height | **float** | 圖表框架的高度（以點為單位）。 |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | [SmartArt](../../../aspose.slides.smartart/) 版面配置類型。 |

### 傳回值

新建立的 [SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/)。

## 備註

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```

## 另請參閱

* Enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)