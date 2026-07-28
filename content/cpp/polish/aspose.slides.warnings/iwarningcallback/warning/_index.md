---
title: Warning()
second_title: Aspose.Slides dla C++ – Odniesienie API
description: Metoda wywołania zwrotnego, która odbiera ostrzeżenie i decyduje, czy operacja powinna zostać przerwana.
type: docs
weight: 1
url: /pl/aspose.slides.warnings/iwarningcallback/warning/
---
## IWarningCallback::Warning(System::SharedPtr\<IWarningInfo\>) method


Metoda wywołania zwrotnego, która odbiera ostrzeżenie i decyduje, czy operacja powinna zostać przerwana.

```cpp
virtual ReturnAction Aspose::Slides::Warnings::IWarningCallback::Warning(System::SharedPtr<IWarningInfo> warning)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| warning | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningInfo](../../iwarninginfo/)\> | Ostrzeżenie do przetworzenia. |

### Wartość zwracana

Decyzja o przerwaniu [ReturnAction](../../returnaction/).

## Zobacz także

* Enum [ReturnAction](../../returnaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IWarningInfo](../../iwarninginfo/)
* Class [IWarningCallback](../)
* Namespace [Aspose::Slides::Warnings](../../)
* Library [Aspose.Slides](../../../)