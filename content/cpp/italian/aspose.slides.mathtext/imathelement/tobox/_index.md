---
title: ToBox()
second_title: Riferimento API di Aspose.Slides per C++
description: Posiziona questo elemento in una scatola non visiva (raggruppamento logico) utilizzata per raggruppare i componenti di un'equazione o di un'altra istanza di testo matematico. Un oggetto incassato può (ad esempio) fungere da emulatore di operatore con o senza punto di allineamento, servire come punto di interruzione di riga o essere raggruppato in modo da non consentire interruzioni di riga all'interno.
type: docs
weight: 274
url: /it/aspose.slides.mathtext/imathelement/tobox/
---
## IMathElement::ToBox() metodo

Posiziona questo elemento in una scatola non visiva (raggruppamento logico) che viene usata per raggruppare i componenti di un'equazione o di un'altra istanza di testo matematico. Un oggetto incassato può (ad esempio) fungere da emulatore di operatore con o senza punto di allineamento, servire come punto di interruzione di riga o essere raggruppato in modo da non consentire interruzioni di riga all'interno.

```cpp
virtual System::SharedPtr<IMathBox> Aspose::Slides::MathText::IMathElement::ToBox()=0
```

### Valore di ritorno

Scatola logica con questo elemento posizionato all'interno

## Osservazioni

Esempio:
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBox](../../imathbox/)
* Classe [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)