---
title: GetDateTimeFormats()
second_title: Aspose.Slides dla C++ Referencja API
description: Zwraca tablicę ciągów znaków, w której każdy element jest reprezentacją tekstową bieżącego obiektu sformatowanego przy użyciu jednego ze standardowych specyfikatorów formatu daty i czasu.
type: docs
weight: 547
url: /pl/system/datetime/getdatetimeformats/
---
## DateTime::GetDateTimeFormats() const metoda


Zwraca tablicę ciągów znaków, w której każdy element jest reprezentacją tekstową bieżącego obiektu sformatowanego przy użyciu jednego ze standardowych specyfikatorów formatu daty i czasu.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats() const
```

## DateTime::GetDateTimeFormats(char_t) const metoda


Zwraca tablicę ciągów znaków, w której każdy element jest reprezentacją tekstową bieżącego obiektu sformatowanego przy użyciu określonego standardowego specyfikatora formatu daty i czasu.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| format | char_t | Standardowy specyfikator formatu daty i czasu. |

## DateTime::GetDateTimeFormats(const SharedPtr\<IFormatProvider\>\&) const metoda


Zwraca tablicę ciągów znaków, w której każdy element jest reprezentacją tekstową bieżącego obiektu sformatowanego przy użyciu jednego ze standardowych specyfikatorów formatu daty i czasu oraz określonego dostawcy formatu.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(const SharedPtr<IFormatProvider> &provider) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dostawca formatu. |

## DateTime::GetDateTimeFormats(char_t, const SharedPtr\<IFormatProvider\>\&) const metoda


Zwraca tablicę ciągów znaków, w której każdy element jest reprezentacją tekstową bieżącego obiektu sformatowanego przy użyciu określonego standardowego specyfikatora formatu daty i czasu oraz dostawcy formatu.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format, const SharedPtr<IFormatProvider> &provider) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| format | char_t | Standardowy specyfikator formatu daty i czasu. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dostawca formatu. |

## Zobacz także

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasa [String](../../string/)
* Klasa [DateTime](../)
* Klasa [IFormatProvider](../../iformatprovider/)
* Przestrzeń nazw [System](../../)
* Library [Aspose.Slides](../../../)