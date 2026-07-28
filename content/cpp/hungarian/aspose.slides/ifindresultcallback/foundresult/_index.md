---
title: FoundResult()
second_title: Aspose.Slides C++ API referencia
description: Visszahívási metódus, amely adatokat kap a megtalált szövegről.
type: docs
weight: 1
url: /hu/aspose.slides/ifindresultcallback/foundresult/
---
## IFindResultCallback::FoundResult(System::SharedPtr\<ITextFrame\>, System::String, System::String, int32_t) metódus

Visszahívási metódus, amely adatokat kap a megtalált szövegről.

```cpp
virtual void Aspose::Slides::IFindResultCallback::FoundResult(System::SharedPtr<ITextFrame> textFrame, System::String sourceText, System::String foundText, int32_t textPosition)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../itextframe/)\> | A [ITextFrame](../../itextframe/), amelyben a szöveget megtalálták. |
| sourceText | [System::String](../../../system/string/) | A forrásszöveg, amelyben a szöveget megtalálták. |
| foundText | [System::String](../../../system/string/) | A megtalált szöveg. |
| textPosition | **int32_t** | A megtalált szöveg pozíciója. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ITextFrame](../../itextframe/)
* Osztály [String](../../../system/string/)
* Osztály [IFindResultCallback](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)