---
title: get_HideBottom()
second_title: Riferimento API di Aspose.Slides per C++
description: Nascondi il bordo inferiore (predefinito è false) - specifica lo stato nascosto o mostrato del bordo inferiore della casella del bordo.
type: docs
weight: 40
url: /it/aspose.slides.mathtext/imathborderbox/get_hidebottom/
---
## IMathBorderBox::get_HideBottom() metodo


Nascondi il bordo inferiore (il valore predefinito è false) - specifica lo stato nascosto o mostrato del bordo inferiore della casella del bordo.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_HideBottom()=0
```

## Osservazioni


Esempio: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideBottom(true);
```

## Vedi anche

* Classe [IMathBorderBox](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)