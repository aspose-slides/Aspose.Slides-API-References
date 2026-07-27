---
title: InsertAfter()
second_title: Referência da API Aspose.Slides para C++
description: Insere o nó especificado imediatamente após o nó de referência especificado.
type: docs
weight: 391
url: /pt/system.xml/xmlnode/insertafter/
---
## XmlNode::InsertAfter(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) método

Insere o nó especificado imediatamente após o nó de referência especificado.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../)\> | O nó a ser inserido. |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../)\> | O nó de referência. **newChild** é colocado após **refChild**. |

### Valor de Retorno

O nó que está sendo inserido.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)