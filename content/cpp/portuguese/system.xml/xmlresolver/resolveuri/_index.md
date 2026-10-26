---
title: ResolveUri()
second_title: Referência da API Aspose.Slides para C++
description: Quando sobrescrito em uma classe derivada, resolve o URI absoluto a partir dos URIs base e relativos.
type: docs
weight: 27
url: /pt/system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri(SharedPtr\<Uri\>, String) método


Quando sobrescrito em uma classe derivada, resolve o URI absoluto a partir dos URIs base e relativo.

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | O URI base usado para resolver o URI relativo. |
| relativeUri | [String](../../../system/string/) | O URI a ser resolvido. O URI pode ser absoluto ou relativo. Se for absoluto, este valor substitui efetivamente o valor **baseUri**. Se for relativo, ele se combina com o **baseUri** para formar um URI absoluto. |

### Valor de Retorno

O URI absoluto ou **nullptr** se o URI relativo não puder ser resolvido.

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [XmlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)