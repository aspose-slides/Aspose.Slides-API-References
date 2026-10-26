---
title: ShapeThumbnailBounds
second_title: Aspose.Slides för Java API-referens
description: Uppräkning av typer av miniatyrbilder för formens gränser.
type: docs
url: /sv/com.aspose.slides/shapethumbnailbounds/
---
**Arv:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ShapeThumbnailBounds extends System.Enum
```

Uppräkning av typer av miniatyrbilder för formens gränser.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Slide](#Slide) | Miniatyrbilden för formen kommer att ha storleken lika med bildens storlek. |
| [Shape](#Shape) | Miniatyrbilden för formen kommer att ha storleken lika med formens avgränsningsrektangel med hänsyn till formens konturinställningar. |
| [Appearance](#Appearance) | Miniatyrbilden för formen kommer att ha storleken lika med formens utseende (inom en bilds gränser). |
### Slide {#Slide}
```
public static final int Slide
```


Miniatyrbilden för formen kommer att ha storleken lika med bildens storlek. Formens position kommer att sparas.

### Shape {#Shape}
```
public static final int Shape
```


Miniatyrbilden för formen kommer att ha storleken lika med formens avgränsningsrektangel med hänsyn till formens konturinställningar.

### Appearance {#Appearance}
```
public static final int Appearance
```


Miniatyrbilden för formen kommer att ha storleken lika med formens utseende (inom en bilds gränser). Det kan finnas fall då formens utseende inte passar in i formens gränser. Till exempel rotation, snedställd fog av vass vinkel, 3D-effekter, osv.