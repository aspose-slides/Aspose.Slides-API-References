---
title: GetAttribute()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce il valore dell'attributo con il nome specificato.
type: docs
weight: 443
url: /it/system.xml/xmlvalidatingreader/getattribute/
---
## XmlValidatingReader::GetAttribute(String) metodo

Restituisce il valore dell'attributo con il nome specificato.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String name) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome qualificato dell'attributo. |

### Valore restituito

Il valore dell'attributo specificato. Se l'attributo non viene trovato, **nullptr** viene restituito.

## XmlValidatingReader::GetAttribute(String, String) metodo

Restituisce il valore dell'attributo con il nome locale e l'Uniform Resource Identifier (URI) dello spazio dei nomi specificati.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String localName, String namespaceURI) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Il nome locale dell'attributo. |
| namespaceURI | [String](../../../system/string/) | L'URI dello spazio dei nomi dell'attributo. |

### Valore restituito

Il valore dell'attributo specificato. Se l'attributo non viene trovato, **nullptr** viene restituito. Questo metodo non sposta il lettore.

## XmlValidatingReader::GetAttribute(int32_t) metodo

Restituisce il valore dell'attributo con l'indice specificato.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(int32_t i) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| i | **int32_t** | L'indice dell'attributo. L'indice è basato su zero. (Il primo attributo ha indice 0.) |

### Valore restituito

Il valore dell'attributo specificato.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlValidatingReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)