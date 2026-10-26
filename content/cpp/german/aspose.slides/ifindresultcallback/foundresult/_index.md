---
title: FoundResult()
second_title: Aspose.Slides für C++ API-Referenz
description: Callback-Methode, die Daten über den gefundenen Text empfängt.
type: docs
weight: 1
url: /de/aspose.slides/ifindresultcallback/foundresult/
---
## IFindResultCallback::FoundResult(System::SharedPtr\<ITextFrame\>, System::String, System::String, int32_t) Methode

Callback-Methode, die Daten über den gefundenen Text empfängt.

```cpp
virtual void Aspose::Slides::IFindResultCallback::FoundResult(System::SharedPtr<ITextFrame> textFrame, System::String sourceText, System::String foundText, int32_t textPosition)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../itextframe/)\> | Der [ITextFrame](../../itextframe/), in dem der Text gefunden wurde. |
| sourceText | [System::String](../../../system/string/) | Der Quelltext, in dem der Text gefunden wurde. |
| foundText | [System::String](../../../system/string/) | Der gefundene Text. |
| textPosition | **int32_t** | Die Position des gefundenen Textes. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ITextFrame](../../itextframe/)
* Klasse [String](../../../system/string/)
* Klasse [IFindResultCallback](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)