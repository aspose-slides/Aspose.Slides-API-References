---
title: FillOverlay
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente un effet de remplissage superposé.
type: docs
url: /fr/com.aspose.slides/filloverlay/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

Représente un effet de remplissage superposé. Un remplissage superposé peut être utilisé pour spécifier un remplissage supplémentaire pour un objet et mélanger les deux remplissages ensemble.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Fill format. |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | Gets effective Fill Overlay effect data with the inheritance applied. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [FillOverlay](../../com.aspose.slides/filloverlay) is equal to the current [FillOverlay](../../com.aspose.slides/filloverlay). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Format de remplissage. Lecture seule [IFillFormat](../../com.aspose.slides/ifillformat).

**Retourne :**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBlend() {#getBlend--}
```
public final int getBlend()
```


FillBlendMode. Lecture/écriture [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Retourne :**
int
### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```


FillBlendMode. Lecture/écriture [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```


Obtient les données effectives de l'effet Fill Overlay avec l'héritage appliqué.

**Retourne :**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - A [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Lecture seule long.

**Retourne :**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si le [FillOverlay](../../com.aspose.slides/filloverlay) spécifié est égal au [FillOverlay](../../com.aspose.slides/filloverlay) actuel.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le [FillOverlay](../../com.aspose.slides/filloverlay) à comparer. |

**Retourne :**
boolean - true si les objets sont égaux ; sinon, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Servir de fonction de hachage pour un type particulier.

**Retourne :**
int - A hash code for the current object.