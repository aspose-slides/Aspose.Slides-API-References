---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt ein Tab zur Sammlung hinzu.
type: docs
weight: 14
url: /de/aspose.slides/itabcollection/add/
---
## ITabCollection::Add(double, TabAlignment) Methode


Fügt ein [Tab](../../tab/) zur Sammlung hinzu.

```cpp
virtual System::SharedPtr<ITab> Aspose::Slides::ITabCollection::Add(double position, TabAlignment align)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | **double** | [Tab](../../tab/) Position. |
| align | [TabAlignment](../../tabalignment/) | [Tab](../../tab/) Ausrichtung. |

### Rückgabewert

Hinzugefügtes Tab.

## ITabCollection::Add(System::SharedPtr\<ITab\>) Methode


Fügt ein [Tab](../../tab/) zur Sammlung hinzu.

```cpp
virtual int32_t Aspose::Slides::ITabCollection::Add(System::SharedPtr<ITab> value)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | Das [Tab](../../tab/) Objekt, das am Ende der Sammlung hinzugefügt wird. |

### Rückgabewert

Der Index, an dem das Tab hinzugefügt wurde.

## Siehe auch

* Enum [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ITab](../../itab/)
* Klasse [ITabCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)