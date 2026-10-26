---
title: get_NewValue()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce il nuovo valore del nodo.
type: docs
weight: 66
url: /it/system.xml/xmlnodechangedeventargs/get_newvalue/
---
## XmlNodeChangedEventArgs::get_NewValue() method

Restituisce il nuovo valore del nodo.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_NewValue()
```

### Valore di ritorno

Il nuovo valore del nodo. Questo metodo restituisce **nullptr** se il nodo non è né un attributo né un nodo di testo, o se il nodo viene rimosso. Se chiamato in un evento **XmlDocument::NodeChanging**, **get_NewValue** restituisce il valore del nodo se la modifica ha successo. Se chiamato in un evento **XmlDocument::NodeChanged**, **get_NewValue** restituisce il valore corrente del nodo.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlNodeChangedEventArgs](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)