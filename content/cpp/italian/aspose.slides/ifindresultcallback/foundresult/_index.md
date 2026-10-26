---
title: FoundResult()
second_title: Riferimento API di Aspose.Slides per C++
description: Metodo di callback che riceve i dati sul testo trovato.
type: docs
weight: 1
url: /it/aspose.slides/ifindresultcallback/foundresult/
---
## IFindResultCallback::FoundResult(System::SharedPtr\<ITextFrame\>, System::String, System::String, int32_t) method

Metodo di callback che riceve i dati sul testo trovato.

```cpp
virtual void Aspose::Slides::IFindResultCallback::FoundResult(System::SharedPtr<ITextFrame> textFrame, System::String sourceText, System::String foundText, int32_t textPosition)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../itextframe/)\> | Il [ITextFrame](../../itextframe/) in cui è stato trovato il testo. |
| sourceText | [System::String](../../../system/string/) | Il testo sorgente in cui è stato trovato il testo. |
| foundText | [System::String](../../../system/string/) | Il testo trovato. |
| textPosition | **int32_t** | La posizione del testo trovato. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ITextFrame](../../itextframe/)
* Classe [String](../../../system/string/)
* Classe [IFindResultCallback](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)