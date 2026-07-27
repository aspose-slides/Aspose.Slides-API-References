---
title: idx_get()
second_title: Referência da API Aspose.Slides para C++
description: "Retorna o primeiro elemento filho com o XmlNode::get_Name especificado."
type: docs
weight: 586
url: /pt/system.xml/xmlnode/idx_get/
---
## XmlNode::idx_get(String) método


Retorna o primeiro elemento filho com o [XmlNode::get_Name](../get_name/) especificado.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String name)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome qualificado do elemento a ser recuperado. |

### Valor de Retorno

O primeiro [XmlElement](../../xmlelement/) que corresponde ao nome especificado. Retorna **nullptr** se não houver correspondência.

## XmlNode::idx_get(String, String) método


Retorna o primeiro elemento filho com os valores [XmlNode::get_LocalName](../get_localname/) e [XmlNode::get_NamespaceURI](../get_namespaceuri/) especificados.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String localname, String ns)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localname | [String](../../../system/string/) | O nome local do elemento. |
| ns | [String](../../../system/string/) | O URI do espaço de nomes do elemento. |

### Valor de Retorno

O primeiro [XmlElement](../../xmlelement/) com o **localname** e **ns** correspondentes. Retorna **nullptr** se não houver correspondência.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlElement](../../xmlelement/)
* Classe [String](../../../system/string/)
* Classe [XmlNode](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)