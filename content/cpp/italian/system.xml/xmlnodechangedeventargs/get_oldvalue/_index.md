---
title: get_OldValue()
second_title: Aspose.Slides per C++ Riferimento API
description: Restituisce il valore originale del nodo.
type: docs
weight: 53
url: /it/system.xml/xmlnodechangedeventargs/get_oldvalue/
---
## XmlNodeChangedEventArgs::get_OldValue() metodo

Restituisce il valore originale del nodo.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_OldValue()
```

### Valore di ritorno

Il valore originale del nodo. Questo metodo restituisce **nullptr** se il nodo non è né un attributo né un nodo di testo, o se il nodo sta per essere inserito. Se chiamato in un evento **XmlDocument::NodeChanging**, **get_OldValue** restituisce il valore corrente del nodo che verrà sostituito se la modifica ha successo. Se chiamato in un evento **XmlDocument::NodeChanged**, **get_OldValue** restituisce il valore del nodo prima della modifica.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlNodeChangedEventArgs](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)