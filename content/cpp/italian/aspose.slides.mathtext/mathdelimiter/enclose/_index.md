---
title: Enclose()
second_title: Riferimento API di Aspose.Slides per C++
description: Racchiude un elemento matematico nei caratteri specificati, come le parentesi o altri caratteri di inquadratura
type: docs
weight: 170
url: /it/aspose.slides.mathtext/mathdelimiter/enclose/
---
## MathDelimiter::Enclose(char16_t, char16_t) metodo

Racchiude un elemento matematico nei caratteri specificati, come le parentesi o altri caratteri di inquadratura

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathDelimiter::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char16_t | Carattere iniziale (di solito parentesi sinistra) |
| endingCharacter | char16_t | Carattere finale (di solito parentesi destra) |

### Valore di ritorno

Se *beginningCharacter* e *endingCharacter* sono null, le proprietà corrispondenti ricevono solo valori e non viene creato un nuovo oggetto (restituisce questa istanza). Altrimenti, restituisce un nuovo elemento matematico di tipo Delimiter che include i caratteri specificati come cornice e questa istanza di [MathDelimiter](../) incorniciata all'interno.

## Osservazioni



Esempio: 
```cpp
auto innerDelimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u",y"))->Enclose(u'{', u'}');
auto outerDelimiter = innerDelimiter->Enclose(u'[', u']');
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathDelimiter](../../imathdelimiter/)
* Classe [MathDelimiter](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)