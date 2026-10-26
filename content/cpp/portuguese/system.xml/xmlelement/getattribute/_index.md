---
title: GetAttribute()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o valor do atributo com o nome especificado.
type: docs
weight: 209
url: /pt/system.xml/xmlelement/getattribute/
---
## XmlElement::GetAttribute(String) method

Retorna o valor do atributo com o nome especificado.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String name)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome do atributo a ser recuperado. Este é um nome qualificado. Ele é comparado ao valor **get_Name** do nó correspondente. |

### Valor de Retorno

O valor do atributo especificado. Uma string vazia é retornada se nenhum atributo correspondente for encontrado ou se o atributo não possuir um valor especificado ou padrão.

## XmlElement::GetAttribute(String, String) method

Retorna o valor do atributo com o nome local e URI de namespace especificados.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String localName, String namespaceURI)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | [String](../../../system/string/) | O nome local do atributo a ser recuperado. |
| namespaceURI | [String](../../../system/string/) | O URI de namespace do atributo a ser recuperado. |

### Valor de Retorno

O valor do atributo especificado. Uma string vazia é retornada se nenhum atributo correspondente for encontrado ou se o atributo não possuir um valor especificado ou padrão.

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlElement](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)