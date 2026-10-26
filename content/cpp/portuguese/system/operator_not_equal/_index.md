---
title: operator!=()
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 2055
url: /pt/system/operator_not_equal/
---
## System::operator!=(ArraySegment\<T\>, ArraySegment\<T\>) função




```cpp
template<typename T> bool System::operator!=(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator!=(std::nullptr_t, DateTime) função




```cpp
constexpr bool System::operator!=(std::nullptr_t, DateTime)
```

## System::operator!=(std::nullptr_t, const DateTimeOffset\&) função




```cpp
constexpr bool System::operator!=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator!=(std::nullptr_t, const Nullable\<T\>\&) função


Determina se o objeto [Nullable](../nullable/) especificado representa um valor que não é igual a null.

```cpp
template<typename T> bool System::operator!=(std::nullptr_t, const Nullable<T> &other)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | std::nullptr_t | A constant reference to an [Nullable](../nullable/) object to test |

### Valor de retorno

True se o objeto especificado representar valor não nulo, false caso contrário

## System::operator!=(const T1\&, const Nullable\<T2\>\&) função


Determina se o valor especificado não é igual ao valor representado pelo objeto [Nullable](../nullable/) especificado ao aplicar [operator!=()](./) a esses valores.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator!=(const T1 &some, const Nullable<T2> &other)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | O tipo do primeiro valor comparado |
| T2 | O tipo subjacente do objeto [Nullable](../nullable/) que representa o segundo valor comparado |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| some | const T1\& | Uma referência constante ao valor que será usado como primeiro comparando |
| other | const [Nullable](../nullable/)\<T2\>\& | Uma referência constante ao objeto [Nullable](../nullable/) cujo valor representado será usado como segundo comparando |

### Valor de retorno

True se os comparandos não forem iguais, otherwise - false

## System::operator!=(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) função


Compara dois ponteiros inteligentes para verificar desigualdade.

```cpp
template<class X,class Y> bool System::operator!=(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| X | Pointee type of first pointer. |
| Y | Pointee type of second pointer. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | First pointer to compare. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Second pointer to compare. |

### Valor de retorno

False se os ponteiros coincidirem, true caso contrário.

## System::operator!=(SmartPtr\<X\> const\&, std::nullptr_t) função


Verifica se o ponteiro inteligente não é nulo.

```cpp
template<class X> bool System::operator!=(SmartPtr<X> const &x, std::nullptr_t)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| X | Pointee type of pointer. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | Pointer to check. |

### Valor de retorno

False se o ponteiro for nulo, true caso contrário.

## System::operator!=(std::nullptr_t, SmartPtr\<X\> const\&) função


Verifica se o ponteiro inteligente não é nulo.

```cpp
template<class X> bool System::operator!=(std::nullptr_t, SmartPtr<X> const &x)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| X | Pointee type of pointer. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | std::nullptr_t | Pointer to check. |

### Valor de retorno

False se o ponteiro for nulo, true caso contrário.

## System::operator!=(const SmartPtr\<X\>\&, const Y *) função


Comparação de desigualdade entre ponteiro inteligente e ponteiro simples (C).

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const SmartPtr<X> &x, const Y *y)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| X | type of smart pointer. |
| Y | type of simple pointer. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | smart pointer to compare (left). |
| y | const Y * | pointer to compare (right). |

### Valor de retorno

False se os ponteiros coincidirem, true caso contrário.

## System::operator!=(const X *, const SmartPtr\<Y\>\&) função


Comparação de igualdade entre ponteiro simples (C) e ponteiro inteligente.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const X *x, const SmartPtr<Y> &y)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| X | type of simple pointer. |
| Y | type of smart pointer. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | const X * | pointer to compare (right). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | smart pointer to compare (left). |

### Valor de retorno

False se os ponteiros coincidirem, true caso contrário.

## System::operator!=(Chars\&, const String\&) função


[String](../string/) comparação.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator!=(Chars &left, const String &right)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Chars | [String](../string/) tipo literal. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| left | Chars\& | [String](../string/) literal to compare. |
| right | const [String](../string/)\& | [String](../string/) to compare. |

### Valor de retorno

false se as strings coincidirem, true caso contrário.

## System::operator!=(T\&, const String\&) função


[String](../string/) comparação.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator!=(T &left, const String &right)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | [String](../string/) pointer type. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| left | T\& | [String](../string/) pointer to compare. |
| right | const [String](../string/)\& | [String](../string/) to compare. |

### Valor de retorno

false se as strings coincidirem, true caso contrário.

## System::operator!=(const SharedPtr\<Object\>\&, const String\&) função


[Object](../object/) e comparação de string.

```cpp
bool System::operator!=(const SharedPtr<Object> &left, const String &right)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) to convert to string and compare. |
| right | const [String](../string/)\& | [String](../string/) to compare. |

### Valor de retorno

false se a representação em string do objeto for igual à string, true caso contrário.

## System::operator!=(std::nullptr_t, const String\&) função


Verifica se a string é nula.

```cpp
bool System::operator!=(std::nullptr_t, const String &str)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) to check. |

### Valor de retorno

false se a string for nula, true caso contrário.

## System::operator!=(std::nullptr_t, TimeSpan) função




```cpp
constexpr bool System::operator!=(std::nullptr_t, TimeSpan)
```

## System::operator!=(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) função


Determina se os URIs representados pelos objetos atual e especificado não são iguais.

```cpp
bool System::operator!=(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | The first [Uri](../uri/) object to compare |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | The second [Uri](../uri/) object to compare |

### Valor de retorno

True se os URIs não forem iguais, otherwise - false

## Veja Também

* Typedef [SharedPtr](../sharedptr/)
* Classe [ArraySegment](../arraysegment/)
* Classe [DateTime](../datetime/)
* Classe [DateTimeOffset](../datetimeoffset/)
* Classe [Nullable](../nullable/)
* Classe [SmartPtr](../smartptr/)
* Classe [Object](../object/)
* Classe [String](../string/)
* Classe [TimeSpan](../timespan/)
* Classe [Uri](../uri/)
* Estrutura [IsNullable](../isnullable/)
* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)