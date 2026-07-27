---
title: InsertAfter()
second_title: Referência da API Aspose.Slides for C++
description: Insere o atributo especificado imediatamente após o atributo de referência especificado.
type: docs
weight: 66
url: /pt/system.xml/xmlattributecollection/insertafter/
---
## XmlAttributeCollection::InsertAfter(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) método

Insere o atributo especificado imediatamente após o atributo de referência especificado.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertAfter(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | O atributo a ser inserido. |
| refNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | O atributo de referência. **newNode** é colocado após o **refNode**. |

### Valor de retorno

O [XmlAttribute](../../xmlattribute/) a inserir na coleção.

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlAttribute](../../xmlattribute/)
* Classe [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)