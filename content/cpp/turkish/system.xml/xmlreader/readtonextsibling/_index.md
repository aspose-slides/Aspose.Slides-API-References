---
title: ReadToNextSibling()
second_title: Aspose.Slides için C++ API Referansı
description: XmlReader'ı belirtilen nitelikli adıyla sonraki kardeş öğeye ilerletir.
type: docs
weight: 924
url: /tr/system.xml/xmlreader/readtonextsibling/
---
## XmlReader::ReadToNextSibling(String) yöntemi

[XmlReader](../)'yi belirtilen nitelikli adıyla sonraki kardeş öğeye ilerletir.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String name)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Geçmek istediğiniz kardeş öğenin nitelikli adı. |

### Dönüş Değeri

**true** eşleşen bir kardeş öğe bulunursa; aksi takdirde **false**. Eşleşen bir kardeş öğe bulunamazsa, [XmlReader](../) ebeveyn öğenin son etiketine konumlandırılır ([XmlReader::get_NodeType](../get_nodetype/) değeri [XmlNodeType::EndElement](../../xmlnodetype/)).

## XmlReader::ReadToNextSibling(String, String) yöntemi

[XmlReader](../)'yi belirtilen yerel ad ve ad alanı URI'siyle sonraki kardeş öğeye ilerletir.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String localName, String namespaceURI)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Geçmek istediğiniz kardeş öğenin yerel adı. |
| namespaceURI | [String](../../../system/string/) | Geçmek istediğiniz kardeş öğenin ad alanı URI'si. |

### Dönüş Değeri

**true** eşleşen bir kardeş öğe bulunursa; aksi takdirde **false**. Eşleşen bir kardeş öğe bulunamazsa, [XmlReader](../) ebeveyn öğenin son etiketine konumlandırılır ([XmlReader::get_NodeType](../get_nodetype/) değeri [XmlNodeType::EndElement](../../xmlnodetype/)).

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [XmlReader](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)