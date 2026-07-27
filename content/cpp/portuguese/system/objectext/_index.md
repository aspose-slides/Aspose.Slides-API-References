---
title: ObjectExt
second_title: Aspose.Slides para C++ Referência da API
description: Fornece métodos estáticos que emulam os métodos C# Object chamados para tipos C++ não-Object (strings, números, etc.). Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por nenhum meio.
type: docs
weight: 1145
url: /pt/system/objectext/
---
## ObjectExt classe

Fornece métodos estáticos que emulam os métodos C# [Object](../object/) chamados para tipos C++ não-Object (strings, números, etc.). Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por nenhum meio.

```cpp
class ObjectExt : public System::ObjectType
```

## Métodos

| Método | Descrição |
| --- | --- |
| static std::enable_if<(std::is_fundamental\<To\>::value), std::array\<To, sizeof...(From)>\>::type [ArrayInitializerCast](./arrayinitializercast/)(From ...) | Converte valores fundamentais de arrays (que C# faz implicitamente, mas C++ aparentemente não faz). |
| static std::enable_if\<std::is_enum\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Empacota tipos de valor para conversão para [Object](../object/). Implementação para tipos enum. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Empacota tipos de valor para conversão para [Object](../object/). Implementação para tipos não-enum. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Empacota tipos [Nullable](../nullable/) para conversão para [Object](../object/). |
| static [SmartPtr](../smartptr/)\<[Object](../object/)\> [Box](./box/)(const [String](../string/)\&) | Empacota valores de string. |
| static [SmartPtr](../smartptr/)\<[System::BoxedValueBase](../boxedvaluebase/)\> [BoxEnum](./boxenum/)(T) | Empacota tipos enum para serem propagados como [Object](../object/). |
| static [SmartPtr](../smartptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CastToIList](./casttoilist/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) |  |
| static auto [Coalesce](./coalesce/)(T0, T1) | Implementação da tradução do operador '??' para tipos não anuláveis. |
| static T0 [Coalesce](./coalesce/)([System::Nullable](../nullable/)\<T0\>, T1) | Implementação da tradução do operador '??' para tipos anuláveis. |
| static auto [CoalesceAssign](./coalesceassign/)(T0\&, T1) | Implementação da tradução do operador '??='. |
| static std::conditional\<std::is_convertible\<RT2, RT1\>::value, RT1, RT2\>::type [CoalesceInternal](./coalesceinternal/)(RT1, F) | Implementação da tradução do operador '??' para tipos não anuláveis. Sobrecarga para o caso de RT2 ser convertível para RT1. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) |  |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | Substituição para chamadas C# [Object.Equals](../object/equals/) que funcionam para qualquer tipo em C++. Sobrecarga para tipos de ponteiro inteligente. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(T, const T2\&) | Substituição para chamadas C# [Object.Equals](../object/equals/) que funcionam para qualquer tipo em C++. Sobrecarga para tipos de estrutura. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | Substituição para chamadas C# [Object.Equals](../object/equals/) que funcionam para qualquer tipo em C++. Sobrecarga para tipos escalares. |
| static **bool** [Equals](./equals/)(const char_t(&), [String](../string/)) | Substituição para chamadas C# [Object.Equals](../object/equals/) que funcionam para qualquer tipo em C++. Sobrecarga para literal de string com comparação de strings. |
| static **bool** [Equals](./equals/)(const **float**\&, const **float**\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](./equals/)(const **double**\&, const **double**\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static std::enable_if\<[System::IsSmartPtr](../issmartptr/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static int [GetHashCode](./gethashcode/)(const T\&) | Implementa chamadas [GetHashCode()](./gethashcode/); funciona tanto em subclasses [Object](../object/) quanto em tipos não relacionados. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Implementa a tradução de typeof(). Sobrecarga para ponteiros inteligentes. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Implementa a tradução de typeof(). Sobrecarga para estruturas. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Implementa a tradução de typeof(). Sobrecarga para exceções. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | Implementa a tradução de typeof(). Sobrecarga para tipos primitivos. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | Implementa a tradução de typeof(). Sobrecarga para tipos [Nullable](../nullable/). |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementa a tradução de typeof(). Sobrecarga para tipos primitivos. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementa a tradução de typeof(). Sobrecarga para tipos enum. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementa a tradução de typeof(). Sobrecarga para estruturas e ponteiros. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementa a tradução de typeof(). Sobrecarga para [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementa a tradução de typeof(). Sobrecarga para MutlicastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementa a tradução de typeof(). Sobrecarga para estruturas e ponteiros. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)(const [String](../string/)\&) | Implementa a tradução de typeof(). Sobrecarga para tipo string. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementa a tradução de typeof(). Sobrecarga para **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementa a tradução de typeof(). Sobrecarga para **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementa a tradução de typeof(). Sobrecarga para **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementa a tradução de typeof(). Sobrecarga para **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementa a tradução de typeof(). Sobrecarga para **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementa a tradução de typeof(). Sobrecarga para **uint8_t**. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, **bool**\>::type [Is](./is/)(const T\&) | Implementa a tradução do operador 'is'. Especialização para tipos empacotáveis (valor) que são exatamente isso. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Implementa a tradução do operador 'is'. Especialização para tipos ponteiro otimizados para classes 'final'. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&\!std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Implementa a tradução do operador 'is'. Especialização para tipos ponteiro. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Implementa a tradução do operador 'is'. Especialização para tipos de valor. |
| static std::enable_if<\!std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Implementa a tradução do operador 'is'. Especialização para tipos não convertíveis. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Implementa a tradução do operador 'is'. Especialização para tipos ponteiro. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Is](./is/)(const [ExceptionWrapper](../exceptionwrapper/)\<U\>\&) | Implementa a tradução do operador 'is'. Especialização para tipos wrapper de exceção. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implementa a tradução do operador 'is'. Especialização para tipos anuláveis. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implementa a tradução do operador 'is'. Especialização para tipos empacotáveis com operador == definido. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implementa a tradução do operador 'is'. Especialização para tipos empacotáveis sem == definido. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!std::is_same\<V, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<V\>\&) | Implementa a tradução do operador 'is'. Especialização para tipos de valor empacotados a interfaces. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Implementa a tradução do operador 'is'. Especialização para tipos enum. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [WeakPtr](../weakptr/)\<U\>\&) | Implementa a tradução do operador 'is'. Especialização para tipos enum versus ponteiros fracos. |
| static **bool** [Is](./is/)(const [Nullable](../nullable/)\<U\>\&) | Implementa a tradução do operador 'is'. Especialização para tipo [Nullable](../nullable/). |
| static **bool** [Is](./is/)(const char16_t *) | Implementa a tradução do operador 'is'. Especialização para literal de string. |
| static **bool** [Is](./is/)(**int32_t**) | Implementa a tradução do operador 'is'. Especialização para literal inteiro. |
| static **bool** [IsBoxedValue](./isboxedvalue/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Verifica se o objeto é um valor empacotado. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | Converte [Object](../object/) para tipo desconhecido, lidando tanto com tipo de ponteiro inteligente quanto com situações de valor empacotado. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | Converte [Object](../object/) para tipo desconhecido, lidando tanto com tipo de ponteiro inteligente quanto com situações de valor empacotado. |
| static [String](../string/) [ToString](./tostring/)(const char_t *) | Substituição para o método C# ToString para funcionar em qualquer tipo C++. |
| static [String](../string/) [ToString](./tostring/)(const [Nullable](../nullable/)\<T\>\&) | Substituição para o método C# ToString para funcionar em qualquer tipo C++. |
| static std::enable_if\<std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Substituição para o método C# ToString para funcionar em qualquer tipo C++. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Substituição para o método C# ToString para funcionar em qualquer tipo C++. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value||std::is_pointer\<T\>::value||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Substituição para o método C# ToString para funcionar em qualquer tipo C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Substituição para o método C# ToString para funcionar em qualquer tipo C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | Substituição para o método C# ToString para funcionar em qualquer tipo C++. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Substituição para o método C# ToString para funcionar em qualquer tipo C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Substituição para o método C# ToString para funcionar em qualquer tipo C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_reference\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | Substituição para o método C# ToString para funcionar em qualquer tipo C++. |
| static std::enable_if\<std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Desempacota tipos de valor após conversão para [Object](../object/). Implementação para tipos enum. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Desempacota tipos de valor após conversão para [Object](../object/). Implementação para tipos não-enum e não anuláveis. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Desempacota tipos de valor após conversão para [Object](../object/). Implementação para tipos não-enum e não anuláveis. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::numeric_limits\<T\>::is_integer, T\>::type [Unbox](./unbox/)(E) | Desempacota tipos enum para inteiro. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(E) | Converte tipos enum. |
| static [String](../string/) [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Desempacota valores de string. |
| static [String](../string/) [UnboxStringSafe](./unboxstringsafe/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Desempacota string de valor empacotado. |
| static [Nullable](../nullable/)\<T\> [UnboxToNullable](./unboxtonullable/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Desempacota objeto para tipo anulável. |
| static std::enable_if<\!std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Verifica se objeto de tipo desconhecido é nullptr. Sobrecarga para tipos não escalares. |
| static std::enable_if\<std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Verifica se objeto de tipo desconhecido é nullptr. Sobrecarga para tipos escalares. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(T) | Converte tipo desconhecido para [Object](../object/), lidando tanto com tipo de ponteiro inteligente quanto com tipo de valor. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(const T\&) | Converte tipo desconhecido para [Object](../object/), lidando tanto com tipo de ponteiro inteligente quanto com tipo de valor. |

## Veja Também

* Classe [ObjectType](../objecttype/)
* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)