---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Unveränderliches Objekt, das effektive Textstileigenschaften enthält.
type: docs
url: /de/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

Unveränderliches Objekt, das effektive Textstileigenschaften enthält.

--------------------

Dieses Interface wird zusammen mit dem [ITextStyle](../../com.aspose.slides/itextstyle) Interface verwendet, um effektive Formatierungswerte mit angewandter Vererbung zurückzugeben.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Gibt die Ebene des effektiven Stils zurück. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Gibt effektive Standardabsatz-Eigenschaften zurück. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```


Gibt die Ebene des effektiven Stils zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Nullbasierter Index der Ebene. Muss im Intervall 0..8 liegen. |

**Rückgabewert:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - Effektive Formatierung der Ebene [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```


Gibt effektive Standardabsatz-Eigenschaften zurück. Nur lesbar [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**Rückgabewert:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)