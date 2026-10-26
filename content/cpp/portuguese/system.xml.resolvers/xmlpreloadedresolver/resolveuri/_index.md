---
title: ResolveUri()
second_title: Referência da API Aspose.Slides para C++
description: Resolve o URI absoluto a partir do URI base e dos URIs relativos.
type: docs
weight: 40
url: /pt/system.xml.resolvers/xmlpreloadedresolver/resolveuri/
---
## XmlPreloadedResolver::ResolveUri(SharedPtr\<Uri\>, String) método

Resolve o URI absoluto a partir do URI base e dos URIs relativos.

```cpp
SharedPtr<Uri> System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | O URI base usado para resolver o URI relativo. |
| relativeUri | [String](../../../system/string/) | O URI a ser resolvido. O URI pode ser absoluto ou relativo. Se for absoluto, esse valor substitui efetivamente o valor **baseUri**. Se for relativo, ele se combina com o **baseUri** para formar um URI absoluto. |

### Valor de Retorno

O [Uri](../../../system/uri/) que representa o URI absoluto ou **nullptr** se o URI relativo não puder ser resolvido.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Biblioteca [Aspose.Slides](../../../)