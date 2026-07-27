---
title: Create()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una nueva instancia de XmlReader con la URI especificada.
type: docs
weight: 1015
url: /es/system.xml/xmlreader/create/
---
## XmlReader::Create(const String\&) método


Crea una nueva [XmlReader](../) instancia con la URI especificada.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | La URI del archivo que contiene los datos XML. La clase [XmlUrlResolver](../../xmlurlresolver/) se usa para convertir la ruta a una representación de datos canónica. |

### Valor devuelto

Un objeto que se usa para leer los datos XML en el flujo.

## XmlReader::Create(const String\&, const SharedPtr\<XmlReaderSettings\>\&) método


Crea una nueva [XmlReader](../) instancia utilizando la URI y los ajustes especificados.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, const SharedPtr<XmlReaderSettings> &settings)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | La URI del archivo que contiene los datos XML. El objeto [XmlResolver](../../xmlresolver/) en el objeto [XmlReaderSettings](../../xmlreadersettings/) se usa para convertir la ruta a una representación de datos canónica. Si el valor de XmlReaderSettings::get_XmlResolver es **nullptr**, se usa un nuevo objeto [XmlUrlResolver](../../xmlurlresolver/). |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Los ajustes para la nueva instancia [XmlReader](../). Este valor puede ser **nullptr**. |

### Valor devuelto

Un objeto que se usa para leer los datos XML en el flujo.

## XmlReader::Create(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) método


Crea una nueva [XmlReader](../) instancia utilizando la URI, los ajustes y la información de contexto para el análisis.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | La URI del archivo que contiene los datos XML. El objeto [XmlResolver](../../xmlresolver/) en el objeto [XmlReaderSettings](../../xmlreadersettings/) se usa para convertir la ruta a una representación de datos canónica. Si el valor de XmlReaderSettings::get_XmlResolver es **nullptr**, se usa un nuevo objeto [XmlUrlResolver](../../xmlurlresolver/). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Los ajustes para la nueva instancia [XmlReader](../). Este valor puede ser **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | La información de contexto requerida para analizar el fragmento XML. La información de contexto puede incluir el [XmlNameTable](../../xmlnametable/) a usar, codificación, alcance de espacio de nombres, el ámbito actual **xml:lang** y **xml:space**, URI base y la definición de tipo de documento. Este valor puede ser **nullptr**. |

### Valor devuelto

Un objeto que se usa para leer los datos XML en el flujo.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&) método


Crea una nueva [XmlReader](../) instancia usando el flujo especificado con los ajustes predeterminados.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | El flujo que contiene los datos XML. El [XmlReader](../) escanea los primeros bytes del flujo en busca de una marca de orden de bytes u otro indicio de codificación. Cuando se determina la codificación, ésta se usa para continuar leyendo el flujo, y el procesamiento continúa analizando la entrada como un flujo de caracteres (Unicode). |

### Valor devuelto

Un objeto que se usa para leer los datos XML en el flujo.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) método


Crea una nueva [XmlReader](../) instancia con el flujo y los ajustes especificados.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlReaderSettings> &settings)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | El flujo que contiene los datos XML. El [XmlReader](../) escanea los primeros bytes del flujo en busca de una marca de orden de bytes u otro indicio de codificación. Cuando se determina la codificación, ésta se usa para continuar leyendo el flujo, y el procesamiento continúa analizando la entrada como un flujo de caracteres (Unicode). |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Los ajustes para la nueva instancia [XmlReader](../). Este valor puede ser **nullptr**. |

### Valor devuelto

Un objeto que se usa para leer los datos XML en el flujo.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) método


Crea una nueva [XmlReader](../) instancia usando el flujo especificado, la URI base y los ajustes.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | El flujo que contiene los datos XML. El [XmlReader](../) escanea los primeros bytes del flujo en busca de una marca de orden de bytes u otro indicio de codificación. Cuando se determina la codificación, ésta se usa para continuar leyendo el flujo, y el procesamiento continúa analizando la entrada como un flujo de caracteres (Unicode). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Los ajustes para la nueva instancia [XmlReader](../). Este valor puede ser **nullptr**. |
| baseUri | const [String](../../../system/string/)\& | La URI base para la entidad o documento que se está leyendo. Este valor puede ser **nullptr**. **[Security](../../../system.security/) Nota** La URI base se utiliza para resolver la URI relativa del documento XML. No utilice una URI base de una fuente no confiable. |

