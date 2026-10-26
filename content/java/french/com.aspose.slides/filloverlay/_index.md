---
title: FillOverlay
second_title: Référence API Aspose.Slides pour Java
description: Représente un effet Fill Overlay.
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

Représente un effet Fill Overlay. Un fill overlay peut être utilisé pour spécifier un remplissage supplémentaire pour un objet et fusionner les deux remplissages ensemble.
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


Fill format. Lecture seule [IFillFormat](../../com.aspose.slides/ifillformat).

**Renvoie :**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBlend() {#getBlend--}
```
public final int getBlend()
```


FillBlendMode. Lecture/écriture [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Renvoie :**
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


Gets effective Fill Overlay effect data with the inheritance applied.

**Renvoie :**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - Un [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Lecture seule long.

**Renvoie :**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si le [FillOverlay](../../com.aspose.slides/filloverlay) spécifié est égal au [FillOverlay](../../com.aspose.slides/filloverlay) actuel.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The [FillOverlay](../../com.aspose.slides/filloverlay) to compare. |

**Renvoie :**
boolean - true si les objets sont égaux ; sinon, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Fonction de hachage pour un type particulier.

**Renvoie :**
int - Un code de hachage pour l'objet actuel.