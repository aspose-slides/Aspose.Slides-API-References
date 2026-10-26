---
title: GetColumnAlignment()
second_title: Aspose.Slides per C++ - Riferimento API
description: Ottieni l'allineamento orizzontale della colonna specificata
type: docs
weight: 235
url: /it/aspose.slides.mathtext/imathmatrix/getcolumnalignment/
---
## IMathMatrix::GetColumnAlignment(int32_t) metodo


Ottieni l'allineamento orizzontale della colonna specificata

```cpp
virtual MathHorizontalAlignment Aspose::Slides::MathText::IMathMatrix::GetColumnAlignment(int32_t columnIndex)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| columnIndex | **int32_t** | Indice di colonna basato su zero |

### Valore di ritorno

Allineamento orizzontale della colonna specificata
## Osservazioni



Esempio: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## Vedi anche

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Classe [IMathMatrix](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)