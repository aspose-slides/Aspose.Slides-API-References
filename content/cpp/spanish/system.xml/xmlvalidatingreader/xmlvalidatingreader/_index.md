---
title: XmlValidatingReader()
second_title: Referencia de API de Aspose.Slides para C++
description: Inicializa una nueva instancia de la clase XmlValidatingReader que valida el contenido devuelto del XmlReader proporcionado.
type: docs
weight: 430
url: /es/system.xml/xmlvalidatingreader/xmlvalidatingreader/
---
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<XmlReader\>\&) constructor

Inicializa una nueva instancia de la clase [XmlValidatingReader](../) que valida el contenido devuelto por el [XmlReader](../../xmlreader/) proporcionado.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<XmlReader> &reader)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\>\& | El [XmlReader](../../xmlreader/) desde el cual leer durante la validación. La implementación actual solo admite [XmlTextReader](../../xmltextreader/). |

## XmlValidatingReader::XmlValidatingReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

Inicializa una nueva instancia de la clase [XmlValidatingReader](../) con los valores especificados.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | La cadena que contiene el fragmento XML a analizar. |
| fragType | [XmlNodeType](../../xmlnodetype/) | El XmlNodeType del fragmento XML. Esto también determina lo que la cadena del fragmento puede contener (ver tabla a continuación). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | El [XmlParserContext](../../xmlparsercontext/) en el que se analizará el fragmento XML. Incluye el [NameTable](../../nametable/) a usar, la codificación, el alcance del espacio de nombres, el **xml:lang** actual y el alcance **xml:space**. |

## Observaciones

La tabla siguiente enumera los valores válidos para **fragType** y cómo el lector analiza cada uno de los diferentes tipos de nodo. 

| XmlNodeType | El fragmento puede contener |
| --- | --- |
| Element| Cualquier contenido de elemento válido (por ejemplo, cualquier combinación de elementos, comentarios, instrucciones de procesamiento, cdata, texto y referencias de entidad). |
| [Attribute](../../../system/attribute/)| El valor de un atributo (la parte dentro de comillas). |
| Document| El contenido de un documento XML completo; esto impone reglas a nivel de documento. |

## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

Inicializa una nueva instancia de la clase [XmlValidatingReader](../) con los valores especificados.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | El flujo que contiene el fragmento XML a analizar. |
| fragType | [XmlNodeType](../../xmlnodetype/) | El XmlNodeType del fragmento XML. Esto determina lo que el fragmento puede contener (ver tabla a continuación). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | El [XmlParserContext](../../xmlparsercontext/) en el que se analizará el fragmento XML. Incluye el [XmlNameTable](../../xmlnametable/) a usar, la codificación, el alcance del espacio de nombres, el **xml:lang** actual y el alcance **xml:space**. |

## Observaciones

La tabla siguiente enumera los valores válidos para **fragType** y cómo el lector analiza cada uno de los diferentes tipos de nodo. 

| XmlNodeType | El fragmento puede contener |
| --- | --- |
| Element| Cualquier contenido de elemento válido (por ejemplo, cualquier combinación de elementos, comentarios, instrucciones de procesamiento, cdata, texto y referencias de entidad). |
| [Attribute](../../../system/attribute/)| El valor de un atributo (la parte dentro de comillas). |
| Document| El contenido de un documento XML completo; esto impone reglas a nivel de documento. |

## Véase también

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlReader](../../xmlreader/)
* Clase [XmlValidatingReader](../)
* Clase [String](../../../system/string/)
* Clase [XmlParserContext](../../xmlparsercontext/)
* Clase [Stream](../../../system.io/stream/)
* Espacio de nombres [System::Xml](../../)
* Library [Aspose.Slides](../../../)