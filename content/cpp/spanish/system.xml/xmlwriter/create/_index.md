---
title: Create()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una nueva instancia de XmlWriter usando el nombre de archivo especificado.
type: docs
weight: 469
url: /es/system.xml/xmlwriter/create/
---
## XmlWriter::Create(const String\&) method

Crea una nueva instancia [XmlWriter](../) usando el nombre de archivo especificado.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | El archivo al que desea escribir. El [XmlWriter](../) crea un archivo en la ruta especificada y escribe en él con la sintaxis de texto XML 1.0. **outputFileName** debe ser una ruta del sistema de archivos. |

### Valor de retorno

Un objeto [XmlWriter](../).

## XmlWriter::Create(const String\&, SharedPtr\<XmlWriterSettings\>) method

Crea una nueva instancia [XmlWriter](../) usando el nombre de archivo y el objeto [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName, SharedPtr<XmlWriterSettings> settings)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | El archivo al que desea escribir. El [XmlWriter](../) crea un archivo en la ruta especificada y escribe en él con la sintaxis de texto XML 1.0. **outputFileName** debe ser una ruta del sistema de archivos. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | El objeto [XmlWriterSettings](../../xmlwritersettings/) utilizado para configurar la nueva instancia [XmlWriter](../). Si es **nullptr**, se usa un [XmlWriterSettings](../../xmlwritersettings/) con la configuración predeterminada. Si el [XmlWriter](../) se está utilizando con el método XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), debe usar el valor XslCompiledTransform::get_OutputSettings para obtener un objeto [XmlWriterSettings](../../xmlwritersettings/) con la configuración correcta. Esto garantiza que el objeto [XmlWriter](../) creado tenga la configuración de salida correcta. |

### Valor de retorno

Un objeto [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&) method

Crea una nueva instancia [XmlWriter](../) usando el flujo especificado.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | El flujo al que desea escribir. El [XmlWriter](../) escribe la sintaxis de texto XML 1.0 y lo agrega al flujo especificado. |

### Valor de retorno

Un objeto [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) method

Crea una nueva instancia [XmlWriter](../) usando el flujo y el objeto [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output, SharedPtr<XmlWriterSettings> settings)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | El flujo al que desea escribir. El [XmlWriter](../) escribe la sintaxis de texto XML 1.0 y lo agrega al flujo especificado. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | El objeto [XmlWriterSettings](../../xmlwritersettings/) utilizado para configurar la nueva instancia [XmlWriter](../). Si es **nullptr**, se usa un [XmlWriterSettings](../../xmlwritersettings/) con la configuración predeterminada. Si el [XmlWriter](../) se está utilizando con el método XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), debe usar el valor XslCompiledTransform::get_OutputSettings para obtener un objeto [XmlWriterSettings](../../xmlwritersettings/) con la configuración correcta. Esto garantiza que el objeto [XmlWriter](../) creado tenga la configuración de salida correcta. |

### Valor de retorno

Un objeto [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&) method

Crea una nueva instancia [XmlWriter](../) usando el TextWriter especificado.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | El TextWriter al que desea escribir. El [XmlWriter](../) escribe la sintaxis de texto XML 1.0 y lo agrega al TextWriter especificado. |

### Valor de retorno

Un objeto [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) method

Crea una nueva instancia [XmlWriter](../) usando el TextWriter y los objetos [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output, SharedPtr<XmlWriterSettings> settings)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | El TextWriter al que desea escribir. El [XmlWriter](../) escribe la sintaxis de texto XML 1.0 y lo agrega al TextWriter especificado. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | El objeto [XmlWriterSettings](../../xmlwritersettings/) utilizado para configurar la nueva instancia [XmlWriter](../). Si es **nullptr**, se usa un [XmlWriterSettings](../../xmlwritersettings/) con la configuración predeterminada. Si el [XmlWriter](../) se está utilizando con el método XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), debe usar el valor XslCompiledTransform::get_OutputSettings para obtener un objeto [XmlWriterSettings](../../xmlwritersettings/) con la configuración correcta. Esto garantiza que el objeto [XmlWriter](../) creado tenga la configuración de salida correcta. |

### Valor de retorno

Un objeto [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&) method

Crea una nueva instancia [XmlWriter](../) usando el [Text::StringBuilder](../../../system.text/stringbuilder/) especificado.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | El [Text::StringBuilder](../../../system.text/stringbuilder/) al que desea escribir. El contenido escrito por el [XmlWriter](../) se agrega al [Text::StringBuilder](../../../system.text/stringbuilder/). |

### Valor de retorno

Un objeto [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) method

Crea una nueva instancia [XmlWriter](../) usando los objetos [Text::StringBuilder](../../../system.text/stringbuilder/) y [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output, SharedPtr<XmlWriterSettings> settings)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | El [Text::StringBuilder](../../../system.text/stringbuilder/) al que desea escribir. El contenido escrito por el [XmlWriter](../) se agrega al [Text::StringBuilder](../../../system.text/stringbuilder/). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | El objeto [XmlWriterSettings](../../xmlwritersettings/) utilizado para configurar la nueva instancia [XmlWriter](../). Si es **nullptr**, se usa un [XmlWriterSettings](../../xmlwritersettings/) con la configuración predeterminada. Si el [XmlWriter](../) se está utilizando con el método XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), debe usar el valor XslCompiledTransform::get_OutputSettings para obtener un objeto [XmlWriterSettings](../../xmlwritersettings/) con la configuración correcta. Esto garantiza que el objeto [XmlWriter](../) creado tenga la configuración de salida correcta. |

### Valor de retorno

Un objeto [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&) method

Crea una nueva instancia [XmlWriter](../) usando el objeto [XmlWriter](../) especificado.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | El objeto [XmlWriter](../) que desea usar como escritor subyacente. |

### Valor de retorno

Un objeto [XmlWriter](../) que envuelve al objeto [XmlWriter](../) especificado.

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) method

Crea una nueva instancia [XmlWriter](../) usando los objetos [XmlWriter](../) y [XmlWriterSettings](../../xmlwritersettings/) especificados.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output, SharedPtr<XmlWriterSettings> settings)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | El objeto [XmlWriter](../) que desea usar como escritor subyacente. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | El objeto [XmlWriterSettings](../../xmlwritersettings/) utilizado para configurar la nueva instancia [XmlWriter](../). Si es **nullptr**, se usa un [XmlWriterSettings](../../xmlwritersettings/) con la configuración predeterminada. Si el [XmlWriter](../) se está utilizando con el método XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), debe usar el valor XslCompiledTransform::get_OutputSettings para obtener un objeto [XmlWriterSettings](../../xmlwritersettings/) con la configuración correcta. Esto garantiza que el objeto [XmlWriter](../) creado tenga la configuración de salida correcta. |

### Valor de retorno

Un objeto [XmlWriter](../) que envuelve al objeto [XmlWriter](../) especificado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlWriter](../)
* Clase [String](../../../system/string/)
* Clase [XmlWriterSettings](../../xmlwritersettings/)
* Clase [Stream](../../../system.io/stream/)
* Clase [TextWriter](../../../system.io/textwriter/)
* Clase [StringBuilder](../../../system.text/stringbuilder/)
* Espacio de nombres [System::Xml](../../)
* Library [Aspose.Slides](../../../)