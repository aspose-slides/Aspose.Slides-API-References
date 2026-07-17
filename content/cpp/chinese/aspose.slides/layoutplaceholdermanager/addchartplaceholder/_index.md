---
title: AddChartPlaceholder()
second_title: Aspose.Slides C++ API 参考
description: 向布局幻灯片添加一个新的占位符形状以容纳图表。
type: docs
weight: 66
url: /zh/aspose.slides/layoutplaceholdermanager/addchartplaceholder/
---
## LayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) 方法

添加一个新的占位符形状到布局幻灯片，以容纳 Chart。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 新占位符形状的 X 坐标。 |
| y | **float** | 新占位符形状的 Y 坐标。 |
| width | **float** | 新占位符形状的宽度。 |
| height | **float** | 新占位符形状的高度。 |

### 返回值

创建了带有 Chart 占位符的 [IAutoShape](../../iautoshape/)。

## 备注

以下示例演示如何将 Chart 占位符形状添加到布局幻灯片。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IAutoShape](../../iautoshape/)
* 类 [LayoutPlaceholderManager](../)
* 命名空间 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)