---
title: PersistenceType
second_title: Riferimento API Aspose.Slides per C++
description: Specifica il metodo utilizzato per memorizzare le proprietà del controllo ActiveX.
type: docs
weight: 6189
url: /it/aspose.slides/persistencetype/
---
## PersistenceType enum


Specifica il metodo usato per memorizzare le proprietà del controllo ActiveX.

```cpp
enum class PersistenceType
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| NotDefined | -1 | ID di persistenza non specificato. |
| PersistPropertyBag | 0 | Specifica che il controllo ActiveX è persistito usando la persistenza basata su property-bag. La persistenza basata su property-bag memorizza un controllo ActiveX mediante una raccolta di coppie nome-valore che indicano i dati persistiti dal controllo ActiveX. |
| PersistStream | 1 | Specifica che il controllo ActiveX è persistito usando la persistenza basata su stream che non supporta l'inizializzazione del controllo ActiveX a uno stato predefinito. |
| PersistStreamInit | 2 | Specifica che il controllo ActiveX è persistito usando la persistenza basata su stream che supporta l'inizializzazione del controllo ActiveX a uno stato predefinito. |
| PersistStorage | 3 | Specifica che il controllo ActiveX è persistito usando la persistenza basata su storage. |

## Vedi anche

* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)