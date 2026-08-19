---
title: TextAnimation
second_title: Aspose.Slides för Java API-referens
description: Representerar textanimation.
type: docs
url: /sv/com.aspose.slides/textanimation/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)
```
public class TextAnimation implements ITextAnimation
```

Representerar textanimation.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Lägg till en ny effekt i slutet av den aktuella sekvensen för gruppens textanimationer. |
| [getBuildType()](#getBuildType--) | Lista över byggtyp (t.ex. |
| [setBuildType(int value)](#setBuildType-int-) | Lista över byggtyp (t.ex. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Länkad formeffekt med grupp eller inte (null). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Länkad formeffekt med grupp eller inte (null). |
### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```


### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```


Lägg till en ny effekt i slutet av den aktuella sekvensen för gruppens textanimationer. Endast giltig om antalet textparagrafer är lika med eller större än antalet effekter i denna grupp!

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| effectType | int | Typ av en animationseffekt [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Undertyper av animationseffekt [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Utlösningstyp för effekt [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Returvärde:**
[IEffect](../../com.aspose.slides/ieffect) - Nytt effektobjekt [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```


Lista över byggtyp (t.ex. Stycke 1,2,3, Alla på en gång) för textanimation. Läs/skriv [BuildType](../../com.aspose.slides/buildtype).

**Returvärde:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```


Lista över byggtyp (t.ex. Stycke 1,2,3, Alla på en gång) för textanimation. Läs/skriv [BuildType](../../com.aspose.slides/buildtype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```


Länkad formeffekt med grupp eller inte (null). Läs/skriv [IEffect](../../com.aspose.slides/ieffect).

**Returvärde:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```


Länkad formeffekt med grupp eller inte (null). Läs/skriv [IEffect](../../com.aspose.slides/ieffect).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |