---
title: IPictureFrame
second_title: Aspose.Slides dla Androida poprzez odniesienie do Java API
description: Reprezentuje ramkę z obrazem wewnątrz.
type: docs
url: /pl/com.aspose.slides/ipictureframe/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

Reprezentuje ramkę z obrazem wewnątrz.
## Metody

| Metoda | Opis |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Zwraca PictureFrame's locks. |
| [getPictureFormat()](#getPictureFormat--) | Zwraca obiekt PictureFillFormat dla ramki obrazu. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Zwraca lub ustawia skalę wysokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Zwraca lub ustawia skalę wysokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Zwraca lub ustawia skalę szerokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Zwraca lub ustawia skalę szerokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```

Zwraca PictureFrame's locks. Tylko do odczytu [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Zwraca:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getPictureFormat() {#getPictureFormat--}
```
public abstract IPictureFillFormat getPictureFormat()
```

Zwraca obiekt PictureFillFormat dla ramki obrazu. Tylko do odczytu [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Zwraca:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public abstract float getRelativeScaleHeight()
```

Zwraca lub ustawia skalę wysokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. Wartość 1.0 odpowiada 100%. Odczyt/zapis float.

**Zwraca:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```

Zwraca lub ustawia skalę wysokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. Wartość 1.0 odpowiada 100%. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |
### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```

Zwraca lub ustawia skalę szerokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. Wartość 1.0 odpowiada 100%. Odczyt/zapis float.

**Zwraca:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```

Zwraca lub ustawia skalę szerokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. Wartość 1.0 odpowiada 100%. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |