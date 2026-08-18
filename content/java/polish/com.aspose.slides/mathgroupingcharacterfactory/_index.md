---
title: MathGroupingCharacterFactory
second_title: Aspose.Slides dla Java - odniesienie API
description: Umożliwia tworzenie znaku grupowania matematycznego
type: docs
url: /pl/com.aspose.slides/mathgroupingcharacterfactory/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathGroupingCharacterFactory](../../com.aspose.slides/imathgroupingcharacterfactory)
```
public class MathGroupingCharacterFactory implements IMathGroupingCharacterFactory
```

Pozwala utworzyć znak grupowania matematycznego

--------------------

Dla zgodności z COM
## Konstruktorzy

| Konstruktor | Opis |
| --- | --- |
| [MathGroupingCharacterFactory()](#MathGroupingCharacterFactory--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Tworzy znak grupowania matematycznego |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Tworzy znak grupowania matematycznego |
### MathGroupingCharacterFactory() {#MathGroupingCharacterFactory--}
```
public MathGroupingCharacterFactory()
```


### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


Tworzy znak grupowania matematycznego

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | element matematyczny, któremu zastosować znak grupowania |
| character | char | znak grupujący |
| position | int | pozycja znaku grupującego |
| verticalJustification | int | wyrównanie pionowe |

**Zwraca:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nowy element znaku grupowania
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```


Tworzy znak grupowania matematycznego

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | element matematyczny, któremu zastosować znak grupowania |

**Zwraca:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nowy element znaku grupowania