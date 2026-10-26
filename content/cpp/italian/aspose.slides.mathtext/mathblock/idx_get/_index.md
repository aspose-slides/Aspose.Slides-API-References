---
title: idx_get()
second_title: Aspose.Slides per C++ Riferimento API
description: Ottiene IMathElement all'indice specificato.
type: docs
weight: 27
url: /it/aspose.slides.mathtext/mathblock/idx_get/
---
## MathBlock::idx_get(int32_t) metodo


Ottiene [IMathElement](../../imathelement/) all'indice specificato.

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBlock::idx_get(int32_t index) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero dell'elemento |

### Valore di ritorno

L'elemento matematico.
## Osservazioni



Esempio: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)