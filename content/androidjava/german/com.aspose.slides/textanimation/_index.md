---
title: TextAnimation
second_title: Aspose.Slides für Android via Java API Referenz
description: Stellt Textanimation dar.
type: docs
url: /de/com.aspose.slides/textanimation/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)
```
public class TextAnimation implements ITextAnimation
```

Stellt Textanimation dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Fügt einen neuen Effekt am Ende der aktuellen Sequenz zu den Gruppen-Textanimationen hinzu. |
| [getBuildType()](#getBuildType--) | Liste des Build-Typs (z. B. |
| [setBuildType(int value)](#setBuildType-int-) | Liste des Build-Typs (z. B. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Verknüpfter Formeffekt mit Gruppe oder nicht (null). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Verknüpfter Formeffekt mit Gruppe oder nicht (null). |
### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```


### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```


Fügt einen neuen Effekt am Ende der aktuellen Sequenz zu den Gruppen-Textanimationen hinzu. Nur gültig, wenn die Anzahl der Textabsätze gleich oder größer ist als die Anzahl der Effekte dieser Gruppe!

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| effectType | int | Typ eines Animationseffekts [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtypen des Animationseffekts [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Auslösetyp des Effekts [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Rückgabe:**
[IEffect](../../com.aspose.slides/ieffect) - Neues Effektobjekt [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```


Liste des Build-Typs (z. B. Absatz 1,2,3, Alle gleichzeitig) der Textanimation. Lese-/Schreib [BuildType](../../com.aspose.slides/buildtype).

**Rückgabe:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```


Liste des Build-Typs (z. B. Absatz 1,2,3, Alle gleichzeitig) der Textanimation. Lese-/Schreib [BuildType](../../com.aspose.slides/buildtype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```


Verknüpfter Formeffekt mit Gruppe oder nicht (null). Lese-/Schreib [IEffect](../../com.aspose.slides/ieffect).

**Rückgabe:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```


Verknüpfter Formeffekt mit Gruppe oder nicht (null). Lese-/Schreib [IEffect](../../com.aspose.slides/ieffect).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |