---
title: ToArray()
second_title: Aspose.Slides for C++ API 参考
description: 创建并返回一个包含所有幻灯片的数组。
type: docs
weight: 144
url: /zh/aspose.slides/slidecollection/toarray/
---
## SlideCollection::ToArray() 方法

创建并返回包含所有幻灯片的数组。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::ToArray() override
```

### 返回值

[Slide](../../slide/) 的数组

## SlideCollection::ToArray(int32_t, int32_t) 方法

创建并返回包含指定范围内所有幻灯片的数组。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::ToArray(int32_t startIndex, int32_t count) override
```

### 返回值

[Slide](../../slide/) 的数组

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ISlide](../../islide/)
* 类 [SlideCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 链接库 [Aspose.Slides](../../../)