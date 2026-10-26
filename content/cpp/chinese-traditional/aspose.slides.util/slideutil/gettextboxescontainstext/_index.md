---
title: GetTextBoxesContainsText()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回指定投影片中包含給定文字的所有文字框。
type: docs
weight: 66
url: /zh-hant/aspose.slides.util/slideutil/gettextboxescontainstext/
---
## SlideUtil::GetTextBoxesContainsText(System::SharedPtr\<IBaseSlide\>, System::String, bool) 方法


傳回指定投影片中包含給定文字的所有文字框。

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetTextBoxesContainsText(System::SharedPtr<IBaseSlide> slide, System::String text, bool checkPlaceholderText)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | 要搜尋的投影片。 |
| text | [System::String](../../../system/string/) | 要在文字框中搜尋的文字。 |
| checkPlaceholderText | **bool** | 指示是否包括空的文字框，但其佔位文字包含搜尋文字。 |

### 傳回值

一個包含指定文字的 [ITextFrame](../../../aspose.slides/itextframe/) 物件陣列。

## 另請參閱

* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [ITextFrame](../../../aspose.slides/itextframe/)
* 類別 [IBaseSlide](../../../aspose.slides/ibaseslide/)
* 類別 [String](../../../system/string/)
* 類別 [SlideUtil](../)
* 命名空間 [Aspose::Slides::Util](../../)
* 函式庫 [Aspose.Slides](../../../)