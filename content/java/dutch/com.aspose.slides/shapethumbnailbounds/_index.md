---
title: ShapeThumbnailBounds
second_title: Aspose.Slides voor Java API-referentie
description: Enumeratie van typen van shape thumbnail bounds.
type: docs
url: /nl/com.aspose.slides/shapethumbnailbounds/
---
**Erfenis:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ShapeThumbnailBounds extends System.Enum
```

Enumeratie van typen van shape thumbnail bounds.
## Velden

| Field | Beschrijving |
| --- | --- |
| [Slide](#Slide) | Shape-miniatuur heeft de grootte gelijk aan slide-grootte. |
| [Shape](#Shape) | Shape-miniatuur heeft de grootte gelijk aan de shape bounds-rectangle met inachtneming van shape outline-instellingen. |
| [Appearance](#Appearance) | Shape-miniatuur heeft de grootte gelijk aan de shape appearance (in bounds van een slide). |
### Dia {#Slide}
```
public static final int Slide
```


Shape-miniatuur heeft de grootte gelijk aan slide-grootte. Shape-positie wordt bewaard.

### Vorm {#Shape}
```
public static final int Shape
```


Shape-miniatuur heeft de grootte gelijk aan de shape bounds-rectangle met inachtneming van shape outline-instellingen.

### Weergave {#Appearance}
```
public static final int Appearance
```


Shape-miniatuur heeft de grootte gelijk aan de shape appearance (in bounds van een slide). Het kan gevallen zijn waarin de shape appearance niet past in de shape bounds. B.v. rotatie, miter-samenvoeging van een scherpe hoek, 3D-effecten, enz.