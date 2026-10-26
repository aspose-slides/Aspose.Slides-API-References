---
title: ReadToDescendant()
second_title: Aspose.Slides for C++ API Referansı
description: XmlReader'ı belirtilen nitelikli ada sahip bir sonraki alt öğeye ilerletir.
type: docs
weight: 911
url: /tr/system.xml/xmlreader/readtodescendant/
---
## XmlReader::ReadToDescendant(String) metodu

[XmlReader](../) öğesini belirtilen nitelikli ada sahip bir sonraki alt öğeye ilerletir.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String name)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Geçiş yapmak istediğiniz öğenin nitelikli adı. |

### Dönüş Değeri

**true** eşleşen bir alt öğe bulunursa; aksi takdirde **false**. Eşleşen bir alt öğe bulunamazsa, [XmlReader](../) öğesi öğenin son etiketine ([XmlReader::get_NodeType](../get_nodetype/) değeri [XmlNodeType::EndElement](../../xmlnodetype/)) konumlandırılır. [XmlReader::ReadToDescendant(String)](./) çağrıldığında [XmlReader](../) bir öğe üzerinde konumlandırılmamışsa, bu metot **false** döndürür ve [XmlReader](../) konumu değişmez.

## XmlReader::ReadToDescendant(String, String) metodu

[XmlReader](../) öğesini belirtilen yerel ada ve ad alanı URI'sine sahip bir sonraki alt öğeye ilerletir.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String localName, String namespaceURI)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Geçiş yapmak istediğiniz öğenin yerel adı. |
| namespaceURI | [String](../../../system/string/) | Geçiş yapmak istediğiniz öğenin ad alanı URI'si. |

### Dönüş Değeri

**true** eşleşen bir alt öğe bulunursa; aksi takdirde **false**. Eşleşen bir alt öğe bulunamazsa, [XmlReader](../) öğesi öğenin son etiketine ([XmlReader::get_NodeType](../get_nodetype/) değeri [XmlNodeType::EndElement](../../xmlnodetype/)) konumlandırılır. [XmlReader::ReadToDescendant(String,String)](./) çağrıldığında [XmlReader](../) bir öğe üzerinde konumlandırılmamışsa, bu metot **false** döndürür ve [XmlReader](../) konumu değişmez.

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [XmlReader](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)