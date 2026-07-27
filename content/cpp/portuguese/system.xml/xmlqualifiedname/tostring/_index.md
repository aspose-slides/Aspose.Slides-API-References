---
title: ToString()
second_title: Aspose.Slides para C++ Referência da API
description: Retorna o valor de string do XmlQualifiedName.
type: docs
weight: 79
url: /pt/system.xml/xmlqualifiedname/tostring/
---
## XmlQualifiedName::ToString() const método


Retorna o valor de string do [XmlQualifiedName](../).

```cpp
String System::Xml::XmlQualifiedName::ToString() const override
```


### Valor de Retorno

O valor de string do [XmlQualifiedName](../) no formato **namespace:localname**. Se o objeto não tiver um namespace definido, este método retorna apenas o nome local.

## XmlQualifiedName::ToString(const String\&, const String\&) método


Retorna o valor de string do [XmlQualifiedName](../).

```cpp
static String System::Xml::XmlQualifiedName::ToString(const String &name, const String &ns)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | O nome do objeto. |
| ns | const [String](../../../system/string/)\& | O namespace do objeto. |

### Valor de Retorno

O valor de string do [XmlQualifiedName](../) no formato **namespace:localname**. Se o objeto não tiver um namespace definido, este método retorna apenas o nome local.

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlQualifiedName](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)