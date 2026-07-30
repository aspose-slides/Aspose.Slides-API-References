---
title: MoveToAttribute()
second_title: Riferimento API Aspose.Slides per C++
description: "Quando sovrascritto in una classe derivata, sposta il lettore all'attributo con il valore XmlReader::get_Name specificato."
type: docs
weight: 625
url: /it/system.xml/xmlreader/movetoattribute/
---
## XmlReader::MoveToAttribute(String) metodo

Quando sovrascritto in una classe derivata, sposta il lettore all'attributo con il valore [XmlReader::get_Name](../get_name/) specificato.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome qualificato dell'attributo. |

### Valore restituito

**true** se l'attributo è trovato; altrimenti, **false**. Se **false**, la posizione del lettore non cambia.

## XmlReader::MoveToAttribute(String, String) metodo

Quando sovrascritto in una classe derivata, sposta il lettore all'attributo con i valori [XmlReader::get_LocalName](../get_localname/) e [XmlReader::get_NamespaceURI](../get_namespaceuri/) specificati.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name, String ns)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome locale dell'attributo. |
| ns | [String](../../../system/string/) | L'URI dello spazio dei nomi dell'attributo. |

### Valore restituito

**true** se l'attributo è trovato; altrimenti, **false**. Se **false**, la posizione del lettore non cambia.

## XmlReader::MoveToAttribute(int32_t) metodo

Quando sovrascritto in una classe derivata, sposta il lettore all'attributo con l'indice specificato.

```cpp
virtual void System::Xml::XmlReader::MoveToAttribute(int32_t i)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| i | **int32_t** | L'indice dell'attributo. |

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)