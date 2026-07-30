---
title: Enclose()
second_title: Riferimento API di Aspose.Slides per C++
description: Racchiude gli elementi figlio di questo blocco nei caratteri specificati, come le parentesi o altri caratteri, come incorniciatura
type: docs
weight: 222
url: /it/aspose.slides.mathtext/mathblock/enclose/
---
## MathBlock::Enclose(char16_t, char16_t) metodo

Racchiude gli elementi figlio di questo blocco nei caratteri specificati, come le parentesi o altri caratteri, come incorniciatura

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| beginningCharacter | char16_t | Carattere iniziale (di solito parentesi sinistra) |
| endingCharacter | char16_t | Carattere finale (di solito parentesi destra) |

### Valore di ritorno

L'elemento matematico di tipo [IMathDelimiter](../../imathdelimiter/) che include i caratteri specificati come incorniciatura
## Osservazioni



Esempio: 
```cpp
auto block = System::MakeObject<MathematicalText>(u"x")->Join(u"+y");
auto delimiter = System::ExplicitCast<IMathElement>(block)->Enclose(u'[', u']');
```

## MathBlock::Enclose(char16_t, char16_t, char16_t) metodo

Racchiude gli elementi figlio di questo blocco nei caratteri specificati, come le parentesi o altri, come incorniciatura e delimita con un carattere separatore

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| beginningCharacter | char16_t | Carattere iniziale (di solito parentesi sinistra) |
| endingCharacter | char16_t | Carattere finale (di solito parentesi destra) |
| separatorCharacter | char16_t | Carattere di separazione |

### Valore di ritorno

L'elemento matematico di tipo [IMathDelimiter](../../imathdelimiter/) che include i caratteri specificati come incorniciatura e delimitatore
## Osservazioni



Esempio: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathDelimiter](../../imathdelimiter/)
* Classe [MathBlock](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)