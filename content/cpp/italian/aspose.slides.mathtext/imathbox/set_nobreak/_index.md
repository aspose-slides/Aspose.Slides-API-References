---
title: set_NoBreak()
second_title: Riferimento API di Aspose.Slides per C++
description: "Nessuna interruzione. Questa proprietà specifica la proprietà \"unbreakable\" sulla casella dell'oggetto. Quando è true, nessuna interruzione di riga può verificarsi all'interno della casella. Ciò può essere importante per gli emulatori di operatori che consistono di più di un operatore binario. Quando questo elemento non è specificato, le interruzioni possono verificarsi all'interno della casella. Predefinito: true"
type: docs
weight: 53
url: /it/aspose.slides.mathtext/imathbox/set_nobreak/
---
## IMathBox::set_NoBreak(bool) metodo


Nessuna interruzione. Questa proprietà specifica la proprietà \"unbreakable\" sulla casella dell'oggetto. Quando è true, nessuna interruzione di riga può verificarsi all'interno della casella. Ciò può essere importante per gli emulatori di operatori che consistono di più di un operatore binario. Quando questo elemento non è specificato, le interruzioni possono verificarsi all'interno della casella. Predefinito: true

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_NoBreak(bool value)=0
```

## Note


Esempio: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## Vedi anche

* Classe [IMathBox](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)