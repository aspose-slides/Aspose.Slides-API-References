---
title: CreatePortion()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en tom textportion.
type: docs
weight: 1
url: /sv/aspose.slides/portionfactory/createportion/
---
## PortionFactory::CreatePortion() metod

Skapar en tom text portion.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion() override
```

### Returvärde

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::String) metod

Skapar en text portion från en angiven string.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::String str) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | String. |

### Returvärde

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) metod

Skapar en portion med användning av en specificerad portion data.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::SharedPtr<IPortion> portion) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | En portion att använda. |

### Returvärde

[Portion](../../portion/).

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IPortion](../../iportion/)
* Klass [PortionFactory](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)