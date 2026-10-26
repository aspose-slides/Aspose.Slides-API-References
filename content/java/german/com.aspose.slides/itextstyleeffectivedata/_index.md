---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective text style properties.
type: docs
url: /de/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

Unveränderliches Objekt, das wirksame Texteigenschafts-Parameter enthält.

--------------------

Dieses Interface wird zusammen mit dem [ITextStyle](../../com.aspose.slides/itextstyle) Interface verwendet, um wirksame Formatierungswerte mit angewandter Vererbung zurückzugeben.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Gibt die Ebene des effektiven Stils zurück. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Gibt die effektiven Standard-Absatz-Eigenschaften zurück. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```

Gibt die Ebene des effektiven Stils zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Null-basierter Index der Ebene. Muss im Intervall 0..8 liegen. |

**Rückgabewert:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - Effektive Formatierung der Ebene [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```

Gibt die effektiven Standard-Absatz-Eigenschaften zurück. Nur-lesbar [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**Rückgabewert:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)