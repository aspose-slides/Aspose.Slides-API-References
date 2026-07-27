---
title: GetCustomAttribute()
second_title: Referência da API Aspose.Slides para C++
description: Retorna um atributo personalizado de um tipo especificado aplicado ao tipo especificado.
type: docs
weight: 1
url: /pt/system/attribute/getcustomattribute/
---
## Attribute::GetCustomAttribute(const TypeInfo\&, const TypeInfo\&) método

Retorna um atributo personalizado de um tipo especificado aplicado ao tipo especificado.

```cpp
static Object::ptr System::Attribute::GetCustomAttribute(const TypeInfo &type, const TypeInfo &attributeType)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Atributo de tipo do qual é recuperado |
| attributeType | const [TypeInfo](../../typeinfo/)\& | Tipo do atributo a ser recuperado |

### Valor de Retorno

Um atributo recuperado ou null se o tipo especificado não possuir um atributo do tipo especificado.

## Veja Também

* Typedef [ptr](../../object/ptr/)
* Class [TypeInfo](../../typeinfo/)
* Class [Attribute](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)