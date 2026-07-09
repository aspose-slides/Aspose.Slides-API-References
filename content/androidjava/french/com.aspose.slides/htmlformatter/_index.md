---
title: HtmlFormatter
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente le modèle de fichier HTML.
type: docs
url: /fr/com.aspose.slides/htmlformatter/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)  
```
public final class HtmlFormatter implements IHtmlFormatter
```

Représente le modèle de fichier HTML.

## Méthodes

| Méthode | Description |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | Crée et renvoie un formateur HTML pour une vue de document simple qui consiste en une séquence de diapositives les unes sous les autres. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | Crée et renvoie un formateur HTML pour un diaporama simple qui affiche les diapositives les unes après les autres. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | Crée et renvoie un formateur HTML pour une génération HTML personnalisée pilotée par des rappels. |

### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```

Crée et renvoie un formateur HTML pour une vue de document simple qui consiste en une séquence de diapositives les unes sous les autres.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| css | java.lang.String | Spécifie le CSS pour ce fichier. |
| showSlideTitle | boolean | Ajoute le titre de la diapositive s'il y en a un au-dessus de l'image de la diapositive. |

**Valeur de retour:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - L'objet [HtmlFormatter](../../com.aspose.slides/htmlformatter).

### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```

Crée et renvoie un formateur HTML pour un diaporama simple qui affiche les diapositives les unes après les autres.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| css | java.lang.String | Spécifie l'URL du fichier CCS utilisé. |
| showSlideTitle | boolean | Ajoute le titre de la diapositive s'il y en a un au-dessus de l'image de la diapositive. |

**Valeur de retour:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - L'objet [HtmlFormatter](../../com.aspose.slides/htmlformatter).

### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```

Crée et renvoie un formateur HTML pour une génération HTML personnalisée pilotée par des rappels.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Interface de rappel qui contrôle la génération du fichier HTML. |

**Valeur de retour:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - L'objet [HtmlFormatter](../../com.aspose.slides/htmlformatter).