---
title: KeyValuePair()
second_title: Referencia de API de Aspose.Slides para C++
description: Inicializador de par clave-valor nulo.
type: docs
weight: 1
url: /es/system.collections.generic/keyvaluepair/keyvaluepair/
---
## KeyValuePair::KeyValuePair() constructor

Inicializador de par clave-valor nulo.

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair()
```

## KeyValuePair::KeyValuePair(const TKey\&, const TValue\&) constructor

Constructor.

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const TKey &key, const TValue &value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | const TKey\& | Clave. |
| value | const TValue\& | Valor. |

## KeyValuePair::KeyValuePair(const std::pair\<OtherK, OtherV\>\&) constructor

Constructor de conversión de tipo.

```cpp
template<typename OtherK,typename OtherV> System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const std::pair<OtherK, OtherV> &pair)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| OtherK | Tipo de clave diferente. |
| OtherV | Tipo de valor diferente. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pair | const std::pair\<OtherK, OtherV\>\& | Valor del par. |

## Ver también

* Clase [KeyValuePair](../)
* Espacio de nombres [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)