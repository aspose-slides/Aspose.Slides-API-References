---
title: InsertAfter()
second_title: Referência da API Aspose.Slides para C++
description: Insere o nó especificado imediatamente após o nó de referência especificado.
type: docs
weight: 222
url: /pt/system.xml/xmlattribute/insertafter/
---
## XmlAttribute::InsertAfter(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) método


Insere o nó especificado imediatamente após o nó de referência especificado.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | O [XmlNode](../../xmlnode/) a ser inserido. |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | O [XmlNode](../../xmlnode/) que é o nó de referência. O **newChild** é colocado após o **refChild**. |

### Valor de Retorno

O [XmlNode](../../xmlnode/) inserido.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlAttribute](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)