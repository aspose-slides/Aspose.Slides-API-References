---
title: ITextAnimation
second_title: Aspose.Slides for Android via Java API Reference
description: Szöveg animáció ábrázolása.
type: docs
url: /hu/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

Szöveg animáció ábrázolása.
## Metódusok

| Method | Description |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Új hatás hozzáadása a jelenlegi sorozat végéhez, a csoportos szöveganimációk végéhez. |
| [getBuildType()](#getBuildType--) | Felépítési típus listája (például |
| [setBuildType(int value)](#setBuildType-int-) | Felépítési típus listája (például |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Csoporthoz vagy anélkül (null) kapcsolt alakzat hatás Olvasás/írás [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Csoporthoz vagy anélkül (null) kapcsolt alakzat hatás Olvasás/írás [IEffect](../../com.aspose.slides/ieffect). |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```


Új hatás hozzáadása a jelenlegi sorozat végéhez, a csoportos szöveganimációk végéhez. Csak akkor érvényes, ha a szövegbekezdések száma egyenlő vagy nagyobb, mint a csoport hatásainak száma!

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| effectType | int | Az animációs hatás típusa [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Az animációs hatás altípusa [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | A hatás aktiválási típusa [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Visszatérési érték:**
[IEffect](../../com.aspose.slides/ieffect) - Új hatásobjektum [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```


A szöveg animáció felépítési típusainak listája (például Bekezdés 1,2,3, Mind egyszerre). Olvasás/írás \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Visszatérési érték:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```


A szöveg animáció felépítési típusainak listája (például Bekezdés 1,2,3, Mind egyszerre). Olvasás/írás \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```


Csoporthoz vagy anélkül (null) kapcsolt alakzat hatás Olvasás/írás [IEffect](../../com.aspose.slides/ieffect).

**Visszatérési érték:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```


Csoporthoz vagy anélkül (null) kapcsolt alakzat hatás Olvasás/írás [IEffect](../../com.aspose.slides/ieffect).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |