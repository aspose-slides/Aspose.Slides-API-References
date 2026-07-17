---
title: AddContentPlaceholder()
second_title: Aspose.Slides 用于 C++ 的 API 参考
description: 向布局幻灯片添加一个新的占位符形状以容纳内容，例如图片、表格、媒体或文本。
type: docs
weight: 1
url: /zh/aspose.slides/layoutplaceholdermanager/addcontentplaceholder/
---
## LayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) 方法

向布局幻灯片添加一个新的占位符形状以容纳内容，例如图片、表格、媒体或文本。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 新占位符形状的 X 坐标。 |
| y | **float** | 新占位符形状的 Y 坐标。 |
| width | **float** | 新占位符形状的宽度。 |
| height | **float** | 新占位符形状的高度。 |

### 返回值

已创建[IAutoShape](../../iautoshape/)，并带有内容占位符。

## 备注

下面的示例展示了如何向布局幻灯片添加内容占位符形状。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IAutoShape](../../iautoshape/)
* 类 [LayoutPlaceholderManager](../)
* 命名空间 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)