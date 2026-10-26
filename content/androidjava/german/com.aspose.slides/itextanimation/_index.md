---
title: ITextAnimation
second_title: Aspose.Slides for Android via Java API Reference
description: Represent text animation.
type: docs
url: /de/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

Stellt Textanimation dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Fügt einen neuen Effekt am Ende der aktuellen Sequenz zur Gruppe von Texteanimationen hinzu. |
| [getBuildType()](#getBuildType--) | Liste des Aufbautyps (z. B. |
| [setBuildType(int value)](#setBuildType-int-) | Liste des Aufbautyps (z. B. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Mit Gruppe verknüpfter Formeffekt oder nicht (null) Lesen/Schreiben [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Mit Gruppe verknüpfter Formeffekt oder nicht (null) Lesen/Schreiben [IEffect](../../com.aspose.slides/ieffect). |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```

Fügt einen neuen Effekt am Ende der aktuellen Sequenz zur Gruppe von Texteanimationen hinzu. Nur gültig, wenn die Anzahl der Textabsätze gleich oder größer ist als die Anzahl der Effekte dieser Gruppe!

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| effectType | int | Art eines Animationseffekts [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Untertypen des Animationseffekts [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Auslösetyp des Effekts [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Rückgabewert:**
[IEffect](../../com.aspose.slides/ieffect) - Neues Effektobjekt [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```

Liste des Aufbautyps (z. B. Absatz 1,2,3, Alles auf einmal) einer Textanimation. Lesen/Schreiben #getBuildType.getBuildType/#setBuildType(int).setBuildType(int).

**Rückgabewert:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```

Liste des Aufbautyps (z. B. Absatz 1,2,3, Alles auf einmal) einer Textanimation. Lesen/Schreiben #getBuildType.getBuildType/#setBuildType(int).setBuildType(int).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```

Mit Gruppe verknüpfter Formeffekt oder nicht (null) Lesen/Schreiben [IEffect](../../com.aspose.slides/ieffect).

**Rückgabewert:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```

Mit Gruppe verknüpfter Formeffekt oder nicht (null) Lesen/Schreiben [IEffect](../../com.aspose.slides/ieffect).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |