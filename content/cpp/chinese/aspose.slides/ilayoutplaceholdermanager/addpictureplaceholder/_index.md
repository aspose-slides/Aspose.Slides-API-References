---
title: AddPicturePlaceholder()
second_title: Aspose.Slides for C++ API 参考
description: 向布局幻灯片添加一个新的占位形状以容纳图片。
type: docs
weight: 53
url: /zh/aspose.slides/ilayoutplaceholdermanager/addpictureplaceholder/
---
## ILayoutPlaceholderManager::AddPicturePlaceholder(float, float, float, float) 方法

向布局幻灯片添加一个新的占位形状以容纳图片。

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddPicturePlaceholder(float x, float y, float width, float height)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 新占位形状的 X 坐标。 |
| y | **float** | 新占位形状的 Y 坐标。 |
| width | **float** | 新占位形状的宽度。 |
| height | **float** | 新占位形状的高度。 |

### 返回值

已创建 [IAutoShape](../../iautoshape/)，并带有 [Picture](../../picture/) 占位符。

## 备注

以下示例展示了如何将 [Picture](../../picture/) 占位形状添加到布局幻灯片。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddPicturePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IAutoShape](../../iautoshape/)
* 类 [ILayoutPlaceholderManager](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)