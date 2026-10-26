---
title: get_ExplicitBreak()
second_title: Riferimento API Aspose.Slides per C++
description: "Interruzione esplicita specifica se c'è un'interruzione di riga all'inizio dell'oggetto Box, in modo che la riga venga avvolta all'inizio dell'oggetto box. Specifica il numero dell'operatore nella riga precedente di testo matematico che deve essere usato come punto di allineamento per la riga corrente di testo matematico. Valori possibili: 1..255 Predefinito: 0 (nessuna interruzione esplicita)"
type: docs
weight: 118
url: /it/aspose.slides.mathtext/mathbox/get_explicitbreak/
---
## MathBox::get_ExplicitBreak() metodo

Interruzione esplicita specifica se esiste un'interruzione di riga all'inizio dell'oggetto Box, in modo che la riga venga avvolta all'inizio dell'oggetto box. Specifica il numero dell'operatore nella riga precedente di testo matematico che deve essere usato come punto di allineamento per la riga corrente di testo matematico. Valori possibili: 1..255 Predefinito: 0 (nessuna interruzione esplicita)

```cpp
uint8_t Aspose::Slides::MathText::MathBox::get_ExplicitBreak() override
```

## Osservazioni

Esempio:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Vedi anche

* Classe [MathBox](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)