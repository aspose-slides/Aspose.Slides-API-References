---
title: GetAttribute()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce il valore dell'attributo con il nome specificato.
type: docs
weight: 495
url: /it/system.xml/xmltextreader/getattribute/
---
## XmlTextReader::GetAttribute(String) metodo


Restituisce il valore dell'attributo con il nome specificato.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String name) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome qualificato dell'attributo. |

### Valore di ritorno

Il valore dell'attributo specificato. Se l'attributo non viene trovato, **nullptr** è restituito.

## XmlTextReader::GetAttribute(String, String) metodo


Restituisce il valore dell'attributo con il nome locale e l'URI dello spazio dei nomi specificati.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String localName, String namespaceURI) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Il nome locale dell'attributo. |
| namespaceURI | [String](../../../system/string/) | L'URI dello spazio dei nomi dell'attributo. |

### Valore di ritorno

Il valore dell'attributo specificato. Se l'attributo non viene trovato, **nullptr** è restituito. Questo metodo non sposta il lettore.

## XmlTextReader::GetAttribute(int32_t) metodo


Restituisce il valore dell'attributo con l'indice specificato.

```cpp
String System::Xml::XmlTextReader::GetAttribute(int32_t i) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| i | **int32_t** | L'indice dell'attributo. L'indice parte da zero. (Il primo attributo ha indice 0.) |

### Valore di ritorno

Il valore dell'attributo specificato.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)