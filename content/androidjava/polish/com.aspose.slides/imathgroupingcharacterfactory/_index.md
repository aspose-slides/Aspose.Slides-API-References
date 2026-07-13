---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Umożliwia tworzenie znaku grupującego w matematyce
type: docs
url: /pl/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

Umożliwia tworzenie znaku grupującego w matematyce

--------------------

Dla zgodności z COM
## Metody

| Metoda | Opis |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Tworzy znak grupujący w matematyce |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Tworzy znak grupujący w matematyce |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


Tworzy znak grupujący w matematyce

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | element matematyczny, do którego ma zostać zastosowany znak grupujący |
| character | char | znak grupujący |
| position | int | pozycja znaku grupującego |
| verticalJustification | int | pionowe wyrównanie |

**Zwraca:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nowy element znaku grupującego
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```


Tworzy znak grupujący w matematyce

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | element matematyczny, do którego ma zostać zastosowany znak grupujący |

**Zwraca:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nowy element znaku grupującego