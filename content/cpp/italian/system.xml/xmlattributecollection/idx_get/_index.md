---
title: idx_get()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce l'attributo con l'indice specificato.
type: docs
weight: 1
url: /it/system.xml/xmlattributecollection/idx_get/
---
## XmlAttributeCollection::idx_get(int32_t) metodo

Restituisce l'attributo con l'indice specificato.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(int32_t i)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| i | **int32_t** | L'indice dell'attributo. |

### Valore di ritorno

L'attributo all'indice specificato.

## XmlAttributeCollection::idx_get(const String\&) metodo

Restituisce l'attributo con il nome specificato.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &name)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Il nome qualificato dell'attributo. |

### Valore di ritorno

L'attributo con il nome specificato. Se l'attributo non esiste, questo metodo restituisce **nullptr**.

## XmlAttributeCollection::idx_get(const String\&, const String\&) metodo

Restituisce l'attributo con il nome locale e lo Uniform Resource Identifier (URI) dello spazio dei nomi specificati.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &localName, const String &namespaceURI)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Il nome locale dell'attributo. |
| namespaceURI | const [String](../../../system/string/)\& | L'URI dello spazio dei nomi dell'attributo. |

### Valore di ritorno

L'attributo con il nome locale e l'URI dello spazio dei nomi specificato. Se l'attributo non esiste, questo metodo restituisce **nullptr**.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlAttributeCollection](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)