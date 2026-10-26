---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Niezmienny obiekt zawierający efektywne właściwości stylu tekstu.
type: docs
url: /pl/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

Niezmienny obiekt zawierający efektywne właściwości stylu tekstu.

--------------------

Ten interfejs jest używany razem z interfejsem [ITextStyle](../../com.aspose.slides/itextstyle) do zwracania wartości formatowania z uwzględnieniem dziedziczenia.

## Metody

| Metoda | Opis |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Zwraca poziom efektywnego stylu. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Zwraca efektywne domyślne właściwości akapitu. |

### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```

Zwraca poziom efektywnego stylu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks poziomu zaczynający się od zera. Musi mieścić się w przedziale 0..8. |

**Zwraca:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - Efektywne formatowanie poziomu [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```

Zwraca efektywne domyślne właściwości akapitu. Tylko do odczytu [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**Zwraca:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)