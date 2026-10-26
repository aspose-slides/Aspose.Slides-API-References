---
title: ITextAnimation
second_title: Aspose.Slides for Java API Reference
description: Representerar textanimation.
type: docs
url: /sv/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

Representerar textanimation.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Lägg till en ny effekt i slutet av den aktuella sekvensen till slutet av gruppens textanimationer. |
| [getBuildType()](#getBuildType--) | Lista över byggetyp (för exp. |
| [setBuildType(int value)](#setBuildType-int-) | Lista över byggetyp (för exp. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Länkad formseffekt med grupp eller inte (null) Läs/skriv [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Länkad formseffekt med grupp eller inte (null) Läs/skriv [IEffect](../../com.aspose.slides/ieffect). |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```


Lägg till en ny effekt i slutet av den aktuella sekvensen till slutet av gruppens textanimationer. Giltig endast om antalet textparagrafer är lika med eller större än antalet effekter i denna grupp!

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| effectType | int | Typ av en animeringseffekt [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Undertyper av animeringseffekt [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Utlösartyp för effekt [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Returnerar:**
[IEffect](../../com.aspose.slides/ieffect) - Ny effektobjekt [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```


Lista över byggetyp (för exp. Paragraph 1,2,3, All at Once) för textanimation. Läs/skriv \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Returnerar:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```


Lista över byggetyp (för exp. Paragraph 1,2,3, All at Once) för textanimation. Läs/skriv \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```


Länkad formseffekt med grupp eller inte (null) Läs/skriv [IEffect](../../com.aspose.slides/ieffect).

**Returnerar:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```


Länkad formseffekt med grupp eller inte (null) Läs/skriv [IEffect](../../com.aspose.slides/ieffect).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |