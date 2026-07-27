---
title: "System::Collections::Generic::Details::CastRules"
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 365
url: /pt/system.collections.generic.details.castrules/
---
## Estruturas

| Estrutura | Descrição |
| --- | --- |
| [CastType](./casttype/) | Contém as funções para determinar o tipo de conversão. |
## Funções

| Função | Descrição |
| --- | --- |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, Result\> [Cast](./cast/)(Source) | Converte o tipo de origem para o tipo de resultado. Usado quando os tipos de origem e de resultado são os mesmos. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, Result\> [Cast](./cast/)(Source) | Converte o tipo de origem para o tipo de resultado. Usado quando o tipo de origem pode ser convertido estaticamente para o tipo de resultado. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, Result\> [Cast](./cast/)(Source) | Converte o tipo de origem para o tipo de resultado. Usado quando os tipos não são os mesmos e o tipo de origem não pode ser convertido estaticamente para o tipo de resultado. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, Result\> [Cast](./cast/)(Source) | Converte o tipo de origem para o tipo de resultado. Usado quando o tipo de origem está sendo encapsulado na instância da classe [Nullable](../system/nullable/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, Result\> [Cast](./cast/)(Source) | Converte o tipo de origem para o tipo de resultado. Usado quando o tipo de origem está sendo desencapsulado da instância da classe [Nullable](../system/nullable/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, Result\> [Cast](./cast/)(Source) | Converte o tipo de origem para o tipo de resultado. Usado quando o tipo de origem está sendo encapsulado na instância da classe [Object](../system/object/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, Result\> [Cast](./cast/)(Source) | Converte o tipo de origem para o tipo de resultado. Usado quando o tipo de origem está sendo desencapsulado da instância da classe [Object](../system/object/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, Result\> [Cast](./cast/)(Source) | Converte o tipo de origem para o tipo de resultado. Usado quando a conversão é inválida ou a conversão é explícita. |
| **bool** [IsNull](./isnull/)(T) | Verifica se o valor representado é nullptr. |
| **bool** [IsNull](./isnull/)([SharedPtr](../system/sharedptr/)\<T\>) | Verifica se o valor representado é nullptr. |
| **bool** [IsNull](./isnull/)([Nullable](../system/nullable/)\<T\>) | Verifica se o valor representado é nullptr. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, **bool**\> [CanCast](./cancast/)(Source) | Verifica a possibilidade de conversão. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, **bool**\> [CanCast](./cancast/)(Source) | Verifica a possibilidade de conversão. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, **bool**\> [CanCast](./cancast/)(Source) | Verifica a possibilidade de conversão. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, **bool**\> [CanCast](./cancast/)(Source) | Verifica a possibilidade de conversão. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, **bool**\> [CanCast](./cancast/)(Source) | Verifica a possibilidade de conversão. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, **bool**\> [CanCast](./cancast/)(Source) | Verifica a possibilidade de conversão. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, **bool**\> [CanCast](./cancast/)(Source) | Verifica a possibilidade de conversão. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, **bool**\> [CanCast](./cancast/)(Source) | Verifica a possibilidade de conversão. |