---
title: IPortionFormat
second_title: Aspose.Slides pour Android via la référence API Java
description: Cette classe contient les propriétés de mise en forme de la portion de texte.
type: docs
url: /fr/com.aspose.slides/iportionformat/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

Cette classe contient les propriétés de mise en forme de la portion de texte. Contrairement à [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), toutes les propriétés de cette classe sont modifiables.

--------------------

Cette classe est utilisée pour renvoyer et manipuler les propriétés de mise en forme de la portion de texte définies pour la portion particulière. Cela signifie qu'aucune héritage n'est appliqué lors de la récupération des valeurs, si bien que dans la plupart des cas vous obtiendrez des valeurs signifiant « indéfini ».

Afin d'obtenir les valeurs effectives des paramètres de mise en forme, y compris héritées, vous devez utiliser la méthode [getEffective](../../com.aspose.slides/iportionformat\#getEffective) qui renvoie une instance [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Renvoie ou définit l'identifiant du signet. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Renvoie ou définit l'identifiant du signet. |
| [getSmartTagClean()](#getSmartTagClean--) | Détermine si la smart tag doit être nettoyée. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Détermine si la smart tag doit être nettoyée. |
| [getEffective()](#getEffective--) | Obtient les données de mise en forme effectives de la portion avec l'héritage appliqué. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```


Renvoie ou définit l'identifiant du signet. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```


Renvoie ou définit l'identifiant du signet. Lecture/écriture String.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```


Détermine si la smart tag doit être nettoyée. Aucun héritage appliqué. Lecture/écriture boolean.

**Renvoie :**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```


Détermine si la smart tag doit être nettoyée. Aucun héritage appliqué. Lecture/écriture boolean.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```


Obtient les données de mise en forme effectives de la portion avec l'héritage appliqué.

**Renvoie :**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).