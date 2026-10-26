---
title: IndexOf()
second_title: Referência da API Aspose.Slides para C++
description: Retorna um índice da regra especificada na coleção.
type: docs
weight: 157
url: /pt/aspose.slides/fontfallbackrule/indexof/
---
## FontFallBackRule::IndexOf(System::String) método


Retorna um índice da regra especificada na coleção.

```cpp
int32_t Aspose::Slides::FontFallBackRule::IndexOf(System::String fontName) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Nome da fonte a ser encontrado. |

### Valor de Retorno

Índice de uma fonte ou -1 se a fonte não for encontrada na lista.
## Observações



```cpp
// Cria uma regra que contém uma lista de fontes.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Obtém o índice de Tahoma.
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```


## Veja Também

* Classe [String](../../../system/string/)
* Classe [FontFallBackRule](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)