---
title: XmlTextWriter()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una instancia de la clase XmlTextWriter usando el flujo y la codificación especificados.
type: docs
weight: 183
url: /es/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) constructor


Crea una instancia de la clase [XmlTextWriter](../) utilizando el flujo y la codificación especificados.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | El flujo al que desea escribir. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | La codificación a generar. Si la codificación es **nullptr** escribe el flujo como UTF-8 y omite el atributo de codificación del **ProcessingInstruction**. |

## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) constructor


Crea una instancia de la clase [XmlTextWriter](../) utilizando el archivo especificado.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | El nombre del archivo al que escribir. Si el archivo existe, lo trunca y sobrescribe con el nuevo contenido. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | La codificación a generar. Si la codificación es **nullptr** escribe el archivo como UTF-8 y omite el atributo de codificación del **ProcessingInstruction**. |

## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) constructor


Crea una instancia de la clase [XmlTextWriter](../) utilizando el TextWriter especificado.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | El TextWriter al que escribir. Se asume que el TextWriter ya está configurado con la codificación correcta. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Stream](../../../system.io/stream/)
* Clase [Encoding](../../../system.text/encoding/)
* Clase [XmlTextWriter](../)
* Clase [String](../../../system/string/)
* Clase [TextWriter](../../../system.io/textwriter/)
* Espacio de nombres [System::Xml](../../)
* Library [Aspose.Slides](../../../)