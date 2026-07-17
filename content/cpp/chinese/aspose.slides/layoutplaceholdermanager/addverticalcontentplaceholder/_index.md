---
title: AddVerticalContentPlaceholder()
second_title: Aspose.Slides C++ API 参考
description: 向布局幻灯片添加一个新的占位符形状，以容纳内容，例如图片、表格、媒体或文本，方向为垂直。
type: docs
weight: 14
url: /zh/aspose.slides/layoutplaceholdermanager/addverticalcontentplaceholder/
---
## LayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) 方法


向布局幻灯片添加一个新的占位符形状，以容纳内容，例如图片、表格、媒体或文本，方向为垂直。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 新占位符形状的 X 坐标。 |
| y | **float** | 新占位符形状的 Y 坐标。 |
| width | **float** | 新占位符形状的宽度。 |
| height | **float** | 新占位符形状的高度。 |

### 返回值

创建了带有内容（垂直）占位符的 [IAutoShape](../../iautoshape/)。

## 备注



下面的示例展示了如何向布局幻灯片添加内容（垂直）占位符形状。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IAutoShape](../../iautoshape/)
* 类 [LayoutPlaceholderManager](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)