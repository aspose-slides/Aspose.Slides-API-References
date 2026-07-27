---
title: IndexOf()
second_title: Referência da API Aspose.Slides for C++
description: Retorna um índice da regra especificada na coleção.
type: docs
weight: 118
url: /pt/aspose.slides/ifontfallbackrule/indexof/
---
## IFontFallBackRule::IndexOf(System::String) método


Retorna um índice da regra especificada na coleção.

```cpp
virtual int32_t Aspose::Slides::IFontFallBackRule::IndexOf(System::String fontName)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Nome da fonte a ser encontrada. |

### Valor de Retorno

Índice de uma fonte ou -1 se a fonte não for encontrada na lista.
## Observações



```cpp
// Cria uma regra que contém uma lista de fontes.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Obtenha o índice de Tahoma
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```


## Veja Também

* Classe [String](../../../system/string/)
* Classe [IFontFallBackRule](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)