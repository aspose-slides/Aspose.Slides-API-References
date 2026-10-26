---
title: RemoveAttribute()
second_title: Aspose.Slides para C++ Referência da API
description: Remove um atributo pelo nome.
type: docs
weight: 235
url: /pt/system.xml/xmlelement/removeattribute/
---
## XmlElement::RemoveAttribute(String) método

Remove um atributo pelo nome.

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String name)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome do atributo a ser removido. Este é um nome qualificado. Ele é comparado ao valor **get_Name** do nó correspondente. |

## XmlElement::RemoveAttribute(String, String) método

Remove um atributo com o nome local e o URI de namespace especificados. (Se o atributo removido possui um valor padrão, ele é imediatamente substituído).

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String localName, String namespaceURI)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | [String](../../../system/string/) | O nome local do atributo a ser removido. |
| namespaceURI | [String](../../../system/string/) | O URI de namespace do atributo a ser removido. |

## Ver também

* Classe [String](../../../system/string/)
* Classe [XmlElement](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)