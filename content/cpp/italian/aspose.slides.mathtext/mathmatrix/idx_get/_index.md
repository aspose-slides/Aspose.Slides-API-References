---
title: idx_get()
second_title: Riferimento API Aspose.Slides per C++
description: Elemento della matrice
type: docs
weight: 209
url: /it/aspose.slides.mathtext/mathmatrix/idx_get/
---
## MathMatrix::idx_get(int32_t, int32_t) metodo


Elemento della matrice

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathMatrix::idx_get(int32_t row, int32_t column) override
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| row | **int32_t** | L'indice basato su zero della riga da cui ottenere l'elemento |
| column | **int32_t** | L'indice basato su zero della colonna da cui ottenere l'elemento |

### Valore di ritorno


## Note



Esempio: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathMatrix](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)