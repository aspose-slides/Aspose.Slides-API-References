---
title: StringWriter()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een nieuw exemplaar van StringWriter met de opgegeven StringBuilder en IFormatProvider.
type: docs
weight: 1
url: /nl/system.io/stringwriter/stringwriter/
---
## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&, const IFormatProviderPtr\&) constructor


Construeert een nieuw exemplaar van [StringWriter](../) met de opgegeven StringBuilder en [IFormatProvider](../../../system/iformatprovider/).

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb, const IFormatProviderPtr &formatProvider)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | Het StringBuilder-object dat wordt gebruikt door de [StringWriter](../) die wordt geconstrueerd |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | Een [IFormatProvider](../../../system/iformatprovider/)-object dat wordt gebruikt door het object dat wordt geconstrueerd |

## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&) constructor


Construeert een nieuw exemplaar van [StringWriter](../) met de opgegeven StringBuilder en [IFormatProvider](../../../system/iformatprovider/) van de huidige cultuur.

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | Het StringBuilder-object dat wordt gebruikt door de [StringWriter](../) die wordt geconstrueerd |

## StringWriter::StringWriter(const IFormatProviderPtr\&) constructor


Construeert een nieuw exemplaar van [StringWriter](../) met de opgegeven [IFormatProvider](../../../system/iformatprovider/).

```cpp
System::IO::StringWriter::StringWriter(const IFormatProviderPtr &formatProvider)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | Een [IFormatProvider](../../../system/iformatprovider/)-object dat wordt gebruikt door het object dat wordt geconstrueerd |

## StringWriter::StringWriter() constructor


Construeert een nieuw exemplaar van [StringWriter](../) met [IFormatProvider](../../../system/iformatprovider/) van de huidige cultuur.

```cpp
System::IO::StringWriter::StringWriter()
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [IFormatProviderPtr](../../../system/iformatproviderptr/)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Class [StringWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)