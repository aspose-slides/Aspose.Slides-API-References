---
title: set_ExplicitBreak()
second_title: Aspose.Slides per C++ Riferimento API
description: "L'interruzione esplicita indica se esiste un'interruzione di riga all'inizio dell'oggetto Box, in modo che la riga vada a capo all'inizio dell'oggetto box. Specifica il numero dell'operatore nella riga precedente del testo matematico che deve essere usato come punto di allineamento per la riga corrente del testo matematico. Valori possibili: 1..255 Predefinito: 0 (nessuna interruzione esplicita)"
type: docs
weight: 131
url: /it/aspose.slides.mathtext/mathbox/set_explicitbreak/
---
## MathBox::set_ExplicitBreak(uint8_t) metodo


L'interruzione esplicita indica se esiste un'interruzione di riga all'inizio dell'oggetto Box, in modo che la riga vada a capo all'inizio dell'oggetto box. Specifica il numero dell'operatore nella riga precedente del testo matematico che deve essere usato come punto di allineamento per la riga corrente del testo matematico. Valori possibili: 1..255 Predefinito: 0 (nessuna interruzione esplicita)

```cpp
void Aspose::Slides::MathText::MathBox::set_ExplicitBreak(uint8_t value) override
```

## Note


Esempio: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Vedi anche

* Classe [MathBox](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)