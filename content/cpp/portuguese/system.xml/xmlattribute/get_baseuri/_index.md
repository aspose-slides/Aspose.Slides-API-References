---
title: get_BaseURI()
second_title: Aspose.Slides para C++ Referência da API
description: Retorna o Identificador Uniforme de Recurso (URI) base do nó.
type: docs
weight: 183
url: /pt/system.xml/xmlattribute/get_baseuri/
---
## XmlAttribute::get_BaseURI() método


Retorna o Identificador Uniforme de Recurso (URI) base do nó.

```cpp
String System::Xml::XmlAttribute::get_BaseURI() override
```


### Valor de Retorno

O local de onde o nó foi carregado ou [String::Empty](../../../system/string/empty/) se o nó não tem URI base. [Attribute](../../../system/attribute/) nós têm o mesmo URI base que seu elemento proprietário. Se um nó de atributo não possui elemento proprietário, get_BaseURI retorna [String::Empty](../../../system/string/empty/).

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlAttribute](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)