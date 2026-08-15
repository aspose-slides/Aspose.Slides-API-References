---
title: GetAllTextFrames()
second_title: Aspose.Slides for C++ API 參考
description: 返回 PPTX 簡報中的所有文字框。
type: docs
weight: 79
url: /zh-hant/aspose.slides.util/slideutil/getalltextframes/
---
## SlideUtil::GetAllTextFrames(System::SharedPtr\<IPresentation\>, bool) 方法

返回 PPTX 簡報中的所有文字框。

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetAllTextFrames(System::SharedPtr<IPresentation> pres, bool withMasters)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | 已掃描的簡報。 |
| withMasters | **bool** | 決定是否要掃描母片。 |

### 返回值

[TextFrame](../../../aspose.slides/textframe/) 物件的陣列。

## 另請參閱

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ITextFrame](../../../aspose.slides/itextframe/)
* 類別 [IPresentation](../../../aspose.slides/ipresentation/)
* 類別 [SlideUtil](../)
* 命名空間 [Aspose::Slides::Util](../../)
* 程式庫 [Aspose.Slides](../../../)