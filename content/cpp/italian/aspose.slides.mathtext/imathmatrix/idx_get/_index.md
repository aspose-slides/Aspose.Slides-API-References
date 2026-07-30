---
title: idx_get()
second_title: Riferimento API di Aspose.Slides per C++
description: Elementi della matrice
type: docs
weight: 209
url: /it/aspose.slides.mathtext/imathmatrix/idx_get/
---
## IMathMatrix::idx_get(int32_t, int32_t) method


Elementi della matrice

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathMatrix::idx_get(int32_t row, int32_t column)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| row | **int32_t** | L'indice base-zero della riga da cui ottenere l'elemento |
| column | **int32_t** | L'indice base-zero della colonna da cui ottenere l'elemento |

### Valore di ritorno


## Osservazioni



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