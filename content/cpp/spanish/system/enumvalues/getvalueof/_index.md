---
title: GetValueOf()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve el valor empaquetado de la constante del enum con el nombre especificado.
type: docs
weight: 53
url: /es/system/enumvalues/getvalueof/
---
## EnumValues::GetValueOf(const String\&, bool) const método


Devuelve el valor empaquetado de la constante del enum con el nombre especificado.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(const String &str, bool ignoreCase) const override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [String](../../string/)\& | El nombre de la constante del enum |
| ignoreCase | **bool** | Especifica si se debe ignorar mayúsculas y minúsculas al interpretar el nombre de la constante del enum |

### Valor devuelto

Un valor empaquetado de la constante del enum cuyo nombre se especifica en **str**.

## EnumValues::GetValueOf(long) const método


Devuelve el valor empaquetado de la constante del enum con el valor especificado.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(long val) const override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| val | long | El valor de la constante del enum |

### Valor devuelto

Un valor empaquetado de la constante del enum cuyo valor se especifica en **str**.

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [String](../../string/)
* Class [EnumValues](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)