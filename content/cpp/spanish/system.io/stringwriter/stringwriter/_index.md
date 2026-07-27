---
title: StringWriter()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye una nueva instancia de StringWriter usando el StringBuilder especificado y IFormatProvider.
type: docs
weight: 1
url: /es/system.io/stringwriter/stringwriter/
---
## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&, const IFormatProviderPtr\&) constructor

Construye una nueva instancia de [StringWriter](../) usando el StringBuilder especificado y [IFormatProvider](../../../system/iformatprovider/).

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb, const IFormatProviderPtr &formatProvider)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | El objeto StringBuilder que será usado por el [StringWriter](../) que se está construyendo |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | Un objeto [IFormatProvider](../../../system/iformatprovider/) que será usado por el objeto que se está construyendo |

## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&) constructor

Construye una nueva instancia de [StringWriter](../) usando el StringBuilder especificado y [IFormatProvider](../../../system/iformatprovider/) de la cultura actual.

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | El objeto StringBuilder que será usado por el [StringWriter](../) que se está construyendo |

## StringWriter::StringWriter(const IFormatProviderPtr\&) constructor

Construye una nueva instancia de [StringWriter](../) usando el [IFormatProvider](../../../system/iformatprovider/) especificado.

```cpp
System::IO::StringWriter::StringWriter(const IFormatProviderPtr &formatProvider)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | Un objeto [IFormatProvider](../../../system/iformatprovider/) que será usado por el objeto que se está construyendo |

## StringWriter::StringWriter() constructor

Construye una nueva instancia de [StringWriter](../) usando [IFormatProvider](../../../system/iformatprovider/) de la cultura actual.

```cpp
System::IO::StringWriter::StringWriter()
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [IFormatProviderPtr](../../../system/iformatproviderptr/)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Class [StringWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)