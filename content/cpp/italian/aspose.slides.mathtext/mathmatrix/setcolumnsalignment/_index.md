---
title: SetColumnsAlignment()
second_title: Riferimento API Aspose.Slides per C++
description: Imposta l'allineamento orizzontale delle colonne specificate
type: docs
weight: 274
url: /it/aspose.slides.mathtext/mathmatrix/setcolumnsalignment/
---
## MathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) metodo

Imposta l'allineamento orizzontale delle colonne specificate

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| columnIndex | **int32_t** | Indice a base zero della prima colonna per impostare l'allineamento |
| columnsCount | **uint32_t** | Il numero di colonne per specificare l'allineamento |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Nuovo valore dell'allineamento orizzontale della colonna specificata |
## Osservazioni



Esempio: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## Vedi anche

* Enumerazione [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Classe [MathMatrix](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)