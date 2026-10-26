---
title: idx_get()
second_title: Referência da API Aspose.Slides para C++
description: Obtém IMathElement no índice especificado.
type: docs
weight: 27
url: /pt/aspose.slides.mathtext/mathblock/idx_get/
---
## MathBlock::idx_get(int32_t) método


Obtém [IMathElement](../../imathelement/) no índice especificado.

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBlock::idx_get(int32_t index) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero do item |

### Valor de Retorno

O elemento matemático.
## Observações



Example: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)