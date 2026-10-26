---
title: Read()
second_title: Referencia de API de Aspose.Slides para C++
description: "Lee un esquema XML del IO::TextReader suministrado."
type: docs
weight: 365
url: /es/system.xml.schema/xmlschema/read/
---
## XmlSchema::Read(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) method

Lee un XML [Schema](../../) del [IO::TextReader](../../../system.io/textreader/) suministrado.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::TextReader> &reader, ValidationEventHandler validationEventHandler)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | El [IO::TextReader](../../../system.io/textreader/) que contiene el XML [Schema](../../) a leer. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | El controlador de eventos de validación que recibe información sobre los errores de sintaxis XML [Schema](../../). |

### Valor de retorno

El objeto [XmlSchema](../) que representa el XML [Schema](../../).

## XmlSchema::Read(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) method

Lee un XML [Schema](../../) del flujo suministrado.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::Stream> &stream, ValidationEventHandler validationEventHandler)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | El flujo de datos suministrado. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | El controlador de eventos de validación que recibe información sobre los errores de sintaxis XML [Schema](../../). |

### Valor de retorno

El objeto [XmlSchema](../) que representa el XML [Schema](../../).

## XmlSchema::Read(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) method

Lee un XML [Schema](../../) del [XmlReader](../../../system.xml/xmlreader/) suministrado.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<XmlReader> &reader, ValidationEventHandler validationEventHandler)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | El [XmlReader](../../../system.xml/xmlreader/) que contiene el XML [Schema](../../) a leer. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | El controlador de eventos de validación que recibe información sobre los errores de sintaxis XML [Schema](../../). |

### Valor de retorno

El objeto [XmlSchema](../) que representa el XML [Schema](../../).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Clase [XmlSchema](../)
* Clase [TextReader](../../../system.io/textreader/)
* Clase [Stream](../../../system.io/stream/)
* Clase [XmlReader](../../../system.xml/xmlreader/)
* Espacio de nombres [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)