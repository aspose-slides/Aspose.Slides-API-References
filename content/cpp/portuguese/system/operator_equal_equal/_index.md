---
title: operator==()
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 2042
url: /pt/system/operator_equal_equal/
---
## System::operator==(ArraySegment\<T\>, ArraySegment\<T\>) função




```cpp
template<typename T> bool System::operator==(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator==(std::nullptr_t, DateTime) função




```cpp
constexpr bool System::operator==(std::nullptr_t, DateTime)
```

## System::operator==(std::nullptr_t, const DateTimeOffset\&) função




```cpp
constexpr bool System::operator==(std::nullptr_t, const DateTimeOffset &)
```

## System::operator==(std::nullptr_t, const Nullable\<T\>\&) função


Determina se o objeto [Nullable](../nullable/) especificado representa um valor que é igual a null.

```cpp
template<typename T> bool System::operator==(std::nullptr_t, const Nullable<T> &other)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | std::nullptr_t | Uma referência constante a um objeto [Nullable](../nullable/) para teste |

### Valor de Retorno

True se o objeto especificado representa valor nulo, false caso contrário

## System::operator==(const T1\&, const Nullable\<T2\>\&) função


Determina se o valor especificado é igual ao valor representado pelo objeto [Nullable](../nullable/) especificado ao aplicar [operator==()](./) a esses valores.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator==(const T1 &some, const Nullable<T2> &other)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | O tipo do primeiro valor comparando |
| T2 | O tipo subjacente do objeto [Nullable](../nullable/) que representa o segundo valor comparando |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| some | const T1\& | Uma referência constante ao valor que será usado como primeiro comparando |
| other | const [Nullable](../nullable/)\<T2\>\& | Uma referência constante ao objeto [Nullable](../nullable/) cujo valor representado será usado como segundo comparando |

### Valor de Retorno

True se os comparandos são iguais, caso contrário - false

## System::operator==(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) função


Compara igualdade de dois smart pointers.

```cpp
template<class X,class Y> bool System::operator==(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| X | Tipo do apontado do primeiro ponteiro. |
| Y | Tipo do apontado do segundo ponteiro. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | Primeiro ponteiro a comparar. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Segundo ponteiro a comparar. |

### Valor de Retorno

True se os ponteiros coincidem, false caso contrário.

## System::operator==(std::nullptr_t, SmartPtr\<X\> const\&) função


Verifica se o ponteiro inteligente é null.

```cpp
template<class X> bool System::operator==(std::nullptr_t, SmartPtr<X> const &x)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| X | Tipo do apontado do ponteiro. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | std::nullptr_t | Ponteiro a ser verificado. |

### Valor de Retorno

True se o ponteiro é null, false caso contrário.

## System::operator==(const SmartPtr\<X\>\&, const Y *) função


Comparação de igualdade de ponteiro inteligente contra ponteiro simples (C).

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const SmartPtr<X> &x, const Y *y)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| X | tipo do ponteiro inteligente. |
| Y | tipo do ponteiro simples. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | ponteiro inteligente a comparar (esquerda). |
| y | const Y * | ponteiro a comparar (direita). |

### Valor de Retorno

True se os ponteiros coincidem, false caso contrário.

## System::operator==(const X *, const SmartPtr\<Y\>\&) função


Comparação de igualdade de ponteiro inteligente contra ponteiro simples (C).

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const X *x, const SmartPtr<Y> &y)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| X | tipo do ponteiro simples. |
| Y | tipo do ponteiro inteligente. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | const X * | ponteiro a comparar (direita). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | ponteiro inteligente a comparar (esquerda). |

### Valor de Retorno

True se os ponteiros coincidem, false caso contrário.

## System::operator==(T const\&, std::nullptr_t) função


Verifica se o objeto de tipo valor (estrutura C# traduzida, etc.) é null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(T const &x, std::nullptr_t)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo de valor. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | T const\& | [Object](../object/) a ser verificado. |

### Valor de Retorno

True se o objeto é null, false caso contrário.

## System::operator==(std::nullptr_t, T const\&) função


Verifica se o objeto de tipo valor (estrutura C# traduzida, etc.) é null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(std::nullptr_t, T const &x)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo de valor. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | std::nullptr_t | [Object](../object/) a ser verificado. |

### Valor de Retorno

True se o objeto é null, false caso contrário.

## System::operator==(Chars\&, const String\&) função


[String](../string/) comparação.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator==(Chars &left, const String &right)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Chars | Tipo literal [String](../string/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| left | Chars\& | Literal [String](../string/) a ser comparado. |
| right | const [String](../string/)\& | [String](../string/) a ser comparado. |

### Valor de Retorno

true se as strings coincidem, false caso contrário.

## System::operator==(T\&, const String\&) função


[String](../string/) comparação.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator==(T &left, const String &right)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo de ponteiro [String](../string/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| left | T\& | Ponteiro [String](../string/) a ser comparado. |
| right | const [String](../string/)\& | [String](../string/) a ser comparado. |

### Valor de Retorno

true se as strings coincidem, false caso contrário.

## System::operator==(const SharedPtr\<Object\>\&, const String\&) função


[Object](../object/) e comparação de string.

```cpp
bool System::operator==(const SharedPtr<Object> &left, const String &right)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) a ser convertido em string e comparado. |
| right | const [String](../string/)\& | [String](../string/) a ser comparado. |

### Valor de Retorno

true se a representação em string do objeto é igual à string, false caso contrário.

## System::operator==(std::nullptr_t, const String\&) função


Verifica se a string é null.

```cpp
bool System::operator==(std::nullptr_t, const String &str)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) a ser verificado. |

### Valor de Retorno

true se a string é null, false caso contrário.

## System::operator==(std::nullptr_t, TimeSpan) função




```cpp
constexpr bool System::operator==(std::nullptr_t, TimeSpan)
```

## System::operator==(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) função


Determina se os URIs representados pelos objetos atual e especificado são iguais.

```cpp
bool System::operator==(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | O primeiro objeto [Uri](../uri/) a comparar |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | O segundo objeto [Uri](../uri/) a comparar |

### Valor de Retorno

True se os URIs são iguais, caso contrário - false

## See Also

* Typedef [SharedPtr](../sharedptr/)
* Class [ArraySegment](../arraysegment/)
* Class [DateTime](../datetime/)
* Class [DateTimeOffset](../datetimeoffset/)
* Class [Nullable](../nullable/)
* Class [SmartPtr](../smartptr/)
* Class [Object](../object/)
* Class [String](../string/)
* Class [TimeSpan](../timespan/)
* Class [Uri](../uri/)
* Struct [IsNullable](../isnullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)