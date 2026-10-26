---
title: Load()
second_title: Referencia de API de Aspose.Slides para C++
description: Carga el documento XML desde la URL especificada.
type: docs
weight: 508
url: /es/system.xml/xmldocument/load/
---
## XmlDocument::Load(String) método

Cargas el documento XML desde la URL especificada.

```cpp
virtual void System::Xml::XmlDocument::Load(String filename)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | [String](../../../system/string/) | URL del archivo que contiene el documento XML a cargar. La URL puede ser un archivo local o una URL HTTP (una dirección [Web](../../../system.web/)). |

## XmlDocument::Load(SharedPtr\<IO::Stream\>) método

Cargas el documento XML desde el flujo especificado.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::Stream> inStream)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | El flujo que contiene el documento XML a cargar. |

## XmlDocument::Load(SharedPtr\<IO::TextReader\>) método

Cargas el documento XML desde el TextReader especificado.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::TextReader> txtReader)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| txtReader | [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | El TextReader usado para suministrar los datos XML al documento. |

## XmlDocument::Load(SharedPtr\<XmlReader\>) método

Cargas el documento XML desde el [XmlReader](../../xmlreader/) especificado.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<XmlReader> reader)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | El [XmlReader](../../xmlreader/) usado para suministrar los datos XML al documento. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [XmlDocument](../)
* Clase [Stream](../../../system.io/stream/)
* Clase [TextReader](../../../system.io/textreader/)
* Clase [XmlReader](../../xmlreader/)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)