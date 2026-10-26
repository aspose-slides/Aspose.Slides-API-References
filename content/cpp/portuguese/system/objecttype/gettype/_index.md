---
title: GetType()
second_title: Referência da API Aspose.Slides para C++
description: Implementa a tradução de typeof(). Sobrecarga para ponteiros inteligentes.
type: docs
weight: 1
url: /pt/system/objecttype/gettype/
---
## ObjectType::GetType(const T\&) método

Implementa a tradução de typeof(). Sobrecarga para ponteiros inteligentes.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo de objeto ponteiro. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) para obter [TypeInfo](../../typeinfo/). |

### Valor de retorno

Referência constante à estrutura [TypeInfo](../../typeinfo/) descrevendo a classe final do objeto passado.

## ObjectType::GetType(const T\&) método

Implementa a tradução de typeof(). Sobrecarga para estruturas.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo de estrutura. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) para obter [TypeInfo](../../typeinfo/). |

### Valor de retorno

Referência constante à estrutura [TypeInfo](../../typeinfo/) descrevendo a classe final do objeto passado.

## ObjectType::GetType(const T\&) método

Implementa a tradução de typeof(). Sobrecarga para exceções.

```cpp
template<typename T> static std::enable_if<IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo de exceção. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) para obter [TypeInfo](../../typeinfo/). |

### Valor de retorno

Referência constante à estrutura [TypeInfo](../../typeinfo/) descrevendo a classe final do objeto passado.

## ObjectType::GetType(const T) método

Implementa a tradução de typeof(). Sobrecarga para tipos primitivos.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value||std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo primitivo. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const T | IGNORADO |

### Valor de retorno

Referência constante à estrutura [TypeInfo](../../typeinfo/) descrevendo o tipo do objeto passado.

## ObjectType::GetType(const T) método

Implementa a tradução de typeof(). Sobrecarga para tipos [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo [Nullable](../../nullable/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const T | IGNORADO |

### Valor de retorno

Referência constante à estrutura [TypeInfo](../../typeinfo/) descrevendo o tipo do objeto passado.

## ObjectType::GetType() método

Implementa a tradução de typeof(). Sobrecarga para tipos primitivos.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value &&!std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo primitivo. |

### Valor de retorno

Referência constante à estrutura [TypeInfo](../../typeinfo/) descrevendo o tipo especificado.

## ObjectType::GetType() método

Implementa a tradução de typeof(). Sobrecarga para tipos enum.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo primitivo. |

### Valor de retorno

Referência constante à estrutura [TypeInfo](../../typeinfo/) descrevendo o tipo especificado.

## ObjectType::GetType() método

Implementa a tradução de typeof(). Sobrecarga para estruturas e ponteiros.

```cpp
template<typename T> static std::enable_if<(!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsBoxable<T>::value)||IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo primitivo. |

### Valor de retorno

Referência constante à estrutura [TypeInfo](../../typeinfo/) descrevendo a estrutura especificada.

## ObjectType::GetType() método

Implementa a tradução de typeof(). Sobrecarga para [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo [Nullable](../../nullable/). |

### Valor de retorno

Referência constante à estrutura [TypeInfo](../../typeinfo/) descrevendo a estrutura especificada.

## ObjectType::GetType() método

Implementa a tradução de typeof(). Sobrecarga para MutlicastDelegate.

```cpp
template<typename T> static std::enable_if<detail::is_a<T, MulticastDelegate>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo MutlicastDelegate. |

### Valor de retorno

Referência constante à estrutura [TypeInfo](../../typeinfo/) descrevendo a estrutura especificada.

## ObjectType::GetType() método

Implementa a tradução de typeof(). Sobrecarga para estruturas e ponteiros.

```cpp
template<typename T> static std::enable_if<!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&IsBoxable<T>::value &&!detail::is_a<T, MulticastDelegate>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo primitivo. |

### Valor de retorno

Referência constante à estrutura [TypeInfo](../../typeinfo/) descrevendo a estrutura especificada ou tipo apontado se solicitado [SmartPtr](../../smartptr/).

## ObjectType::GetType(const String\&) método

Implementa a tradução de typeof(). Sobrecarga para tipo string.

```cpp
static const System::TypeInfo & System::ObjectType::GetType(const String &obj)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo primitivo. |

### Valor de retorno

Referência constante à estrutura [TypeInfo](../../typeinfo/) descrevendo o tipo [String](../../string/).

## ObjectType::GetType() método

Implementa a tradução de typeof(). Sobrecarga para **uint8_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() método

Implementa a tradução de typeof(). Sobrecarga para char16_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() método

Implementa a tradução de typeof(). Sobrecarga para **int32_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() método

Implementa a tradução de typeof(). Sobrecarga para **int64_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() método

Implementa a tradução de typeof(). Sobrecarga para bool.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() método

Implementa a tradução de typeof(). Sobrecarga para [Void](../../void/).

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## Ver também

* Classe [ObjectType](../)
* Classe [TypeInfo](../../typeinfo/)
* Classe [String](../../string/)
* Estrutura [IsSmartPtr](../../issmartptr/)
* Estrutura [IsExceptionWrapper](../../isexceptionwrapper/)
* Estrutura [IsNullable](../../isnullable/)
* Estrutura [IsBoxable](../../isboxable/)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)