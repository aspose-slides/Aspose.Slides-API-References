---
title: IsNull()
second_title: Referencia de API de Aspose.Slides para C++
description: Comprueba si el valor específico es null. Versión para tipos aritméticos y enumerados.
type: docs
weight: 1
url: /es/system/testtools/isnull/
---
## TestTools::IsNull(T) método

Comprueba si el valor específico es null. [Version](../../version/) para tipos aritméticos y enumerados.

```cpp
template<typename T> static std::enable_if<std::is_arithmetic<T>::value||std::is_enum<T>::value, bool>::type System::TestTools::IsNull(T obj)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo del valor que se está comprobando. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | T | Valor que se comprueba para null. |

### Valor devuelto

Siempre devuelve false.

## TestTools::IsNull(const T&) método

Comprueba si el valor específico es null. [Version](../../version/) para tipos de valor no aritméticos y no enumerados.

```cpp
template<typename T> static std::enable_if<!std::is_arithmetic<T>::value &&!std::is_enum<T>::value, bool>::type System::TestTools::IsNull(const T &obj)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo del valor que se está comprobando. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T& | Valor que se comprueba para null. |

### Valor devuelto

True si el objeto se compara con nullptr como true, false en caso contrario.

## TestTools::IsNull(const SharedPtr\<T\>&) método

Comprueba si el valor específico es null. [Version](../../version/) para tipos de valor no aritméticos.

```cpp
template<typename T> static bool System::TestTools::IsNull(const SharedPtr<T> &obj)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo del valor que se está comprobando. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<T\>\& | Valor que se comprueba para null. |

### Valor devuelto

True si el objeto se compara con nullptr como true, false en caso contrario.

## TestTools::IsNull(System::Collections::Generic::KeyValuePair\<K, V\>&) método

Comprueba si el valor específico es null. [Version](../../version/) para pares clave-valor.

```cpp
template<typename K,typename V> static bool System::TestTools::IsNull(System::Collections::Generic::KeyValuePair<K, V> &kvp)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| K | Tipo de clave. |
| V | Tipo de valor. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| kvp | [System::Collections::Generic::KeyValuePair](../../../system.collections.generic/keyvaluepair/)\<K, V\>\& | Objeto de par. |

### Valor devuelto

True si el par se considera null, false en caso contrario.

## TestTools::IsNull(const System::String&) método

Comprueba si la cadena es null.

```cpp
static bool System::TestTools::IsNull(const System::String &str)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) para comprobar. |

### Valor devuelto

True si la cadena se considera null, false en caso contrario.

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Class [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Class [String](../../string/)
* Struct [TestTools](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)