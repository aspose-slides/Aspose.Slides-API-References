---
title: LayoutPlaceholderManager
second_title: Aspose.Slides Java API referencia
description: Képviseli azt a menedzsert, amely lehetővé teszi, hogy helyőrzőket adjon hozzá az elrendezési diához.
type: docs
url: /hu/com.aspose.slides/layoutplaceholdermanager/
---
**Öröklés:**
java.lang.Object

**Minden implementált interfész:**
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

Ez a menedzser lehetővé teszi, hogy helyőrzőket adjon hozzá az elrendezési diához.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad hozzá az elrendezési diához, amely tartalmat, például képet, táblázatot, médiát vagy szöveget tartalmaz. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad hozzá az elrendezési diához, amely tartalmat, például képet, táblázatot, médiát vagy szöveget függőleges irányban tartalmaz. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad hozzá az elrendezési diához, amely szövegtartalmat tartalmaz. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad hozzá az elrendezési diához, amely szövegtartalmat függőleges irányban tartalmaz. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad hozzá az elrendezési diához, amely képet tartalmaz. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad hozzá az elrendezési diához, amely diagramot tartalmaz. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad hozzá az elrendezési diához, amely táblázatot tartalmaz. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad hozzá az elrendezési diához, amely SmartArt diagramot tartalmaz. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad hozzá az elrendezési diához, amely médiaobjektumot tartalmaz. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad hozzá az elrendezési diához, amely online képet tartalmaz. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

Új helyőrző alakzatot ad hozzá az elrendezési diához, amely tartalmat, például képet, táblázatot, médiát vagy szöveget tartalmaz.

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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új helyőrző alakzat X koordinátája. |
| y | float | Az új helyőrző alakzat Y koordinátája. |
| width | float | Az új helyőrző alakzat szélessége. |
| height | float | Az új helyőrző alakzat magassága. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy tartalom helyőrzővel.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Új helyőrző alakzatot ad hozzá az elrendezési diához, amely tartalmat, például képet, táblázatot, médiát vagy szöveget függőleges irányban tartalmaz.

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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új helyőrző alakzat X koordinátája. |
| y | float | Az új helyőrző alakzat Y koordinátája. |
| width | float | Az új helyőrző alakzat szélessége. |
| height | float | Az új helyőrző alakzat magassága. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy tartalom (vertikális) helyőrzővel.
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

Új helyőrző alakzatot ad hozzá az elrendezési diához, amely szövegtartalmat tartalmaz.

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
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy szöveg helyőrzővel.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Új helyőrző alakzatot ad hozzá az elrendezési diához, amely szövegtartalmat függőleges irányban tartalmaz.

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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új helyőrző alakzat X koordinátája. |
| y | float | Az új helyőrző alakzat Y koordinátája. |
| width | float | Az új helyőrző alakzat szélessége. |
| height | float | Az új helyőrző alakzat magassága. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy szöveg (vertikális) helyőrzővel.
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Új helyőrző alakzatot ad hozzá az elrendezési diához, amely képet tartalmaz.

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
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy kép helyőrzővel.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

Új helyőrző alakzatot ad hozzá az elrendezési diához, amely diagramot tartalmaz.

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
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy diagram helyőrzővel.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

Új helyőrző alakzatot ad hozzá az elrendezési diához, amely táblázatot tartalmaz.

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
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy táblázat helyőrzővel.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

Új helyőrző alakzatot ad hozzá az elrendezési diához, amely SmartArt diagramot tartalmaz.

--------------------

> ```
> Az alábbi példa bemutatja, hogyan adható a SmartArt helyőrző alakzat az elrendezési diára.
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
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Új helyőrző alakzatot ad hozzá az elrendezési diához, amely médiaobjektumot tartalmaz.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új helyőrző alakzat X koordinátája. |
| y | float | Az új helyőrző alakzat Y koordinátája. |
| width | float | Az új helyőrző alakzat szélessége. |
| height | float | Az új helyőrző alakzat magassága. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy média helyőrzővel.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

Új helyőrző alakzatot ad hozzá az elrendezési diához, amely online képet tartalmaz.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új helyőrző alakzat X koordinátája. |
| y | float | Az új helyőrző alakzat Y koordinátája. |
| width | float | Az új helyőrző alakzat szélessége. |
| height | float | Az új helyőrző alakzat magassága. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy online kép helyőrzővel.