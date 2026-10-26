---
title: Add()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge un Tab alla collezione.
type: docs
weight: 53
url: /it/aspose.slides/tabcollection/add/
---
## TabCollection::Add(double, TabAlignment) metodo

Aggiunge un [Tab](../../tab/) alla collezione.

```cpp
System::SharedPtr<ITab> Aspose::Slides::TabCollection::Add(double position, TabAlignment align) override
```

### Valore restituito

Tab aggiunto.

## TabCollection::Add(System::SharedPtr\<ITab\>) metodo

Aggiunge un [Tab](../../tab/) alla collezione.

```cpp
int32_t Aspose::Slides::TabCollection::Add(System::SharedPtr<ITab> value) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | L'oggetto [Tab](../../tab/) da aggiungere alla fine della collezione. |

### Valore restituito

L'indice al quale il tab è stato aggiunto.

## Vedi anche

* Enum [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITab](../../itab/)
* Class [TabCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)