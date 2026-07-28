---
title: FoundResult()
second_title: Aspose.Slides dla C++ - referencja API
description: Metoda wywołania zwrotnego, która otrzymuje dane o znalezionym tekście.
type: docs
weight: 1
url: /pl/aspose.slides/ifindresultcallback/foundresult/
---
## IFindResultCallback::FoundResult(System::SharedPtr\<ITextFrame\>, System::String, System::String, int32_t) method

Metoda wywołania zwrotnego, która otrzymuje dane o znalezionym tekście.

```cpp
virtual void Aspose::Slides::IFindResultCallback::FoundResult(System::SharedPtr<ITextFrame> textFrame, System::String sourceText, System::String foundText, int32_t textPosition)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../itextframe/)\> | Obiekt [ITextFrame](../../itextframe/) w którym znaleziono tekst. |
| sourceText | [System::String](../../../system/string/) | Tekst źródłowy, w którym znaleziono tekst. |
| foundText | [System::String](../../../system/string/) | Znaleziony tekst. |
| textPosition | **int32_t** | Pozycja znalezionego tekstu. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITextFrame](../../itextframe/)
* Class [String](../../../system/string/)
* Class [IFindResultCallback](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)