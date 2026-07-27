---
title: InsertBefore()
second_title: Referência da API Aspose.Slides para C++
description: Insere o nó especificado imediatamente antes do nó de referência especificado.
type: docs
weight: 209
url: /pt/system.xml/xmlattribute/insertbefore/
---
## XmlAttribute::InsertBefore(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) método

Insere o nó especificado imediatamente antes do nó de referência especificado.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | O [XmlNode](../../xmlnode/) a ser inserido. |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | O [XmlNode](../../xmlnode/) que é o nó de referência. O **newChild** é colocado antes deste nó. |

### Valor de Retorno

O [XmlNode](../../xmlnode/) inserido.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlAttribute](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)