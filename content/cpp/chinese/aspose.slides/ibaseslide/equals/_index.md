---
title: Equals()
second_title: Aspose.Slides C++ API 参考
description: 确定两个 IBaseSlide 实例是否相等。返回值基于幻灯片的结构和静态内容计算。如果所有形状、样式、文本、动画及其他设置等全部相等，则两个幻灯片相等。比较不考虑唯一标识符值，例如 SlideId，以及动态内容，例如 Date Placeholder 中的当前日期值。
type: docs
weight: 183
url: /zh/aspose.slides/ibaseslide/equals/
---
## IBaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) 方法

确定两个 [IBaseSlide](../) 实例是否相等。返回值根据幻灯片的结构和静态内容计算。如果所有形状、样式、文本、动画以及其他设置等全部相等，则两个幻灯片相等。比较不考虑唯一标识符值，例如 SlideId，以及动态内容，例如 Date [Placeholder](../../placeholder/) 中的当前日期值。

```cpp
virtual bool Aspose::Slides::IBaseSlide::Equals(System::SharedPtr<IBaseSlide> slide)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../)\> | 用于与当前 [IBaseSlide](../) 比较的 [IBaseSlide](../)。 |

### 返回值

**true** 如果指定的 [IBaseSlide](../) 等于当前 [IBaseSlide](../)；否则，**false**。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IBaseSlide](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)