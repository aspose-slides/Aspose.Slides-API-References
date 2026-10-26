---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Options pour extraire le HTML du texte Pptx.
type: docs
url: /fr/com.aspose.slides/texttohtmlconversionoptions/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

Options pour extraire le HTML du texte Pptx.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Renvoie ou définit la valeur, indiquant si les en-têtes du presse-papier doivent être ajoutés. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Renvoie ou définit la valeur, indiquant si les en-têtes du presse-papier doivent être ajoutés. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Renvoie ou définit la profondeur d'héritage pour les propriétés de texte. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Renvoie ou définit la profondeur d'héritage pour les propriétés de texte. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Renvoie ou définit un objet de rappel qui contrôle la façon dont l'objet externe sera stocké. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Renvoie ou définit un objet de rappel qui contrôle la façon dont l'objet externe sera stocké. |
| [getEncodingName()](#getEncodingName--) | Renvoie ou définit le nom du codage html. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Renvoie ou définit le nom du codage html. |
### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```

### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```

Renvoie ou définit la valeur, indiquant si les en-têtes du presse-papier doivent être ajoutés. Lecture/écriture booléen.

**Renvoie :**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```

Renvoie ou définit la valeur, indiquant si les en-têtes du presse-papier doivent être ajoutés. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```

Renvoie ou définit la profondeur d'héritage pour les propriétés de texte. Lecture/écriture [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Renvoie :**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```

Renvoie ou définit la profondeur d'héritage pour les propriétés de texte. Lecture/écriture [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```

Renvoie ou définit un objet de rappel qui contrôle la façon dont l'objet externe sera stocké. Lecture/écriture [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Renvoie :**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```

Renvoie ou définit un objet de rappel qui contrôle la façon dont l'objet externe sera stocké. Lecture/écriture [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```

Renvoie ou définit le nom d'encodage html. Cette valeur sera enregistrée dans le fichier HTML généré, mais il incombe à l'appelant de s'assurer que le fichier sera enregistré avec cet encodage. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```

Renvoie ou définit le nom d'encodage html. Cette valeur sera enregistrée dans le fichier HTML généré, mais il incombe à l'appelant de s'assurer que le fichier sera enregistré avec cet encodage. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |