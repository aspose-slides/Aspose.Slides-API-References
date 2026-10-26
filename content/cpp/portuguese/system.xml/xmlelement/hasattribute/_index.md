---
title: HasAttribute()
second_title: Referência da API Aspose.Slides para C++
description: Determina se o nó atual possui um atributo com o nome especificado.
type: docs
weight: 300
url: /pt/system.xml/xmlelement/hasattribute/
---
## XmlElement::HasAttribute(String) método

Determina se o nó atual possui um atributo com o nome especificado.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String name)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome do atributo a ser encontrado. Este é um nome qualificado. Ele é comparado ao valor **get_Name** do nó correspondente. |

### Valor de Retorno

**true** se o nó atual possui o atributo especificado; caso contrário, **false**.

## XmlElement::HasAttribute(String, String) método

Determina se o nó atual possui um atributo com o nome local e o URI do namespace especificados.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String localName, String namespaceURI)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | [String](../../../system/string/) | O nome local do atributo a ser encontrado. |
| namespaceURI | [String](../../../system/string/) | O URI do namespace do atributo a ser encontrado. |

### Valor de Retorno

**true** se o nó atual possui o atributo especificado; caso contrário, **false**.

## Ver Também

* Classe [String](../../../system/string/)
* Classe [XmlElement](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)