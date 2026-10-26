---
title: operator==()
second_title: Referencia de API de Aspose.Slides para C++
description: Compara dos pares clave-valor usando la semántica de 'equals'. Utiliza el operador == o el método EqualsTo para ambas claves y valores, según esté definido.
type: docs
weight: 690
url: /es/system.collections.generic/operator_equal_equal/
---
## System::Collections::Generic::operator==(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) función

Compara dos pares clave-valor usando la semántica de 'equals'. Utiliza el operador == o el método EqualsTo para ambas claves y valores, según esté definido.

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator==(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TKey | Tipo de clave. |
| TValue | Tipo de valor. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | operando LHS. |
| right | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | operando RHS. |

### Valor devuelto

Devuelve true si ambas claves y valores coinciden, false en caso contrario.

## Véase también

* Clase [KeyValuePair](../keyvaluepair/)
* Espacio de nombres [System::Collections::Generic](../)
* Biblioteca [Aspose.Slides](../../)