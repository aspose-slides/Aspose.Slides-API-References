---
title: LayoutPlaceholderManager
second_title: Aspose.Slides Android számára Java API hivatkozás
description: Olyan kezelőt képvisel, amely lehetővé teszi helyőrzők hozzáadását az elrendezési diához.
type: docs
url: /hu/com.aspose.slides/layoutplaceholdermanager/
---
**Öröklődés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

Képviseli azt a kezelőt, amely lehetővé teszi helyőrzők hozzáadását az elrendezési diára.

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad az elrendezési diára, amely tartalmat, például képet, táblázatot, médiát vagy szöveget tartalmaz. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad az elrendezési diára, amely tartalmat, például képet, táblázatot, médiát vagy szöveget függőlegesen tartalmaz. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad az elrendezési diára, amely szöveges tartalmat tartalmaz. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad az elrendezési diára, amely szöveges tartalmat függőlegesen tartalmaz. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad az elrendezési diára, amely képet tartalmaz. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad az elrendezési diára, amely diagramot tartalmaz. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad az elrendezési diára, amely táblázatot tartalmaz. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad az elrendezési diára, amely SmartArt diagramot tartalmaz. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad az elrendezési diára, amely médiát tartalmaz. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Új helyőrző alakzatot ad az elrendezési diára, amely online képet tartalmaz. |

### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

Új helyőrző alakzatot ad az elrendezési diára, amely tartalmat, például képet, táblázatot, médiát vagy szöveget tartalmaz.

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
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) tartalomhelyőrzővel.

### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Új helyőrző alakzatot ad az elrendezési diára, amely tartalmat, például képet, táblázatot, médiát vagy szöveget függőlegesen tartalmaz.

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
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) függőleges tartalomhelyőrzővel.

### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

Új helyőrző alakzatot ad az elrendezési diára, amely szöveges tartalmat tartalmaz.

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
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) szöveghelyőrzővel.

### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Új helyőrző alakzatot ad az elrendezési diára, amely szöveges tartalmat függőlegesen tartalmaz.

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
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) függőleges szöveghelyőrzővel.

### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Új helyőrző alakzatot ad az elrendezési diára, amely képet tartalmaz.

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
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) képpel rendelkező helyőrző.

### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

Új helyőrző alakzatot ad az elrendezési diára, amely diagramot tartalmaz.

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
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) diagramhelyőrzővel.

### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

Új helyőrző alakzatot ad az elrendezési diára, amely táblázatot tartalmaz.

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
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) táblázathelyőrzővel.

### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

Új helyőrző alakzatot ad az elrendezési diára, amely SmartArt diagramot tartalmaz.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Az új helyőrző alakzat X koordinátája. |
| y | float | Az új helyőrző alakzat Y koordinátája. |
| width | float | Az új helyőrző alakzat szélessége. |
| height | float | Az új helyőrző alakzat magassága. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) SmartArt helyőrzővel.

### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Új helyőrző alakzatot ad az elrendezési diára, amely médiát tartalmaz.

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
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) médiahelyőrzővel.

### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

Új helyőrző alakzatot ad az elrendezési diára, amely online képet tartalmaz.

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
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) online képpel rendelkező helyőrző.