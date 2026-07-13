---
title: ICommonSlideViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Reprezentuje wspólne właściwości widoku slajdu.
type: docs
url: /pl/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

Reprezentuje wspólne właściwości widoku slajdu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getScale()](#getScale--) | Określa współczynnik skalowania widoku w procentach. |
| [setScale(int value)](#setScale-int-) | Określa współczynnik skalowania widoku w procentach. |
| [getVariableScale()](#getVariableScale--) | Określa, że zawartość widoku powinna automatycznie skalować się, aby najlepiej dopasować do bieżącego rozmiaru okna. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Określa, że zawartość widoku powinna automatycznie skalować się, aby najlepiej dopasować do bieżącego rozmiaru okna. |
| [getDrawingGuides()](#getDrawingGuides--) | Zwraca kolekcję prowadnic rysowania. |
### getScale() {#getScale--}
```
public abstract int getScale()
```

Określa współczynnik skalowania widoku w procentach. Odczyt/zapis int.

**Zwraca:**
int
### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```

Określa współczynnik skalowania widoku w procentach. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```

Określa, że zawartość widoku powinna automatycznie skalować się, aby najlepiej dopasować do bieżącego rozmiaru okna. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```

Określa, że zawartość widoku powinna automatycznie skalować się, aby najlepiej dopasować do bieżącego rozmiaru okna. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Zwraca kolekcję prowadnic rysowania. Tylko do odczytu [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Dodawanie nowej pionowej prowadnicy rysowania po prawej stronie środka slajdu
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
>      // Dodawanie nowej poziomej prowadnicy rysowania pod środkiem slajdu
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)