### Valor devuelto

Un objeto que se usa para leer los datos XML en el flujo.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) método


Crea una nueva [XmlReader](../) instancia usando el flujo, los ajustes y la información de contexto para el análisis.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | El flujo que contiene los datos XML. El [XmlReader](../) escanea los primeros bytes del flujo en busca de una marca de orden de bytes u otro indicio de codificación. Cuando se determina la codificación, ésta se usa para continuar leyendo el flujo, y el procesamiento continúa analizando la entrada como un flujo de caracteres (Unicode). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Los ajustes para la nueva instancia [XmlReader](../). Este valor puede ser **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | La información de contexto requerida para analizar el fragmento XML. La información de contexto puede incluir el [XmlNameTable](../../xmlnametable/) a usar, codificación, alcance de espacio de nombres, el ámbito actual **xml:lang** y **xml:space**, URI base y la definición de tipo de documento. Este valor puede ser **nullptr**. |

### Valor devuelto

Un objeto que se usa para leer los datos XML en el flujo.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&) método


Crea una nueva [XmlReader](../) instancia utilizando el lector de texto especificado.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | El lector de texto del cual leer los datos XML. Un lector de texto devuelve un flujo de caracteres Unicode, por lo que la codificación especificada en la declaración XML no es utilizada por el lector XML para decodificar el flujo de datos. |

### Valor devuelto

Un objeto que se usa para leer los datos XML en el flujo.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) método


Crea una nueva [XmlReader](../) instancia utilizando el lector de texto y los ajustes especificados.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlReaderSettings> &settings)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | El lector de texto del cual leer los datos XML. Un lector de texto devuelve un flujo de caracteres Unicode, por lo que la codificación especificada en la declaración XML no es utilizada por el lector XML para decodificar el flujo de datos. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Los ajustes para el nuevo [XmlReader](../). Este valor puede ser **nullptr**. |

### Valor devuelto

Un objeto que se usa para leer los datos XML en el flujo.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) método


Crea una nueva [XmlReader](../) instancia utilizando el lector de texto, los ajustes y la URI base.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | El lector de texto del cual leer los datos XML. Un lector de texto devuelve un flujo de caracteres Unicode, por lo que la codificación especificada en la declaración XML no es utilizada por el [XmlReader](../) para decodificar el flujo de datos. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Los ajustes para la nueva instancia [XmlReader](../). Este valor puede ser **nullptr**. |
| baseUri | const [String](../../../system/string/)\& | La URI base para la entidad o documento que se está leyendo. Este valor puede ser **nullptr**. **[Security](../../../system.security/) Nota** La URI base se utiliza para resolver la URI relativa del documento XML. No utilice una URI base de una fuente no confiable. |

### Valor devuelto

Un objeto que se usa para leer los datos XML en el flujo.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) método


Crea una nueva [XmlReader](../) instancia utilizando el lector de texto, los ajustes y la información de contexto para el análisis.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | El lector de texto del cual leer los datos XML. Un lector de texto devuelve un flujo de caracteres Unicode, por lo que la codificación especificada en la declaración XML no es utilizada por el lector XML para decodificar el flujo de datos. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Los ajustes para la nueva instancia [XmlReader](../). Este valor puede ser **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | La información de contexto requerida para analizar el fragmento XML. La información de contexto puede incluir el [XmlNameTable](../../xmlnametable/) a usar, codificación, alcance de espacio de nombres, el ámbito actual **xml:lang** y **xml:space**, URI base y la definición de tipo de documento. Este valor puede ser **nullptr**. |

### Valor devuelto

Un objeto que se usa para leer los datos XML en el flujo.

## XmlReader::Create(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) método


Crea una nueva [XmlReader](../) instancia utilizando el lector XML y los ajustes especificados.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<XmlReader> &reader, SharedPtr<XmlReaderSettings> settings)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../)\>\& | El objeto que desea usar como lector XML subyacente. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Los ajustes para la nueva instancia [XmlReader](../). El nivel de conformidad del objeto [XmlReaderSettings](../../xmlreadersettings/) debe coincidir con el nivel de conformidad del lector subyacente, o debe establecerse en [ConformanceLevel::Auto](../../conformancelevel/). |

### Valor devuelto

Un objeto que envuelve al objeto [XmlReader](../) especificado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [Stream](../../../system.io/stream/)
* Class [TextReader](../../../system.io/textreader/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)