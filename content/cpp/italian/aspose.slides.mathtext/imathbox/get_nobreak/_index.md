---
title: get_NoBreak()
second_title: Riferimento API di Aspose.Slides per C++
description: "Nessuna interruzione. Questa proprietà specifica la proprietà \"unbreakable\" sull'oggetto box. Quando true, non possono verificarsi interruzioni di riga all'interno del box. Questo può essere importante per gli emulatori di operatori che consistono di più di un operatore binario. Quando questo elemento non è specificato, le interruzioni possono verificarsi all'interno del box. Predefinito: true"
type: docs
weight: 40
url: /it/aspose.slides.mathtext/imathbox/get_nobreak/
---
## IMathBox::get_NoBreak() metodo


Nessuna interruzione. Questa proprietà specifica la proprietà \"unbreakable\" sull'oggetto box. Quando true, non possono verificarsi interruzioni di riga all'interno del box. Questo può essere importante per gli emulatori di operatori che consistono di più di un operatore binario. Quando questo elemento non è specificato, le interruzioni possono verificarsi all'interno del box. Predefinito: true

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_NoBreak()=0
```

## Osservazioni


Esempio: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## Vedi anche

* Classe [IMathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)