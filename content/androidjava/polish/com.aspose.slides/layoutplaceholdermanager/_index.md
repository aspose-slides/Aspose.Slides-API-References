---
title: LayoutPlaceholderManager
second_title: Aspose.Slides dla Androida poprzez referencję API Java
description: Reprezentuje menedżera, który umożliwia dodawanie pól zastępczych do slajdu układu.
type: docs
url: /pl/com.aspose.slides/layoutplaceholdermanager/
---
**Dziedziczenie:**  
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**  
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

Reprezentuje menedżera, który pozwala dodawać pola zastępcze do slajdu układu.

## Metody

| Metoda | Opis |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Dodaje nowy kształt pola zastępczego do slajdu układu, aby przechowywać zawartość, taką jak obraz, tabela, multimedia lub tekst. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Dodaje nowy kształt pola zastępczego do slajdu układu, aby przechowywać zawartość, taką jak obraz, tabela, multimedia lub tekst w pionowym kierunku. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Dodaje nowy kształt pola zastępczego do slajdu układu, aby przechowywać zawartość tekstową. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Dodaje nowy kształt pola zastępczego do slajdu układu, aby przechowywać zawartość tekstową w pionowym kierunku. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Dodaje nowy kształt pola zastępczego do slajdu układu, aby przechowywać obraz. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Dodaje nowy kształt pola zastępczego do slajdu układu, aby przechowywać wykres. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Dodaje nowy kształt pola zastępczego do slajdu układu, aby przechowywać tabelę. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Dodaje nowy kształt pola zastępczego do slajdu układu, aby przechowywać diagram SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Dodaje nowy kształt pola zastępczego do slajdu układu, aby przechowywać obiekt multimedialny. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Dodaje nowy kształt pola zastępczego do slajdu układu, aby przechowywać obraz online. |

### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

Dodaje nowy kształt pola zastępczego do slajdu układu, aby przechowywać zawartość, taką jak obraz, tabela, multimedia lub tekst.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna X nowego kształtu pola zastępczego. |
| y | float | Współrzędna Y nowego kształtu pola zastępczego. |
| width | float | Szerokość nowego kształtu pola zastępczego. |
| height | float | Wysokość nowego kształtu pola zastępczego. |

**Zwraca:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Utworzono [IAutoShape](../../com.aspose.slides/iautoshape) z placeholderem Content.

### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Dodaje nowy kształt pola zastępczego do slajdu układu, aby przechowywać zawartość, taką jak obraz, tabela, multimedia lub tekst w pionowym kierunku.

--------------------

> ```
> Poniższy przykład pokazuje, jak dodać kształt zastępczy Content (Vertical) do slajdu układu.
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
| x | float | Współrzędna X nowego kształtu pola zastępczego. |
| y | float | Współrzędna Y nowego kształtu pola zastępczego. |
| width | float | Szerokość nowego kształtu pola zastępczego. |
| height | float | Wysokość nowego kształtu pola zastępczego. |

**Zwraca:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Utworzono [IAutoShape](../../com.aspose.slides/iautoshape) z placeholderem Content (Vertical).

### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

Dodaje nowy kształt pola zastępczego do slajdu układu, aby przechowywać zawartość tekstową.

--------------------

> ```
> Poniższy przykład pokazuje, jak dodać kształt zastępczy Text do slajdu układu.
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
| x | float | Współrzędna X nowego kształtu pola zastępczego. |
| y | float | Współrzędna Y nowego kształtu pola zastępczego. |
| width | float | Szerokość nowego kształtu pola zastępczego. |
| height | float | Wysokość nowego kształtu pola zastępczego. |

**Zwraca:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Utworzono [IAutoShape](../../com.aspose.slides/iautoshape) z placeholderem Text.

### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Dodaje nowy kształt pola zastępczego do slajdu układu, aby przechowywać zawartość tekstową w pionowym kierunku.

--------------------

