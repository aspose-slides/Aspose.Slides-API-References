---
title: CreateAttribute()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un XmlAttribute con il nome specificato.
type: docs
weight: 274
url: /it/system.xml/xmldocument/createattribute/
---
## XmlDocument::CreateAttribute(const String\&) method


Crea un [XmlAttribute](../../xmlattribute/) con il nome specificato.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &name)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Il nome qualificato dell'attributo. Se il nome contiene due punti, il valore [XmlNode::get_Prefix](../../xmlnode/get_prefix/) riflette la parte del nome precedente il primo due punti e il valore [XmlDocument::get_LocalName](../get_localname/) riflette la parte del nome successiva al primo due punti. [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) rimane vuoto a meno che il prefisso non sia un prefisso incorporato riconosciuto come **xmlns**. In questo caso get_NamespaceURI ha un valore di [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### Valore restituito

Il nuovo [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&) method


Crea un [XmlAttribute](../../xmlattribute/) con il nome qualificato specificato e [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &qualifiedName, const String &namespaceURI)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | Il nome qualificato dell'attributo. Se il nome contiene due punti, il valore [XmlNode::get_Prefix](../../xmlnode/get_prefix/) rifletterà la parte del nome precedente i due punti e il valore [XmlDocument::get_LocalName](../get_localname/) rifletterà la parte del nome successiva ai due punti. |
| namespaceURI | const [String](../../../system/string/)\& | L'URI del namespace dell'attributo. Se il nome qualificato include un prefisso **xmlns**, allora questo parametro deve essere [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### Valore restituito

Il nuovo [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&, const String\&) method


Crea un [XmlAttribute](../../xmlattribute/) con i [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) e [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) specificati.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &prefix, const String &localName, const String &namespaceURI)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Il prefisso dell'attributo (se presente). [String::Empty](../../../system/string/empty/) e **nullptr** sono equivalenti. |
| localName | const [String](../../../system/string/)\& | Il nome locale dell'attributo. |
| namespaceURI | const [String](../../../system/string/)\& | L'URI del namespace dell'attributo (se presente). [String::Empty](../../../system/string/empty/) e **nullptr** sono equivalenti. Se **prefix** è **xmlns**, allora questo parametro deve essere [http://www.w3.org/2000/xmlns/;](http://www.w3.org/2000/xmlns/;) altrimenti viene sollevata un'eccezione. |

### Valore restituito

Il nuovo [XmlAttribute](../../xmlattribute/).

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlAttribute](../../xmlattribute/)
* Classe [String](../../../system/string/)
* Classe [XmlDocument](../)
* Spazio dei nomi [System::Xml](../../)
* Library [Aspose.Slides](../../../)