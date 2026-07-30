---
title: Accent()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta un segno diacritico (un carattere sopra questo elemento)
type: docs
weight: 209
url: /it/aspose.slides.mathtext/imathelement/accent/
---
## IMathElement::Accent(char16_t) metodo


Imposta un segno diacritico (un carattere sopra questo elemento)

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathElement::Accent(char16_t accentCharacter)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| accentCharacter | char16_t | Carattere di accento. Il valore deve essere compreso nell'intervallo (U+0300\\u2013U+036F) o (U+20D0\\u2013U+20EF) |

### Valore di ritorno

Nuova istanza del tipo [IMathAccent](../../imathaccent/)
## Osservazioni



Esempio: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathAccent](../../imathaccent/)
* Classe [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)