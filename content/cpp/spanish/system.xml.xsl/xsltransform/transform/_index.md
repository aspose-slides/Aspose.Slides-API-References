---
title: Transform()
second_title: Referencia de la API de Aspose.Slides para C++
description: Transforma los datos XML en el XPathNavigator usando los args especificados y envía el resultado a un XmlReader.
type: docs
weight: 40
url: /es/system.xml.xsl/xsltransform/transform/
---
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transforma los datos XML en el XPathNavigator usando los **args** especificados y envía el resultado a un [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un XPathNavigator que contiene los datos a transformar. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver la función **document()** de XSLT. Si es **nullptr**, la función **document()** no se resuelve. El [XmlResolver](../../../system.xml/xmlresolver/) no se almacena en caché después de que este método finaliza. |

### Valor devuelto

Un [XmlReader](../../../system.xml/xmlreader/) que contiene los resultados de la transformación.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) method

Transforma los datos XML en el XPathNavigator usando los **args** especificados y envía el resultado a un [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un XPathNavigator que contiene los datos a transformar. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |

### Valor devuelto

Un [XmlReader](../../../system.xml/xmlreader/) que contiene los resultados de la transformación.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transforma los datos XML en el XPathNavigator usando los **args** especificados y envía el resultado a un [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un XPathNavigator que contiene los datos a transformar. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | El [XmlWriter](../../../system.xml/xmlwriter/) al que desea enviar la salida. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver la función **document()** de XSLT. Si es **nullptr**, la función **document()** no se resuelve. El [XmlResolver](../../../system.xml/xmlresolver/) no se almacena en caché después de que este método finaliza. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

Transforma los datos XML en el XPathNavigator usando los **args** especificados y envía el resultado a un [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un XPathNavigator que contiene los datos a transformar. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | El [XmlWriter](../../../system.xml/xmlwriter/) al que desea enviar la salida. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transforma los datos XML en el XPathNavigator usando los **args** especificados y envía el resultado a un Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un XPathNavigator que contiene los datos a transformar. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | El stream al que desea enviar la salida. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver la función **document()** de XSLT. Si es **nullptr**, la función **document()** no se resuelve. El [XmlResolver](../../../system.xml/xmlresolver/) no se almacena en caché después de que este método finaliza. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

Transforma los datos XML en el XPathNavigator usando los **args** especificados y envía el resultado a un Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un XPathNavigator que contiene los datos a transformar. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | El stream al que desea enviar la salida. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transforma los datos XML en el XPathNavigator usando los **args** especificados y envía el resultado a un TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un XPathNavigator que contiene los datos a transformar. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | El TextWriter al que desea enviar la salida. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver la función **document()** de XSLT. Si es **nullptr**, la función **document()** no se resuelve. El [XmlResolver](../../../system.xml/xmlresolver/) no se almacena en caché después de que este método finaliza. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

Transforma los datos XML en el XPathNavigator usando los **args** especificados y envía el resultado a un TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un XPathNavigator que contiene los datos a transformar. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | El TextWriter al que desea enviar la salida. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transforma los datos XML en el IXPathNavigable usando los **args** especificados y envía el resultado a un [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser ya sea un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene los datos a transformar. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver la función **document()** de XSLT. Si es **nullptr**, la función **document()** no se resuelve. El [XmlResolver](../../../system.xml/xmlresolver/) no se almacena en caché después de que este método finaliza. |

### Valor devuelto

Un [XmlReader](../../../system.xml/xmlreader/) que contiene los resultados de la transformación.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) method

Transforma los datos XML en el IXPathNavigable usando los **args** especificados y envía el resultado a un [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser ya sea un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene los datos a transformar. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |

### Valor devuelto

Un [XmlReader](../../../system.xml/xmlreader/) que contiene los resultados de la transformación.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transforma los datos XML en el IXPathNavigable usando los **args** especificados y envía el resultado a un TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser ya sea un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene los datos a transformar. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | El TextWriter al que desea enviar la salida. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver la función **document()** de XSLT. Si es **nullptr**, la función **document()** no se resuelve. El [XmlResolver](../../../system.xml/xmlresolver/) no se almacena en caché después de que este método finaliza. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

Transforma los datos XML en el IXPathNavigable usando los **args** especificados y envía el resultado a un TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser ya sea un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene los datos a transformar. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | El TextWriter al que desea enviar la salida. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transforma los datos XML en el IXPathNavigable usando los **args** especificados y envía el resultado a un Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser ya sea un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene los datos a transformar. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | El stream al que desea enviar la salida. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver la función **document()** de XSLT. Si es **nullptr**, la función **document()** no se resuelve. El [XmlResolver](../../../system.xml/xmlresolver/) no se almacena en caché después de que el método [XslTransform::Transform](./) finaliza. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

Transforma los datos XML en el IXPathNavigable usando los **args** especificados y envía el resultado a un Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser ya sea un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene los datos a transformar. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | El stream al que desea enviar la salida. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transforma los datos XML en el IXPathNavigable usando los **args** especificados y envía el resultado a un [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser ya sea un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene los datos a transformar. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | El [XmlWriter](../../../system.xml/xmlwriter/) al que desea enviar la salida. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver la función **document()** de XSLT. Si es **nullptr**, la función **document()** no se resuelve. El [XmlResolver](../../../system.xml/xmlresolver/) no se almacena en caché después de que este método finaliza. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

Transforma los datos XML en el IXPathNavigable usando los **args** especificados y envía el resultado a un [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser ya sea un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene los datos a transformar. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | El [XmlWriter](../../../system.xml/xmlwriter/) al que desea enviar la salida. |

## XslTransform::Transform(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transforma los datos XML en el archivo de entrada y envía el resultado a un archivo de salida.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | La URL del documento fuente a transformar. |
| outputfile | const [String](../../../system/string/)\& | La URL del archivo de salida. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver la función **document()** de XSLT. Si es **nullptr**, la función **document()** no se resuelve. El [XmlResolver](../../../system.xml/xmlresolver/) no se almacena en caché después de que el método [XslTransform::Transform](./) finaliza. |

## XslTransform::Transform(const String\&, const String\&) method

Transforma los datos XML en el archivo de entrada y envía el resultado a un archivo de salida.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | La URL del documento fuente a transformar. |
| outputfile | const [String](../../../system/string/)\& | La URL del archivo de salida. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlReader](../../../system.xml/xmlreader/)
* Clase [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Clase [XsltArgumentList](../../xsltargumentlist/)
* Clase [XmlResolver](../../../system.xml/xmlresolver/)
* Clase [XslTransform](../)
* Clase [XmlWriter](../../../system.xml/xmlwriter/)
* Clase [Stream](../../../system.io/stream/)
* Clase [TextWriter](../../../system.io/textwriter/)
* Clase [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Xml::Xsl](../../)
* Biblioteca [Aspose.Slides](../../../)