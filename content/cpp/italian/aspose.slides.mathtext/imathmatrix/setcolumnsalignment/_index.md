---
title: SetColumnsAlignment()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta l'allineamento orizzontale delle colonne specificate
type: docs
weight: 261
url: /it/aspose.slides.mathtext/imathmatrix/setcolumnsalignment/
---
## IMathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) method


Imposta l'allineamento orizzontale delle colonne specificate

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| columnIndex | **int32_t** | Indice base zero della prima colonna a cui impostare l'allineamento |
| columnsCount | **uint32_t** | Il numero di colonne per cui specificare l'allineamento |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Nuovo valore dell'allineamento orizzontale della colonna specificata |
## Osservazioni



Esempio: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## Vedi anche

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Classe [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)