---
title: ToArray()
second_title: Referência da API Aspose.Slides para C++
description: Cria e retorna um array com todas as fontes FallBack para esta regra.
type: docs
weight: 144
url: /pt/aspose.slides/fontfallbackrule/toarray/
---
## FontFallBackRule::ToArray() método

Cria e retorna um array com todas as fontes FallBack para esta regra.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray() override
```

### Valor de Retorno

Array de [System::String](../../../system/string/)
## Observações

```cpp
// Crie uma regra que contém uma lista de fontes.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Obtenha todos os nomes de fontes como array.
ArrayPtr<String> fontNames = newRule->ToArray();
```

## FontFallBackRule::ToArray(int32_t, int32_t) método

Cria e retorna um array com todas as fontes FallBack do intervalo especificado na lista.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray(int32_t startIndex, int32_t count) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| startIndex | **int32_t** | Um índice da primeira fonte a ser adicionada. |
| count | **int32_t** | Um número de fontes a ser adicionada. |

### Valor de Retorno

Array de [System::String](../../../system/string/)
## Observações

```cpp
// Crie uma regra que contém uma lista de fontes.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Obtenha os dois últimos nomes de fonte como array.
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [FontFallBackRule](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)