---
title: idx_get()
second_title: Riferimento API di Aspose.Slides per C++
description: Quando sovrascritto in una classe derivata, restituisce il valore dell'attributo con l'indice specificato.
type: docs
weight: 612
url: /it/system.xml/xmlreader/idx_get/
---
## XmlReader::idx_get(int32_t) metodo

Quando sovrascritto in una classe derivata, restituisce il valore dell'attributo con l'indice specificato.

```cpp
virtual String System::Xml::XmlReader::idx_get(int32_t i)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| i | **int32_t** | L'indice dell'attributo. |

### Valore restituito

Il valore dell'attributo specificato.

## XmlReader::idx_get(String) metodo

Quando sovrascritto in una classe derivata, restituisce il valore dell'attributo con il valore [XmlReader::get_Name](../get_name/) specificato.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome qualificato dell'attributo. |

### Valore restituito

Il valore dell'attributo specificato. Se l'attributo non viene trovato, viene restituito **nullptr**.

## XmlReader::idx_get(String, String) metodo

Quando sovrascritto in una classe derivata, restituisce il valore dell'attributo con i valori [XmlReader::get_LocalName](../get_localname/) e [XmlReader::get_NamespaceURI](../get_namespaceuri/) specificati.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name, String namespaceURI)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome locale dell'attributo. |
| namespaceURI | [String](../../../system/string/) | L'URI del namespace dell'attributo. |

### Valore restituito

Il valore dell'attributo specificato. Se l'attributo non viene trovato, viene restituito **nullptr**.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Namespace [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)