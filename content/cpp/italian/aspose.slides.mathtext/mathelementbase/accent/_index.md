---
title: Accent()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta un segno di accento (un carattere sopra questo elemento)
type: docs
weight: 196
url: /it/aspose.slides.mathtext/mathelementbase/accent/
---
## MathElementBase::Accent(char16_t) metodo

Imposta un segno di accento (un carattere sopra questo elemento)

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathElementBase::Accent(char16_t accentCharacter) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| accentCharacter | char16_t | Carattere di accento. Il valore dovrebbe essere nell'intervallo (U+0300\\u2013U+036F) o (U+20D0\\u2013U+20EF) |

### Valore restituito

Nuova istanza di tipo [IMathAccent](../../imathaccent/)
## Osservazioni

Esempio: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathAccent](../../imathaccent/)
* Classe [MathElementBase](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)