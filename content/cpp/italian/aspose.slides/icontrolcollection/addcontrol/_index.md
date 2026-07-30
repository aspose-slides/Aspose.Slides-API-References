---
title: AddControl()
second_title: Riferimento API Aspose.Slides per C++
description: Crea e aggiunge un nuovo controllo alla raccolta.
type: docs
weight: 53
url: /it/aspose.slides/icontrolcollection/addcontrol/
---
## IControlCollection::AddControl(ControlType, float, float, float, float) metodo

Crea e aggiunge un nuovo controllo alla raccolta.

```cpp
virtual System::SharedPtr<IControl> Aspose::Slides::IControlCollection::AddControl(ControlType controlType, float x, float y, float width, float height)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| controlType | [ControlType](../../controltype/) | Tipo di un controllo da aggiungere. |
| x | **float** | La coordinata X per il lato sinistro del riquadro della forma. |
| y | **float** | La coordinata Y per il lato superiore del riquadro della forma. |
| width | **float** | La larghezza del riquadro della forma. |
| height | **float** | L'altezza del riquadro della forma. |

### Valore di ritorno

Controllo creato [IControl](../../icontrol/).

## Vedi anche

* Enum [ControlType](../../controltype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IControl](../../icontrol/)
* Class [IControlCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)