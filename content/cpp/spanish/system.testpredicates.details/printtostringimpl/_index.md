---
title: PrintToStringImpl()
second_title: Referencia de API de Aspose.Slides para C++
description: "Imprime la subclase System::Object a cadena usando el método ToString()."
type: docs
weight: 14
url: /es/system.testpredicates.details/printtostringimpl/
---
## System::TestPredicates::Details::PrintToStringImpl(const SharedPtr\<T\>\&, long long) función


Imprime la subclase [System::Object](../../system/object/) a cadena usando el método ToString().

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const SharedPtr<T> &value, long long s)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de clase final. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Puntero al objeto a imprimir. |
| s | long long | Un parámetro de servicio que sirve como selector de sobrecarga de función basado en el tipo de este parámetro; el valor del parámetro se ignora |

### Valor de retorno

[String](../../system/string/) representación del objeto pasado o "nullptr", si **value** es nulo.

## System::TestPredicates::Details::PrintToStringImpl(const WeakPtr\<T\>\&, long long) función


Imprime la subclase [System::Object](../../system/object/) a cadena usando el método ToString().

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const WeakPtr<T> &value, long long s)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de clase final. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [WeakPtr](../../system/weakptr/)\<T\>\& | Puntero al objeto a imprimir. |
| s | long long | Un parámetro de servicio que sirve como selector de sobrecarga de función basado en el tipo de este parámetro; el valor del parámetro se ignora |

### Valor de retorno

[String](../../system/string/) representación del objeto pasado o "nullptr", si **value** es nulo.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) función


Imprime el objeto a cadena usando el método ToString().

```cpp
template<typename T> std::enable_if<!TypeTraits::has_print_to_method<T>::value &&System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) a imprimir. |
| s | long long | Un parámetro de servicio que sirve como selector de sobrecarga de función basado en el tipo de este parámetro; el valor del parámetro se ignora |

### Valor de retorno

[String](../../system/string/) representación del objeto pasado.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) función


Imprime el objeto a cadena usando el método PrintTo.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&!TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) a imprimir. |
| s | long long | Un parámetro de servicio que sirve como selector de sobrecarga de función basado en el tipo de este parámetro; el valor del parámetro se ignora |

### Valor de retorno

[String](../../system/string/) representación del objeto pasado.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) función


Imprime el objeto a cadena usando el método PrintTo.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) a imprimir. |
| s | long long | Un parámetro de servicio que sirve como selector de sobrecarga de función basado en el tipo de este parámetro; el valor del parámetro se ignora |

### Valor de retorno

[String](../../system/string/) representación del objeto pasado.

## System::TestPredicates::Details::PrintToStringImpl(const std::pair\<T1, T2\>\&, long long) función


Imprime el par a cadena.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const std::pair<T1, T2> &value, long long s)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | Primer argumento de tipo de par. |
| T2 | Segundo argumento de tipo de par. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const std::pair\<T1, T2\>\& | [Object](../../system/object/) a imprimir. |
| s | long long | Un parámetro de servicio que sirve como selector de sobrecarga de función basado en el tipo de este parámetro; el valor del parámetro se ignora |

### Valor de retorno

Representaciones de cadena conjuntas de ambos componentes del primer y segundo par.

## System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair\<T1, T2\>\&, long long) función


Imprime el par a cadena.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair<T1, T2> &value, long long s)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | Primer argumento de tipo de par. |
| T2 | Segundo argumento de tipo de par. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<T1, T2\>\& | [Object](../../system/object/) a imprimir. |
| s | long long | Un parámetro de servicio que sirve como selector de sobrecarga de función basado en el tipo de este parámetro; el valor del parámetro se ignora |

### Valor de retorno

Representaciones de cadena conjuntas de ambos componentes del primer y segundo par.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) función


Imprime contenedores al estilo STL a cadena imprimiendo sus elementos (no más de 32).

```cpp
template<typename T> std::enable_if<TypeTraits::IsCppContainer<T>::value &&!std::is_base_of<Object, T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &container, long long s)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| container | const T\& | [Object](../../system/object/) a imprimir. |
| s | long long | Un parámetro de servicio que sirve como selector de sobrecarga de función basado en el tipo de este parámetro; el valor del parámetro se ignora |

### Valor de retorno

Representaciones de cadena conjuntas de los elementos contenidos.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, int) función


Imprime otros tipos a cadena usando funciones proporcionadas por gtest.

```cpp
template<typename T> std::string System::TestPredicates::Details::PrintToStringImpl(const T &value, int s)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) a imprimir. |
| s | int | Un parámetro de servicio que sirve como selector de sobrecarga de función basado en el tipo de este parámetro; el valor del parámetro se ignora |

### Valor de retorno

[String](../../system/string/) representaciones del objeto pasado.

## Ver también

* Typedef [SharedPtr](../../system/sharedptr/)
* Clase [WeakPtr](../../system/weakptr/)
* Clase [KeyValuePair](../../system.collections.generic/keyvaluepair/)
* Clase [Object](../../system/object/)
* Estructura [has_print_to_method](../../system.testpredicates.typetraits/has_print_to_method/)
* Estructura [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Estructura [IsCppContainer](../../system.testpredicates.typetraits/iscppcontainer/)
* Espacio de nombres [System::TestPredicates::Details](../)
* Biblioteca [Aspose.Slides](../../)