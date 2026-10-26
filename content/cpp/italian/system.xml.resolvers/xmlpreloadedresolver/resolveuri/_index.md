---
title: ResolveUri()
second_title: Riferimento API di Aspose.Slides per C++
description: Risolvi l'URI assoluto a partire dall'URI di base e da quello relativo.
type: docs
weight: 40
url: /it/system.xml.resolvers/xmlpreloadedresolver/resolveuri/
---
## XmlPreloadedResolver::ResolveUri(SharedPtr\<Uri\>, String) metodo

Risolvi l'URI assoluto a partire dall'URI di base e da quello relativo.

```cpp
SharedPtr<Uri> System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'URI di base usato per risolvere l'URI relativo. |
| relativeUri | [String](../../../system/string/) | L'URI da risolvere. L'URI può essere assoluto o relativo. Se è assoluto, questo valore sostituisce effettivamente il valore **baseUri**. Se è relativo, si combina con **baseUri** per creare un URI assoluto. |

### Valore restituito

Il [Uri](../../../system/uri/) che rappresenta l'URI assoluto o **nullptr** se l'URI relativo non può essere risolto.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [XmlPreloadedResolver](../)
* Spazio dei nomi [System::Xml::Resolvers](../../)
* Libreria [Aspose.Slides](../../../)