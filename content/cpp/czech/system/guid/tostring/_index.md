---
title: ToString()
second_title: Aspose.Slides pro C++ API Reference
description: Převádí GUID reprezentovaný aktuálním objektem na jeho řetězcové vyjádření.
type: docs
weight: 79
url: /cs/system/guid/tostring/
---
## Guid::ToString() const metoda


Převádí GUID reprezentovaný aktuálním objektem na jeho řetězcové vyjádření.

```cpp
String System::Guid::ToString() const
```

## Guid::ToString(const String\&) const metoda


Převádí GUID reprezentovaný aktuálním objektem na jeho řetězcové vyjádření pomocí zadaného formátu řetězce.

```cpp
String System::Guid::ToString(const String &format) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| format | const [String](../../string/)\& | Formát, který se má použít |

### Návratová hodnota

Řetězcové vyjádření hodnoty GUID reprezentované aktuálním objektem

## Guid::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const metoda


Převádí GUID reprezentovaný aktuálním objektem na jeho řetězcové vyjádření pomocí zadaného formátu řetězce a kultury.

```cpp
String System::Guid::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| format | const [String](../../string/)\& | Formát, který se má použít |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultura, která se má použít |

### Návratová hodnota

Řetězcové vyjádření hodnoty GUID reprezentované aktuálním objektem

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Guid](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)