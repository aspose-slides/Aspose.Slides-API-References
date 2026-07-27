---
title: CreateAttribute()
second_title: Referência da API Aspose.Slides para C++
description: Cria um XmlAttribute com o nome especificado.
type: docs
weight: 274
url: /pt/system.xml/xmldocument/createattribute/
---
## XmlDocument::CreateAttribute(const String\&) método

Cria um [XmlAttribute](../../xmlattribute/) com o nome especificado.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &name)
```

### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | O nome qualificado do atributo. Se o nome contiver dois pontos, o valor [XmlNode::get_Prefix](../../xmlnode/get_prefix/) reflete a parte do nome que precede o primeiro dois-pontos e o valor [XmlDocument::get_LocalName](../get_localname/) reflete a parte do nome que segue o primeiro dois-pontos. O [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) permanece vazio a menos que o prefixo seja um prefixo interno reconhecido, como **xmlns**. Nesse caso, get_NamespaceURI tem o valor [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### Return Value

O novo [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&) método

Cria um [XmlAttribute](../../xmlattribute/) com o nome qualificado especificado e [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &qualifiedName, const String &namespaceURI)
```

### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | O nome qualificado do atributo. Se o nome contiver dois pontos, o valor [XmlNode::get_Prefix](../../xmlnode/get_prefix/) refletirá a parte do nome que precede os dois-pontos e o valor [XmlDocument::get_LocalName](../get_localname/) refletirá a parte do nome que segue os dois-pontos. |
| namespaceURI | const [String](../../../system/string/)\& | O namespaceURI do atributo. Se o nome qualificado incluir um prefixo **xmlns**, então este parâmetro deve ser [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### Return Value

O novo [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&, const String\&) método

Cria um [XmlAttribute](../../xmlattribute/) com o [XmlNode::get_Prefix](../../xmlnode/get_prefix/) especificado, [XmlDocument::get_LocalName](../get_localname/) e [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &prefix, const String &localName, const String &namespaceURI)
```

### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | O prefixo do atributo (se houver). [String::Empty](../../../system/string/empty/) e **nullptr** são equivalentes. |
| localName | const [String](../../../system/string/)\& | O nome local do atributo. |
| namespaceURI | const [String](../../../system/string/)\& | O namespace URI do atributo (se houver). [String::Empty](../../../system/string/empty/) e **nullptr** são equivalentes. Se **prefix** for **xmlns**, então este parâmetro deve ser [http://www.w3.org/2000/xmlns/;](http://www.w3.org/2000/xmlns/;) caso contrário uma exceção é lançada. |

### Return Value

O novo [XmlAttribute](../../xmlattribute/).

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlAttribute](../../xmlattribute/)
* Classe [String](../../../system/string/)
* Classe [XmlDocument](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)