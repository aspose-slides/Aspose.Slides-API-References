---
title: StringWriter()
second_title: Aspose.Slides pro C++ - referenční API
description: Vytvoří novou instanci StringWriter pomocí zadaného StringBuilderu a IFormatProvideru.
type: docs
weight: 1
url: /cs/system.io/stringwriter/stringwriter/
---
## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&, const IFormatProviderPtr\&) konstruktor

Vytvoří novou instanci [StringWriter](../) pomocí zadaného StringBuilderu a [IFormatProvider](../../../system/iformatprovider/).

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb, const IFormatProviderPtr &formatProvider)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | Objekt StringBuilder, který bude použit [StringWriter](../) při konstrukci |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | Objekt [IFormatProvider](../../../system/iformatprovider/), který bude použit objektem, který se vytváří |

## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&) konstruktor

Vytvoří novou instanci [StringWriter](../) pomocí zadaného StringBuilderu a [IFormatProvider](../../../system/iformatprovider/) z aktuální kultury.

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | Objekt StringBuilder, který bude použit [StringWriter](../) při konstrukci |

## StringWriter::StringWriter(const IFormatProviderPtr\&) konstruktor

Vytvoří novou instanci [StringWriter](../) pomocí zadaného [IFormatProvider](../../../system/iformatprovider/).

```cpp
System::IO::StringWriter::StringWriter(const IFormatProviderPtr &formatProvider)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | Objekt [IFormatProvider](../../../system/iformatprovider/), který bude použit objektem, který se vytváří |

## StringWriter::StringWriter() konstruktor

Vytvoří novou instanci [StringWriter](../) pomocí [IFormatProvider](../../../system/iformatprovider/) z aktuální kultury.

```cpp
System::IO::StringWriter::StringWriter()
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [IFormatProviderPtr](../../../system/iformatproviderptr/)
* Třída [StringBuilder](../../../system.text/stringbuilder/)
* Třída [StringWriter](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)