---
title: FontFallBackRule()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma nova instância.
type: docs
weight: 66
url: /pt/aspose.slides/fontfallbackrule/fontfallbackrule/
---
## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::String) construtor


Cria uma nova instância.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::String fontNames)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| startIndex | **uint32_t** | Índice inicial do intervalo unicode |
| endIndex | **uint32_t** | Índice final do intervalo unicode |
| fontNames | [System::String](../../../system/string/) | Nome ou nomes da fonte (separados por vírgula) para FallBack |
## Observações



```cpp
// Cria nova instância de FantFallBackRule com uma fonte.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
// Cria nova instância de FantFallBackRule com várias fontes.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma");
```


## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::ArrayPtr\<System::String\>) construtor


Cria uma nova instância.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::ArrayPtr<System::String> fontNames)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| startIndex | **uint32_t** | Índice inicial do intervalo unicode |
| endIndex | **uint32_t** | Índice final do intervalo unicode |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Nome ou nomes da fonte (separados por vírgula) para FallBack |
## Observações



```cpp
// Cria nova instância de FantFallBackRule com duas fontes
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Mincho", u"MS Gothic"}));
// Cria nova instância de FantFallBackRule com várias fontes.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```


## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [FontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)