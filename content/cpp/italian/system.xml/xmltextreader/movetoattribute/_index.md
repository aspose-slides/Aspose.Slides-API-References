---
title: MoveToAttribute()
second_title: Riferimento API di Aspose.Slides per C++
description: Sposta al attributo con il nome specificato.
type: docs
weight: 508
url: /it/system.xml/xmltextreader/movetoattribute/
---
## XmlTextReader::MoveToAttribute(String) metodo

Sposta al attributo con il nome specificato.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String name) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome qualificato dell'attributo. |

### Valore restituito

**true** se l'attributo è trovato; altrimenti, **false**. Se **false**, la posizione del lettore non cambia.

## XmlTextReader::MoveToAttribute(String, String) metodo

Sposta al attributo con il nome locale e l'URI dello spazio dei nomi specificati.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String localName, String namespaceURI) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Il nome locale dell'attributo. |
| namespaceURI | [String](../../../system/string/) | L'URI dello spazio dei nomi dell'attributo. |

### Valore restituito

**true** se l'attributo è trovato; altrimenti, **false**. Se **false**, la posizione del lettore non cambia.

## XmlTextReader::MoveToAttribute(int32_t) metodo

Sposta al attributo con l'indice specificato.

```cpp
void System::Xml::XmlTextReader::MoveToAttribute(int32_t i) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| i | **int32_t** | L'indice dell'attributo. |

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlTextReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)