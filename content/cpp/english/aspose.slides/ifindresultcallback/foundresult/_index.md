---
title: FoundResult()
second_title: Aspose.Slides for C++ API Reference
description: Callback method that receives data about the found text.
type: docs
weight: 1
url: /aspose.slides/ifindresultcallback/foundresult/
---
## IFindResultCallback::FoundResult(System::SharedPtr\<ITextFrame\>, System::String, System::String, int32_t) method


Callback method that receives data about the found text.

```cpp
virtual void Aspose::Slides::IFindResultCallback::FoundResult(System::SharedPtr<ITextFrame> textFrame, System::String sourceText, System::String foundText, int32_t textPosition)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../itextframe/)\> | The [ITextFrame](../../itextframe/) in which the text was found. |
| sourceText | [System::String](../../../system/string/) | The source text in which the text was found. |
| foundText | [System::String](../../../system/string/) | The found text. |
| textPosition | **int32_t** | The position of the found text. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITextFrame](../../itextframe/)
* Class [String](../../../system/string/)
* Class [IFindResultCallback](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)