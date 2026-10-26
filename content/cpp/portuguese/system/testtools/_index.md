---
title: TestTools
second_title: Referência da API Aspose.Slides para C++
description: Fornece um conjunto de métodos úteis que verificam algumas propriedades básicas de diferentes tipos e funções.
type: docs
weight: 1925
url: /pt/system/testtools/
---
## TestTools struct

Fornece um conjunto de métodos úteis que verificam algumas propriedades básicas de diferentes tipos e funções.

```cpp
class TestTools
```

## Métodos

| Método | Descrição |
| --- | --- |
| static **bool** [AssertThrows](./assertthrows/)(const std::function\<void()>\&) | Verifica se a função lança exceção de qualquer tipo. |
| static **bool** [IsEmpty](./isempty/)(const [System::String](../string/)\&) | Verifica se a string está vazia. |
| static **bool** [IsEmpty](./isempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Verifica se a coleção está vazia. |
| static std::enable_if\<std::is_arithmetic\<T\>::value||std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(T) | Verifica se o valor específico é null. [Version](../version/) para tipos aritméticos e enum. |
| static std::enable_if<\!std::is_arithmetic\<T\>::value\&&\!std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(const T\&) | Verifica se o valor específico é null. [Version](../version/) para tipos de valor não aritméticos e não enum. |
| static **bool** [IsNull](./isnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Verifica se o valor específico é null. [Version](../version/) para tipos de valor não aritméticos. |
| static **bool** [IsNull](./isnull/)([System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<K, V\>\&) | Verifica se o valor específico é null. [Version](../version/) para pares chave-valor. |
| static **bool** [IsNull](./isnull/)(const [System::String](../string/)\&) | Verifica se a string é null. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Verifica se a coleção é null ou vazia. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [System::String](../string/)\&) | Verifica se a string é null ou vazia. |
## Veja Também

* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)