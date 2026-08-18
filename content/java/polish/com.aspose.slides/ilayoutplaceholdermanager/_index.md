---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje menedżera, który umożliwia dodawanie symboli zastępczych do slajdu układu.
type: docs
url: /pl/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

Reprezentuje menedżera, który umożliwia dodawanie symboli zastępczych do slajdu układu.
## Metody

| Metoda | Opis |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Dodaje nowy kształt symbolu zastępczego do slajdu układu, aby przechowywać zawartość, taką jak obraz, tabela, multimedia lub tekst. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Dodaje nowy kształt symbolu zastępczego do slajdu układu, aby przechowywać zawartość, taką jak obraz, tabela, multimedia lub tekst w pionowym kierunku. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Dodaje nowy kształt symbolu zastępczego do slajdu układu, aby przechowywać tekst. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Dodaje nowy kształt symbolu zastępczego do slajdu układu, aby przechowywać tekst w pionowym kierunku. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Dodaje nowy kształt symbolu zastępczego do slajdu układu, aby przechowywać obraz. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Dodaje nowy kształt symbolu zastępczego do slajdu układu, aby przechowywać wykres. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Dodaje nowy kształt symbolu zastępczego do slajdu układu, aby przechowywać tabelę. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Dodaje nowy kształt symbolu zastępczego do slajdu układu, aby przechowywać diagram SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Dodaje nowy kształt symbolu zastępczego do slajdu układu, aby przechowywać obiekt multimedialny. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Dodaje nowy kształt symbolu zastępczego do slajdu układu, aby przechowywać obraz online. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

Dodaje nowy kształt symbolu zastępczego do slajdu układu, aby przechowywać zawartość, taką jak obraz, tabela, multimedia lub tekst.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna X nowego kształtu symbolu zastępczego. |
| y | float | Współrzędna Y nowego kształtu symbolu zastępczego. |
| width | float | Szerokość nowego kształtu symbolu zastępczego. |
| height | float | Wysokość nowego kształtu symbolu zastępczego. |

**Zwraca:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Utworzono [IAutoShape](../../com.aspose.slides/iautoshape) z symbolem zastępczym zawartości.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Dodaje nowy kształt symbolu zastępczego do slajdu układu, aby przechowywać zawartość, taką jak obraz, tabela, multimedia lub tekst w pionowym kierunku.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna X nowego kształtu symbolu zastępczego. |
| y | float | Współrzędna Y nowego kształtu symbolu zastępczego. |
| width | float | Szerokość nowego kształtu symbolu zastępczego. |
| height | float | Wysokość nowego kształtu symbolu zastępczego. |

**Zwraca:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Utworzono [IAutoShape](../../com.aspose.slides/iautoshape) z symbolem zastępczym zawartości (pionowej).
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

Dodaje nowy kształt symbolu zastępczego do slajdu układu, aby przechowywać tekst.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna X nowego kształtu symbolu zastępczego. |
| y | float | Współrzędna Y nowego kształtu symbolu zastępczego. |
| width | float | Szerokość nowego kształtu symbolu zastępczego. |
| height | float | Wysokość nowego kształtu symbolu zastępczego. |

**Zwraca:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Utworzono [IAutoShape](../../com.aspose.slides/iautoshape) z symbolem zastępczym tekstowym.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Dodaje nowy kształt symbolu zastępczego do slajdu układu, aby przechowywać tekst w pionowym kierunku.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna X nowego kształtu symbolu zastępczego. |
| y | float | Współrzędna Y nowego kształtu symbolu zastępczego. |
| width | float | Szerokość nowego kształtu symbolu zastępczego. |
| height | float | Wysokość nowego kształtu symbolu zastępczego. |

**Zwraca:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Utworzono [IAutoShape](../../com.aspose.slides/iautoshape) z symbolem zastępczym tekstowym (pionowym).
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Dodaje nowy kształt symbolu zastępczego do slajdu układu, aby przechowywać obraz.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna X nowego kształtu symbolu zastępczego. |
| y | float | Współrzędna Y nowego kształtu symbolu zastępczego. |
| width | float | Szerokość nowego kształtu symbolu zastępczego. |
| height | float | Wysokość nowego kształtu symbolu zastępczego. |

**Zwraca:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Utworzono [IAutoShape](../../com.aspose.slides/iautoshape) z symbolem zastępczym obrazu.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

Dodaje nowy kształt symbolu zastępczego do slajdu układu, aby przechowywać wykres.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna X nowego kształtu symbolu zastępczego. |
| y | float | Współrzędna Y nowego kształtu symbolu zastępczego. |
| width | float | Szerokość nowego kształtu symbolu zastępczego. |
| height | float | Wysokość nowego kształtu symbolu zastępczego. |

**Zwraca:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Utworzono [IAutoShape](../../com.aspose.slides/iautoshape) z symbolem zastępczym wykresu.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

Dodaje nowy kształt symbolu zastępczego do slajdu układu, aby przechowywać tabelę.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna X nowego kształtu symbolu zastępczego. |
| y | float | Współrzędna Y nowego kształtu symbolu zastępczego. |
| width | float | Szerokość nowego kształtu symbolu zastępczego. |
| height | float | Wysokość nowego kształtu symbolu zastępczego. |

**Zwraca:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Utworzono [IAutoShape](../../com.aspose.slides/iautoshape) z symbolem zastępczym tabeli.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

Dodaje nowy kształt symbolu zastępczego do slajdu układu, aby przechowywać diagram SmartArt.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna X nowego kształtu symbolu zastępczego. |
| y | float | Współrzędna Y nowego kształtu symbolu zastępczego. |
| width | float | Szerokość nowego kształtu symbolu zastępczego. |
| height | float | Wysokość nowego kształtu symbolu zastępczego. |

**Zwraca:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Utworzono [IAutoShape](../../com.aspose.slides/iautoshape) z symbolem zastępczym SmartArt.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Dodaje nowy kształt symbolu zastępczego do slajdu układu, aby przechowywać obiekt multimedialny.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna X nowego kształtu symbolu zastępczego. |
| y | float | Współrzędna Y nowego kształtu symbolu zastępczego. |
| width | float | Szerokość nowego kształtu symbolu zastępczego. |
| height | float | Wysokość nowego kształtu symbolu zastępczego. |

**Zwraca:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Utworzono [IAutoShape](../../com.aspose.slides/iautoshape) z symbolem zastępczym multimediów.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

Dodaje nowy kształt symbolu zastępczego do slajdu układu, aby przechowywać obraz online.

--------------------

> ```
> Poniższy przykład pokazuje, jak dodać kształt symbolu zastępczego Online Image do slajdu układu.
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
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna X nowego kształtu symbolu zastępczego. |
| y | float | Współrzędna Y nowego kształtu symbolu zastępczego. |
| width | float | Szerokość nowego kształtu symbolu zastępczego. |
| height | float | Wysokość nowego kształtu symbolu zastępczego. |

**Zwraca:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Utworzono [IAutoShape](../../com.aspose.slides/iautoshape) z symbolem zastępczym obrazu online.