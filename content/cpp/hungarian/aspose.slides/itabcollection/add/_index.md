---
title: Add()
second_title: Aspose.Slides C++ API referenciája
description: Hozzáad egy Tab-ot a gyűjteményhez.
type: docs
weight: 14
url: /hu/aspose.slides/itabcollection/add/
---
## ITabCollection::Add(double, TabAlignment) metódus


Hozzáad egy [Tab](../../tab/) a gyűjteményhez.

```cpp
virtual System::SharedPtr<ITab> Aspose::Slides::ITabCollection::Add(double position, TabAlignment align)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| position | **double** | [Tab](../../tab/) pozíció. |
| align | [TabAlignment](../../tabalignment/) | [Tab](../../tab/) igazítás. |

### Visszatérési érték

Hozzáadott tab.

## ITabCollection::Add(System::SharedPtr\<ITab\>) metódus


Hozzáad egy [Tab](../../tab/) a gyűjteményhez.

```cpp
virtual int32_t Aspose::Slides::ITabCollection::Add(System::SharedPtr<ITab> value)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | A [Tab](../../tab/) objektum, amely a gyűjtemény végére lesz hozzáadva. |

### Visszatérési érték

Az index, amelyre a tab hozzá lett adva.

## Lásd még

* Enum [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ITab](../../itab/)
* Osztály [ITabCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)