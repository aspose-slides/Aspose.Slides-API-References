---
title: Transform()
second_title: Referencia de API de Aspose.Slides para C++
description: Ejecuta la transformación usando el documento de entrada especificado por el objeto IXPathNavigable y escribe los resultados en un XmlWriter.
type: docs
weight: 40
url: /es/system.xml.xsl/xslcompiledtransform/transform/
---
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) método


Ejecuta la transformación usando el documento de entrada especificado por el objeto IXPathNavigable y escribe los resultados en [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XmlWriter> &results)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser un [XmlNode](../../../system.xml/xmlnode/) (típicamente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene los datos a transformar. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | El [XmlWriter](../../../system.xml/xmlwriter/) al que desea escribir. Si la hoja de estilo contiene un elemento **xsl:output**, debe crear el [XmlWriter](../../../system.xml/xmlwriter/) usando el objeto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) devuelto por el valor [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Esto garantiza que el [XmlWriter](../../../system.xml/xmlwriter/) tenga la configuración de salida correcta. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) método


Ejecuta la transformación usando el documento de entrada especificado por el objeto IXPathNavigable y escribe los resultados en [XmlWriter](../../../system.xml/xmlwriter/). El [XsltArgumentList](../../xsltargumentlist/) proporciona argumentos adicionales en tiempo de ejecución.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser un [XmlNode](../../../system.xml/xmlnode/) (típicamente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene los datos a transformar. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. Este valor puede ser **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | El [XmlWriter](../../../system.xml/xmlwriter/) al que desea escribir. Si la hoja de estilo contiene un elemento **xsl:output**, debe crear el [XmlWriter](../../../system.xml/xmlwriter/) usando el objeto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) devuelto por el valor [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Esto garantiza que el [XmlWriter](../../../system.xml/xmlwriter/) tenga la configuración de salida correcta. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) método


Ejecuta la transformación usando el documento de entrada especificado por el objeto IXPathNavigable y escribe los resultados en un TextWriter. El [XsltArgumentList](../../xsltargumentlist/) proporciona argumentos adicionales en tiempo de ejecución.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser un [XmlNode](../../../system.xml/xmlnode/) (típicamente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene los datos a transformar. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. Este valor puede ser **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | El TextWriter al que desea escribir. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) método


Ejecuta la transformación usando el documento de entrada especificado por el objeto IXPathNavigable y escribe los resultados en un flujo. El [XsltArgumentList](../../xsltargumentlist/) proporciona argumentos adicionales en tiempo de ejecución.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser un [XmlNode](../../../system.xml/xmlnode/) (típicamente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene los datos a transformar. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. Este valor puede ser **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | El flujo al que desea escribir. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) método


Ejecuta la transformación usando el documento de entrada especificado por el objeto [XmlReader](../../../system.xml/xmlreader/) y escribe los resultados en [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XmlWriter> &results)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | El [XmlReader](../../../system.xml/xmlreader/) que contiene el documento de entrada. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | El [XmlWriter](../../../system.xml/xmlwriter/) al que desea escribir. Si la hoja de estilo contiene un elemento **xsl:output**, debe crear el [XmlWriter](../../../system.xml/xmlwriter/) usando el objeto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) devuelto por el valor [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Esto garantiza que el [XmlWriter](../../../system.xml/xmlwriter/) tenga la configuración de salida correcta. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) método


Ejecuta la transformación usando el documento de entrada especificado por el objeto [XmlReader](../../../system.xml/xmlreader/) y escribe los resultados en [XmlWriter](../../../system.xml/xmlwriter/). El [XsltArgumentList](../../xsltargumentlist/) proporciona argumentos adicionales en tiempo de ejecución.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Un [XmlReader](../../../system.xml/xmlreader/) que contiene el documento de entrada. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. Este valor puede ser **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | El [XmlWriter](../../../system.xml/xmlwriter/) al que desea escribir. Si la hoja de estilo contiene un elemento **xsl:output**, debe crear el [XmlWriter](../../../system.xml/xmlwriter/) usando el objeto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) devuelto por el valor [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Esto garantiza que el [XmlWriter](../../../system.xml/xmlwriter/) tenga la configuración de salida correcta. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) método


Ejecuta la transformación usando el documento de entrada especificado por el objeto [XmlReader](../../../system.xml/xmlreader/) y escribe los resultados en un TextWriter. El [XsltArgumentList](../../xsltargumentlist/) proporciona argumentos adicionales en tiempo de ejecución.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Un [XmlReader](../../../system.xml/xmlreader/) que contiene el documento de entrada. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. Este valor puede ser **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | El TextWriter al que desea escribir. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) método


Ejecuta la transformación usando el documento de entrada especificado por el objeto [XmlReader](../../../system.xml/xmlreader/) y escribe los resultados en un flujo. El [XsltArgumentList](../../xsltargumentlist/) proporciona argumentos adicionales en tiempo de ejecución.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Un [XmlReader](../../../system.xml/xmlreader/) que contiene el documento de entrada. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. Este valor puede ser **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | El flujo al que desea escribir. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XmlWriter\>\&) método