> ```
> Poniższy przykład pokazuje, jak dodać kształt zastępczy Text (Vertical) do slajdu układu.
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
| x | float | Współrzędna X nowego kształtu pola zastępczego. |
| y | float | Współrzędna Y nowego kształtu pola zastępczego. |
| width | float | Szerokość nowego kształtu pola zastępczego. |
| height | float | Wysokość nowego kształtu pola zastępczego. |

**Zwraca:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Utworzono [IAutoShape](../../com.aspose.slides/iautoshape) z placeholderem Text (Vertical).

### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Dodaje nowy kształt pola zastępczego do slajdu układu, aby przechowywać obraz.

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
| x | float | Współrzędna X nowego kształtu pola zastępczego. |
| y | float | Współrzędna Y nowego kształtu pola zastępczego. |
| width | float | Szerokość nowego kształtu pola zastępczego. |
| height | float | Wysokość nowego kształtu pola zastępczego. |

**Zwraca:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Utworzono [IAutoShape](../../com.aspose.slides/iautoshape) z placeholderem Picture.

### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

Dodaje nowy kształt pola zastępczego do slajdu układu, aby przechowywać wykres.

--------------------

> ```
> Poniższy przykład pokazuje, jak dodać kształt zastępczy Chart do slajdu układu.
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
| x | float | Współrzędna X nowego kształtu pola zastępczego. |
| y | float | Współrzędna Y nowego kształtu pola zastępczego. |
| width | float | Szerokość nowego kształtu pola zastępczego. |
| height | float | Wysokość nowego kształtu pola zastępczego. |

**Zwraca:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Utworzono [IAutoShape](../../com.aspose.slides/iautoshape) z placeholderem Chart.

### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

Dodaje nowy kształt pola zastępczego do slajdu układu, aby przechowywać tabelę.

--------------------

> ```
> Poniższy przykład pokazuje, jak dodać kształt zastępczy Table do slajdu układu.
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
| x | float | Współrzędna X nowego kształtu pola zastępczego. |
| y | float | Współrzędna Y nowego kształtu pola zastępczego. |
| width | float | Szerokość nowego kształtu pola zastępczego. |
| height | float | Wysokość nowego kształtu pola zastępczego. |

**Zwraca:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Utworzono [IAutoShape](../../com.aspose.slides/iautoshape) z placeholderem Table.

### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

Dodaje nowy kształt pola zastępczego do slajdu układu, aby przechowywać diagram SmartArt.

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
| x | float | Współrzędna X nowego kształtu pola zastępczego. |
| y | float | Współrzędna Y nowego kształtu pola zastępczego. |
| width | float | Szerokość nowego kształtu pola zastępczego. |
| height | float | Wysokość nowego kształtu pola zastępczego. |

**Zwraca:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Utworzono [IAutoShape](../../com.aspose.slides/iautoshape) z placeholderem SmartArt.

### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Dodaje nowy kształt pola zastępczego do slajdu układu, aby przechowywać obiekt multimedialny.

--------------------

> ```
> Poniższy przykład pokazuje, jak dodać kształt zastępczy Media do slajdu układu.
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
| x | float | Współrzędna X nowego kształtu pola zastępczego. |
| y | float | Współrzędna Y nowego kształtu pola zastępczego. |
| width | float | Szerokość nowego kształtu pola zastępczego. |
| height | float | Wysokość nowego kształtu pola zastępczego. |

**Zwraca:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Utworzono [IAutoShape](../../com.aspose.slides/iautoshape) z placeholderem Media.

### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

Dodaje nowy kształt pola zastępczego do slajdu układu, aby przechowywać obraz online.

--------------------

> ```
> Poniższy przykład pokazuje, jak dodać kształt zastępczy Online Image do slajdu układu.
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
| x | float | Współrzędna X nowego kształtu pola zastępczego. |
| y | float | Współrzędna Y nowego kształtu pola zastępczego. |
| width | float | Szerokość nowego kształtu pola zastępczego. |
| height | float | Wysokość nowego kształtu pola zastępczego. |

**Zwraca:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Utworzono [IAutoShape](../../com.aspose.slides/iautoshape) z placeholderem Online Image.