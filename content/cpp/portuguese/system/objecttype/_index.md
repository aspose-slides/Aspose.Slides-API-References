---
title: ObjectType
second_title: Referência da API Aspose.Slides para C++
description: Fornece métodos estáticos que implementam getters de tipo de objeto. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por qualquer meio.
type: docs
weight: 1158
url: /pt/system/objecttype/
---
## ObjectType classe

Fornece métodos estáticos que implementam getters de tipo de objeto. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por qualquer meio.

```cpp
class ObjectType
```

## Métodos

| Método | Descrição |
| --- | --- |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Implementa a tradução de typeof(). Sobrecarga para ponteiros inteligentes. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Implementa a tradução de typeof(). Sobrecarga para estruturas. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Implementa a tradução de typeof(). Sobrecarga para exceções. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | Implementa a tradução de typeof(). Sobrecarga para tipos primitivos. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | Implementa a tradução de typeof(). Sobrecarga para tipos [Nullable](../nullable/). |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementa a tradução de typeof(). Sobrecarga para tipos primitivos. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementa a tradução de typeof(). Sobrecarga para tipos enum. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementa a tradução de typeof(). Sobrecarga para estruturas e ponteiros. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementa a tradução de typeof(). Sobrecarga para [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementa a tradução de typeof(). Sobrecarga para MutlicastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementa a tradução de typeof(). Sobrecarga para estruturas e ponteiros. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)(const [String](../string/)\&) | Implementa a tradução de typeof(). Sobrecarga para o tipo string. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementa a tradução de typeof(). Sobrecarga para **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementa a tradução de typeof(). Sobrecarga para **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementa a tradução de typeof(). Sobrecarga para **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementa a tradução de typeof(). Sobrecarga para **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementa a tradução de typeof(). Sobrecarga para **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementa a tradução de typeof(). Sobrecarga para **uint8_t**. |

## Veja Também

* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)