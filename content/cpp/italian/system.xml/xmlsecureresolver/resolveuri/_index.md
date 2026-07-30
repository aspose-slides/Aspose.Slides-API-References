---
title: ResolveUri()
second_title: Riferimento API di Aspose.Slides per C++
description: Risolve l'URI assoluto dalla base e dagli URI relativi chiamando ResolveUri sull'XmlResolver sottostante.
type: docs
weight: 40
url: /it/system.xml/xmlsecureresolver/resolveuri/
---
## XmlSecureResolver::ResolveUri(SharedPtr\<Uri\>, String) metodo


Risolve l'URI assoluto dalla base e dagli URI relativi chiamando **ResolveUri** sull'[XmlResolver](../../xmlresolver/) sottostante.

```cpp
SharedPtr<Uri> System::Xml::XmlSecureResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'URI di base usato per risolvere l'URI relativo. |
| relativeUri | [String](../../../system/string/) | L'URI da risolvere. L'URI può essere assoluto o relativo. Se assoluto, questo valore sostituisce effettivamente il valore **baseUri**. Se relativo, si combina con **baseUri** per creare un URI assoluto. |

### Valore restituito

L'URI assoluto o **nullptr** se l'URI relativo non può essere risolto (restituito chiamando **ResolveUri** sull'[XmlResolver](../../xmlresolver/) sottostante).

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlSecureResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)