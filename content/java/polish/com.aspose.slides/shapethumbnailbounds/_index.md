---
title: ShapeThumbnailBounds
second_title: Odwołanie do API Aspose.Slides dla Java
description: Wyliczenie typów granic miniatury kształtu.
type: docs
url: /pl/com.aspose.slides/shapethumbnailbounds/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ShapeThumbnailBounds extends System.Enum
```

Wyliczenie typów granic miniatury kształtu.
## Pola

| Pole | Opis |
| --- | --- |
| [Slide](#Slide) | Miniatura kształtu będzie miała rozmiar równy rozmiarowi slajdu. |
| [Shape](#Shape) | Miniatura kształtu będzie miała rozmiar równy prostokątowi granic kształtu, uwzględniając ustawienia konturu kształtu. |
| [Appearance](#Appearance) | Miniatura kształtu będzie miała rozmiar równy wyglądowi kształtu (w granicach slajdu). |
### Slide {#Slide}
```
public static final int Slide
```

Miniatura Shape będzie miała rozmiar równy rozmiarowi slajdu. Pozycja Shape zostanie zachowana.

### Shape {#Shape}
```
public static final int Shape
```

Miniatura Shape będzie miała rozmiar równy prostokątowi granic kształtu, uwzględniając ustawienia konturu kształtu.

### Appearance {#Appearance}
```
public static final int Appearance
```

Miniatura Shape będzie miała rozmiar równy wyglądowi kształtu (w granicach slajdu). Mogą wystąpić przypadki, w których wygląd kształtu nie mieści się w granicach kształtu. Np. rotacja, łączenie ostrym kątem, efekty 3D itp.