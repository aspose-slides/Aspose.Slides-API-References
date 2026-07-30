---
title: get_NoBreak()
second_title: Riferimento API di Aspose.Slides per C++
description: "Nessuna interruzione Questa proprietà specifica la proprietà \"unbreakable\" sul box dell'oggetto. Quando è true, non possono verificarsi interruzioni di riga all'interno del box. Questo può essere importante per gli emulatori di operatori che consistono in più di un operatore binario. Quando questo elemento non è specificato, le interruzioni possono verificarsi all'interno del box. Predefinito: true"
type: docs
weight: 40
url: /it/aspose.slides.mathtext/mathbox/get_nobreak/
---
## MathBox::get_NoBreak() metodo


Nessuna interruzione Questa proprietà specifica la proprietà \"unbreakable\" sul box dell'oggetto. Quando è true, non possono verificarsi interruzioni di riga all'interno del box. Questo può essere importante per gli emulatori di operatori che consistono in più di un operatore binario. Quando questo elemento non è specificato, le interruzioni possono verificarsi all'interno del box. Predefinito: true

```cpp
bool Aspose::Slides::MathText::MathBox::get_NoBreak() override
```

## Osservazioni


Esempio: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## Vedi anche

* Classe [MathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)