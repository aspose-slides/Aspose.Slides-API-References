---
title: MoveToAttribute()
second_title: Riferimento API Aspose.Slides per C++
description: Sposta al attributo con il nome specificato.
type: docs
weight: 300
url: /it/system.xml/xmlnodereader/movetoattribute/
---
## XmlNodeReader::MoveToAttribute(String) metodo

Sposta al attributo con il nome specificato.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome qualificato dell'attributo. |

### Valore di ritorno

**true** se l'attributo è trovato; altrimenti, **false**. Se **false**, la posizione del lettore non cambia.

## XmlNodeReader::MoveToAttribute(String, String) metodo

Sposta al attributo con il nome locale e lo URI dello spazio dei nomi specificati.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name, String namespaceURI) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome locale dell'attributo. |
| namespaceURI | [String](../../../system/string/) | L'URI dello spazio dei nomi dell'attributo. |

### Valore di ritorno

**true** se l'attributo è trovato; altrimenti, **false**. Se **false**, la posizione del lettore non cambia.

## XmlNodeReader::MoveToAttribute(int32_t) metodo

Sposta al attributo con l'indice specificato.

```cpp
void System::Xml::XmlNodeReader::MoveToAttribute(int32_t attributeIndex) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| attributeIndex | **int32_t** | L'indice dell'attributo. |

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlNodeReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)