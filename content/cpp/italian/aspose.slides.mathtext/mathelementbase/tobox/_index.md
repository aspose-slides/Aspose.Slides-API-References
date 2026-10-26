---
title: ToBox()
second_title: Riferimento API di Aspose.Slides per C++
description: Posiziona questo elemento in una scatola non visiva (raggruppamento logico) che viene utilizzata per raggruppare componenti di un'equazione o di un'altra istanza di testo matematico. Un oggetto incapsulato può (ad esempio) fungere da emulatore di operatore con o senza un punto di allineamento, fungere da punto di interruzione di riga, o essere raggruppato in modo da non consentire interruzioni di riga all'interno.
type: docs
weight: 261
url: /it/aspose.slides.mathtext/mathelementbase/tobox/
---
## MathElementBase::ToBox() metodo

Posiziona questo elemento in una scatola non visiva (raggruppamento logico) che viene usata per raggruppare componenti di un'equazione o di un'altra istanza di testo matematico. Un oggetto incastrato può (ad esempio) servire come emulatore di operatore con o senza un punto di allineamento, servire come punto di interruzione di riga, o essere raggruppato in modo da non consentire interruzioni di riga all'interno.

```cpp
System::SharedPtr<IMathBox> Aspose::Slides::MathText::MathElementBase::ToBox() override
```

### Valore di ritorno

Scatola logica con questo elemento posizionato all'interno
## Osservazioni



Esempio: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## Vedere anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBox](../../imathbox/)
* Classe [MathElementBase](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)