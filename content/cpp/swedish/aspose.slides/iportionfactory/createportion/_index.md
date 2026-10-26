---
title: CreatePortion()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en tom textdel.
type: docs
weight: 1
url: /sv/aspose.slides/iportionfactory/createportion/
---
## IPortionFactory::CreatePortion() metod


Skapar en tom textdel.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion()=0
```


### Returvärde

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::String) metod


Skapar en textdel från angiven sträng.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::String str)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | Sträng. |

### Returvärde

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) metod


Skapar en del med användning av specificerad deldata.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::SharedPtr<IPortion> portion)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | En del att använda. |

### Returvärde

[Portion](../../portion/).

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IPortion](../../iportion/)
* Klass [IPortionFactory](../)
* Klass [String](../../../system/string/)
* Namnutrymme [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)