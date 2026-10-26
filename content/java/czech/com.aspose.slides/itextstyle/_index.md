---
title: ITextStyle
second_title: Aspose.Slides for Java API Reference
description: Vlastnosti formátování stylu textu.
type: docs
url: /cs/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

Vlastnosti formátování stylu textu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Pokud úroveň stylu existuje, vrátí ji, jinak vrátí null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Výchozí vlastnosti odstavce. |
| [getEffective()](#getEffective--) | Získá efektivní data formátování stylu textu s aplikovaným děděním. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

Pokud úroveň stylu existuje, vrátí ji, jinak vrátí null.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index úrovně. Musí ležet v intervalu 0..8. |

**Návratová hodnota:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Formátování úrovně [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```

Výchozí vlastnosti odstavce. Pouze pro čtení [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Návratová hodnota:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

Získá efektivní data formátování stylu textu s aplikovaným děděním.

**Návratová hodnota:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Jedná se o [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).