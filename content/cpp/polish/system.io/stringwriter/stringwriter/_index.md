---
title: StringWriter()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy nową instancję klasy StringWriter przy użyciu określonego StringBuilder i IFormatProvider.
type: docs
weight: 1
url: /pl/system.io/stringwriter/stringwriter/
---
## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&, const IFormatProviderPtr\&) konstruktor


Tworzy nową instancję [StringWriter](../) przy użyciu określonego StringBuilder i [IFormatProvider](../../../system/iformatprovider/).

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb, const IFormatProviderPtr &formatProvider)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | Obiekt StringBuilder używany przez tworzoną [StringWriter](../) |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | Obiekt [IFormatProvider](../../../system/iformatprovider/) używany przez tworzony obiekt |

## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&) konstruktor


Tworzy nową instancję [StringWriter](../) przy użyciu określonego StringBuilder i [IFormatProvider](../../../system/iformatprovider/) z bieżącej kultury.

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | Obiekt StringBuilder używany przez tworzoną [StringWriter](../) |

## StringWriter::StringWriter(const IFormatProviderPtr\&) konstruktor


Tworzy nową instancję [StringWriter](../) przy użyciu określonego [IFormatProvider](../../../system/iformatprovider/).

```cpp
System::IO::StringWriter::StringWriter(const IFormatProviderPtr &formatProvider)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | Obiekt [IFormatProvider](../../../system/iformatprovider/) używany przez tworzony obiekt |

## StringWriter::StringWriter() konstruktor


Tworzy nową instancję [StringWriter](../) przy użyciu [IFormatProvider](../../../system/iformatprovider/) z bieżącej kultury.

```cpp
System::IO::StringWriter::StringWriter()
```

## Zobacz również

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [IFormatProviderPtr](../../../system/iformatproviderptr/)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Class [StringWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)