---
title: FoundResult()
second_title: Aspose.Slides för C++ API-referens
description: Återuppringningsmetod som tar emot data om den hittade texten.
type: docs
weight: 1
url: /sv/aspose.slides/ifindresultcallback/foundresult/
---
## IFindResultCallback::FoundResult(System::SharedPtr\<ITextFrame\>, System::String, System::String, int32_t) metod

Återuppringningsmetod som tar emot data om den hittade texten.

```cpp
virtual void Aspose::Slides::IFindResultCallback::FoundResult(System::SharedPtr<ITextFrame> textFrame, System::String sourceText, System::String foundText, int32_t textPosition)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../itextframe/)\> | Den [ITextFrame](../../itextframe/) där texten hittades. |
| sourceText | [System::String](../../../system/string/) | Källtexten där texten hittades. |
| foundText | [System::String](../../../system/string/) | Den hittade texten. |
| textPosition | **int32_t** | Positionen för den hittade texten. |

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ITextFrame](../../itextframe/)
* Klass [String](../../../system/string/)
* Klass [IFindResultCallback](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)