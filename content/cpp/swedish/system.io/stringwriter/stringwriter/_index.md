---
title: StringWriter()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans av StringWriter med den angivna StringBuilder och IFormatProvider.
type: docs
weight: 1
url: /sv/system.io/stringwriter/stringwriter/
---
## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&, const IFormatProviderPtr\&) konstruktor

Skapar en ny instans av [StringWriter](../) med den angivna StringBuilder och [IFormatProvider](../../../system/iformatprovider/).

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb, const IFormatProviderPtr &formatProvider)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | StringBuilder-objektet som ska användas av [StringWriter](../) som konstrueras |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | Ett [IFormatProvider](../../../system/iformatprovider/)-objekt som ska användas av objektet som konstrueras |

## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&) konstruktor

Skapar en ny instans av [StringWriter](../) med den angivna StringBuilder och [IFormatProvider](../../../system/iformatprovider/) från den aktuella kulturen.

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | StringBuilder-objektet som ska användas av [StringWriter](../) som konstrueras |

## StringWriter::StringWriter(const IFormatProviderPtr\&) konstruktor

Skapar en ny instans av [StringWriter](../) med den angivna [IFormatProvider](../../../system/iformatprovider/).

```cpp
System::IO::StringWriter::StringWriter(const IFormatProviderPtr &formatProvider)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | Ett [IFormatProvider](../../../system/iformatprovider/)-objekt som ska användas av objektet som konstrueras |

## StringWriter::StringWriter() konstruktor

Skapar en ny instans av [StringWriter](../) med [IFormatProvider](../../../system/iformatprovider/) från den aktuella kulturen.

```cpp
System::IO::StringWriter::StringWriter()
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [IFormatProviderPtr](../../../system/iformatproviderptr/)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Class [StringWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)