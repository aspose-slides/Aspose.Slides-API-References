---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Java Référence de l'API
description: Objet immuable contenant les propriétés de style de texte effectives.
type: docs
url: /fr/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

Objet immuable contenant les propriétés de style de texte effectives.

--------------------

Cette interface est utilisée conjointement avec l'interface [ITextStyle](../../com.aspose.slides/itextstyle) pour renvoyer les valeurs de formatage effectives avec héritage appliqué.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Returns level of effective style. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Returns effective default paragraph properties. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```

Renvoie le niveau du style effectif.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice basé sur zéro du niveau. Doit se situer dans l'intervalle 0..8. |

**Renvoie:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - Formatage effectif du niveau [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```

Renvoie les propriétés de paragraphe par défaut effectives. En lecture seule [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**Renvoie:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)