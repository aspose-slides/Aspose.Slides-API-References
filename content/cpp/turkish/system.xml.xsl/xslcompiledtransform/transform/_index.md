---
title: Transform()
second_title: Aspose.Slides for C++ API Referansı
description: IXPathNavigable nesnesi tarafından belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir XmlWriter'a yazar.
type: docs
weight: 40
url: /tr/system.xml.xsl/xslcompiledtransform/transform/
---
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) method

IXPathNavigable nesnesi tarafından belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir [XmlWriter](../../../system.xml/xmlwriter/)'e yazar.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XmlWriter> &results)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable arayüzünü uygulayan bir nesne. [XmlNode](../../../system.xml/xmlnode/) (genellikle [XmlDocument](../../../system.xml/xmldocument/)) veya dönüştürülecek verileri içeren bir XPathDocument olabilir. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/)'a çıktı vermek istediğiniz yer. Stil sayfası bir **xsl:output** öğesi içeriyorsa, [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) değerinden dönen [XmlWriterSettings](../../../system.xml/xmlwritersettings/) nesnesini kullanarak [XmlWriter](../../../system.xml/xmlwriter/) oluşturmalısınız. Bu, [XmlWriter](../../../system.xml/xmlwriter/)'nin doğru çıktı ayarlarına sahip olmasını sağlar. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

IXPathNavigable nesnesi tarafından belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir [XmlWriter](../../../system.xml/xmlwriter/)'e yazar. [XsltArgumentList](../../xsltargumentlist/) ek çalışma zamanı argümanları sağlar.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable arayüzünü uygulayan bir nesne. [XmlNode](../../../system.xml/xmlnode/) (genellikle [XmlDocument](../../../system.xml/xmldocument/)) veya dönüştürülecek verileri içeren bir XPathDocument olabilir. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Dönüşüm için giriş olarak kullanılan, ad alanı nitelikli argümanları içeren bir [XsltArgumentList](../../xsltargumentlist/). Bu değer **nullptr** olabilir. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/)'a çıktı vermek istediğiniz yer. Stil sayfası bir **xsl:output** öğesi içeriyorsa, [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) değerinden dönen [XmlWriterSettings](../../../system.xml/xmlwritersettings/) nesnesini kullanarak [XmlWriter](../../../system.xml/xmlwriter/) oluşturmalısınız. Bu, [XmlWriter](../../../system.xml/xmlwriter/)'nin doğru çıktı ayarlarına sahip olmasını sağlar. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

IXPathNavigable nesnesi tarafından belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir TextWriter'a yazar. [XsltArgumentList](../../xsltargumentlist/) ek çalışma zamanı argümanları sağlar.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable arayüzünü uygulayan bir nesne. [XmlNode](../../../system.xml/xmlnode/) (genellikle [XmlDocument](../../../system.xml/xmldocument/)) veya dönüştürülecek verileri içeren bir XPathDocument olabilir. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Dönüşüm için giriş olarak kullanılan, ad alanı nitelikli argümanları içeren bir [XsltArgumentList](../../xsltargumentlist/). Bu değer **nullptr** olabilir. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Çıktıyı vermek istediğiniz TextWriter. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

IXPathNavigable nesnesi tarafından belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir akışa yazar. [XsltArgumentList](../../xsltargumentlist/) ek çalışma zamanı argümanları sağlar.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable arayüzünü uygulayan bir nesne. [XmlNode](../../../system.xml/xmlnode/) (genellikle [XmlDocument](../../../system.xml/xmldocument/)) veya dönüştürülecek verileri içeren bir XPathDocument olabilir. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Dönüşüm için giriş olarak kullanılan, ad alanı nitelikli argümanları içeren bir [XsltArgumentList](../../xsltargumentlist/). Bu değer **nullptr** olabilir. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Çıktıyı vermek istediğiniz akış. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) method

