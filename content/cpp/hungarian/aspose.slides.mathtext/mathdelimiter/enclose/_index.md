---
title: Enclose()
second_title: Aspose.Slides C++ API referencia
description: Lezár egy matematikai elemet a megadott karakterekkel, például zárójelekkel vagy más karakterekkel keretként
type: docs
weight: 170
url: /hu/aspose.slides.mathtext/mathdelimiter/enclose/
---
## MathDelimiter::Enclose(char16_t, char16_t) metódus


Lezár egy matematikai elemet a megadott karakterekkel, például zárójelekkel vagy más karakterekkel keretként

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathDelimiter::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| beginningCharacter | char16_t | Kezdő karakter (általában bal zárójel) |
| endingCharacter | char16_t | Záró karakter (általában jobb zárójel) |

### Visszatérési érték

Ha a *beginningCharacter* és a *endingCharacter* null értékű, akkor a megfelelő tulajdonságok csak értékeket kapnak, és új objektum nem jön létre (visszaadja ezt a példányt). Egyébként egy új type Delimiter matematikai elemet ad vissza, amely a megadott karaktereket keretként tartalmazza, és ebben a [MathDelimiter](../) példányban van keretezve.
## Megjegyzések



Példa: 
```cpp
auto innerDelimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u",y"))->Enclose(u'{', u'}');
auto outerDelimiter = innerDelimiter->Enclose(u'[', u']');
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathDelimiter](../../imathdelimiter/)
* Osztály [MathDelimiter](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)