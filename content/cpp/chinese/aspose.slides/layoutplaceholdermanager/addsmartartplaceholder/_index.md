---
title: AddSmartArtPlaceholder()
second_title: Aspose.Slides C++ API 参考
description: 向布局幻灯片添加一个新的占位符形状，以容纳 SmartArt 图表。
type: docs
weight: 92
url: /zh/aspose.slides/layoutplaceholdermanager/addsmartartplaceholder/
---
## LayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) 方法

向布局幻灯片添加一个新的占位符形状，用于容纳 [SmartArt](../../../aspose.slides.smartart/) 图表。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 新占位符形状的 X 坐标。 |
| y | **float** | 新占位符形状的 Y 坐标。 |
| width | **float** | 新占位符形状的宽度。 |
| height | **float** | 新占位符形状的高度。 |

### 返回值

已创建 [IAutoShape](../../iautoshape/)，其中包含一个 [SmartArt](../../../aspose.slides.smartart/) 占位符。

## 备注

下面的示例展示了如何将 [SmartArt](../../../aspose.slides.smartart/) 占位符形状添加到布局幻灯片。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IAutoShape](../../iautoshape/)
* 类 [LayoutPlaceholderManager](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)