---
title: RemoveAt()
second_title: Referência da API Aspose.Slides para C++
description: Remove a fonte FallBack no índice especificado da lista.
type: docs
weight: 131
url: /pt/aspose.slides/fontfallbackrule/removeat/
---
## FontFallBackRule::RemoveAt(int32_t) método


Remove a fonte FallBack no índice especificado da lista.

```cpp
void Aspose::Slides::FontFallBackRule::RemoveAt(int32_t index) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero da fonte a ser removida. |
## Observações



```cpp
// Cria uma regra que contém uma lista de fontes.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Remove Tahoma da lista.
newRule->RemoveAt(2);
```


## Veja Também

* Classe [FontFallBackRule](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)