---
title: CreatePortion()
second_title: Aspose.Slides C++ API referenciája
description: Létrehoz egy üres szövegrészt.
type: docs
weight: 1
url: /hu/aspose.slides/portionfactory/createportion/
---
## PortionFactory::CreatePortion() method

Létrehoz egy üres szövegrészt.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion() override
```

### Visszatérési érték

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::String) method

Létrehoz egy szövegrészt a megadott karakterláncból.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::String str) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | String. |

### Visszatérési érték

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) method

Létrehoz egy részt a megadott részadatok felhasználásával.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::SharedPtr<IPortion> portion) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | A használni kívánt rész. |

### Visszatérési érték

[Portion](../../portion/).

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IPortion](../../iportion/)
* Osztály [PortionFactory](../)
* Osztály [String](../../../system/string/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)