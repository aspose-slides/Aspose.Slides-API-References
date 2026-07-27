---
title: operator+()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve una nueva instancia de la clase Decimal que representa un valor que es la suma del valor especificado y del valor representado por el objeto Decimal especificado.
type: docs
weight: 2185
url: /es/system/operator_plus/
---
## System::operator+(const T\&, const Decimal\&) función

Devuelve una nueva instancia de la clase [Decimal](../decimal/) que representa un valor que es la suma del valor especificado y del valor representado por el objeto [Decimal](../decimal/) especificado.

```cpp
template<typename T,typename _> Decimal System::operator+(const T &x, const Decimal &d)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const T\& | El primer sumando |
| d | const [Decimal](../decimal/)\& | La referencia constante al objeto [Decimal](../decimal/) que representa el segundo sumando |

### Valor de retorno

Una nueva instancia de la clase [Decimal](../decimal/) que representa un valor que es la suma de **x** y el valor representado por **d**.

## System::operator+(MulticastDelegate\<T\>, MulticastDelegate\<T\>) función

Conecta todas las devoluciones de llamada del delegado de la mano derecha al final de la lista de devoluciones de llamada del delegado de la mano izquierda.

```cpp
template<typename T> MulticastDelegate<T> System::operator+(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | El delegado al que se añaden las devoluciones de llamada. |
| rhv | MulticastDelegate\<T\> | El delegado cuyas devoluciones de llamada se están añadiendo. |

### Valor de retorno

Devuelve un delegado que contiene las devoluciones de llamada del valor de la mano izquierda y luego las de la mano derecha.

## System::operator+(const T1\&, const Nullable\<T2\>\&) función

Suma valores no nulos y valores nulos.

```cpp
template<typename T1,typename T2,typename> auto System::operator+(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some+other.get_Value())>
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | Tipo del operando izquierdo. |
| T2 | Tipo del operando derecho. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| some | const T1\& | Operando izquierdo. |
| other | const [Nullable](../nullable/)\<T2\>\& | Operando derecho. |

### Valor de retorno

Resultado de la suma.

## System::operator+(T\&, const String\&) función

[String](../string/) concatenación.

```cpp
template<typename T> std::enable_if<IsStringLiteral<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | [String](../string/) tipo literal. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | T\& | Literal para concatenar a la cadena. |
| right | const [String](../string/)\& | [String](../string/) para concatenar. |

### Valor de retorno

Cadena concatenada.

## System::operator+(T\&, const String\&) función

[String](../string/) concatenación.

```cpp
template<typename T> std::enable_if<IsStringPointer<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | [String](../string/) tipo puntero. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | T\& | [String](../string/) puntero para concatenar a la cadena. |
| right | const [String](../string/)\& | [String](../string/) para concatenar. |

### Valor de retorno

Cadena concatenada.

## System::operator+(const char_t, const String\&) función

[String](../string/) concatenación.

```cpp
String System::operator+(const char_t left, const String &right)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | const char_t | Carácter para concatenar a la cadena. |
| right | const [String](../string/)\& | [String](../string/) para concatenar. |

### Valor de retorno

Cadena concatenada.

## Ver también

* Clase [Decimal](../decimal/)
* Clase [Nullable](../nullable/)
* Clase [String](../string/)
* Estructura [IsStringLiteral](../isstringliteral/)
* Estructura [IsStringPointer](../isstringpointer/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)