---
title: StringWriter()
second_title: Aspose.Slides für C++ API-Referenz
description: Konstruiert eine neue Instanz von StringWriter mit dem angegebenen StringBuilder und IFormatProvider.
type: docs
weight: 1
url: /de/system.io/stringwriter/stringwriter/
---
## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&, const IFormatProviderPtr\&) Konstruktor


Konstruiert eine neue Instanz von [StringWriter](../) mit dem angegebenen StringBuilder und [IFormatProvider](../../../system/iformatprovider/).

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb, const IFormatProviderPtr &formatProvider)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | Das StringBuilder-Objekt, das vom zu erstellenden [StringWriter](../) verwendet wird |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | Ein [IFormatProvider](../../../system/iformatprovider/)-Objekt, das vom zu erstellenden Objekt verwendet wird |

## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&) Konstruktor


Konstruiert eine neue Instanz von [StringWriter](../) mit dem angegebenen StringBuilder und [IFormatProvider](../../../system/iformatprovider/) aus der aktuellen Kultur.

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | Das StringBuilder-Objekt, das vom zu erstellenden [StringWriter](../) verwendet wird |

## StringWriter::StringWriter(const IFormatProviderPtr\&) Konstruktor


Konstruiert eine neue Instanz von [StringWriter](../) mit dem angegebenen [IFormatProvider](../../../system/iformatprovider/).

```cpp
System::IO::StringWriter::StringWriter(const IFormatProviderPtr &formatProvider)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | Ein [IFormatProvider](../../../system/iformatprovider/)-Objekt, das vom zu erstellenden Objekt verwendet wird |

## StringWriter::StringWriter() Konstruktor


Konstruiert eine neue Instanz von [StringWriter](../) unter Verwendung von [IFormatProvider](../../../system/iformatprovider/) aus der aktuellen Kultur.

```cpp
System::IO::StringWriter::StringWriter()
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [IFormatProviderPtr](../../../system/iformatproviderptr/)
* Klasse [StringBuilder](../../../system.text/stringbuilder/)
* Klasse [StringWriter](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)