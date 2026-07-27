---
title: ResolveUri()
second_title: Referência da API Aspose.Slides para C++
description: Resolve o URI absoluto a partir dos URIs base e relativo chamando ResolveUri no XmlResolver subjacente.
type: docs
weight: 40
url: /pt/system.xml/xmlsecureresolver/resolveuri/
---
## XmlSecureResolver::ResolveUri(SharedPtr\<Uri\>, String) método

Resolve o URI absoluto a partir dos URIs base e relativo chamando **ResolveUri** no [XmlResolver](../../xmlresolver/) subjacente.

```cpp
SharedPtr<Uri> System::Xml::XmlSecureResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | O URI base usado para resolver o URI relativo. |
| relativeUri | [String](../../../system/string/) | O URI a ser resolvido. O URI pode ser absoluto ou relativo. Se for absoluto, este valor substitui efetivamente o valor **baseUri**. Se for relativo, ele combina com o **baseUri** para formar um URI absoluto. |

### Valor de Retorno

O URI absoluto ou **nullptr** se o URI relativo não puder ser resolvido (retornado ao chamar **ResolveUri** no [XmlResolver](../../xmlresolver/) subjacente).

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [XmlSecureResolver](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)