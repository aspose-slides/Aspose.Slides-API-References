---
title: GetDateTimeFormats()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt ein Array von Zeichenketten zurück, wobei jedes Element die String-Darstellung des aktuellen Objekts ist, formatiert mit einem der standardmäßigen Datums- und Zeitformat-Spezifizierer.
type: docs
weight: 547
url: /de/system/datetime/getdatetimeformats/
---
## DateTime::GetDateTimeFormats() const Methode


Gibt ein Array von Zeichenketten zurück, wobei jedes Element die String-Darstellung des aktuellen Objekts ist, formatiert mit einem der standardmäßigen Datums- und Zeitformat-Spezifizierer.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats() const
```

## DateTime::GetDateTimeFormats(char_t) const Methode


Gibt ein Array von Zeichenketten zurück, wobei jedes Element die String-Darstellung des aktuellen Objekts ist, formatiert mit dem angegebenen standardmäßigen Datums- und Zeitformat-Spezifizierer.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | char_t | Standard-Datums- und Zeitformat-Spezifizierer. |

## DateTime::GetDateTimeFormats(const SharedPtr\<IFormatProvider\>\&) const Methode


Gibt ein Array von Zeichenketten zurück, wobei jedes Element die String-Darstellung des aktuellen Objekts ist, formatiert mit einem der standardmäßigen Datums- und Zeitformat-Spezifizierer und dem angegebenen Format-Provider.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(const SharedPtr<IFormatProvider> &provider) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format-Provider. |

## DateTime::GetDateTimeFormats(char_t, const SharedPtr\<IFormatProvider\>\&) const Methode


Gibt ein Array von Zeichenketten zurück, wobei jedes Element die String-Darstellung des aktuellen Objekts ist, formatiert mit dem angegebenen standardmäßigen Datums- und Zeitformat-Spezifizierer und dem Format-Provider.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format, const SharedPtr<IFormatProvider> &provider) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | char_t | Standard-Datums- und Zeitformat-Spezifizierer. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format-Provider. |

## Siehe Auch

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [DateTime](../)
* Klasse [IFormatProvider](../../iformatprovider/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)