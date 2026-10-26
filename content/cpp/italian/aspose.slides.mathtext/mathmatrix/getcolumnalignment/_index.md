---
title: GetColumnAlignment()
second_title: Aspose.Slides per C++ Riferimento API
description: Ottiene l'allineamento orizzontale della colonna specificata
type: docs
weight: 248
url: /it/aspose.slides.mathtext/mathmatrix/getcolumnalignment/
---
## MathMatrix::GetColumnAlignment(int32_t) metodo


Ottiene l'allineamento orizzontale della colonna specificata

```cpp
MathHorizontalAlignment Aspose::Slides::MathText::MathMatrix::GetColumnAlignment(int32_t columnIndex) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| columnIndex | **int32_t** | Indice di colonna a base zero |

### Valore restituito

Allineamento orizzontale della colonna specificata
## Osservazioni



Esempio: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## Vedi anche

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Classe [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)