[XmlReader](../../../system.xml/xmlreader/) nesnesi tarafından belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir [XmlWriter](../../../system.xml/xmlwriter/)'e yazar.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XmlWriter> &results)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Giriş belgesini içeren [XmlReader](../../../system.xml/xmlreader/). |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/)'a çıktı vermek istediğiniz yer. Stil sayfası bir **xsl:output** öğesi içeriyorsa, [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) değerinden dönen [XmlWriterSettings](../../../system.xml/xmlwritersettings/) nesnesini kullanarak [XmlWriter](../../../system.xml/xmlwriter/) oluşturmalısınız. Bu, [XmlWriter](../../../system.xml/xmlwriter/)'nin doğru çıktı ayarlarına sahip olmasını sağlar. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

[XmlReader](../../../system.xml/xmlreader/) nesnesi tarafından belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir [XmlWriter](../../../system.xml/xmlwriter/)'e yazar. [XsltArgumentList](../../xsltargumentlist/) ek çalışma zamanı argümanları sağlar.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Giriş belgesini içeren bir [XmlReader](../../../system.xml/xmlreader/). |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Dönüşüm için giriş olarak kullanılan, ad alanı nitelikli argümanları içeren bir [XsltArgumentList](../../xsltargumentlist/). Bu değer **nullptr** olabilir. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/)'a çıktı vermek istediğiniz yer. Stil sayfası bir **xsl:output** öğesi içeriyorsa, [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) değerinden dönen [XmlWriterSettings](../../../system.xml/xmlwritersettings/) nesnesini kullanarak [XmlWriter](../../../system.xml/xmlwriter/) oluşturmalısınız. Bu, [XmlWriter](../../../system.xml/xmlwriter/)'nin doğru çıktı ayarlarına sahip olmasını sağlar. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

[XmlReader](../../../system.xml/xmlreader/) nesnesi tarafından belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir TextWriter'a yazar. [XsltArgumentList](../../xsltargumentlist/) ek çalışma zamanı argümanları sağlar.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Giriş belgesini içeren bir [XmlReader](../../../system.xml/xmlreader/). |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Dönüşüm için giriş olarak kullanılan, ad alanı nitelikli argümanları içeren bir [XsltArgumentList](../../xsltargumentlist/). Bu değer **nullptr** olabilir. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Çıktıyı vermek istediğiniz TextWriter. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

[XmlReader](../../../system.xml/xmlreader/) nesnesi tarafından belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir akışa yazar. [XsltArgumentList](../../xsltargumentlist/) ek çalışma zamanı argümanları sağlar.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Giriş belgesini içeren bir [XmlReader](../../../system.xml/xmlreader/). |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Dönüşüm için giriş olarak kullanılan, ad alanı nitelikli argümanları içeren bir [XsltArgumentList](../../xsltargumentlist/). Bu değer **nullptr** olabilir. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Çıktıyı vermek istediğiniz akış. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XmlWriter\>\&) method

URI tarafından belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir [XmlWriter](../../../system.xml/xmlwriter/)'e yazar.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XmlWriter> &results)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Giriş belgesinin URI'si. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/)'a çıktı vermek istediğiniz yer. Stil sayfası bir **xsl:output** öğesi içeriyorsa, [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) değerinden dönen [XmlWriterSettings](../../../system.xml/xmlwritersettings/) nesnesini kullanarak [XmlWriter](../../../system.xml/xmlwriter/) oluşturmalısınız. Bu, [XmlWriter](../../../system.xml/xmlwriter/)'nin doğru çıktı ayarlarına sahip olmasını sağlar. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

URI tarafından belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir [XmlWriter](../../../system.xml/xmlwriter/)'e yazar. [XsltArgumentList](../../xsltargumentlist/) ek çalışma zamanı argümanları sağlar.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Giriş belgesinin URI'si. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Dönüşüm için giriş olarak kullanılan, ad alanı nitelikli argümanları içeren bir [XsltArgumentList](../../xsltargumentlist/). Bu değer **nullptr** olabilir. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/)'a çıktı vermek istediğiniz yer. Stil sayfası bir **xsl:output** öğesi içeriyorsa, [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) değerinden dönen [XmlWriterSettings](../../../system.xml/xmlwritersettings/) nesnesini kullanarak [XmlWriter](../../../system.xml/xmlwriter/) oluşturmalısınız. Bu, [XmlWriter](../../../system.xml/xmlwriter/)'nin doğru çıktı ayarlarına sahip olmasını sağlar. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

