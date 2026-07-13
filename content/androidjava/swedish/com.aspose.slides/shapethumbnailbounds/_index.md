---
title: ShapeThumbnailBounds
second_title: Aspose.Slides för Android via Java API-referens
description: Uppräkning av typer av bildförhandsgränser för former.
type: docs
url: /sv/com.aspose.slides/shapethumbnailbounds/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ShapeThumbnailBounds extends System.Enum
```

Uppräkning av typer av bildförhandsgränser för former.
## Fields

| Field | Description |
| --- | --- |
| [Slide](#Slide) | Formens miniatyrbild får storleken lika med bildens storlek. |
| [Shape](#Shape) | Formens miniatyrbild får storleken lika med formens avgränsningsrektangel med hänsyn till formens konturinställningar. |
| [Appearance](#Appearance) | Formens miniatyrbild får storleken lika med formens utseende (inom bildens gränser). |
### Bild {#Slide}
```
public static final int Slide
```

Formens miniatyrbild får storleken lika med bildens storlek. Formens position sparas.

### Form {#Shape}
```
public static final int Shape
```

Formens miniatyrbild får storleken lika med formens avgränsningsrektangel med hänsyn till formens konturinställningar.

### Utseende {#Appearance}
```
public static final int Appearance
```

Formens miniatyrbild får storleken lika med formens utseende (inom bildens gränser). Det kan finnas fall då formens utseende inte passar inom formens avgränsningar. T.ex. rotation, sned kant av spetsig vinkel, 3D-effekter, etc.