---
title: TextAnimation
second_title: Aspose.Slides for Android via Java API Reference
description: Szöveganimációt ábrázol.
type: docs
url: /hu/com.aspose.slides/textanimation/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)
```
public class TextAnimation implements ITextAnimation
```

Szöveganimációt jelenít meg.

## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Új effektust ad a jelenlegi sorozat végéhez, a csoport szöveganimációk végéhez. |
| [getBuildType()](#getBuildType--) | Az építési típusok listája (például |
| [setBuildType(int value)](#setBuildType-int-) | Az építési típusok listája (például |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Csoporthoz kapcsolt alakzat hatása vagy nem (null). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Csoporthoz kapcsolt alakzat hatása vagy nem (null). |

### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```

### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```

Új effektust ad a jelenlegi sorozat végéhez, a csoport szöveganimációk végéhez. Csak akkor érvényes, ha a szövegbekezdések száma egyenlő vagy nagyobb, mint a csoport effektusainak száma!

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| effectType | int | Az animáció effektus típusa [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Az animáció effektus altípusai [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Az effektus aktiválási típusa [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Visszatérési érték:**
[IEffect](../../com.aspose.slides/ieffect) - Új effektus objektum [IEffect](../../com.aspose.slides/ieffect)

### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```

A szöveganimáció építési típusa (például bekezdés 1,2,3, egyszerre) listája. Olvasás/írás [BuildType](../../com.aspose.slides/buildtype).

**Visszatérési érték:**
int

### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```

A szöveganimáció építési típusa (például bekezdés 1,2,3, egyszerre) listája. Olvasás/írás [BuildType](../../com.aspose.slides/buildtype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```

A csoporthoz kapcsolt vagy nem kapcsolt alakzat hatása (null). Olvasás/írás [IEffect](../../com.aspose.slides/ieffect).

**Visszatérési érték:**
[IEffect](../../com.aspose.slides/ieffect)

### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```

A csoporthoz kapcsolt vagy nem kapcsolt alakzat hatása (null). Olvasás/írás [IEffect](../../com.aspose.slides/ieffect).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |