---
title: LayoutPlaceholderManager
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje správce, který umožňuje přidávat zástupné objekty do snímku rozvržení.
type: docs
url: /cs/com.aspose.slides/layoutplaceholdermanager/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

Představuje správce, který umožňuje přidávat zástupné objekty do snímku rozvržení.
## Metody

| Metoda | Popis |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Přidá nový tvar zástupce do snímku rozvržení pro uložení obsahu, například obrázku, tabulky, média nebo textu. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Přidá nový tvar zástupce do snímku rozvržení pro uložení obsahu, například obrázku, tabulky, média nebo textu ve svislém směru. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Přidá nový tvar zástupce do snímku rozvržení pro uložení textového obsahu. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Přidá nový tvar zástupce do snímku rozvržení pro uložení textového obsahu ve svislém směru. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Přidá nový tvar zástupce do snímku rozvržení pro uložení obrázku. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Přidá nový tvar zástupce do snímku rozvržení pro uložení grafu. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Přidá nový tvar zástupce do snímku rozvržení pro uložení tabulky. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Přidá nový tvar zástupce do snímku rozvržení pro uložení SmartArt diagramu. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Přidá nový tvar zástupce do snímku rozvržení pro uložení mediálního objektu. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Přidá nový tvar zástupce do snímku rozvržení pro uložení online obrázku. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

Přidá nový tvar zástupce do snímku rozvržení pro uložení obsahu, například obrázku, tabulky, média nebo textu.

--------------------

> ```
> The following example shows how to add the Content placeholder shape to the layout slide.
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addContentPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice nového tvaru zástupce. |
| y | float | Y-souřadnice nového tvaru zástupce. |
| width | float | Šířka nového tvaru zástupce. |
| height | float | Výška nového tvaru zástupce. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) s obsahovým zástupcem.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Přidá nový tvar zástupce do snímku rozvržení pro uložení obsahu, například obrázku, tabulky, média nebo textu ve svislém směru.

--------------------

> ```
> The following example shows how to add the Content (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalContentPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice nového tvaru zástupce. |
| y | float | Y-souřadnice nového tvaru zástupce. |
| width | float | Šířka nového tvaru zástupce. |
| height | float | Výška nového tvaru zástupce. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) s obsahovým (vertikálním) zástupcem.
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

Přidá nový tvar zástupce do snímku rozvržení pro uložení textového obsahu.

--------------------

> ```
> The following example shows how to add the Text placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTextPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice nového tvaru zástupce. |
| y | float | Y-souřadnice nového tvaru zástupce. |
| width | float | Šířka nového tvaru zástupce. |
| height | float | Výška nového tvaru zástupce. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) s textovým zástupcem.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Přidá nový tvar zástupce do snímku rozvržení pro uložení textového obsahu ve svislém směru.

--------------------

> ```
> The following example shows how to add the Text (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTextPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice nového tvaru zástupce. |
| y | float | Y-souřadnice nového tvaru zástupce. |
| width | float | Šířka nového tvaru zástupce. |
| height | float | Výška nového tvaru zástupce. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) s textovým (vertikálním) zástupcem.
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Přidá nový tvar zástupce do snímku rozvržení pro uložení obrázku.

--------------------

> ```
> The following example shows how to add the Picture placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addPicturePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice nového tvaru zástupce. |
| y | float | Y-souřadnice nového tvaru zástupce. |
| width | float | Šířka nového tvaru zástupce. |
| height | float | Výška nového tvaru zástupce. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) s obrázkovým zástupcem.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

Přidá nový tvar zástupce do snímku rozvržení pro uložení grafu.

--------------------

> ```
> The following example shows how to add the Chart placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addChartPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice nového tvaru zástupce. |
| y | float | Y-souřadnice nového tvaru zástupce. |
| width | float | Šířka nového tvaru zástupce. |
| height | float | Výška nového tvaru zástupce. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) se zástupcem grafu.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

Přidá nový tvar zástupce do snímku rozvržení pro uložení tabulky.

--------------------

> ```
> The following example shows how to add the Table placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTablePlaceholder(20, 20, 500, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice nového tvaru zástupce. |
| y | float | Y-souřadnice nového tvaru zástupce. |
| width | float | Šířka nového tvaru zástupce. |
| height | float | Výška nového tvaru zástupce. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) se zástupcem tabulky.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

Přidá nový tvar zástupce do snímku rozvržení pro uložení SmartArt diagramu.

--------------------

> ```
> The following example shows how to add the SmartArt placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addSmartArtPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice nového tvaru zástupce. |
| y | float | Y-souřadnice nového tvaru zástupce. |
| width | float | Šířka nového tvaru zástupce. |
| height | float | Výška nového tvaru zástupce. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) se SmartArt zástupcem.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Přidá nový tvar zástupce do snímku rozvržení pro uložení mediálního objektu.

--------------------

> ```
> The following example shows how to add the Media placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addMediaPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice nového tvaru zástupce. |
| y | float | Y-souřadnice nového tvaru zástupce. |
| width | float | Šířka nového tvaru zástupce. |
| height | float | Výška nového tvaru zástupce. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) se zástupcem média.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

Přidá nový tvar zástupce do snímku rozvržení pro uložení online obrázku.

--------------------

> ```
> The following example shows how to add the Online Image placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addOnlineImagePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice nového tvaru zástupce. |
| y | float | Y-souřadnice nového tvaru zástupce. |
| width | float | Šířka nového tvaru zástupce. |
| height | float | Výška nového tvaru zástupce. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) s online obrázkovým zástupcem.