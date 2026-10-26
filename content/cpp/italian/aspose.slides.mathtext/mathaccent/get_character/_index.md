---
title: get_Character()
second_title: Riferimento API di Aspose.Slides per C++
description: "Carattere di accento Il valore deve essere compreso nell'intervallo (U+0300\\u2013U+036F) o(U+20D0\\u2013U+20EF) Valore predefinito: Accento circonflesso combinante (U+0302)"
type: docs
weight: 14
url: /it/aspose.slides.mathtext/mathaccent/get_character/
---
## MathAccent::get_Character() metodo


Carattere di accento Il valore deve essere compreso nell'intervallo (U+0300\\u2013U+036F) o (U+20D0\\u2013U+20EF) Valore predefinito: Accento circonflesso combinante (U+0302)

```cpp
char16_t Aspose::Slides::MathText::MathAccent::get_Character() override
```

## Osservazioni


Esempio: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Vedi anche

* Classe [MathAccent](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)