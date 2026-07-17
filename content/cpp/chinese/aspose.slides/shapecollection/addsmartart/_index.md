---
title: AddSmartArt()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个 SmartArt 图表并将其添加到形状集合的末尾。
type: docs
weight: 79
url: /zh/aspose.slides/shapecollection/addsmartart/
---
## ShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) 方法

创建一个[SmartArt](../../../aspose.slides.smartart/)图表，并将其添加到形状集合的末尾。

```cpp
System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::ShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 图表框架的 x 坐标，单位为点。 |
| y | **float** | 图表框架的 y 坐标，单位为点。 |
| width | **float** | 图表框架的宽度，单位为点。 |
| height | **float** | 图表框架的高度，单位为点。 |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | [SmartArt](../../../aspose.slides.smartart/) 布局类型。 |

### 返回值

新创建的 [SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/)。

## 备注

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```

## 另见

* 枚举 [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* 类 [ShapeCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)