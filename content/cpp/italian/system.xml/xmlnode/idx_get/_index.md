---
title: idx_get()
second_title: Riferimento API di Aspose.Slides per C++
description: "Restituisce il primo elemento figlio con il XmlNode::get_Name specificato."
type: docs
weight: 586
url: /it/system.xml/xmlnode/idx_get/
---
## XmlNode::idx_get(String) metodo


Restituisce il primo elemento figlio con il [XmlNode::get_Name](../get_name/) specificato.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String name)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome qualificato dell'elemento da recuperare. |

### Valore di ritorno

Il primo [XmlElement](../../xmlelement/) che corrisponde al nome specificato. Restituisce **nullptr** se non c'è alcuna corrispondenza.

## XmlNode::idx_get(String, String) metodo


Restituisce il primo elemento figlio con i valori [XmlNode::get_LocalName](../get_localname/) e [XmlNode::get_NamespaceURI](../get_namespaceuri/) specificati.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String localname, String ns)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Il nome locale dell'elemento. |
| ns | [String](../../../system/string/) | L'URI dello spazio dei nomi dell'elemento. |

### Valore di ritorno

Il primo [XmlElement](../../xmlelement/) con **localname** e **ns** corrispondenti. Restituisce **nullptr** se non c'è alcuna corrispondenza.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlElement](../../xmlelement/)
* Classe [String](../../../system/string/)
* Classe [XmlNode](../)
* Spazio dei nomi [System::Xml](../../)
* Library [Aspose.Slides](../../../)