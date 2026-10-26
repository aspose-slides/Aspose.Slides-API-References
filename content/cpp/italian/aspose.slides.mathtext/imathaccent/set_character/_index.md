---
title: set_Character()
second_title: Riferimento API di Aspose.Slides per C++
description: "Carattere di accento Il valore deve essere compreso nell'intervallo (U+0300\\u2013U+036F) o(U+20D0\\u2013U+20EF) Valore predefinito: Combining Circumflex Accent (U+0302)"
type: docs
weight: 27
url: /it/aspose.slides.mathtext/imathaccent/set_character/
---
## IMathAccent::set_Character(char16_t) metodo

Carattere di accento Il valore deve essere compreso nell'intervallo (U+0300\\u2013U+036F) o(U+20D0\\u2013U+20EF) Valore predefinito: Combining Circumflex Accent (U+0302)

```cpp
virtual void Aspose::Slides::MathText::IMathAccent::set_Character(char16_t value)=0
```

## Osservazioni

Esempio: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Vedi anche

* Classe [IMathAccent](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)