---
title: FoundResult()
second_title: Aspose.Slides voor C++ API-referentie
description: Callback-methode die gegevens ontvangt over de gevonden tekst.
type: docs
weight: 1
url: /nl/aspose.slides/ifindresultcallback/foundresult/
---
## IFindResultCallback::FoundResult(System::SharedPtr\<ITextFrame\>, System::String, System::String, int32_t) methode


Callback-methode die gegevens ontvangt over de gevonden tekst.

```cpp
virtual void Aspose::Slides::IFindResultCallback::FoundResult(System::SharedPtr<ITextFrame> textFrame, System::String sourceText, System::String foundText, int32_t textPosition)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../itextframe/)\> | De [ITextFrame](../../itextframe/) waarin de tekst werd gevonden. |
| sourceText | [System::String](../../../system/string/) | De brontekst waarin de tekst werd gevonden. |
| foundText | [System::String](../../../system/string/) | De gevonden tekst. |
| textPosition | **int32_t** | De positie van de gevonden tekst. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ITextFrame](../../itextframe/)
* Klasse [String](../../../system/string/)
* Klasse [IFindResultCallback](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)