---
title: ITextStyle
second_title: Aspose.Slides for Android prostřednictvím Java API Reference
description: Vlastnosti formátování textového stylu.
type: docs
url: /cs/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

Vlastnosti formátování textového stylu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Pokud existuje úroveň stylu, vrátí ji, jinak vrátí null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Výchozí vlastnosti odstavce. |
| [getEffective()](#getEffective--) | Získá data efektivního formátování textového stylu s použitým děděním. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

Pokud existuje úroveň stylu, vrátí ji, jinak vrátí null.

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

Získá data efektivního formátování textového stylu s použitým děděním.

**Návratová hodnota:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - A [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).