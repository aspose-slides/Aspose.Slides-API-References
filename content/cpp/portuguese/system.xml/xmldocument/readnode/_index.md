---
title: ReadNode()
second_title: Referência da API Aspose.Slides for C++
description: Cria um objeto XmlNode com base nas informações no XmlReader. O leitor deve estar posicionado em um nó ou atributo.
type: docs
weight: 495
url: /pt/system.xml/xmldocument/readnode/
---
## XmlDocument::ReadNode(SharedPtr\<XmlReader\>) método


Cria um objeto [XmlNode](../../xmlnode/) com base nas informações no [XmlReader](../../xmlreader/). O leitor deve estar posicionado em um nó ou atributo.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ReadNode(SharedPtr<XmlReader> reader)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | A fonte XML. |

### Valor de Retorno

O novo [XmlNode](../../xmlnode/) ou **nullptr** se não houver mais nós.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlReader](../../xmlreader/)
* Classe [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)