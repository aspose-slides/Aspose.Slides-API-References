---
title: GetAttribute()
second_title: Riferimento API Aspose.Slides per C++
description: "Quando sovrascritto in una classe derivata, restituisce il valore dell'attributo con il valore XmlReader::get_Name specificato."
type: docs
weight: 599
url: /it/system.xml/xmlreader/getattribute/
---
## XmlReader::GetAttribute(String) method

Quando sovrascritto in una classe derivata, restituisce il valore dell'attributo con il valore [XmlReader::get_Name](../get_name/) specificato.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name)=0
```

### Arguments

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome qualificato dell'attributo. |

### Valore di ritorno

Il valore dell'attributo specificato. Se l'attributo non viene trovato o il valore è [String::Empty](../../../system/string/empty/), viene restituito **nullptr**.

## XmlReader::GetAttribute(String, String) method

Quando sovrascritto in una classe derivata, ottiene il valore dell'attributo con i valori [XmlReader::get_LocalName](../get_localname/) e [XmlReader::get_NamespaceURI](../get_namespaceuri/) specificati.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name, String namespaceURI)=0
```

### Arguments

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome locale dell'attributo. |
| namespaceURI | [String](../../../system/string/) | L'URI dello spazio dei nomi dell'attributo. |

### Valore di ritorno

Il valore dell'attributo specificato. Se l'attributo non viene trovato o il valore è [String::Empty](../../../system/string/empty/), viene restituito **nullptr**. Questo metodo non sposta il lettore.

## XmlReader::GetAttribute(int32_t) method

Quando sovrascritto in una classe derivata, ottiene il valore dell'attributo con l'indice specificato.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(int32_t i)=0
```

### Arguments

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| i | **int32_t** | L'indice dell'attributo. L'indice parte da zero. (Il primo attributo ha indice 0.) |

### Valore di ritorno

Il valore dell'attributo specificato. Questo metodo non sposta il lettore.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)