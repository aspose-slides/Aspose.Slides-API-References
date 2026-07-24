---
title: Transform()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen args kullanarak XPathNavigator'daki XML verilerini dönüştürür ve sonucu bir XmlReader'a yazar.
type: docs
weight: 40
url: /tr/system.xml.xsl/xsltransform/transform/
---
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

XPathNavigator'daki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir [XmlReader](../../../system.xml/xmlreader/)'e yazar.

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Dönüştürülecek verileri içeren bir XPathNavigator. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Dönüşüm için girdi olarak kullanılan ad alanı nitelikli argümanları içeren bir [XsltArgumentList](../../xsltargumentlist/). |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **document()** işlevini çözmek için kullanılan [XmlResolver](../../../system.xml/xmlresolver/). Bu **nullptr** ise, **document()** işlevi çözülmez. [XmlResolver](../../../system.xml/xmlresolver/) bu yöntem tamamlandıktan sonra önbelleğe alınmaz. |

### Dönüş Değeri

Dönüşüm sonuçlarını içeren bir [XmlReader](../../../system.xml/xmlreader/).

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) method

XPathNavigator'daki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir [XmlReader](../../../system.xml/xmlreader/)'e yazar.

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Dönüştürülecek verileri içeren bir XPathNavigator. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Dönüşüm için girdi olarak kullanılan ad alanı nitelikli argümanları içeren bir [XsltArgumentList](../../xsltargumentlist/). |

### Dönüş Değeri

Dönüşüm sonuçlarını içeren bir [XmlReader](../../../system.xml/xmlreader/).

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

XPathNavigator'daki XML verilerini belirtilen args kullanarak dönüştürür ve sonucu bir [XmlWriter](../../../system.xml/xmlwriter/)'ye yazar.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Dönüştürülecek verileri içeren bir XPathNavigator. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Dönüşüm için girdi olarak kullanılan ad alanı nitelikli argümanları içeren bir [XsltArgumentList](../../xsltargumentlist/). |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Yazmak istediğiniz [XmlWriter](../../../system.xml/xmlwriter/). |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **document()** işlevini çözmek için kullanılan [XmlResolver](../../../system.xml/xmlresolver/). Bu **nullptr** ise, **document()** işlevi çözülmez. [XmlResolver](../../../system.xml/xmlresolver/) bu yöntem tamamlandıktan sonra önbelleğe alınmaz. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

XPathNavigator'daki XML verilerini belirtilen args kullanarak dönüştürür ve sonucu bir [XmlWriter](../../../system.xml/xmlwriter/)'e yazar.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Dönüştürülecek verileri içeren bir XPathNavigator. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Dönüşüm için girdi olarak kullanılan ad alanı nitelikli argümanları içeren bir [XsltArgumentList](../../xsltargumentlist/). |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Yazmak istediğiniz [XmlWriter](../../../system.xml/xmlwriter/). |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

XPathNavigator'daki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir Akışa yazar.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Dönüştürülecek verileri içeren bir XPathNavigator. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Dönüşüm için girdi olarak kullanılan ad alanı nitelikli argümanları içeren bir [XsltArgumentList](../../xsltargumentlist/). |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Yazmak istediğiniz akış. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **document()** işlevini çözmek için kullanılan [XmlResolver](../../../system.xml/xmlresolver/). Bu **nullptr** ise, **document()** işlevi çözülmez. [XmlResolver](../../../system.xml/xmlresolver/) bu yöntem tamamlandıktan sonra önbelleğe alınmaz. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

XPathNavigator'daki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir Akışa yazar.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Dönüştürülecek verileri içeren bir XPathNavigator. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Dönüşüm için girdi olarak kullanılan ad alanı nitelikli argümanları içeren bir [XsltArgumentList](../../xsltargumentlist/). |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Yazmak istediğiniz akış. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

