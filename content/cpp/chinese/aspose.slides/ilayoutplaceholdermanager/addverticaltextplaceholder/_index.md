---
title: AddVerticalTextPlaceholder()
second_title: Aspose.Slides for C++ API 参考
description: 向布局幻灯片添加一个新的占位符形状，以垂直方向容纳文本内容。
type: docs
weight: 40
url: /zh/aspose.slides/ilayoutplaceholdermanager/addverticaltextplaceholder/
---
## ILayoutPlaceholderManager::AddVerticalTextPlaceholder(float, float, float, float) 方法

向布局幻灯片添加一个新的占位符形状，以垂直方向容纳文本内容。

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddVerticalTextPlaceholder(float x, float y, float width, float height)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 新占位符形状的 X 坐标。 |
| y | **float** | 新占位符形状的 Y 坐标。 |
| width | **float** | 新占位符形状的宽度。 |
| height | **float** | 新占位符形状的高度。 |

### 返回值

创建了带有文本（垂直）占位符的 [IAutoShape](../../iautoshape/)。

## 备注

以下示例展示了如何将文本（垂直）占位符形状添加到布局幻灯片。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalTextPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IAutoShape](../../iautoshape/)
* 类 [ILayoutPlaceholderManager](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)