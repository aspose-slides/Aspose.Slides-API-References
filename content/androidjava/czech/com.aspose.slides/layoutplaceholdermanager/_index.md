---
title: LayoutPlaceholderManager
second_title: Aspose.Slides pro Android prostřednictvím reference Java API
description: Představuje správce, který umožňuje přidávat zástupné objekty do snímku rozvržení.
type: docs
url: /cs/com.aspose.slides/layoutplaceholdermanager/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)  
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

Představuje správce, který umožňuje přidávat zástupné objekty do snímku rozvržení.

## Metody

| Method | Description |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do snímku rozvržení pro obsah, například obrázek, tabulku, média nebo text. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do snímku rozvržení pro obsah, například obrázek, tabulku, média nebo text ve svislém směru. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do snímku rozvržení pro textový obsah. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do snímku rozvržení pro textový obsah ve svislém směru. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do snímku rozvržení pro obrázek. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do snímku rozvržení pro graf. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do snímku rozvržení pro tabulku. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do snímku rozvržení pro diagram SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do snímku rozvržení pro multimediální objekt. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do snímku rozvržení pro online obrázek. |

### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

Přidá nový tvar zástupného objektu do snímku rozvržení pro obsah, například obrázek, tabulku, média nebo text.

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Souřadnice X nového tvaru zástupného objektu. |
| y | float | Souřadnice Y nového tvaru zástupného objektu. |
| width | float | Šířka nového tvaru zástupného objektu. |
| height | float | Výška nového tvaru zástupného objektu. |

**Návratová hodnota:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) s placeholderem obsahu.

### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Přidá nový tvar zástupného objektu do snímku rozvržení pro obsah, například obrázek, tabulku, média nebo text ve svislém směru.

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Souřadnice X nového tvaru zástupného objektu. |
| y | float | Souřadnice Y nového tvaru zástupného objektu. |
| width | float | Šířka nového tvaru zástupného objektu. |
| height | float | Výška nového tvaru zástupného objektu. |

**Návratová hodnota:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) s placeholderem obsahu (vertikální).

### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

Přidá nový tvar zástupného objektu do snímku rozvržení pro textový obsah.

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Souřadnice X nového tvaru zástupného objektu. |
| y | float | Souřadnice Y nového tvaru zástupného objektu. |
| width | float | Šířka nového tvaru zástupného objektu. |
| height | float | Výška nového tvaru zástupného objektu. |

**Návratová hodnota:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) s textovým placeholderem.

### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Přidá nový tvar zástupného objektu do snímku rozvržení pro textový obsah ve svislém směru.

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Souřadnice X nového tvaru zástupného objektu. |
| y | float | Souřadnice Y nového tvaru zástupného objektu. |
| width | float | Šířka nového tvaru zástupného objektu. |
| height | float | Výška nového tvaru zástupného objektu. |

**Návratová hodnota:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) s textovým placeholderem (vertikální).

### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Přidá nový tvar zástupného objektu do snímku rozvržení pro obrázek.

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Souřadnice X nového tvaru zástupného objektu. |
| y | float | Souřadnice Y nového tvaru zástupného objektu. |
| width | float | Šířka nového tvaru zástupného objektu. |
| height | float | Výška nového tvaru zástupného objektu. |

**Návratová hodnota:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) s obrázkovým placeholderem.

### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

Přidá nový tvar zástupného objektu do snímku rozvržení pro graf.

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Souřadnice X nového tvaru zástupného objektu. |
| y | float | Souřadnice Y nového tvaru zástupného objektu. |
| width | float | Šířka nového tvaru zástupného objektu. |
| height | float | Výška nového tvaru zástupného objektu. |

**Návratová hodnota:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) s grafickým placeholderem.

### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

Přidá nový tvar zástupného objektu do snímku rozvržení pro tabulku.

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Souřadnice X nového tvaru zástupného objektu. |
| y | float | Souřadnice Y nového tvaru zástupného objektu. |
| width | float | Šířka nového tvaru zástupného objektu. |
| height | float | Výška nového tvaru zástupného objektu. |

**Návratová hodnota:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) s tabulkovým placeholderem.

### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

Přidá nový tvar zástupného objektu do snímku rozvržení pro diagram SmartArt.

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Souřadnice X nového tvaru zástupného objektu. |
| y | float | Souřadnice Y nového tvaru zástupného objektu. |
| width | float | Šířka nového tvaru zástupného objektu. |
| height | float | Výška nového tvaru zástupného objektu. |

**Návratová hodnota:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) s SmartArt placeholderem.

### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Přidá nový tvar zástupného objektu do snímku rozvržení pro multimediální objekt.

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Souřadnice X nového tvaru zástupného objektu. |
| y | float | Souřadnice Y nového tvaru zástupného objektu. |
| width | float | Šířka nového tvaru zástupného objektu. |
| height | float | Výška nového tvaru zástupného objektu. |

**Návratová hodnota:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) s multimediálním placeholderem.

### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

Přidá nový tvar zástupného objektu do snímku rozvržení pro online obrázek.

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Souřadnice X nového tvaru zástupného objektu. |
| y | float | Souřadnice Y nového tvaru zástupného objektu. |
| width | float | Šířka nového tvaru zástupného objektu. |
| height | float | Výška nového tvaru zástupného objektu. |

**Návratová hodnota:**  
[IAutoShape](../../com.aspose.slides/iautoshape) – Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) s online obrázkovým placeholderem.