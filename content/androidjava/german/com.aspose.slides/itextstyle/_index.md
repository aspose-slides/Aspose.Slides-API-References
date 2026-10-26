---
title: ITextStyle
second_title: Aspose.Slides for Android via Java API Reference
description: Text style formatting properties.
type: docs
url: /de/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

Textstilformatierungseigenschaften.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Wenn die Ebene des Stils existiert, wird sie zurückgegeben, andernfalls wird null zurückgegeben. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Standardabsatz-Eigenschaften. |
| [getEffective()](#getEffective--) | Ruft effektive Textstil-Formatierungsdaten mit angewandter Vererbung ab. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

Wenn die Ebene des Stils existiert, wird sie zurückgegeben, andernfalls wird null zurückgegeben.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Nullbasierter Index der Ebene. Muss im Intervall 0..8 liegen. |

**Rückgabewert:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Formatierung von Ebene [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```

Standardabsatz-Eigenschaften. Nur lesbar [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Rückgabewert:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

Ruft effektive Textstil-Formatierungsdaten mit angewandter Vererbung ab.

**Rückgabewert:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Ein [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).