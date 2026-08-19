---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Java API Reference
description: Represents manager that allows you to add placeholders to the layout slide.
type: docs
url: /cs/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

Reprezentuje správce, který vám umožňuje přidávat zástupné objekty do rozložení snímku.
## Methods

| Method | Description |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do rozložení snímku pro uložení obsahu, například obrázku, tabulky, média nebo textu. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do rozložení snímku pro uložení obsahu, například obrázku, tabulky, média nebo textu ve svislém směru. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do rozložení snímku pro uložení textového obsahu. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do rozložení snímku pro uložení textového obsahu ve svislém směru. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do rozložení snímku pro uložení obrázku. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do rozložení snímku pro uložení grafu. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do rozložení snímku pro uložení tabulky. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do rozložení snímku pro uložení diagramu SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do rozložení snímku pro uložení mediálního objektu. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Přidá nový tvar zástupného objektu do rozložení snímku pro uložení online obrázku. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```


Přidá nový tvar zástupného objektu do rozložení snímku pro uložení obsahu, například obrázku, tabulky, média nebo textu.

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
| x | float | Souřadnice X nového tvaru placeholderu. |
| y | float | Souřadnice Y nového tvaru placeholderu. |
| width | float | Šířka nového tvaru placeholderu. |
| height | float | Výška nového tvaru placeholderu. |

**Návratová hodnota:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) s placeholderem typu Content.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```


Přidá nový tvar zástupného objektu do rozložení snímku pro uložení obsahu, například obrázku, tabulky, média nebo textu ve svislém směru.

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
| x | float | Souřadnice X nového tvaru placeholderu. |
| y | float | Souřadnice Y nového tvaru placeholderu. |
| width | float | Šířka nového tvaru placeholderu. |
| height | float | Výška nového tvaru placeholderu. |

**Návratová hodnota:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) s placeholderem typu Content (Vertical).
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```


Přidá nový tvar zástupného objektu do rozložení snímku pro uložení textového obsahu.

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
| x | float | Souřadnice X nového tvaru placeholderu. |
| y | float | Souřadnice Y nového tvaru placeholderu. |
| width | float | Šířka nového tvaru placeholderu. |
| height | float | Výška nového tvaru placeholderu. |

**Návratová hodnota:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) s placeholderem typu Text.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```


Přidá nový tvar zástupného objektu do rozložení snímku pro uložení textového obsahu ve svislém směru.

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
| x | float | Souřadnice X nového tvaru placeholderu. |
| y | float | Souřadnice Y nového tvaru placeholderu. |
| width | float | Šířka nového tvaru placeholderu. |
| height | float | Výška nového tvaru placeholderu. |

**Návratová hodnota:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) s placeholderem typu Text (Vertical).
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```


Přidá nový tvar zástupného objektu do rozložení snímku pro uložení obrázku.

--------------------

> ```
> Následující příklad ukazuje, jak přidat tvar placeholderu typu Picture do rozložení snímku.
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
| x | float | Souřadnice X nového tvaru placeholderu. |
| y | float | Souřadnice Y nového tvaru placeholderu. |
| width | float | Šířka nového tvaru placeholderu. |
| height | float | Výška nového tvaru placeholderu. |

**Návratová hodnota:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) s placeholderem typu Picture.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```


Přidá nový tvar zástupného objektu do rozložení snímku pro uložení grafu.

--------------------

> ```
> Následující příklad ukazuje, jak přidat tvar placeholderu typu Chart do rozložení snímku.
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
| x | float | Souřadnice X nového tvaru placeholderu. |
| y | float | Souřadnice Y nového tvaru placeholderu. |
| width | float | Šířka nového tvaru placeholderu. |
| height | float | Výška nového tvaru placeholderu. |

**Návratová hodnota:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) s placeholderem typu Chart.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```


Přidá nový tvar zástupného objektu do rozložení snímku pro uložení tabulky.

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
| x | float | Souřadnice X nového tvaru placeholderu. |
| y | float | Souřadnice Y nového tvaru placeholderu. |
| width | float | Šířka nového tvaru placeholderu. |
| height | float | Výška nového tvaru placeholderu. |

**Návratová hodnota:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) s placeholderem typu Table.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```


Přidá nový tvar zástupného objektu do rozložení snímku pro uložení diagramu SmartArt.

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
| x | float | Souřadnice X nového tvaru placeholderu. |
| y | float | Souřadnice Y nového tvaru placeholderu. |
| width | float | Šířka nového tvaru placeholderu. |
| height | float | Výška nového tvaru placeholderu. |

**Návratová hodnota:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) s placeholderem typu SmartArt.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```


Přidá nový tvar zástupného objektu do rozložení snímku pro uložení mediálního objektu.

--------------------

> ```
> Následující příklad ukazuje, jak přidat tvar placeholderu typu Media do rozložení snímku.
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
| x | float | Souřadnice X nového tvaru placeholderu. |
| y | float | Souřadnice Y nového tvaru placeholderu. |
| width | float | Šířka nového tvaru placeholderu. |
| height | float | Výška nového tvaru placeholderu. |

**Návratová hodnota:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) s placeholderem typu Media.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```


Přidá nový tvar zástupného objektu do rozložení snímku pro uložení online obrázku.

--------------------

> ```
> Následující příklad ukazuje, jak přidat tvar placeholderu typu Online Image do rozložení snímku.
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
| x | float | Souřadnice X nového tvaru placeholderu. |
| y | float | Souřadnice Y nového tvaru placeholderu. |
| width | float | Šířka nového tvaru placeholderu. |
| height | float | Výška nového tvaru placeholderu. |

**Návratová hodnota:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Vytvořeno [IAutoShape](../../com.aspose.slides/iautoshape) s placeholderem typu Online Image.