XPathNavigator'daki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir TextWriter'a yazar.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Dönüştürülecek verileri içeren bir XPathNavigator. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Dönüşüm için girdi olarak kullanılan ad alanı nitelikli argümanları içeren bir [XsltArgumentList](../../xsltargumentlist/). |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Yazmak istediğiniz TextWriter. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **document()** işlevini çözmek için kullanılan [XmlResolver](../../../system.xml/xmlresolver/). Bu **nullptr** ise, **document()** işlevi çözülmez. [XmlResolver](../../../system.xml/xmlresolver/) bu yöntem tamamlandıktan sonra önbelleğe alınmaz. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

XPathNavigator'daki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir TextWriter'a yazar.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Dönüştürülecek verileri içeren bir XPathNavigator. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Dönüşüm için girdi olarak kullanılan ad alanı nitelikli argümanları içeren bir [XsltArgumentList](../../xsltargumentlist/). |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Yazmak istediğiniz TextWriter. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

IXPathNavigable'daki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir [XmlReader](../../../system.xml/xmlreader/)'e yazar.

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable arayüzünü uygulayan bir nesne. Bu, bir [XmlNode](../../../system.xml/xmlnode/) (genellikle bir [XmlDocument](../../../system.xml/xmldocument/)) ya da verileri içeren bir XPathDocument olabilir. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Dönüşüm için girdi olarak kullanılan ad alanı nitelikli argümanları içeren bir [XsltArgumentList](../../xsltargumentlist/). |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **document()** işlevini çözmek için kullanılan [XmlResolver](../../../system.xml/xmlresolver/). Bu **nullptr** ise, **document()** işlevi çözülmez. [XmlResolver](../../../system.xml/xmlresolver/) bu yöntem tamamlandıktan sonra önbelleğe alınmaz. |

### Dönüş Değeri

Dönüşüm sonuçlarını içeren bir [XmlReader](../../../system.xml/xmlreader/).

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) method

IXPathNavigable'daki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir [XmlReader](../../../system.xml/xmlreader/)'e yazar.

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable arayüzünü uygulayan bir nesne. Bu, bir [XmlNode](../../../system.xml/xmlnode/) (genellikle bir [XmlDocument](../../../system.xml/xmldocument/)) ya da verileri içeren bir XPathDocument olabilir. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Dönüşüm için girdi olarak kullanılan ad alanı nitelikli argümanları içeren bir [XsltArgumentList](../../xsltargumentlist/). |

### Dönüş Değeri

Dönüşüm sonuçlarını içeren bir [XmlReader](../../../system.xml/xmlreader/).

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

IXPathNavigable'daki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir TextWriter'a yazar.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable arayüzünü uygulayan bir nesne. Bu, bir [XmlNode](../../../system.xml/xmlnode/) (genellikle bir [XmlDocument](../../../system.xml/xmldocument/)) ya da verileri içeren bir XPathDocument olabilir. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Dönüşüm için girdi olarak kullanılan ad alanı nitelikli argümanları içeren bir [XsltArgumentList](../../xsltargumentlist/). |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Yazmak istediğiniz TextWriter. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **document()** işlevini çözmek için kullanılan [XmlResolver](../../../system.xml/xmlresolver/). Bu **nullptr** ise, **document()** işlevi çözülmez. [XmlResolver](../../../system.xml/xmlresolver/) bu yöntem tamamlandıktan sonra önbelleğe alınmaz. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

IXPathNavigable'daki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir TextWriter'a yazar.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable arayüzünü uygulayan bir nesne. Bu, bir [XmlNode](../../../system.xml/xmlnode/) (genellikle bir [XmlDocument](../../../system.xml/xmldocument/)) ya da verileri içeren bir XPathDocument olabilir. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Dönüşüm için girdi olarak kullanılan ad alanı nitelikli argümanları içeren bir [XsltArgumentList](../../xsltargumentlist/). |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Yazmak istediğiniz TextWriter. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

