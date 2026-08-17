---
title: ITextAnimation
second_title: Aspose.Slides for Java API Reference
description: Stellt Textanimation dar.
type: docs
url: /de/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

Stellt Textanimation dar.
## Methoden

| Method | Description |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Fügt einen neuen Effekt am Ende der aktuellen Sequenz bis zum Ende der Gruppen-Textanimationen hinzu. |
| [getBuildType()](#getBuildType--) | Liste des Build-Typs (z. B. |
| [setBuildType(int value)](#setBuildType-int-) | Liste des Build-Typs (z. B. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Verbundenes Formeffekt mit Gruppe oder nicht (null) Lesen/Schreiben [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Verbundenes Formeffekt mit Gruppe oder nicht (null) Lesen/Schreiben [IEffect](../../com.aspose.slides/ieffect). |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```

Fügt einen neuen Effekt am Ende der aktuellen Sequenz bis zum Ende der Gruppen-Textanimationen hinzu. Nur gültig, wenn die Anzahl der Textabsätze gleich oder größer ist als die Anzahl der Effekte dieser Gruppe!

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| effectType | int | Typ eines Animationseffekts [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Untertypen des Animationseffekts [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Auslösetyp des Effekts [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Rückgabewert:**
[IEffect](../../com.aspose.slides/ieffect) - Neues Effekt-Objekt [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```

Liste des Build-Typs (z. B. Absatz 1,2,3, Alle auf einmal) der Textanimation. Lesen/Schreiben \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Rückgabewert:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```

Liste des Build-Typs (z. B. Absatz 1,2,3, Alle auf einmal) der Textanimation. Lesen/Schreiben \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```

Verbundenes Formeffekt mit Gruppe oder nicht (null) Lesen/Schreiben [IEffect](../../com.aspose.slides/ieffect).

**Rückgabewert:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```

Verbundenes Formeffekt mit Gruppe oder nicht (null) Lesen/Schreiben [IEffect](../../com.aspose.slides/ieffect).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |