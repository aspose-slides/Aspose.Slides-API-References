---
title: AddControl()
second_title: Riferimento API Aspose.Slides per C++
description: Crea e aggiunge un nuovo controllo alla raccolta.
type: docs
weight: 40
url: /it/aspose.slides/controlcollection/addcontrol/
---
## ControlCollection::AddControl(ControlType, float, float, float, float) method

Crea e aggiunge un nuovo controllo alla raccolta.

```cpp
System::SharedPtr<IControl> Aspose::Slides::ControlCollection::AddControl(ControlType controlType, float x, float y, float width, float height) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| controlType | [ControlType](../../controltype/) | Tipo di controllo da aggiungere. |
| x | **float** | La coordinata X per il lato sinistro del frame della forma. |
| y | **float** | La coordinata Y per il lato superiore del frame della forma. |
| width | **float** | La larghezza del frame della forma. |
| height | **float** | L'altezza del frame della forma. |

### Valore di ritorno

Controllo creato.

## Vedi anche

* Enum [ControlType](../../controltype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IControl](../../icontrol/)
* Classe [ControlCollection](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)