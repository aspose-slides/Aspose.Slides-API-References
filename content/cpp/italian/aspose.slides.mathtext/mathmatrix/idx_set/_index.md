---
title: idx_set()
second_title: Riferimento API di Aspose.Slides per C++
description: Elemento della matrice
type: docs
weight: 222
url: /it/aspose.slides.mathtext/mathmatrix/idx_set/
---
## MathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) metodo


Elemento della matrice

```cpp
void Aspose::Slides::MathText::MathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| row | **int32_t** | L'indice base zero della riga da cui ottenere l'elemento |
| column | **int32_t** | L'indice base zero della colonna da cui ottenere l'elemento |
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
* Classe [MathMatrix](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)