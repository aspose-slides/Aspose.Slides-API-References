---
title: CreateElement()
second_title: Referência da API Aspose.Slides para C++
description: Cria um elemento com o nome especificado.
type: docs
weight: 339
url: /pt/system.xml/xmldocument/createelement/
---
## XmlDocument::CreateElement(const String\&) método

Cria um elemento com o nome especificado.

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &name)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | O nome qualificado do elemento. Se o nome contiver dois pontos, então o valor [XmlNode::get_Prefix](../../xmlnode/get_prefix/) reflete a parte do nome que precede os dois pontos e o valor [XmlDocument::get_LocalName](../get_localname/) reflete a parte do nome que segue os dois pontos. O nome qualificado não pode incluir um prefixo de **xmlns**. |

### Valor de Retorno

O novo [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&) método

Cria um [XmlElement](../../xmlelement/) com o nome qualificado e [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &qualifiedName, const String &namespaceURI)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | O nome qualificado do elemento. Se o nome contiver dois pontos, então o valor [XmlNode::get_Prefix](../../xmlnode/get_prefix/) refletirá a parte do nome que precede os dois pontos e o valor [XmlDocument::get_LocalName](../get_localname/) refletirá a parte do nome que segue os dois pontos. O nome qualificado não pode incluir um prefixo de **xmlns**. |
| namespaceURI | const [String](../../../system/string/)\& | O URI do namespace do elemento. |

### Valor de Retorno

O novo [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&, const String\&) método

Cria um elemento com o [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) e [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) especificados.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &prefix, const String &localName, const String &namespaceURI)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | O prefixo do novo elemento (se houver). [String::Empty](../../../system/string/empty/) e **nullptr** são equivalentes. |
| localName | const [String](../../../system/string/)\& | O nome local do novo elemento. |
| namespaceURI | const [String](../../../system/string/)\& | O URI do namespace do novo elemento (se houver). [String::Empty](../../../system/string/empty/) e **nullptr** são equivalentes. |

### Valor de Retorno

O novo [XmlElement](../../xmlelement/).

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlElement](../../xmlelement/)
* Classe [String](../../../system/string/)
* Classe [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)