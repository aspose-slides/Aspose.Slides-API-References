---
title: Remove()
second_title: Referência da API Aspose.Slides para C++
description: Remove a primeira ocorrência de uma fonte FallBack específica da lista.
type: docs
weight: 118
url: /pt/aspose.slides/fontfallbackrule/remove/
---
## FontFallBackRule::Remove(System::String) método


Remove a primeira ocorrência de uma fonte FallBack específica da lista.

```cpp
void Aspose::Slides::FontFallBackRule::Remove(System::String fontName) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | O nome da fonte a ser removido da lista. |
## Observações



```cpp
// Cria uma regra que contém uma lista de fontes.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Remove Tahoma da lista.
newRule->Remove(u"Tahoma");
```


## Ver Também

* Classe [String](../../../system/string/)
* Classe [FontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)