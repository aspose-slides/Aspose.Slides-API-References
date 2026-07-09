---
title: IOverridableText
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente le texte remplaçable pour un graphique.
type: docs
url: /fr/com.aspose.slides/ioverridabletext/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

Représente le texte remplaçable pour un graphique.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Peut contenir un texte riche formaté. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Initialise TextFrameForOverriding avec le texte du paramètre "text". |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```

Peut contenir un texte riche formaté. Si cette propriété n’est pas nulle, alors cette valeur de texte formaté remplace le texte généré automatiquement. Le texte généré automatiquement est une propriété implicite de l’étiquette de données, de l’étiquette d’unité d’affichage de l’axe des valeurs, du titre de l’axe, du titre du graphique, de l’étiquette de la ligne de tendance. Le texte généré automatiquement est formaté avec la propriété IFormattedTextContainer.TextFormat. Lecture seule [ITextFrame](../../com.aspose.slides/itextframe).

**Renvoie :**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```

Initialise TextFrameForOverriding avec le texte du paramètre "text". Si TextFrameForOverriding est déjà initialisé, il change simplement son texte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte pour un nouveau TextFrameForOverriding. |

**Renvoie :**
[ITextFrame](../../com.aspose.slides/itextframe) - Cadre de texte [ITextFrame](../../com.aspose.slides/itextframe)