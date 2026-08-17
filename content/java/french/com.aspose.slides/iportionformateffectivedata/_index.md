---
title: IPortionFormatEffectiveData
second_title: Référence de l'API Aspose.Slides pour Java
description: Objet immuable qui contient les propriétés de formatage effectif des portions de texte.
type: docs
url: /fr/com.aspose.slides/iportionformateffectivedata/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IBasePortionFormatEffectiveData](../../com.aspose.slides/ibaseportionformateffectivedata)
```
public interface IPortionFormatEffectiveData extends IBasePortionFormatEffectiveData
```

Objet immuable contenant les propriétés de formatage de portion de texte effectif.

--------------------

Cette interface est utilisée conjointement avec l’interface [IPortionFormat](../../com.aspose.slides/iportionformat) pour renvoyer les valeurs de formatage effectives avec l’héritage appliqué.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Renvoie l’identifiant du signet. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Renvoie le lien hypertexte défini pour le clic de la souris. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Renvoie le lien hypertexte défini pour le survol de la souris. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```


Renvoie l’identifiant du signet. Lecture seule String.

**Renvoie :**
java.lang.String
### getHyperlinkClick() {#getHyperlinkClick--}
```
public abstract IHyperlink getHyperlinkClick()
```


Renvoie le lien hypertexte défini pour le clic de la souris. Lecture seule [IHyperlink](../../com.aspose.slides/ihyperlink).

**Renvoie :**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public abstract IHyperlink getHyperlinkMouseOver()
```


Renvoie le lien hypertexte défini pour le survol de la souris. Lecture seule [IHyperlink](../../com.aspose.slides/ihyperlink).

**Renvoie :**
[IHyperlink](../../com.aspose.slides/ihyperlink)