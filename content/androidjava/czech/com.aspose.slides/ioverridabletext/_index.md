---
title: IOverridableText
second_title: Aspose.Slides pro Android prostřednictvím reference Java API
description: Představuje přepisovatelný text pro graf.
type: docs
url: /cs/com.aspose.slides/ioverridabletext/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

Představuje přepisovatelný text pro graf.
## Metody

| Metoda | Popis |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Může obsahovat bohatě formátovaný text. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inicializuje TextFrameForOverriding pomocí textu v parametru "text". |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```


Může obsahovat bohatě formátovaný text. Pokud tato vlastnost není null, pak tato hodnota formátovaného textu přepisuje automaticky generovaný text. Automaticky generovaný text je implicitní vlastnost popisku dat, popisku jednotky zobrazení hodnotové osy, názvu osy, názvu grafu, popisku trendové čáry. Automaticky generovaný text je formátován pomocí vlastnosti IFormattedTextContainer.TextFormat. Pouze pro čtení [ITextFrame](../../com.aspose.slides/itextframe).

**Vrací:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```


Inicializuje TextFrameForOverriding pomocí textu v parametru "text". Pokud je TextFrameForOverriding již inicializován, pak prostě změní jeho text.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text pro nový TextFrameForOverriding. |

**Vrací:**
[ITextFrame](../../com.aspose.slides/itextframe) - Textový rámec [ITextFrame](../../com.aspose.slides/itextframe)