---
title: Enclose()
second_title: Aspose.Slides för C++ API-referens
description: Innesluter ett matematiskt element i angivna tecken såsom parenteser eller andra tecken som ram
type: docs
weight: 170
url: /sv/aspose.slides.mathtext/mathdelimiter/enclose/
---
## MathDelimiter::Enclose(char16_t, char16_t) metod


Innesluter ett matematiskt element i angivna tecken såsom parenteser eller andra tecken som ram

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathDelimiter::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| beginningCharacter | char16_t | Inledande tecken (vanligtvis vänster hakparentes) |
| endingCharacter | char16_t | Avslutande tecken (vanligtvis höger hakparentes) |

### Returvärde

Om *beginningCharacter* och *endingCharacter* är null, tilldelas motsvarande egenskaper bara värden och inget nytt objekt skapas (returnerar detta objekt). Annars returneras ett nytt matematiskt element av typen Delimiter som inkluderar de angivna tecknen som ram och detta [MathDelimiter](../)-objekt inramat inuti.

## Anmärkningar



Exempel:
```cpp
auto innerDelimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u",y"))->Enclose(u'{', u'}');
auto outerDelimiter = innerDelimiter->Enclose(u'[', u']');
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathDelimiter](../../imathdelimiter/)
* Klass [MathDelimiter](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)