---
title: GetAllTextFrames()
second_title: Aspose.Slides for C++ API 参考
description: 返回 PPTX 演示文稿中的所有文本框。
type: docs
weight: 79
url: /zh/aspose.slides.util/slideutil/getalltextframes/
---
## SlideUtil::GetAllTextFrames(System::SharedPtr\<IPresentation\>, bool) method

返回 PPTX 演示文稿中的所有文本框。

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetAllTextFrames(System::SharedPtr<IPresentation> pres, bool withMasters)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | 已扫描的演示文稿。 |
| withMasters | **bool** | 确定是否应扫描母版幻灯片。 |

### 返回值

[TextFrame](../../../aspose.slides/textframe/) 对象的数组。

## 另请参阅

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ITextFrame](../../../aspose.slides/itextframe/)
* 类 [IPresentation](../../../aspose.slides/ipresentation/)
* 类 [SlideUtil](../)
* 命名空间 [Aspose::Slides::Util](../../)
* 库 [Aspose.Slides](../../../)