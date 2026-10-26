---
title: ToString()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar GUID:en som representeras av det aktuella objektet till dess strängrepresentation.
type: docs
weight: 79
url: /sv/system/guid/tostring/
---
## Guid::ToString() const metod


Konverterar GUID:en som representeras av det aktuella objektet till dess strängrepresentation.

```cpp
String System::Guid::ToString() const
```

## Guid::ToString(const String\&) const metod


Konverterar GUID:en som representeras av det aktuella objektet till dess strängrepresentation med det angivna formatet.

```cpp
String System::Guid::ToString(const String &format) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | const [String](../../string/)\& | Formatet att använda |

### Returvärde

Strängrepresentationen av GUID-värdet som representeras av det aktuella objektet

## Guid::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const metod


Konverterar GUID:en som representeras av det aktuella objektet till dess strängrepresentation med det angivna formatet och kultur.

```cpp
String System::Guid::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | const [String](../../string/)\& | Formatet att använda |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultur att använda |

### Returvärde

Strängrepresentationen av GUID-värdet som representeras av det aktuella objektet

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Klass [String](../../string/)
* Klass [Guid](../)
* Klass [CultureInfo](../../../system.globalization/cultureinfo/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)