---
title: ITextAnimation
second_title: Aspose.Slides for Java API Reference
description: Represent text animation.
type: docs
url: /hu/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

Szöveges animáció ábrázolása.
## Metódusok

| Method | Description |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Új effektust ad hozzá a jelenlegi sorozat végéhez a csoportos szöveganimációk végéhez. |
| [getBuildType()](#getBuildType--) | A felépítési típusok listája (például |
| [setBuildType(int value)](#setBuildType-int-) | A felépítési típusok listája (például |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Csoporthoz tartozó vagy nem tartozó alakzat effektus (null) Olvasás/írás [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Csoporthoz tartozó vagy nem tartozó alakzat effektus (null) Olvasás/írás [IEffect](../../com.aspose.slides/ieffect). |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```

Új effektust ad hozzá a jelenlegi sorozat végéhez a csoportos szöveganimációk végéhez. Csak akkor érvényes, ha a szöveges bekezdések száma egyenlő vagy nagyobb, mint a csoport effektusainak száma!

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| effectType | int | Az animációs effektus típusa [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Az animációs effektus altípusai [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Az effektus aktiválási típusa [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Visszatér:**
[IEffect](../../com.aspose.slides/ieffect) - Új effektus objektum [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```

A felépítési típusok listája (például Bekezdés 1,2,3, Mind egyszerre) a szöveges animációhoz. Olvasás/írás \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Visszatér:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```

A felépítési típusok listája (például Bekezdés 1,2,3, Mind egyszerre) a szöveges animációhoz. Olvasás/írás \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```

Csoporthoz tartozó vagy nem tartozó alakzat effektus (null) Olvasás/írás [IEffect](../../com.aspose.slides/ieffect).

**Visszatér:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```

Csoporthoz tartozó vagy nem tartozó alakzat effektus (null) Olvasás/írás [IEffect](../../com.aspose.slides/ieffect).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |