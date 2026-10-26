---
title: ReadElementString()
second_title: Aspose.Slides for C++ API Referansı
description: "Sadece metin içeren bir öğeyi okur. Ancak, bu işlemi daha doğrudan bir şekilde ele almasını sağladığından dolayı XmlReader::ReadElementContentAsString yönteminin kullanılması önerilir."
type: docs
weight: 859
url: /tr/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() yöntemi

Yalnızca metin içeren bir öğeyi okur. Ancak, [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) yöntemi yerine kullanılmasının önerilmesi, bu işlemi daha doğrudan bir şekilde ele almasını sağladığından dolayıdır.

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```

### Dönüş Değeri

Okunan öğenin içinde bulunan metin. Öğenin boş olması durumunda boş bir dize.

## XmlReader::ReadElementString(String) yöntemi

Bir metin yalnızca öğesini okumadan önce, bulunan öğenin [XmlReader::get_Name](../get_name/) değerinin verilen dizeyle eşleştiğini kontrol eder. Ancak, [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) yöntemi yerine kullanılmasının önerilmesi, bu işlemi daha doğrudan bir şekilde ele almasını sağladığından dolayıdır.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Kontrol edilecek ad. |

### Dönüş Değeri

Okunan öğenin içinde bulunan metin. Öğenin boş olması durumunda boş bir dize.

## XmlReader::ReadElementString(String, String) yöntemi

Bir metin yalnızca öğesini okumadan önce, bulunan öğenin [XmlReader::get_LocalName](../get_localname/) ve [XmlReader::get_NamespaceURI](../get_namespaceuri/) değerlerinin verilen dizelerle eşleştiğini kontrol eder. Ancak, [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) yöntemi yerine kullanılmasının önerilmesi, bu işlemi daha doğrudan bir şekilde ele almasını sağladığından dolayıdır.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Kontrol edilecek yerel ad. |
| ns | [String](../../../system/string/) | Kontrol edilecek ad alanı URI'si. |

### Dönüş Değeri

Okunan öğenin içinde bulunan metin. Öğenin boş olması durumunda boş bir dize.

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [XmlReader](../)
* Ad Alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)