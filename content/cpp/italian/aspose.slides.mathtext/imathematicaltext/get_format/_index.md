---
title: get_Format()
second_title: Riferimento API di Aspose.Slides per C++
description: Proprietà di formattazione del testo
type: docs
weight: 27
url: /it/aspose.slides.mathtext/imathematicaltext/get_format/
---
## IMathematicalText::get_Format() metodo


Proprietà di formattazione del testo

```cpp
virtual System::SharedPtr<IPortionFormat> Aspose::Slides::MathText::IMathematicalText::get_Format()=0
```

## Osservazioni


Esempio: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
mathText->get_Format()->set_FontHeight(28.0f);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPortionFormat](../../../aspose.slides/iportionformat/)
* Classe [IMathematicalText](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)