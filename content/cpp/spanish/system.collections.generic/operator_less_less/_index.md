---
title: operator<<()
second_title: Referencia de API de Aspose.Slides para C++
description: Insertar datos en el flujo usando codificación UTF-8.
type: docs
weight: 716
url: /es/system.collections.generic/operator_less_less/
---
## System::Collections::Generic::operator<<(std::ostream\&, const KeyValuePair\<TKey, TValue\>\&) función


Insertar datos en el flujo usando codificación UTF-8.

```cpp
template<typename TKey,typename TValue> std::ostream & System::Collections::Generic::operator<<(std::ostream &stream, const KeyValuePair<TKey, TValue> &pair)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TKey | Tipo de clave. |
| TValue | Tipo de valor. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | std::ostream\& | Flujo de salida donde insertar los datos. |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) a insertar. |

### Valor devuelto

**stream**.

## System::Collections::Generic::operator<<(std::wostream\&, const KeyValuePair\<TKey, TValue\>\&) función


Insertar datos en el flujo.

```cpp
template<typename TKey,typename TValue> std::wostream & System::Collections::Generic::operator<<(std::wostream &stream, const KeyValuePair<TKey, TValue> &pair)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TKey | Tipo de clave. |
| TValue | Tipo de valor. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | std::wostream\& | Flujo de salida donde insertar los datos. |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) a insertar. |

### Valor devuelto

**stream**.

## Ver también

* Clase [KeyValuePair](../keyvaluepair/)
* Espacio de nombres [System::Collections::Generic](../)
* Biblioteca [Aspose.Slides](../../)