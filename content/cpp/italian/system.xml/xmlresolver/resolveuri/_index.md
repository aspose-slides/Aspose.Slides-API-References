---
title: ResolveUri()
second_title: Riferimento API di Aspose.Slides per C++
description: Quando sovrascritto in una classe derivata, risolve l'URI assoluto a partire dagli URI base e relativo.
type: docs
weight: 27
url: /it/system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri(SharedPtr\<Uri\>, String) method


Quando sovrascritto in una classe derivata, risolve l'URI assoluto a partire dagli URI base e relativo.

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'URI base utilizzato per risolvere l'URI relativo. |
| relativeUri | [String](../../../system/string/) | L'URI da risolvere. L'URI può essere assoluto o relativo. Se assoluto, questo valore sostituisce efficacemente il valore **baseUri**. Se relativo, si combina con il valore **baseUri** per creare un URI assoluto. |

### Valore di ritorno

L'URI assoluto o **nullptr** se l'URI relativo non può essere risolto.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [XmlResolver](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)