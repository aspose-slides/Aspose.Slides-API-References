---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Android via Java API Reference
description: Representuje správce, který umožňuje přidávat zástupné objekty do rozložení snímku.
type: docs
url: /cs/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

Representuje správce, který umožňuje přidávat zástupné objekty do rozložení snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval obsah, jako je obrázek, tabulka, média nebo text. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval obsah, jako je obrázek, tabulka, média nebo text ve svislém směru. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval textový obsah. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval textový obsah ve svislém směru. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval obrázek. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval graf. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval tabulku. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval diagram SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval mediální objekt. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval online obrázek. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```


Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval obsah, jako je obrázek, tabulka, média nebo text.

--------------------

> ```
> The following example shows how to add the Content placeholder shape to the layout slide.
>  
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
| x | float | Souřadnice X nového tvaru zástupného objektu. |
| y | float | Souřadnice Y nového tvaru zástupného objektu. |
| width | float | Šířka nového tvaru zástupného objektu. |
| height | float | Výška nového tvaru zástupného objektu. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořen [IAutoShape](../../com.aspose.slides/iautoshape) s Content placeholder.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```


Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval obsah, jako je obrázek, tabulka, média nebo text ve svislém směru.

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
| x | float | Souřadnice X nového tvaru zástupného objektu. |
| y | float | Souřadnice Y nového tvaru zástupného objektu. |
| width | float | Šířka nového tvaru zástupného objektu. |
| height | float | Výška nového tvaru zástupného objektu. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořen [IAutoShape](../../com.aspose.slides/iautoshape) s Content (Vertical) placeholder.
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```


Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval textový obsah.

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
| x | float | Souřadnice X nového tvaru zástupného objektu. |
| y | float | Souřadnice Y nového tvaru zástupného objektu. |
| width | float | Šířka nového tvaru zástupného objektu. |
| height | float | Výška nového tvaru zástupného objektu. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořen [IAutoShape](../../com.aspose.slides/iautoshape) s Text placeholder.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```


Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval textový obsah ve svislém směru.

--------------------

> ```
> The following example shows how to add the Text (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalTextPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | Souřadnice X nového tvaru zástupného objektu. |
| y | float | Souřadnice Y nového tvaru zástupného objektu. |
| width | float | Šířka nového tvaru zástupného objektu. |
| height | float | Výška nového tvaru zástupného objektu. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořen [IAutoShape](../../com.aspose.slides/iautoshape) s Text (Vertical) placeholder.
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```


Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval obrázek.

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
| x | float | Souřadnice X nového tvaru zástupného objektu. |
| y | float | Souřadnice Y nového tvaru zástupného objektu. |
| width | float | Šířka nového tvaru zástupného objektu. |
| height | float | Výška nového tvaru zástupného objektu. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořen [IAutoShape](../../com.aspose.slides/iautoshape) s Picture placeholder.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```


Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval graf.

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
| x | float | Souřadnice X nového tvaru zástupného objektu. |
| y | float | Souřadnice Y nového tvaru zástupného objektu. |
| width | float | Šířka nového tvaru zástupného objektu. |
| height | float | Výška nového tvaru zástupného objektu. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořen [IAutoShape](../../com.aspose.slides/iautoshape) s Chart placeholder.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```


Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval tabulku.

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
| x | float | Souřadnice X nového tvaru zástupného objektu. |
| y | float | Souřadnice Y nového tvaru zástupného objektu. |
| width | float | Šířka nového tvaru zástupného objektu. |
| height | float | Výška nového tvaru zástupného objektu. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořen [IAutoShape](../../com.aspose.slides/iautoshape) s Table placeholder.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```


Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval diagram SmartArt.

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
| x | float | Souřadnice X nového tvaru zástupného objektu. |
| y | float | Souřadnice Y nového tvaru zástupného objektu. |
| width | float | Šířka nového tvaru zástupného objektu. |
| height | float | Výška nového tvaru zástupného objektu. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořen [IAutoShape](../../com.aspose.slides/iautoshape) s SmartArt placeholder.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```


Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval mediální objekt.

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
| x | float | Souřadnice X nového tvaru zástupného objektu. |
| y | float | Souřadnice Y nového tvaru zástupného objektu. |
| width | float | Šířka nového tvaru zástupného objektu. |
| height | float | Výška nového tvaru zástupného objektu. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořen [IAutoShape](../../com.aspose.slides/iautoshape) s Media placeholder.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```


Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval online obrázek.

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
| x | float | Souřadnice X nového tvaru zástupného objektu. |
| y | float | Souřadnice Y nového tvaru zástupného objektu. |
| width | float | Šířka nového tvaru zástupného objektu. |
| height | float | Výška nového tvaru zástupného objektu. |

**Vrací:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořen [IAutoShape](../../com.aspose.slides/iautoshape) s Online Image placeholder.