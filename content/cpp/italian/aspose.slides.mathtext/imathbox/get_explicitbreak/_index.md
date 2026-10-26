---
title: get_ExplicitBreak()
second_title: Riferimento API Aspose.Slides per C++
description: "Explicit break indica se esiste un'interruzione di riga all'inizio dell'oggetto Box, in modo che la riga vada a capo all'inizio dell'oggetto box. Specifica il numero dell'operatore nella riga precedente del testo matematico che deve essere usato come punto di allineamento per la riga corrente del testo matematico valori possibili: 1..255 Predefinito: 0 (nessuna interruzione esplicita)"
type: docs
weight: 118
url: /it/aspose.slides.mathtext/imathbox/get_explicitbreak/
---
## IMathBox::get_ExplicitBreak() metodo

Explicit break indica se esiste un’interruzione di riga all’inizio dell’oggetto Box, in modo che la riga torni all’inizio dell’oggetto Box. Specifica il numero dell’operatore nella riga precedente del testo matematico che deve essere usato come punto di allineamento per la riga corrente del testo matematico valori possibili: 1..255 Predefinito: 0 (nessuna interruzione esplicita)

```cpp
virtual uint8_t Aspose::Slides::MathText::IMathBox::get_ExplicitBreak()=0
```

## Osservazioni

Esempio:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Vedi anche

* Classe [IMathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)