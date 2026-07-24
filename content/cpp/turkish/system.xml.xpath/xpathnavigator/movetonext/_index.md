---
title: MoveToNext()
second_title: Aspose.Slides C++ API Referansı
description: Türetilmiş bir sınıfta geçersiz kılındığında, XPathNavigator öğesini geçerli düğümün bir sonraki kardeş düğümüne taşır.
type: docs
weight: 586
url: /tr/system.xml.xpath/xpathnavigator/movetonext/
---
## XPathNavigator::MoveToNext() yöntemi

Türetilmiş bir sınıfta geçersiz kılındığında, [XPathNavigator](../) öğesini geçerli düğümün bir sonraki kardeş düğümüne taşır.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext()=0
```

### Dönüş Değeri

**true** eğer [XPathNavigator](../) başarılı bir şekilde bir sonraki kardeş düğüme taşınıyorsa; aksi takdirde **false** eğer daha fazla kardeş düğüm yoksa veya [XPathNavigator](../) şu anda bir öznitelik düğümünde konumlanmışsa. **false** olduğunda, [XPathNavigator](../) konumu değişmez.

## XPathNavigator::MoveToNext(String, String) yöntemi

[XPathNavigator](../) öğesini belirtilen yerel ad ve ad alanı URI'sına sahip bir sonraki kardeş düğüme taşır.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(String localName, String namespaceURI)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Taşınacak bir sonraki kardeş düğümünün yerel adı. |
| namespaceURI | [String](../../../system/string/) | Taşınacak bir sonraki kardeş düğümünün ad alanı URI'sı. |

### Dönüş Değeri

**true** eğer [XPathNavigator](../) başarılı bir şekilde bir sonraki kardeş düğüme taşınıyorsa; **false** eğer daha fazla kardeş düğüm yoksa veya [XPathNavigator](../) şu anda bir öznitelik düğümünde konumlanmışsa. **false** olduğunda, [XPathNavigator](../) konumu değişmez.

## XPathNavigator::MoveToNext(XPathNodeType) yöntemi

[XPathNavigator](../) öğesini belirtilen XPathNodeType ile eşleşen geçerli düğümün bir sonraki kardeş düğümüne taşır.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(XPathNodeType type)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Taşınacak kardeş düğümünün XPathNodeType'ı. |

### Dönüş Değeri

**true** eğer [XPathNavigator](../) başarılı bir şekilde bir sonraki kardeş düğüme taşınıyorsa; aksi takdirde **false** eğer daha fazla kardeş düğüm yoksa veya [XPathNavigator](../) şu anda bir öznitelik düğümünde konumlanmışsa. **false** olduğunda, [XPathNavigator](../) konumu değişmez.

## Bakınız

* Enum [XPathNodeType](../../xpathnodetype/)
* Sınıf [XPathNavigator](../)
* Sınıf [String](../../../system/string/)
* İsim Uzayı [System::Xml::XPath](../../)
* Kütüphane [Aspose.Slides](../../../)