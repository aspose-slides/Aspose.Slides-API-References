---
title: AddSmartArt()
second_title: Aspose.Slides for C++ API 參考
description: 建立 SmartArt 圖表，並將其新增至形狀集合的末端。
type: docs
weight: 40
url: /zh-hant/aspose.slides/ishapecollection/addsmartart/
---
## IShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) method


建立一個 [SmartArt](../../../aspose.slides.smartart/) 圖表，並將其新增至形狀集合的末端。

```cpp
virtual System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::IShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 圖表\\u2019s 框架的 x 座標，以點為單位。 |
| y | **float** | 圖表\\u2019s 框架的 y 座標，以點為單位。 |
| width | **float** | 圖表\\u2019s 框架的寬度，以點為單位。 |
| height | **float** | 圖表\\u2019s 框架的高度，以點為單位。 |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | [SmartArt](../../../aspose.slides.smartart/) 版面配置類型。 |

### Return Value

新建立的 [SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/)。
## 備註



```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```


## 參見

* Enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)