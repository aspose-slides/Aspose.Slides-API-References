---
title: InsertBefore()
second_title: Referência da API Aspose.Slides para C++
description: Insere o atributo especificado imediatamente antes do atributo de referência especificado.
type: docs
weight: 53
url: /pt/system.xml/xmlattributecollection/insertbefore/
---
## XmlAttributeCollection::InsertBefore(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) método

Insere o atributo especificado imediatamente antes do atributo de referência especificado.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertBefore(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | O atributo a ser inserido. |
| refNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | O atributo de referência. **newNode** é colocado antes do **refNode**. |

### Valor de Retorno

O [XmlAttribute](../../xmlattribute/) a ser inserido na coleção.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlAttribute](../../xmlattribute/)
* Classe [XmlAttributeCollection](../)
* Espaço de nomes [System::Xml](../../)
* Library [Aspose.Slides](../../../)