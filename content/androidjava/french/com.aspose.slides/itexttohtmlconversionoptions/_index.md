---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Options pour extraire le HTML du texte Pptx.
type: docs
url: /fr/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

Options pour extraire le HTML du texte Pptx.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Renvoie ou définit la valeur, indiquant si les en-têtes du presse-papier doivent être ajoutés. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Renvoie ou définit la valeur, indiquant si les en-têtes du presse-papier doivent être ajoutés. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Renvoie ou définit la profondeur d’héritage pour les propriétés de texte. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Renvoie ou définit la profondeur d’héritage pour les propriétés de texte. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Renvoie ou définit un objet de rappel qui contrôle la façon dont l’objet externe sera stocké. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Renvoie ou définit un objet de rappel qui contrôle la façon dont l’objet externe sera stocké. |
| [getEncodingName()](#getEncodingName--) | Renvoie ou définit le nom du codage HTML. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Renvoie ou définit le nom du codage HTML. |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```


Renvoie ou définit la valeur, indiquant si les en-têtes du presse-papier doivent être ajoutés. Lecture/écriture boolean.

**Renvoie :**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```


Renvoie ou définit la valeur, indiquant si les en-têtes du presse-papier doivent être ajoutés. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```


Renvoie ou définit la profondeur d’héritage pour les propriétés de texte. Lecture/écriture [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Renvoie :**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```


Renvoie ou définit la profondeur d’héritage pour les propriétés de texte. Lecture/écriture [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```


Renvoie ou définit un objet de rappel qui contrôle la façon dont l’objet externe sera stocké. Lecture/écriture [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Renvoie :**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```


Renvoie ou définit un objet de rappel qui contrôle la façon dont l’objet externe sera stocké. Lecture/écriture [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```


Renvoie ou définit le nom du codage HTML. Cette valeur sera enregistrée dans le fichier HTML généré, mais il appartient à l’appelant de veiller à ce que le fichier soit enregistré avec ce codage. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```


Renvoie ou définit le nom du codage HTML. Cette valeur sera enregistrée dans le fichier HTML généré, mais il appartient à l’appelant de veiller à ce que le fichier soit enregistré avec ce codage. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |