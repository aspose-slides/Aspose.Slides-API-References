---
title: Add()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge un Tab alla collezione.
type: docs
weight: 14
url: /it/aspose.slides/itabcollection/add/
---
## ITabCollection::Add(double, TabAlignment) metodo

Aggiunge un [Tab](../../tab/) alla collezione.

```cpp
virtual System::SharedPtr<ITab> Aspose::Slides::ITabCollection::Add(double position, TabAlignment align)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | **double** | [Tab](../../tab/) posizione. |
| align | [TabAlignment](../../tabalignment/) | [Tab](../../tab/) allineamento. |

### Valore restituito

Tab aggiunto.

## ITabCollection::Add(System::SharedPtr\<ITab\>) metodo

Aggiunge un [Tab](../../tab/) alla collezione.

```cpp
virtual int32_t Aspose::Slides::ITabCollection::Add(System::SharedPtr<ITab> value)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | L'oggetto [Tab](../../tab/) da aggiungere alla fine della collezione. |

### Valore restituito

L'indice al quale è stato aggiunto il tab.

## Vedi anche

* Enum [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITab](../../itab/)
* Class [ITabCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)