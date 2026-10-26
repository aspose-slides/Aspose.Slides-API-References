---
title: set_Character()
second_title: Aspose.Slides per la documentazione API C++
description: "Carattere di accento Il valore deve trovarsi nell'intervallo (U+0300\\u2013U+036F) o(U+20D0\\u2013U+20EF) Valore predefinito: Accento circonflesso combinante (U+0302)"
type: docs
weight: 27
url: /it/aspose.slides.mathtext/mathaccent/set_character/
---
## MathAccent::set_Character(char16_t) metodo


Carattere di accento Il valore deve trovarsi nell'intervallo di (U+0300\\u2013U+036F) o(U+20D0\\u2013U+20EF) Valore predefinito: Accento circonflesso combinante (U+0302)

```cpp
void Aspose::Slides::MathText::MathAccent::set_Character(char16_t value) override
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