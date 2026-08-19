---
title: IDuotoneEffectiveData
second_title: Aspose.Slides voor Java API Referentie
description: Onveranderlijk object dat een Duotoon-effect vertegenwoordigt.
type: docs
url: /nl/com.aspose.slides/iduotoneeffectivedata/
---
**Alle geimplementeerde interfaces:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

Onveranderlijk object dat een Duotoon-effect vertegenwoordigt. Voor elke pixel worden clr1 en clr2 gecombineerd via een lineaire interpolatie om de nieuwe kleur voor die pixel te bepalen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getColor1()](#getColor1--) | Retourneert het doelformaat van de kleur voor donkere pixels. |
| [getColor2()](#getColor2--) | Retourneert het doelformaat van de kleur voor lichte pixels. |
### getColor1() {#getColor1--}
```
public abstract Color getColor1()
```

Retourneert het doelformaat van de kleur voor donkere pixels. Alleen-lezen java.awt.Color.

**Retourneert:**
java.awt.Color
### getColor2() {#getColor2--}
```
public abstract Color getColor2()
```

Retourneert het doelformaat van de kleur voor lichte pixels. Alleen-lezen java.awt.Color.

**Retourneert:**
java.awt.Color