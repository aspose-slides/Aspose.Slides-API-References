---
title: set_ExplicitBreak()
second_title: Riferimento API Aspose.Slides per C++
description: "L'interruzione esplicita specifica se esiste un'interruzione di riga all'inizio dell'oggetto Box, in modo che la linea si avvolga all'inizio dell'oggetto Box. Specifica il numero dell'operatore sulla riga precedente di testo matematico che deve essere usato come punto di allineamento per la riga corrente di testo matematico valori possibili: 1..255 Predefinito: 0 (nessuna interruzione esplicita)"
type: docs
weight: 131
url: /it/aspose.slides.mathtext/imathbox/set_explicitbreak/
---
## IMathBox::set_ExplicitBreak(uint8_t) metodo

L'interruzione esplicita specifica se esiste un'interruzione di riga all'inizio dell'oggetto Box, in modo che la linea si avvolga all'inizio dell'oggetto Box. Specifica il numero dell'operatore sulla riga precedente di testo matematico che deve essere usato come punto di allineamento per la riga corrente di testo matematico valori possibili: 1..255 Predefinito: 0 (nessuna interruzione esplicita)

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_ExplicitBreak(uint8_t value)=0
```

## Osservazioni

Esempio: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Vedi anche

* Class [IMathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)