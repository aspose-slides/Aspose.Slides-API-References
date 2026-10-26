---
title: MathGroupingCharacterFactory
second_title: Aspose.Slides dla Androida poprzez odniesienie API Java
description: Umożliwia tworzenie znaku grupującego w matematyce
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

Umożliwia tworzenie znaku grupującego w matematyce

--------------------

Dla zgodności z COM
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [MathGroupingCharacterFactory()](#MathGroupingCharacterFactory--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Tworzy znak grupujący w matematyce |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Tworzy znak grupujący w matematyce |
### MathGroupingCharacterFactory() {#MathGroupingCharacterFactory--}
```
public MathGroupingCharacterFactory()
```


### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


Tworzy znak grupujący w matematyce

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | element matematyczny, do którego zastosować znak grupujący |
| character | char | znak grupujący |
| position | int | pozycja znaku grupującego |
| verticalJustification | int | pionowe wyrównanie |

**Zwraca:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nowy element znaku grupującego
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```


Tworzy znak grupujący w matematyce

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | element matematyczny, do którego zastosować znak grupujący |

**Zwraca:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nowy element znaku grupującego