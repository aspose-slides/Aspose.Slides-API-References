---
title: IMathBlock
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Gibt eine Instanz von mathematischem Text an, die innerhalb eines MathParagraph enthalten ist und in einer eigenen Zeile beginnt.
type: docs
url: /de/com.aspose.slides/imathblock/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

Gibt eine Instanz von mathematischem Text an, die innerhalb eines MathParagraph enthalten ist und in einer eigenen Zeile beginnt. Alle mathematischen Zonen, einschließlich Gleichungen, Ausdrücken, Arrays von Gleichungen oder Ausdrücken und Formeln werden durch einen Math-Block dargestellt.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | Begrenzt alle untergeordneten Elemente mit Trennzeichen (ohne die Klammern) |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Umschließt untergeordnete Elemente dieses Blocks in angegebenen Zeichen wie Klammern oder anderen als Rahmen und begrenzt sie mit einem Trennzeichen |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Fügt einen anderen mathematischen Block zu diesem hinzu |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Speichert den Inhalt dieses [IMathBlock](../../com.aspose.slides/imathblock) als MathML |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Begrenzt alle untergeordneten Elemente mit Trennzeichen (ohne die Klammern)

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separatorCharacter | char | Zeichen, das als Trennzeichen verwendet wird |

**Rückgabe:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Instanz des IMathDelimiter-Elements
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Umschließt untergeordnete Elemente dieses Blocks in angegebenen Zeichen wie Klammern oder anderen als Rahmen und begrenzt sie mit einem Trennzeichen

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| beginningCharacter | char | Anfangszeichen (gewöhnlich linke Klammer) |
| endingCharacter | char | Endzeichen (gewöhnlich rechte Klammer) |
| separatorCharacter | char | Trennzeichen |

**Rückgabe:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Das Mathe-Element vom Typ [IMathDelimiter](../../com.aspose.slides/imathdelimiter), das die angegebenen Zeichen als Rahmen und Trennzeichen enthält
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```

Fügt einen anderen mathematischen Block zu diesem hinzu

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Der zusammenführende Block |

**Rückgabe:**
[IMathBlock](../../com.aspose.slides/imathblock) - dieser mathematische Block nach dem Zusammenführen
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

Speichert den Inhalt dieses [IMathBlock](../../com.aspose.slides/imathblock) als MathML

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Zielstream |