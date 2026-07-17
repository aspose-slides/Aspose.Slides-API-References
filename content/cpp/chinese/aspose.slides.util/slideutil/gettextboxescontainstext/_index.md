---
title: GetTextBoxesContainsText()
second_title: Aspose.Slides for C++ API 参考
description: 返回指定幻灯片上包含给定文本的所有文本框。
type: docs
weight: 66
url: /zh/aspose.slides.util/slideutil/gettextboxescontainstext/
---
## SlideUtil::GetTextBoxesContainsText(System::SharedPtr\<IBaseSlide\>, System::String, bool) 方法

返回指定幻灯片上包含给定文本的所有文本框。

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetTextBoxesContainsText(System::SharedPtr<IBaseSlide> slide, System::String text, bool checkPlaceholderText)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | 要搜索的幻灯片。 |
| text | [System::String](../../../system/string/) | 要在文本框中搜索的文本。 |
| checkPlaceholderText | **bool** | 指示是否包含空的文本框，但其占位符文本包含搜索文本。 |

### 返回值

包含指定文本的 [ITextFrame](../../../aspose.slides/itextframe/) 对象数组。

## 另请参见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [ITextFrame](../../../aspose.slides/itextframe/)
* 类 [IBaseSlide](../../../aspose.slides/ibaseslide/)
* 类 [String](../../../system/string/)
* 类 [SlideUtil](../)
* 命名空间 [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)