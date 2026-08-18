---
title: ShapeThumbnailBounds
second_title: Aspose.Slides Java API referencia
description: A forma bélyegkép határainak típusainak felsorolása.
type: docs
url: /hu/com.aspose.slides/shapethumbnailbounds/
---
**Öröklődés:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ShapeThumbnailBounds extends System.Enum
```

A forma bélyegkép határainak típusainak felsorolása.
## Mezők

| Mező | Leírás |
| --- | --- |
| [Slide](#Slide) | A forma bélyegkép mérete megegyezik a diavetítés méretével. |
| [Shape](#Shape) | A forma bélyegkép mérete a forma határoló téglalapjának megfelelő lesz, figyelembe véve a forma körvonal beállításait. |
| [Appearance](#Appearance) | A forma bélyegkép mérete a forma megjelenésének megfelelő lesz (a diavetítés határain belül). |
### Slide {#Slide}
```
public static final int Slide
```


A forma bélyegkép mérete megegyezik a diavetítés méretével. A forma pozíciója mentésre kerül.

### Shape {#Shape}
```
public static final int Shape
```


A forma bélyegkép mérete a forma határoló téglalapjának megfelelő lesz, figyelembe véve a forma körvonal beállításait.

### Appearance {#Appearance}
```
public static final int Appearance
```


A forma bélyegkép mérete a forma megjelenésének megfelelő lesz (a diavetítés határain belül). Lehetnek olyan esetek, amikor a forma megjelenése nem illeszkedik a forma határolóba. Például forgatás, éles szög miter illesztése, 3D effektusok stb.