---
title: IPortionFormatEffectiveData
second_title: Référence de l'API Java pour Aspose.Slides sur Android
description: Objet immuable contenant les propriétés de formatage effectif de la portion de texte.
type: docs
url: /fr/com.aspose.slides/iportionformateffectivedata/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IBasePortionFormatEffectiveData](../../com.aspose.slides/ibaseportionformateffectivedata)
```
public interface IPortionFormatEffectiveData extends IBasePortionFormatEffectiveData
```

Objet immuable qui contient les propriétés de formatage de la portion de texte effective.

--------------------

Cette interface est utilisée conjointement avec l'interface [IPortionFormat](../../com.aspose.slides/iportionformat) pour renvoyer les valeurs de formatage effectives avec l'héritage appliqué.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Renvoie l'identifiant du signet. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Renvoie le lien hypertexte défini pour le clic de souris. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Renvoie le lien hypertexte défini pour le survol de la souris. |

### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

Renvoie l'identifiant du signet. String en lecture seule.

**Renvoie :**  
java.lang.String

### getHyperlinkClick() {#getHyperlinkClick--}
```
public abstract IHyperlink getHyperlinkClick()
```

Renvoie le lien hypertexte défini pour le clic de souris. [IHyperlink](../../com.aspose.slides/ihyperlink) en lecture seule.

**Renvoie :**  
[IHyperlink](../../com.aspose.slides/ihyperlink)

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public abstract IHyperlink getHyperlinkMouseOver()
```

Renvoie le lien hypertexte défini pour le survol de la souris. [IHyperlink](../../com.aspose.slides/ihyperlink) en lecture seule.

**Renvoie :**  
[IHyperlink](../../com.aspose.slides/ihyperlink)