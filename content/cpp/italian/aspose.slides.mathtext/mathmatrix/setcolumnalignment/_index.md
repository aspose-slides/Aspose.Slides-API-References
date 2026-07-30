---
title: SetColumnAlignment()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta l'allineamento orizzontale della colonna specificata
type: docs
weight: 261
url: /it/aspose.slides.mathtext/mathmatrix/setcolumnalignment/
---
## MathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) metodo


Imposta l'allineamento orizzontale della colonna specificata

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| columnIndex | **int32_t** | Indice di colonna a base zero |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Nuovo valore dell'allineamento orizzontale della colonna specificata |
## Osservazioni



Esempio: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## Vedi anche

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Classe [MathMatrix](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)