URI tarafından belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir TextWriter'a yazar.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Giriş belgesinin URI'si. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Dönüşüm için giriş olarak kullanılan, ad alanı nitelikli argümanları içeren bir [XsltArgumentList](../../xsltargumentlist/). Bu değer **nullptr** olabilir. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Çıktıyı vermek istediğiniz TextWriter. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

URI tarafından belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir akışa yazar. [XsltArgumentList](../../xsltargumentlist/) ek çalışma zamanı argümanları sağlar.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Giriş belgesinin URI'si. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Dönüşüm için giriş olarak kullanılan, ad alanı nitelikli argümanları içeren bir [XsltArgumentList](../../xsltargumentlist/). Bu değer **nullptr** olabilir. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Çıktıyı vermek istediğiniz akış. |

## XslCompiledTransform::Transform(const String\&, const String\&) method

URI tarafından belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir dosyaya yazar.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const String &resultsFile)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Giriş belgesinin URI'si. |
| resultsFile | const [String](../../../system/string/)\& | Çıktı dosyasının URI'si. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) method

[XmlReader](../../../system.xml/xmlreader/) nesnesi tarafından belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir [XmlWriter](../../../system.xml/xmlwriter/)'e yazar. [XsltArgumentList](../../xsltargumentlist/) ek çalışma zamanı argümanları sağlar ve [XmlResolver](../../../system.xml/xmlresolver/) XSLT **document()** işlevini çözer.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Giriş belgesini içeren bir [XmlReader](../../../system.xml/xmlreader/). |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Dönüşüm için giriş olarak kullanılan, ad alanı nitelikli argümanları içeren bir [XsltArgumentList](../../xsltargumentlist/). Bu değer **nullptr** olabilir. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/)'a çıktı vermek istediğiniz yer. Stil sayfası bir **xsl:output** öğesi içeriyorsa, [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) değerinden dönen [XmlWriterSettings](../../../system.xml/xmlwritersettings/) nesnesini kullanarak [XmlWriter](../../../system.xml/xmlwriter/) oluşturmalısınız. Bu, [XmlWriter](../../../system.xml/xmlwriter/)'nin doğru çıktı ayarlarına sahip olmasını sağlar. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **document()** işlevini çözmek için kullanılan [XmlResolver](../../../system.xml/xmlresolver/). Bu **nullptr** ise, **document()** işlevi çözülmez. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) method

IXPathNavigable nesnesi tarafından belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir [XmlWriter](../../../system.xml/xmlwriter/)'e yazar. [XsltArgumentList](../../xsltargumentlist/) ek çalışma zamanı argümanları sağlar ve [XmlResolver](../../../system.xml/xmlresolver/) XSLT **document()** işlevini çözer.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable nesnesi tarafından belirtilen dönüştürülecek belge. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) olarak argüman listesi. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/)'a çıktı vermek istediğiniz yer. Stil sayfası bir **xsl:output** öğesi içeriyorsa, [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) değerinden dönen [XmlWriterSettings](../../../system.xml/xmlwritersettings/) nesnesini kullanarak [XmlWriter](../../../system.xml/xmlwriter/) oluşturmalısınız. Bu, [XmlWriter](../../../system.xml/xmlwriter/)'nin doğru çıktı ayarlarına sahip olmasını sağlar. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **document()** işlevini çözmek için kullanılan [XmlResolver](../../../system.xml/xmlresolver/). Bu **nullptr** ise, **document()** işlevi çözülmez. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslCompiledTransform](../)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [String](../../../system/string/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)