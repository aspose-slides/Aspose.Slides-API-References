---
title: SetAttribute()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta il valore dell'attributo con il nome specificato.
type: docs
weight: 222
url: /it/system.xml/xmlelement/setattribute/
---
## XmlElement::SetAttribute(String, String) metodo


Imposta il valore dell'attributo con il nome specificato.

```cpp
virtual void System::Xml::XmlElement::SetAttribute(String name, String value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome dell'attributo da creare o modificare. Questo è un nome qualificato. Se il nome contiene due punti viene analizzato in prefisso e componenti del nome locale. |
| value | [String](../../../system/string/) | Il valore da impostare per l'attributo. |

## XmlElement::SetAttribute(String, String, String) metodo


Imposta il valore dell'attributo con il nome locale e l'URI dello spazio dei nomi specificati.

```cpp
virtual String System::Xml::XmlElement::SetAttribute(String localName, String namespaceURI, String value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Il nome locale dell'attributo. |
| namespaceURI | [String](../../../system/string/) | L'URI dello spazio dei nomi dell'attributo. |
| value | [String](../../../system/string/) | Il valore da impostare per l'attributo. |

### Valore di ritorno

Il valore dell'attributo.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlElement](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)