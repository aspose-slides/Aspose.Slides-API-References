---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Neměnný objekt, který obsahuje efektivní vlastnosti textového stylu.
type: docs
url: /cs/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

Neměnný objekt, který obsahuje efektivní vlastnosti textového stylu.

--------------------

Toto rozhraní se používá spolu s rozhraním [ITextStyle](../../com.aspose.slides/itextstyle) k vrácení efektivních hodnot formátování s aplikovaným děděním.
## Metody

| Metoda | Popis |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Vrací úroveň efektivního stylu. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Vrací efektivní výchozí vlastnosti odstavce. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```


Vrací úroveň efektivního stylu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index úrovně počínaje nulou. Musí ležet v intervalu 0..8. |

**Vrací:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - Efektivní formátování úrovně [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```


Vrací efektivní výchozí vlastnosti odstavce. Pouze pro čtení [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**Vrací:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)