---
title: FoundResult()
second_title: Aspose.Slides for C++ API 參考文件
description: 回呼方法，用於接收關於找到的文字之資料。
type: docs
weight: 1
url: /zh-hant/aspose.slides/ifindresultcallback/foundresult/
---
## IFindResultCallback::FoundResult(System::SharedPtr\<ITextFrame\>, System::String, System::String, int32_t) 方法

回呼方法，用於接收關於找到的文字之資料。

```cpp
virtual void Aspose::Slides::IFindResultCallback::FoundResult(System::SharedPtr<ITextFrame> textFrame, System::String sourceText, System::String foundText, int32_t textPosition)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../itextframe/)\> | 在其中找到文字的 [ITextFrame](../../itextframe/)。 |
| sourceText | [System::String](../../../system/string/) | 在其中找到文字的來源文字。 |
| foundText | [System::String](../../../system/string/) | 找到的文字。 |
| textPosition | **int32_t** | 找到文字的位置。 |

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [ITextFrame](../../itextframe/)
* 類別 [String](../../../system/string/)
* 類別 [IFindResultCallback](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)