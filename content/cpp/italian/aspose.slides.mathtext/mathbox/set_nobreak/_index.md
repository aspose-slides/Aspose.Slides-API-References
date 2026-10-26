---
title: set_NoBreak()
second_title: Riferimento API Aspose.Slides per C++
description: "Nessuna interruzione Questa proprietà specifica la proprietà \"unbreakable\" sull'oggetto box. Quando è true, nessuna interruzione di riga può verificarsi all'interno del box. Questo può essere importante per gli emulatori di operatori che consistono di più di un operatore binario. Quando questo elemento non è specificato, le interruzioni possono verificarsi all'interno del box. Predefinito: true"
type: docs
weight: 53
url: /it/aspose.slides.mathtext/mathbox/set_nobreak/
---
## MathBox::set_NoBreak(bool) metodo


Nessuna interruzione Questa proprietà specifica la proprietà \"unbreakable\" sull'oggetto box. Quando è true, nessuna interruzione di riga può verificarsi all'interno del box. Questo può essere importante per gli emulatori di operatori che consistono di più di un operatore binario. Quando questo elemento non è specificato, le interruzioni possono verificarsi all'interno del box. Predefinito: true

```cpp
void Aspose::Slides::MathText::MathBox::set_NoBreak(bool value) override
```

## Osservazioni


Esempio: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## Vedi anche

* Classe [MathBox](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)