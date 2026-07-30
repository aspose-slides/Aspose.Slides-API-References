---
title: Enclose()
second_title: Riferimento API di Aspose.Slides per C++
description: Racchiude gli elementi figli di questo blocco nei caratteri specificati, come parentesi o altri, come inquadratura e li delimita con un carattere separatore
type: docs
weight: 14
url: /it/aspose.slides.mathtext/imathblock/enclose/
---
## IMathBlock::Enclose(char16_t, char16_t, char16_t) metodo

Racchiude gli elementi figli di questo blocco nei caratteri specificati, come parentesi o altri, come inquadratura e li delimita con un carattere separatore

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| beginningCharacter | char16_t | Carattere iniziale (di solito parentesi sinistra) |
| endingCharacter | char16_t | Carattere finale (di solito parentesi destra) |
| separatorCharacter | char16_t | Carattere separatore |

### Valore di ritorno

L'elemento matematico di tipo [IMathDelimiter](../../imathdelimiter/) che include i caratteri specificati come inquadratura e delimitatore

## Osservazioni



Esempio: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathDelimiter](../../imathdelimiter/)
* Classe [IMathBlock](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)