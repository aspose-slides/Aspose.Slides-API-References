---
title: Enclose()
second_title: Riferimento API di Aspose.Slides per C++
description: Racchiude un elemento matematico tra parentesi
type: docs
weight: 40
url: /it/aspose.slides.mathtext/imathelement/enclose/
---
## IMathElement::Enclose() metodo


Racchiude un elemento matematico tra parentesi

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose()=0
```


### Valore restituito

L'elemento matematico di tipo [IMathDelimiter](../../imathdelimiter/) che include le parentesi
## Osservazioni



Esempio: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## IMathElement::Enclose(char16_t, char16_t) metodo


Racchiude questo elemento nei caratteri specificati, come parentesi o altri caratteri come cornice

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose(char16_t beginningCharacter, char16_t endingCharacter)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| beginningCharacter | char16_t | Carattere iniziale (solitamente parentesi sinistra) |
| endingCharacter | char16_t | Carattere finale (solitamente parentesi destra) |

### Valore restituito

L'elemento matematico di tipo [IMathDelimiter](../../imathdelimiter/) che include i caratteri specificati come cornice
## Osservazioni



Esempio: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathDelimiter](../../imathdelimiter/)
* Classe [IMathElement](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)