IXPathNavigable'daki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir Akışa yazar.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable arayüzünü uygulayan bir nesne. Bu, bir [XmlNode](../../../system.xml/xmlnode/) (genellikle bir [XmlDocument](../../../system.xml/xmldocument/)) ya da verileri içeren bir XPathDocument olabilir. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Dönüşüm için girdi olarak kullanılan ad alanı nitelikli argümanları içeren bir [XsltArgumentList](../../xsltargumentlist/). |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Yazmak istediğiniz akış. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **document()** işlevini çözmek için kullanılan [XmlResolver](../../../system.xml/xmlresolver/). Bu **nullptr** ise, **document()** işlevi çözülmez. [XmlResolver](../../../system.xml/xmlresolver/) bu [XslTransform::Transform](./) yöntemi tamamlandıktan sonra önbelleğe alınmaz. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

IXPathNavigable'daki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir Akışa yazar.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable arayüzünü uygulayan bir nesne. Bu, bir [XmlNode](../../../system.xml/xmlnode/) (genellikle bir [XmlDocument](../../../system.xml/xmldocument/)) ya da verileri içeren bir XPathDocument olabilir. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Dönüşüm için girdi olarak kullanılan ad alanı nitelikli argümanları içeren bir [XsltArgumentList](../../xsltargumentlist/). |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Yazmak istediğiniz akış. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

IXPathNavigable'daki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir [XmlWriter](../../../system.xml/xmlwriter/)'e yazar.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable arayüzünü uygulayan bir nesne. Bu, bir [XmlNode](../../../system.xml/xmlnode/) (genellikle bir [XmlDocument](../../../system.xml/xmldocument/)) ya da verileri içeren bir XPathDocument olabilir. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Dönüşüm için girdi olarak kullanılan ad alanı nitelikli argümanları içeren bir [XsltArgumentList](../../xsltargumentlist/). |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Yazmak istediğiniz [XmlWriter](../../../system.xml/xmlwriter/). |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **document()** işlevini çözmek için kullanılan [XmlResolver](../../../system.xml/xmlresolver/). Bu **nullptr** ise, **document()** işlevi çözülmez. [XmlResolver](../../../system.xml/xmlresolver/) bu yöntem tamamlandıktan sonra önbelleğe alınmaz. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

IXPathNavigable'daki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir [XmlWriter](../../../system.xml/xmlwriter/)'e yazar.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable arayüzünü uygulayan bir nesne. Bu, bir [XmlNode](../../../system.xml/xmlnode/) (genellikle bir [XmlDocument](../../../system.xml/xmldocument/)) ya da verileri içeren bir XPathDocument olabilir. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Dönüşüm için girdi olarak kullanılan ad alanı nitelikli argümanları içeren bir [XsltArgumentList](../../xsltargumentlist/). |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Yazmak istediğiniz [XmlWriter](../../../system.xml/xmlwriter/). |

## XslTransform::Transform(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Girdi dosyasındaki XML verilerini dönüştürür ve sonucu bir çıktı dosyasına yazar.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | Dönüştürülecek kaynak belgenin URL'si. |
| outputfile | const [String](../../../system/string/)\& | Çıktı dosyasının URL'si. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **document()** işlevini çözmek için kullanılan [XmlResolver](../../../system.xml/xmlresolver/). Bu **nullptr** ise, **document()** işlevi çözülmez. [XmlResolver](../../../system.xml/xmlresolver/) bu [XslTransform::Transform](./) yöntemi tamamlandıktan sonra önbelleğe alınmaz. |

## XslTransform::Transform(const String\&, const String\&) method

Girdi dosyasındaki XML verilerini dönüştürür ve sonucu bir çıktı dosyasına yazar.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | Dönüştürülecek kaynak belgenin URL'si. |
| outputfile | const [String](../../../system/string/)\& | Çıktı dosyasının URL'si. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [Stream](../../../system.io/stream/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)