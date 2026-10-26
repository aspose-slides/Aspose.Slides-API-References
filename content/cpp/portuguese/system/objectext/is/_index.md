---
title: Is()
second_title: Referência da API Aspose.Slides para C++
description: Implementa a tradução do operador 'is'. Especialização para tipos empacotáveis (valor) que são exatamente isso.
type: docs
weight: 92
url: /pt/system/objectext/is/
---
## ObjectExt::Is(const T\&) método


Implementa a tradução do operador 'is'. Especialização para tipos empacotáveis (valor) que exatamente são isso.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value, bool>::type System::ObjectExt::Is(const T &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo alvo. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) para testar o operador 'is'. Ignorado. |

### Valor de retorno

Sempre verdadeiro

## ObjectExt::Is(const U\&) método


Implementa a tradução do operador 'is'. Especialização para tipos ponteiro otimizados para classes 'final'.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo alvo. |
| U | Tipo testado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) para testar o operador 'is'. |

### Valor de retorno

Verdadeiro se 'is' retornar verdadeiro, falso caso contrário.

## ObjectExt::Is(const U\&) método


Implementa a tradução do operador 'is'. Especialização para tipos ponteiro.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo alvo. |
| U | Tipo testado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) para testar o operador 'is'. |

### Valor de retorno

Verdadeiro se 'is' retornar verdadeiro, falso caso contrário.

## ObjectExt::Is(const Object\&) método


Implementa a tradução do operador 'is'. Especialização para tipos valor.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo alvo. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) para testar o operador 'is'. |

### Valor de retorno

Verdadeiro se 'is' retornar verdadeiro, falso caso contrário.

## ObjectExt::Is(const Object\&) método


Implementa a tradução do operador 'is'. Especialização para tipos não convertíveis.

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo alvo. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) para testar o operador 'is'. |

### Valor de retorno

Sempre retorna falso pois os tipos são não conversíveis.

## ObjectExt::Is(const SmartPtr\<U\>\&) método


Implementa a tradução do operador 'is'. Especialização para tipos ponteiro.

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo alvo. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) para testar o operador 'is'. |

### Valor de retorno

Verdadeiro se 'is' retornar verdadeiro, falso caso contrário.

## ObjectExt::Is(const ExceptionWrapper\<U\>\&) método


Implementa a tradução do operador 'is'. Especialização para tipos de wrapper de exceção.

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo alvo. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [ExceptionWrapper](../../exceptionwrapper/)\<U\>\& | [Object](../../object/) para testar o operador 'is'. |

### Valor de retorno

Verdadeiro se 'is' retornar verdadeiro, falso caso contrário.

## ObjectExt::Is(const SmartPtr\<Object\>\&) método


Implementa a tradução do operador 'is'. Especialização para tipos anuláveis.

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo alvo. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) para testar o operador 'is'. |

### Valor de retorno

Verdadeiro se 'is' retornar verdadeiro, falso caso contrário.

## ObjectExt::Is(const SmartPtr\<Object\>\&) método


Implementa a tradução do operador 'is'. Especialização para tipos empacotáveis com operador == definido.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo alvo. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) para testar o operador 'is'. |

### Valor de retorno

Verdadeiro se 'is' retornar verdadeiro, falso caso contrário.

## ObjectExt::Is(const SmartPtr\<Object\>\&) método


Implementa a tradução do operador 'is'. Especialização para tipos empacotáveis sem operador == definido.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo alvo. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) para testar o operador 'is'. |

### Valor de retorno

Verdadeiro se 'is' retornar verdadeiro, falso caso contrário.

## ObjectExt::Is(const SmartPtr\<V\>\&) método


Implementa a tradução do operador 'is'. Especialização para tipos valor encapsulados em interfaces.

```cpp
template<class T,class V> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!std::is_same<V, Object>::value, bool>::type System::ObjectExt::Is(const SmartPtr<V> &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo alvo. |
| V | Tipo do objeto apontado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<V\>\& | [Object](../../object/) para testar o operador 'is'. |

### Valor de retorno

Verdadeiro se 'is' retornar verdadeiro, falso caso contrário.

## ObjectExt::Is(const SmartPtr\<U\>\&) método


Implementa a tradução do operador 'is'. Especialização para tipos enum.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo alvo. |
| U | Tipo do objeto apontado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) para testar o operador 'is'. |

### Valor de retorno

Verdadeiro se 'is' retornar verdadeiro, falso caso contrário.

## ObjectExt::Is(const WeakPtr\<U\>\&) método


Implementa a tradução do operador 'is'. Especialização para tipos enum versus ponteiros fracos.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo alvo. |
| U | Tipo do objeto apontado. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [WeakPtr](../../weakptr/)\<U\>\& | [Object](../../object/) para testar o operador 'is'. |

### Valor de retorno

Verdadeiro se 'is' retornar verdadeiro, falso caso contrário.

## ObjectExt::Is(const Nullable\<U\>\&) método


Implementa a tradução do operador 'is'. Especialização para tipo [Nullable](../../nullable/).

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo alvo. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [Nullable](../../nullable/)\<U\>\& | [Nullable](../../nullable/) tipo. |

### Valor de retorno

Verdadeiro se 'is' retornar verdadeiro, falso caso contrário.

## ObjectExt::Is(const char16_t *) método


Implementa a tradução do operador 'is'. Especialização para literal de string.

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo alvo. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const char16_t * | [String](../../string/) literal. |

### Valor de retorno

Verdadeiro se 'is' retornar verdadeiro, falso caso contrário.

## ObjectExt::Is(int32_t) método


Implementa a tradução do operador 'is'. Especialização para literal inteiro.

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo alvo. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **int32_t** | literal inteiro. |

### Valor de retorno

Verdadeiro se 'is' retornar verdadeiro, falso caso contrário.

## Veja Também

* Classe [ObjectExt](../)
* Classe [Object](../../object/)
* Classe [SmartPtr](../../smartptr/)
* Classe [ExceptionWrapper](../../exceptionwrapper/)
* Classe [WeakPtr](../../weakptr/)
* Classe [Nullable](../../nullable/)
* Estrutura [IsBoxable](../../isboxable/)
* Estrutura [IsSmartPtr](../../issmartptr/)
* Estrutura [IsExceptionWrapper](../../isexceptionwrapper/)
* Estrutura [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)