Ejecuta la transformación usando el documento de entrada especificado por el URI y escribe los resultados en [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XmlWriter> &results)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | El URI del documento de entrada. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | El [XmlWriter](../../../system.xml/xmlwriter/) al que desea escribir. Si la hoja de estilo contiene un elemento **xsl:output**, debe crear el [XmlWriter](../../../system.xml/xmlwriter/) usando el objeto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) devuelto por el valor [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Esto garantiza que el [XmlWriter](../../../system.xml/xmlwriter/) tenga la configuración de salida correcta. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) método


Ejecuta la transformación usando el documento de entrada especificado por el URI y escribe los resultados en [XmlWriter](../../../system.xml/xmlwriter/). El [XsltArgumentList](../../xsltargumentlist/) proporciona argumentos adicionales en tiempo de ejecución.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | El URI del documento de entrada. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. Este valor puede ser **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | El [XmlWriter](../../../system.xml/xmlwriter/) al que desea escribir. Si la hoja de estilo contiene un elemento **xsl:output**, debe crear el [XmlWriter](../../../system.xml/xmlwriter/) usando el objeto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) devuelto por el valor [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Esto garantiza que el [XmlWriter](../../../system.xml/xmlwriter/) tenga la configuración de salida correcta. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) método


Ejecuta la transformación usando el documento de entrada especificado por el URI y escribe los resultados en un TextWriter.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | El URI del documento de entrada. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. Este valor puede ser **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | El TextWriter al que desea escribir. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) método


Ejecuta la transformación usando el documento de entrada especificado por el URI y escribe los resultados en un flujo. El [XsltArgumentList](../../xsltargumentlist/) proporciona argumentos adicionales en tiempo de ejecución.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | El URI del documento de entrada. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. Este valor puede ser **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | El flujo al que desea escribir. |

## XslCompiledTransform::Transform(const String\&, const String\&) método


Ejecuta la transformación usando el documento de entrada especificado por el URI y escribe los resultados en un archivo.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const String &resultsFile)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | El URI del documento de entrada. |
| resultsFile | const [String](../../../system/string/)\& | El URI del archivo de salida. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) método


Ejecuta la transformación usando el documento de entrada especificado por el objeto [XmlReader](../../../system.xml/xmlreader/) y escribe los resultados en [XmlWriter](../../../system.xml/xmlwriter/). El [XsltArgumentList](../../xsltargumentlist/) proporciona argumentos adicionales en tiempo de ejecución y el [XmlResolver](../../../system.xml/xmlresolver/) resuelve la función XSLT **document()**.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Un [XmlReader](../../../system.xml/xmlreader/) que contiene el documento de entrada. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) que contiene los argumentos calificados por espacio de nombres usados como entrada para la transformación. Este valor puede ser **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | El [XmlWriter](../../../system.xml/xmlwriter/) al que desea escribir. Si la hoja de estilo contiene un elemento **xsl:output**, debe crear el [XmlWriter](../../../system.xml/xmlwriter/) usando el objeto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) devuelto por el valor [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Esto garantiza que el [XmlWriter](../../../system.xml/xmlwriter/) tenga la configuración de salida correcta. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver la función XSLT **document()**. Si esto es **nullptr**, la función **document()** no se resuelve. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) método


Ejecuta la transformación usando el documento de entrada especificado por el objeto IXPathNavigable y escribe los resultados en [XmlWriter](../../../system.xml/xmlwriter/). El [XsltArgumentList](../../xsltargumentlist/) proporciona argumentos adicionales en tiempo de ejecución y el [XmlResolver](../../../system.xml/xmlresolver/) resuelve la función XSLT **document()**.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | El documento a transformar que está especificado por el objeto IXPathNavigable. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Lista de argumentos como [XsltArgumentList](../../xsltargumentlist/). |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | El [XmlWriter](../../../system.xml/xmlwriter/) al que desea escribir. Si la hoja de estilo contiene un elemento **xsl:output**, debe crear el [XmlWriter](../../../system.xml/xmlwriter/) usando el objeto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) que se devuelve del valor [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Esto garantiza que el [XmlWriter](../../../system.xml/xmlwriter/) tenga la configuración de salida correcta. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver la función XSLT **document()**. Si esto es **nullptr**, la función **document()** no se resuelve. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Clase [XmlWriter](../../../system.xml/xmlwriter/)
* Clase [XslCompiledTransform](../)
* Clase [XsltArgumentList](../../xsltargumentlist/)
* Clase [TextWriter](../../../system.io/textwriter/)
* Clase [Stream](../../../system.io/stream/)
* Clase [XmlReader](../../../system.xml/xmlreader/)
* Clase [String](../../../system/string/)
* Clase [XmlResolver](../../../system.xml/xmlresolver/)
* Espacio de nombres [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)