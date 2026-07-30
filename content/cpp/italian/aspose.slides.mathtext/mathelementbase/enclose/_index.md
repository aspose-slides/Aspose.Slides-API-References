---
title: Enclose()
second_title: Riferimento API di Aspose.Slides per C++
description: Racchiude un elemento matematico tra parentesi
type: docs
weight: 27
url: /it/aspose.slides.mathtext/mathelementbase/enclose/
---
## MathElementBase::Enclose() metodo


Racchiude un elemento matematico tra parentesi

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose() override
```


### Valore di ritorno

L'elemento matematico di tipo [IMathDelimiter](../../imathdelimiter/) che include le parentesi
## Note



Esempio: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## MathElementBase::Enclose(char16_t, char16_t) metodo


Racchiude un elemento matematico nei caratteri specificati, come le parentesi o altri caratteri, come cornice

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| beginningCharacter | char16_t | Carattere iniziale (di solito parentesi sinistra) |
| endingCharacter | char16_t | Carattere finale (di solito parentesi destra) |

### Valore di ritorno

L'elemento matematico di tipo [IMathDelimiter](../../imathdelimiter/) che include i caratteri specificati come cornice
## Note



Esempio: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathDelimiter](../../imathdelimiter/)
* Classe [MathElementBase](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)