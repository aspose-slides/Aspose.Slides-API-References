---
title: ShapeThumbnailBounds
second_title: Aspose.Slides dla Androida - odniesienie API Java
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
| [Slide](#Slide) | Miniatura kształtu będzie mieć rozmiar równy rozmiarowi slajdu. |
| [Shape](#Shape) | Miniatura kształtu będzie mieć rozmiar równy prostokątowi granic kształtu, uwzględniając ustawienia konturu kształtu. |
| [Appearance](#Appearance) | Miniatura kształtu będzie mieć rozmiar równy wyglądowi kształtu (w granicach slajdu). |
### Slajd {#Slide}
```
public static final int Slide
```

Miniatura kształtu będzie mieć rozmiar równy rozmiarowi slajdu. Pozycja kształtu zostanie zapisana.

### Kształt {#Shape}
```
public static final int Shape
```

Miniatura kształtu będzie mieć rozmiar równy prostokątowi granic kształtu, uwzględniając ustawienia konturu kształtu.

### Wygląd {#Appearance}
```
public static final int Appearance
```

Miniatura kształtu będzie mieć rozmiar równy wyglądowi kształtu (w granicach slajdu). Mogą wystąpić przypadki, gdy wygląd kształtu nie mieści się w granicach kształtu. Np. rotacja, łączenie krawędzi ostrym kątem, efekty 3D itp.