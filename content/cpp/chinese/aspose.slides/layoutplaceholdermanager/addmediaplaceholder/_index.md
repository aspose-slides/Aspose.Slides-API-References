---
title: AddMediaPlaceholder()
second_title: Aspose.Slides C++ API 参考
description: 向布局幻灯片添加一个新的占位符形状以容纳媒体对象。
type: docs
weight: 105
url: /zh/aspose.slides/layoutplaceholdermanager/addmediaplaceholder/
---
## LayoutPlaceholderManager::AddMediaPlaceholder(float, float, float, float) 方法

向布局幻灯片添加一个新的占位符形状，以容纳媒体对象。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddMediaPlaceholder(float x, float y, float width, float height) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 新占位符形状的 X 坐标。 |
| y | **float** | 新占位符形状的 Y 坐标。 |
| width | **float** | 新占位符形状的宽度。 |
| height | **float** | 新占位符形状的高度。 |

### 返回值

已创建 [IAutoShape](../../iautoshape/)，带有 Media 占位符。

## 备注

以下示例展示了如何向布局幻灯片添加 Media 占位符形状。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddMediaPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IAutoShape](../../iautoshape/)
* 类 [LayoutPlaceholderManager](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)