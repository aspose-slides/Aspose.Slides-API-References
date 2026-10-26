---
title: Is()
second_title: Referencia de la API de Aspose.Slides para C++
description: Implementa la traducción del operador 'is'. Especialización para tipos empaquetables (valor) que son exactamente eso.
type: docs
weight: 92
url: /es/system/objectext/is/
---
## ObjectExt::Is(const T\&) método


Implementa la traducción del operador 'is'. Especialización para tipos (valor) empaquetables que son exactamente eso.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value, bool>::type System::ObjectExt::Is(const T &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) para probar el operador 'is'. Ignorado. |

### Valor de retorno

Siempre verdadero

## ObjectExt::Is(const U\&) método


Implementa la traducción del operador 'is'. Especialización para tipos puntero optimizados para clases 'final'.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |
| U | Tipo probado. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) para probar el operador 'is'. |

### Valor de retorno

Verdadero si 'is' devuelve verdadero, falso en caso contrario.

## ObjectExt::Is(const U\&) método


Implementa la traducción del operador 'is'. Especialización para tipos puntero.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |
| U | Tipo probado. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) para probar el operador 'is'. |

### Valor de retorno

Verdadero si 'is' devuelve verdadero, falso en caso contrario.

## ObjectExt::Is(const Object\&) método


Implementa la traducción del operador 'is'. Especialización para tipos de valor.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) para probar el operador 'is'. |

### Valor de retorno

Verdadero si 'is' devuelve verdadero, falso en caso contrario.

## ObjectExt::Is(const Object\&) método


Implementa la traducción del operador 'is'. Especialización para tipos no convertibles.

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) para probar el operador 'is'. |

### Valor de retorno

Siempre devuelve falso ya que los tipos no son convertibles.

## ObjectExt::Is(const SmartPtr\<U\>\&) método


Implementa la traducción del operador 'is'. Especialización para tipos puntero.

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) para probar el operador 'is'. |

### Valor de retorno

Verdadero si 'is' devuelve verdadero, falso en caso contrario.

## ObjectExt::Is(const ExceptionWrapper\<U\>\&) método


Implementa la traducción del operador 'is'. Especialización para tipos de envoltorio de excepciones.

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [ExceptionWrapper](../../exceptionwrapper/)\<U\>\& | [Object](../../object/) para probar el operador 'is'. |

### Valor de retorno

Verdadero si 'is' devuelve verdadero, falso en caso contrario.

## ObjectExt::Is(const SmartPtr\<Object\>\&) método


Implementa la traducción del operador 'is'. Especialización para tipos anulables.

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) para probar el operador 'is'. |

### Valor de retorno

Verdadero si 'is' devuelve verdadero, falso en caso contrario.

## ObjectExt::Is(const SmartPtr\<Object\>\&) método


Implementa la traducción del operador 'is'. Especialización para tipos empaquetables con el operador == definido.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) para probar el operador 'is'. |

### Valor de retorno

Verdadero si 'is' devuelve verdadero, falso en caso contrario.

## ObjectExt::Is(const SmartPtr\<Object\>\&) método


Implementa la traducción del operador 'is'. Especialización para tipos empaquetables sin == definido.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) para probar el operador 'is'. |

### Valor de retorno

Verdadero si 'is' devuelve verdadero, falso en caso contrario.

## ObjectExt::Is(const SmartPtr\<V\>\&) método


Implementa la traducción del operador 'is'. Especialización para tipos de valor empaquetados a interfaces.

```cpp
template<class T,class V> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!std::is_same<V, Object>::value, bool>::type System::ObjectExt::Is(const SmartPtr<V> &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |
| V | Tipo del objeto apuntado. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<V\>\& | [Object](../../object/) para probar el operador 'is'. |

### Valor de retorno

Verdadero si 'is' devuelve verdadero, falso en caso contrario.

## ObjectExt::Is(const SmartPtr\<U\>\&) método


Implementa la traducción del operador 'is'. Especialización para tipos enum.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |
| U | Tipo del objeto apuntado. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) para probar el operador 'is'. |

### Valor de retorno

Verdadero si 'is' devuelve verdadero, falso en caso contrario.

## ObjectExt::Is(const WeakPtr\<U\>\&) método


Implementa la traducción del operador 'is'. Especialización para tipos enum frente a punteros débiles.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |
| U | Tipo del objeto apuntado. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [WeakPtr](../../weakptr/)\<U\>\& | [Object](../../object/) para probar el operador 'is'. |

### Valor de retorno

Verdadero si 'is' devuelve verdadero, falso en caso contrario.

## ObjectExt::Is(const Nullable\<U\>\&) método


Implementa la traducción del operador 'is'. Especialización para el tipo [Nullable](../../nullable/).

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [Nullable](../../nullable/)\<U\>\& | [Nullable](../../nullable/) tipo. |

### Valor de retorno

Verdadero si 'is' devuelve verdadero, falso en caso contrario.

## ObjectExt::Is(const char16_t *) método


Implementa la traducción del operador 'is'. Especialización para literal de cadena.

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const char16_t * | [String](../../string/) literal. |

### Valor de retorno

Verdadero si 'is' devuelve verdadero, falso en caso contrario.

## ObjectExt::Is(int32_t) método


Implementa la traducción del operador 'is'. Especialización para literal entero.

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo objetivo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **int32_t** | literal entero. |

### Valor de retorno

Verdadero si 'is' devuelve verdadero, falso en caso contrario.

## Ver también

* Clase [ObjectExt](../)
* Clase [Object](../../object/)
* Clase [SmartPtr](../../smartptr/)
* Clase [ExceptionWrapper](../../exceptionwrapper/)
* Clase [WeakPtr](../../weakptr/)
* Clase [Nullable](../../nullable/)
* Estructura [IsBoxable](../../isboxable/)
* Estructura [IsSmartPtr](../../issmartptr/)
* Estructura [IsExceptionWrapper](../../isexceptionwrapper/)
* Estructura [IsNullable](../../isnullable/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)