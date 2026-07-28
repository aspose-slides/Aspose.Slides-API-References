---
title: CreatePortion()
second_title: Aspose.Slides C++ API Referenciája
description: Üres szövegrészt hoz létre.
type: docs
weight: 1
url: /hu/aspose.slides/iportionfactory/createportion/
---
## IPortionFactory::CreatePortion() metódus

Üres szövegrészt hoz létre.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion()=0
```

### Visszatérési érték

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::String) metódus

Szövegrészt hoz létre a megadott karakterláncból.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::String str)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | Karakterlánc. |

### Visszatérési érték

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) metódus

Részletet hoz létre a megadott részletadat használatával.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::SharedPtr<IPortion> portion)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | Használandó rész. |

### Visszatérési érték

[Portion](../../portion/).

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IPortion](../../iportion/)
* Osztály [IPortionFactory](../)
* Osztály [String](../../../system/string/)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)