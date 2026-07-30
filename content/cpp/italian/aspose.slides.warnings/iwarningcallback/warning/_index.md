---
title: Warning()
second_title: Riferimento API Aspose.Slides per C++
description: Metodo di callback che riceve l'avviso e decide se l'operazione deve essere interrotta.
type: docs
weight: 1
url: /it/aspose.slides.warnings/iwarningcallback/warning/
---
## IWarningCallback::Warning(System::SharedPtr\<IWarningInfo\>) metodo

Metodo di callback che riceve l'avviso e decide se l'operazione deve essere interrotta.

```cpp
virtual ReturnAction Aspose::Slides::Warnings::IWarningCallback::Warning(System::SharedPtr<IWarningInfo> warning)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| warning | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningInfo](../../iwarninginfo/)\> | Avviso da elaborare. |

### Valore di ritorno

Decisione di interruzione [ReturnAction](../../returnaction/).

## Vedi anche

* Enum [ReturnAction](../../returnaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IWarningInfo](../../iwarninginfo/)
* Classe [IWarningCallback](../)
* Spazio dei nomi [Aspose::Slides::Warnings](../../)
* Library [Aspose.Slides](../../../)