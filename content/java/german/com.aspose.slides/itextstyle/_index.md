---
title: ITextStyle
second_title: Aspose.Slides for Java API Reference
description: Text style formatting properties.
type: docs
url: /de/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

Textstil-Formatierungseigenschaften.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Falls ein Stil-Level existiert, wird es zurückgegeben, andernfalls wird null zurückgegeben. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Standard-Absatz-Eigenschaften. |
| [getEffective()](#getEffective--) | Ruft die wirksamen Textstil-Formatierungsdaten mit angewandter Vererbung ab. |

### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

Falls ein Stil-Level existiert, wird es zurückgegeben, andernfalls wird null zurückgegeben.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Nullbasierter Index der Ebene. Muss im Intervall 0..8 liegen. |

**Rückgabewert:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Formatierung der Ebene [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```

Standard-Absatz-Eigenschaften. Nur lesbar [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Rückgabewert:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

Ruft die wirksamen Textstil-Formatierungsdaten mit angewandter Vererbung ab.

**Rückgabewert:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Ein [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).