---
title: ReadElementContentAsObject()
second_title: Referência da API Aspose.Slides for C++
description: Lê o elemento atual e retorna o conteúdo como um Object.
type: docs
weight: 469
url: /pt/system.xml/xmlreader/readelementcontentasobject/
---
## XmlReader::ReadElementContentAsObject() método


Lê o elemento atual e retorna o conteúdo como um [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject()
```


### Valor de Retorno

Um objeto encapsulado do tipo mais adequado. O valor [XmlReader::get_ValueType](../get_valuetype/) determina o tipo adequado. Se o conteúdo for tipado como um tipo de lista, este método retorna uma matriz de objetos encapsulados do tipo adequado.

## XmlReader::ReadElementContentAsObject(String, String) método


Verifica se o nome local e o URI do namespace especificados correspondem aos do elemento atual, então lê o elemento atual e retorna o conteúdo como um [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject(String localName, String namespaceURI)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | [String](../../../system/string/) | O nome local do elemento. |
| namespaceURI | [String](../../../system/string/) | O URI do namespace do elemento. |

### Valor de Retorno

Um objeto encapsulado do tipo mais adequado. O valor [XmlReader::get_ValueType](../get_valuetype/) determina o tipo adequado. Se o conteúdo for tipado como um tipo de lista, este método retorna uma matriz de objetos encapsulados do tipo adequado.

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [XmlReader](../)
* Classe [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)