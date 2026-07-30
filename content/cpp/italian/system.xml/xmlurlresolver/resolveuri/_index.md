---
title: ResolveUri()
second_title: Riferimento API Aspose.Slides per C++
description: Risolve l'URI assoluto a partire dagli URI di base e relativi.
type: docs
weight: 66
url: /it/system.xml/xmlurlresolver/resolveuri/
---
## XmlUrlResolver::ResolveUri(SharedPtr\<Uri\>, String) metodo

Risolvi l'URI assoluto a partire dagli URI di base e relativi.

```cpp
SharedPtr<Uri> System::Xml::XmlUrlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'URI di base usato per risolvere l'URI relativo. |
| relativeUri | [String](../../../system/string/) | L'URI da risolvere. L'URI può essere assoluto o relativo. Se assoluto, questo valore sostituisce effettivamente il valore **baseUri**. Se relativo, si combina con il **baseUri** per creare un URI assoluto. |

### Valore di ritorno

L'URI assoluto, oppure **nullptr** se l'URI relativo non può essere risolto.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [XmlUrlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)