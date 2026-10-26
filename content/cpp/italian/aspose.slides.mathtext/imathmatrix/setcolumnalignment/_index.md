---
title: SetColumnAlignment()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta l'allineamento orizzontale della colonna specificata
type: docs
weight: 248
url: /it/aspose.slides.mathtext/imathmatrix/setcolumnalignment/
---
## IMathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) metodo

Imposta l'allineamento orizzontale della colonna specificata

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| columnIndex | **int32_t** | Indice della colonna basato su zero |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Nuovo valore dell'allineamento orizzontale della colonna specificata |
## Osservazioni



Esempio: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## Vedi anche

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Classe [IMathMatrix](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)