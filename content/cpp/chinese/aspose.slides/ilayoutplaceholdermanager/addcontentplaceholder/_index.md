---
title: AddContentPlaceholder()
second_title: Aspose.Slides for C++ API 参考
description: 向布局幻灯片添加一个新的占位符形状以容纳内容，例如图片、表格、媒体或文本。
type: docs
weight: 1
url: /zh/aspose.slides/ilayoutplaceholdermanager/addcontentplaceholder/
---
## ILayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) 方法

向布局幻灯片添加一个新的占位符形状以容纳内容，例如图片、表格、媒体或文本。

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 新占位符形状的 X 坐标。 |
| y | **float** | 新占位符形状的 Y 坐标。 |
| width | **float** | 新占位符形状的宽度。 |
| height | **float** | 新占位符形状的高度。 |

### 返回值

已创建 [IAutoShape](../../iautoshape/)，其中包含内容占位符。

## 备注

下面的示例展示了如何向布局幻灯片添加内容占位符形状。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IAutoShape](../../iautoshape/)
* 类 [ILayoutPlaceholderManager](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)