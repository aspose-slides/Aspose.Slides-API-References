---
title: MoveToAttribute()
second_title: Riferimento API Aspose.Slides per C++
description: Sposta sull'attributo con il nome specificato.
type: docs
weight: 456
url: /it/system.xml/xmlvalidatingreader/movetoattribute/
---
## XmlValidatingReader::MoveToAttribute(String) metodo


Sposta sull'attributo con il nome specificato.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String name) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome qualificato dell'attributo. |

### Valore restituito

**true** se l'attributo viene trovato; altrimenti, **false**. Se **false**, la posizione del lettore non cambia.

## XmlValidatingReader::MoveToAttribute(String, String) metodo


Sposta sull'attributo con il nome locale e l'Uniform Resource Identifier (URI) di spazio dei nomi specificati.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String localName, String namespaceURI) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Il nome locale dell'attributo. |
| namespaceURI | [String](../../../system/string/) | L'URI dello spazio dei nomi dell'attributo. |

### Valore restituito

**true** se l'attributo viene trovato; altrimenti, **false**. Se **false**, la posizione del lettore non cambia.

## XmlValidatingReader::MoveToAttribute(int32_t) metodo


Sposta sull'attributo con l'indice specificato.

```cpp
void System::Xml::XmlValidatingReader::MoveToAttribute(int32_t i) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| i | **int32_t** | L'indice dell'attributo. |

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlValidatingReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)