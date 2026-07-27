---
title: ResolveUri()
second_title: Referência da API Aspose.Slides para C++
description: Resolve o URI absoluto a partir do URI base e dos URIs relativos.
type: docs
weight: 66
url: /pt/system.xml/xmlurlresolver/resolveuri/
---
## XmlUrlResolver::ResolveUri(SharedPtr\<Uri\>, String) método

Resolve o URI base a partir do URI base e do URI relativo.

```cpp
SharedPtr<Uri> System::Xml::XmlUrlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | O URI base usado para resolver o URI relativo. |
| relativeUri | [String](../../../system/string/) | O URI a ser resolvido. O URI pode ser absoluto ou relativo. Se for absoluto, esse valor substitui efetivamente o valor de **baseUri**. Se for relativo, ele se combina com o **baseUri** para formar um URI absoluto. |

### Valor de retorno

O URI absoluto, ou **nullptr** se o URI relativo não puder ser resolvido.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [XmlUrlResolver](../)
* namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)