---
title: MathPhantom()
second_title: Riferimento API di Aspose.Slides per C++
description: Inizializza una nuova istanza della classe MathPhantom utilizzando l'elemento matematico di base specificato.
type: docs
weight: 144
url: /it/aspose.slides.mathtext/mathphantom/mathphantom/
---
## MathPhantom::MathPhantom(System::SharedPtr\<IMathElement\>) costruttore


Inizializza una nuova istanza della classe [MathPhantom](../) utilizzando l'elemento matematico di base specificato.

```cpp
Aspose::Slides::MathText::MathPhantom::MathPhantom(System::SharedPtr<IMathElement> element)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Il [IMathElement](../../imathelement/) di base la cui visibilità e layout saranno controllati dal fantasma. Questo elemento definisce il contenuto che può essere nascosto o mostrato, influenzando comunque l'allineamento geometrico della matematica circostante. |
## Osservazioni



L'elemento fantasma è usato per riservare o sopprimere lo spazio visivo della sua espressione di base senza necessariamente visualizzarlo. Corrisponde all'elemento OMML **<m:phant>**. 

Esempio: 
```cpp
System::SharedPtr<IMathElement> fraction = System::MakeObject<MathFraction>(
    System::MakeObject<MathematicalText>(u"1"),
    System::MakeObject<MathematicalText>(u"2"));
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathPhantom](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)