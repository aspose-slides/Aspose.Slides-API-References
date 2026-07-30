---
title: GetAttribute()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il valore dell'attributo con il nome specificato.
type: docs
weight: 287
url: /it/system.xml/xmlnodereader/getattribute/
---
## XmlNodeReader::GetAttribute(String) metodo


Restituisce il valore dell'attributo con il nome specificato.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name) override
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome qualificato dell'attributo. |

### Valore di ritorno

Il valore dell'attributo specificato. Se l'attributo non viene trovato, **nullptr** viene restituito.

## XmlNodeReader::GetAttribute(String, String) metodo


Restituisce il valore dell'attributo con il nome locale e l'URI dello spazio dei nomi specificati.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name, String namespaceURI) override
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome locale dell'attributo. |
| namespaceURI | [String](../../../system/string/) | L'URI dello spazio dei nomi dell'attributo. |

### Valore di ritorno

Il valore dell'attributo specificato. Se l'attributo non viene trovato, **nullptr** viene restituito.

## XmlNodeReader::GetAttribute(int32_t) metodo


Restituisce il valore dell'attributo con l'indice specificato.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(int32_t attributeIndex) override
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| attributeIndex | **int32_t** | L'indice dell'attributo. L'indice è basato su zero. (Il primo attributo ha indice 0.) |

### Valore di ritorno

Il valore dell'attributo specificato.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlNodeReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)