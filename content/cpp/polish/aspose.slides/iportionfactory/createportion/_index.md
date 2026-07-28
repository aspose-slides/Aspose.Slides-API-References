---
title: CreatePortion()
second_title: Aspose.Slides dla C++ Referencja API
description: Tworzy pusty fragment tekstu.
type: docs
weight: 1
url: /pl/aspose.slides/iportionfactory/createportion/
---
## IPortionFactory::CreatePortion() metoda

Tworzy pusty fragment tekstu.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion()=0
```

### Wartość zwracana

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::String) metoda

Tworzy fragment tekstu z podanego ciągu znaków.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::String str)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | Ciąg znaków. |

### Wartość zwracana

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) metoda

Tworzy fragment przy użyciu podanych danych fragmentu.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::SharedPtr<IPortion> portion)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | Fragment do użycia. |

### Wartość zwracana

[Portion](../../portion/).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPortion](../../iportion/)
* Class [IPortionFactory](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)