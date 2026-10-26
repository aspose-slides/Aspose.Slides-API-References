---
title: idx_set()
second_title: Riferimento API Aspose.Slides per C++
description: Elementi della matrice
type: docs
weight: 222
url: /it/aspose.slides.mathtext/imathmatrix/idx_set/
---
## IMathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) metodo

Elementi della matrice

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| row | **int32_t** | L'indice basato su zero della riga da cui ottenere l'elemento |
| column | **int32_t** | L'indice basato su zero della colonna da cui ottenere l'elemento |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> |  |

## Note

Esempio:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathMatrix](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)