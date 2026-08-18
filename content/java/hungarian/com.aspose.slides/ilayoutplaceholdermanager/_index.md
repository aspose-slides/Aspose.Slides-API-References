---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Java API Reference
description: Represents manager that allows you to add placeholders to the layout slide.
type: docs
url: /hu/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

Az a menedzser, amely lehetővé teszi helyőrzők hozzáadását az elrendezési diához.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad hozzá az elrendezési diához, amely tartalmat (például képet, táblázatot, médiát vagy szöveget) tárol. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad hozzá az elrendezési diához, amely tartalmat (például képet, táblázatot, médiát vagy szöveget) függőleges irányban tárol. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad hozzá az elrendezési diához, amely szövegtartalmat tárol. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad hozzá az elrendezési diához, amely szövegtartalmat függőleges irányban tárol. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad hozzá az elrendezési diához, amely képet tárol. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad hozzá az elrendezési diához, amely diagramot tárol. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad hozzá az elrendezési diához, amely táblázatot tárol. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad hozzá az elrendezési diához, amely SmartArt diagramot tárol. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad hozzá az elrendezési diához, amely médiaobjektumot tárol. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad hozzá az elrendezési diához, amely online képet tárol. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```


Új helyőrző alakzatot ad hozzá az elrendezési diához, amely tartalmat (például képet, táblázatot, médiát vagy szöveget) tárol.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új helyőrző alakzat X koordinátája. |
| y | float | Az új helyőrző alakzat Y koordinátája. |
| width | float | Az új helyőrző alakzat szélessége. |
| height | float | Az új helyőrző alakzat magassága. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy Content helyőrzővel.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```


Új helyőrző alakzatot ad hozzá az elrendezési diához, amely tartalmat (például képet, táblázatot, médiát vagy szöveget) függőleges irányban tárol.

--------------------

> ```
> Az alábbi példa bemutatja, hogyan adhat hozzá egy Content (Vertical) helyőrző alakzatot az elrendezési diához.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalContentPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új helyőrző alakzat X koordinátája. |
| y | float | Az új helyőrző alakzat Y koordinátája. |
| width | float | Az új helyőrző alakzat szélessége. |
| height | float | Az új helyőrző alakzat magassága. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy Content (Vertical) helyőrzővel.
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```


Új helyőrző alakzatot ad hozzá az elrendezési diához, amely szövegtartalmat tárol.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új helyőrző alakzat X koordinátája. |
| y | float | Az új helyőrző alakzat Y koordinátája. |
| width | float | Az új helyőrző alakzat szélessége. |
| height | float | Az új helyőrző alakzat magassága. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy Text helyőrzővel.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```


Új helyőrző alakzatot ad hozzá az elrendezési diához, amely szövegtartalmat függőleges irányban tárol.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új helyőrző alakzat X koordinátája. |
| y | float | Az új helyőrző alakzat Y koordinátája. |
| width | float | Az új helyőrző alakzat szélessége. |
| height | float | Az új helyőrző alakzat magassága. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy Text (Vertical) helyőrzővel.
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```


Új helyőrző alakzatot ad hozzá az elrendezési diához, amely képet tárol.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új helyőrző alakzat X koordinátája. |
| y | float | Az új helyőrző alakzat Y koordinátája. |
| width | float | Az új helyőrző alakzat szélessége. |
| height | float | Az új helyőrző alakzat magassága. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy Picture helyőrzővel.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```


Új helyőrző alakzatot ad hozzá az elrendezési diához, amely diagramot tárol.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új helyőrző alakzat X koordinátája. |
| y | float | Az új helyőrző alakzat Y koordinátája. |
| width | float | Az új helyőrző alakzat szélessége. |
| height | float | Az új helyőrző alakzat magassága. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy Chart helyőrzővel.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```


Új helyőrző alakzatot ad hozzá az elrendezési diához, amely táblázatot tárol.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új helyőrző alakzat X koordinátája. |
| y | float | Az új helyőrző alakzat Y koordinátája. |
| width | float | Az új helyőrző alakzat szélessége. |
| height | float | Az új helyőrző alakzat magassága. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy Table helyőrzővel.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```


Új helyőrző alakzatot ad hozzá az elrendezési diához, amely SmartArt diagramot tárol.

--------------------

> ```
> Az alábbi példa bemutatja, hogyan adhat hozzá egy SmartArt helyőrző alakzatot az elrendezési diához.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addSmartArtPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új helyőrző alakzat X koordinátája. |
| y | float | Az új helyőrző alakzat Y koordinátája. |
| width | float | Az új helyőrző alakzat szélessége. |
| height | float | Az új helyőrző alakzat magassága. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy SmartArt helyőrzővel.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```


Új helyőrző alakzatot ad hozzá az elrendezési diához, amely médiaobjektumot tárol.

--------------------

> ```
> Az alábbi példa bemutatja, hogyan adhat hozzá egy Media helyőrző alakzatot az elrendezési diához.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addMediaPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új helyőrző alakzat X koordinátája. |
| y | float | Az új helyőrző alakzat Y koordinátája. |
| width | float | Az új helyőrző alakzat szélessége. |
| height | float | Az új helyőrző alakzat magassága. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy Media helyőrzővel.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```


Új helyőrző alakzatot ad hozzá az elrendezési diához, amely online képet tárol.

--------------------

> ```
> Az alábbi példa bemutatja, hogyan adhat hozzá egy Online Image helyőrző alakzatot az elrendezési diához.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addOnlineImagePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új helyőrző alakzat X koordinátája. |
| y | float | Az új helyőrző alakzat Y koordinátája. |
| width | float | Az új helyőrző alakzat szélessége. |
| height | float | Az új helyőrző alakzat magassága. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy Online Image helyőrzővel.