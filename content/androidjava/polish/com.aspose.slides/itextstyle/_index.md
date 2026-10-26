---
title: ITextStyle
second_title: Aspose.Slides for Android via Java API Reference
description: Text style formatting properties.
type: docs
url: /pl/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

Właściwości formatowania stylu tekstu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Jeśli poziom stylu istnieje, zwraca go, w przeciwnym razie zwraca null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Domyślne właściwości akapitu. |
| [getEffective()](#getEffective--) | Pobiera skuteczne dane formatowania stylu tekstu z zastosowaną dziedzicznością. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

Jeśli poziom stylu istnieje, zwraca go, w przeciwnym razie zwraca null.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks poziomu zaczynający się od zera. Musi mieścić się w przedziale 0..8. |

**Zwraca:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Formatowanie poziomu [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```

Domyślne właściwości akapitu. Tylko do odczytu [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Zwraca:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

Pobiera skuteczne dane formatowania stylu tekstu z zastosowaną dziedzicznością.

**Zwraca:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Obiekt [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).