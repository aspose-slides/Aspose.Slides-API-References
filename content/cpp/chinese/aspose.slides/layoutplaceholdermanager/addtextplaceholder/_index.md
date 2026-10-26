---
title: AddTextPlaceholder()
second_title: Aspose.Slides for C++ API 参考
description: 向布局幻灯片添加一个新的占位形状以容纳文本内容。
type: docs
weight: 27
url: /zh/aspose.slides/layoutplaceholdermanager/addtextplaceholder/
---
## LayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) method

向布局幻灯片添加一个新的占位形状以容纳文本内容。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 新占位形状的 X 坐标。 |
| y | **float** | 新占位形状的 Y 坐标。 |
| width | **float** | 新占位形状的宽度。 |
| height | **float** | 新占位形状的高度。 |

### 返回值

已创建 [IAutoShape](../../iautoshape/)，其中包含 Text 占位符。

## 备注

以下示例展示了如何向布局幻灯片添加 Text 占位形状。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)