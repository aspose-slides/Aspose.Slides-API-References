---
title: CreateElement()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un elemento con il nome specificato.
type: docs
weight: 339
url: /it/system.xml/xmldocument/createelement/
---
## XmlDocument::CreateElement(const String\&) metodo


Crea un elemento con il nome specificato.

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &name)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Il nome qualificato dell'elemento. Se il nome contiene due punti, il valore [XmlNode::get_Prefix](../../xmlnode/get_prefix/) riflette la parte del nome precedente i due punti e il valore [XmlDocument::get_LocalName](../get_localname/) riflette la parte del nome successiva ai due punti. Il nome qualificato non può includere un prefisso **xmlns**. |

### Valore restituito

Il nuovo [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&) metodo


Crea un [XmlElement](../../xmlelement/) con il nome qualificato e [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &qualifiedName, const String &namespaceURI)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | Il nome qualificato dell'elemento. Se il nome contiene due punti, il valore [XmlNode::get_Prefix](../../xmlnode/get_prefix/) rifletterà la parte del nome precedente i due punti e il valore [XmlDocument::get_LocalName](../get_localname/) rifletterà la parte del nome successiva ai due punti. Il nome qualificato non può includere un prefisso **xmlns**. |
| namespaceURI | const [String](../../../system/string/)\& | L'URI dello spazio dei nomi dell'elemento. |

### Valore restituito

Il nuovo [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&, const String\&) metodo


Crea un elemento con il [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) e [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &prefix, const String &localName, const String &namespaceURI)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Il prefisso del nuovo elemento (se presente). [String::Empty](../../../system/string/empty/) e **nullptr** sono equivalenti. |
| localName | const [String](../../../system/string/)\& | Il nome locale del nuovo elemento. |
| namespaceURI | const [String](../../../system/string/)\& | L'URI dello spazio dei nomi del nuovo elemento (se presente). [String::Empty](../../../system/string/empty/) e **nullptr** sono equivalenti. |

### Valore restituito

Il nuovo [XmlElement](../../xmlelement/).

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlElement](../../xmlelement/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)