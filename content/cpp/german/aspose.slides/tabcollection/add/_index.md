---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt ein Tab zur Sammlung hinzu.
type: docs
weight: 53
url: /de/aspose.slides/tabcollection/add/
---
## TabCollection::Add(double, TabAlignment) Methode

Fügt ein [Tab](../../tab/) zur Sammlung hinzu.

```cpp
System::SharedPtr<ITab> Aspose::Slides::TabCollection::Add(double position, TabAlignment align) override
```

### Rückgabewert

Hinzugefügtes tab.

## TabCollection::Add(System::SharedPtr\<ITab\>) Methode

Fügt ein [Tab](../../tab/) zur Sammlung hinzu.

```cpp
int32_t Aspose::Slides::TabCollection::Add(System::SharedPtr<ITab> value) override
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | Das [Tab](../../tab/)-Objekt, das am Ende der Sammlung hinzugefügt wird. |

### Rückgabewert

Der Index, an dem das tab hinzugefügt wurde.

## Siehe auch

* Enum [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITab](../../itab/)
* Class [TabCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)