---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Android via Java API Reference
description: A kezelő, amely lehetővé teszi helykitöltők hozzáadását a layout diára.
type: docs
url: /hu/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

A kezelő, amely lehetővé teszi helykitöltők hozzáadását a layout diára.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Új helykitöltő alakzatot ad hozzá a layout diához, amely tartalmat, például képet, táblázatot, médiafájlt vagy szöveget tartalmaz. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Új helykitöltő alakzatot ad hozzá a layout diához, amely tartalmat, például képet, táblázatot, médiafájlt vagy szöveget tartalmaz vertikális irányban. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Új helykitöltő alakzatot ad hozzá a layout diához, amely szöveges tartalmat tartalmaz. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Új helykitöltő alakzatot ad hozzá a layout diához, amely szöveges tartalmat tartalmaz vertikális irányban. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Új helykitöltő alakzatot ad hozzá a layout diához, amely képet tartalmaz. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Új helykitöltő alakzatot ad hozzá a layout diához, amely diagramot tartalmaz. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Új helykitöltő alakzatot ad hozzá a layout diához, amely táblázatot tartalmaz. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Új helykitöltő alakzatot ad hozzá a layout diához, amely SmartArt diagramot tartalmaz. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Új helykitöltő alakzatot ad hozzá a layout diához, amely médiaobjektumot tartalmaz. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Új helykitöltő alakzatot ad hozzá a layout diához, amely online képet tartalmaz. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

Új helykitöltő alakzatot ad hozzá a layout diához, amely tartalmat, például képet, táblázatot, médiafájlt vagy szöveget tartalmaz.

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
| x | float | Az új helykitöltő alakzat X koordinátája. |
| y | float | Az új helykitöltő alakzat Y koordinátája. |
| width | float | Az új helykitöltő alakzat szélessége. |
| height | float | Az új helykitöltő alakzat magassága. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy Content helykitöltővel.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Új helykitöltő alakzatot ad hozzá a layout diához, amely tartalmat, például képet, táblázatot, médiafájlt vagy szöveget tartalmaz vertikális irányban.

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
| x | float | Az új helykitöltő alakzat X koordinátája. |
| y | float | Az új helykitöltő alakzat Y koordinátája. |
| width | float | Az új helykitöltő alakzat szélessége. |
| height | float | Az új helykitöltő alakzat magassága. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy Content (Vertical) helykitöltővel.
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

Új helykitöltő alakzatot ad hozzá a layout diához, amely szöveges tartalmat tartalmaz.

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
| x | float | Az új helykitöltő alakzat X koordinátája. |
| y | float | Az új helykitöltő alakzat Y koordinátája. |
| width | float | Az új helykitöltő alakzat szélessége. |
| height | float | Az új helykitöltő alakzat magassága. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy Text helykitöltővel.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Új helykitöltő alakzatot ad hozzá a layout diához, amely szöveges tartalmat tartalmaz vertikális irányban.

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
| x | float | Az új helykitöltő alakzat X koordinátája. |
| y | float | Az új helykitöltő alakzat Y koordinátája. |
| width | float | Az új helykitöltő alakzat szélessége. |
| height | float | Az új helykitöltő alakzat magassága. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy Text (Vertical) helykitöltővel.
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Új helykitöltő alakzatot ad hozzá a layout diához, amely képet tartalmaz.

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
| x | float | Az új helykitöltő alakzat X koordinátája. |
| y | float | Az új helykitöltő alakzat Y koordinátája. |
| width | float | Az új helykitöltő alakzat szélessége. |
| height | float | Az új helykitöltő alakzat magassága. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy Picture helykitöltővel.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

Új helykitöltő alakzatot ad hozzá a layout diához, amely diagramot tartalmaz.

--------------------

> ```
> Az alábbi példa bemutatja, hogyan lehet hozzáadni a Chart helykitöltő alakzatot a layout diához.
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
| x | float | Az új helykitöltő alakzat X koordinátája. |
| y | float | Az új helykitöltő alakzat Y koordinátája. |
| width | float | Az új helykitöltő alakzat szélessége. |
| height | float | Az új helykitöltő alakzat magassága. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy Chart helykitöltővel.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

Új helykitöltő alakzatot ad hozzá a layout diához, amely táblázatot tartalmaz.

--------------------

> ```
> Az alábbi példa bemutatja, hogyan lehet hozzáadni a Table helykitöltő alakzatot a layout diához.
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
| x | float | Az új helykitöltő alakzat X koordinátája. |
| y | float | Az új helykitöltő alakzat Y koordinátája. |
| width | float | Az új helykitöltő alakzat szélessége. |
| height | float | Az új helykitöltő alakzat magassága. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy Table helykitöltővel.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

Új helykitöltő alakzatot ad hozzá a layout diához, amely SmartArt diagramot tartalmaz.

--------------------

> ```
> Az alábbi példa bemutatja, hogyan lehet hozzáadni a SmartArt helykitöltő alakzatot a layout diához.
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
| x | float | Az új helykitöltő alakzat X koordinátája. |
| y | float | Az új helykitöltő alakzat Y koordinátája. |
| width | float | Az új helykitöltő alakzat szélessége. |
| height | float | Az új helykitöltő alakzat magassága. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy SmartArt helykitöltővel.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Új helykitöltő alakzatot ad hozzá a layout diához, amely médiaobjektumot tartalmaz.

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
| x | float | Az új helykitöltő alakzat X koordinátája. |
| y | float | Az új helykitöltő alakzat Y koordinátája. |
| width | float | Az új helykitöltő alakzat szélessége. |
| height | float | Az új helykitöltő alakzat magassága. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy Media helykitöltővel.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

Új helykitöltő alakzatot ad hozzá a layout diához, amely online képet tartalmaz.

--------------------

> ```
> Az alábbi példa bemutatja, hogyan lehet hozzáadni az Online Image helykitöltő alakzatot a layout diához.
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
| x | float | Az új helykitöltő alakzat X koordinátája. |
| y | float | Az új helykitöltő alakzat Y koordinátája. |
| width | float | Az új helykitöltő alakzat szélessége. |
| height | float | Az új helykitöltő alakzat magassága. |

**Visszatérési érték:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Létrehozott [IAutoShape](../../com.aspose.slides/iautoshape) egy Online Image helykitöltővel.