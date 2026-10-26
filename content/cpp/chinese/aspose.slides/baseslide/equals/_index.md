---
title: Equals()
second_title: Aspose.Slides for C++ API 参考
description: 确定两个 IBaseSlide 实例是否相等。返回值基于幻灯片的结构和静态内容计算。如果所有形状、样式、文本、动画以及其他设置等全部相等，则两个幻灯片相等。比较不考虑唯一标识符的值，例如 SlideId，以及动态内容，例如 Date Placeholder 中的当前日期值。
type: docs
weight: 170
url: /zh/aspose.slides/baseslide/equals/
---
## BaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) 方法

确定两个 [IBaseSlide](../../ibaseslide/) 实例是否相等。返回值基于幻灯片的结构和静态内容计算。如果所有形状、样式、文本、动画以及其他设置等全部相等，则两个幻灯片相等。比较不考虑唯一标识符的值，例如 SlideId，以及动态内容，例如 Date [Placeholder](../../placeholder/) 中的当前日期值。

```cpp
bool Aspose::Slides::BaseSlide::Equals(System::SharedPtr<IBaseSlide> slide) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../ibaseslide/)\> | 用于与当前 [IBaseSlide](../../ibaseslide/) 进行比较的 [IBaseSlide](../../ibaseslide/)。 |

### 返回值

**true** 如果指定的 [IBaseSlide](../../ibaseslide/) 与当前 [IBaseSlide](../../ibaseslide/) 相等；否则，**false**。

## 备注

下面的示例展示了如何比较两个幻灯片。 
```cpp
auto presentation1 = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto presentation2 = System::MakeObject<Presentation>(u"HelloWorld.pptx");
for (int32_t i = 0; i < presentation1->get_Masters()->get_Count(); i++)
{
    auto master1 = presentation1->get_Masters()->idx_get(i);
    for (int32_t j = 0; j < presentation2->get_Masters()->get_Count(); j++)
    {
        auto master2 = presentation2->get_Masters()->idx_get(j);
        if (System::ObjectExt::Equals(master1, master2))
        {
            System::Console::WriteLine(System::String::Format(u"SomePresentation1 MasterSlide#{0} is equal to SomePresentation2 MasterSlide#{1}", i, j));
        }
    }
}
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IBaseSlide](../../ibaseslide/)
* 类 [BaseSlide](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)