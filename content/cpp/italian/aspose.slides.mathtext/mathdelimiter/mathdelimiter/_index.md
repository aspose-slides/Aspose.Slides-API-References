---
title: MathDelimiter()
second_title: Riferimento API di Aspose.Slides per C++
description: Inizializza MathDelimiter con l'elemento specificato come unico argomento di base
type: docs
weight: 144
url: /it/aspose.slides.mathtext/mathdelimiter/mathdelimiter/
---
## MathDelimiter::MathDelimiter(System::SharedPtr\<IMathElement\>) costruttore

Inizializza [MathDelimiter](../) con l'elemento specificato come unico argomento di base

```cpp
Aspose::Slides::MathText::MathDelimiter::MathDelimiter(System::SharedPtr<IMathElement> element)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | L'elemento base a cui viene applicato il delimitatore. Può essere null. |
## Osservazioni



Esempio: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = System::MakeObject<MathDelimiter>(element);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathDelimiter](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)