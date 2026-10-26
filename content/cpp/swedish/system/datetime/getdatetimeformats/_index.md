---
title: GetDateTimeFormats()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en array av strängar där varje element är objektets strängrepresentation formaterad med en av de standarddatum- och tidsformatsspecifikerna.
type: docs
weight: 547
url: /sv/system/datetime/getdatetimeformats/
---
## DateTime::GetDateTimeFormats() const method

Returnerar en array av strängar där varje element är objektets strängrepresentation formaterad med en av de standarddatum- och tidsformatsspecifikerna.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats() const
```

## DateTime::GetDateTimeFormats(char_t) const method

Returnerar en array av strängar där varje element är objektets strängrepresentation formaterad med den angivna standarddatum- och tidsformatsspecifikatorn.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | char_t | Standard datum- och tidsformatsspecifikator. |

## DateTime::GetDateTimeFormats(const SharedPtr\<IFormatProvider\>\&) const method

Returnerar en array av strängar där varje element är objektets strängrepresentation formaterad med en av de standarddatum- och tidsformatsspecifikerna samt den angivna formatleverantören.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(const SharedPtr<IFormatProvider> &provider) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatleverantör. |

## DateTime::GetDateTimeFormats(char_t, const SharedPtr\<IFormatProvider\>\&) const method

Returnerar en array av strängar där varje element är objektets strängrepresentation formaterad med den angivna standarddatum- och tidsformatsspecifikatorn samt formatleverantören.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format, const SharedPtr<IFormatProvider> &provider) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | char_t | Standard datum- och tidsformatsspecifikator. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatleverantör. |

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Klass [String](../../string/)
* Klass [DateTime](../)
* Klass [IFormatProvider](../../iformatprovider/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)