---
title: Remove()
second_title: Referência da API Aspose.Slides para C++
description: Remove a primeira ocorrência de uma fonte FallBack específica da lista.
type: docs
weight: 79
url: /pt/aspose.slides/ifontfallbackrule/remove/
---
## IFontFallBackRule::Remove(System::String) método


Remove a primeira ocorrência de uma fonte FallBack específica da lista.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::Remove(System::String fontName)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | O nome da fonte a ser removido da lista. |
## Observações



```cpp
// Cria uma regra que contém uma lista de fontes.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Removendo Tahoma da lista
newRule->Remove(u"Tahoma");
```


## Veja Também

* Classe [String](../../../system/string/)
* Classe [IFontFallBackRule](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)