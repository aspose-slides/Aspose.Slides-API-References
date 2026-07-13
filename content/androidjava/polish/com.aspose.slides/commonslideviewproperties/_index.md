---
title: CommonSlideViewProperties
second_title: Aspose.Slides dla Androida poprzez odwołanie do API Java
description: Reprezentuje wspólne właściwości widoku slajdu.
type: docs
url: /pl/com.aspose.slides/commonslideviewproperties/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
```
public class CommonSlideViewProperties implements ICommonSlideViewProperties
```

Reprezentuje wspólne właściwości widoku slajdu.

--------------------

> ```
> The following example shows how to set the zoom value for slide of PowerPoint Presentation.
>  
>  // Utwórz obiekt Presentation, który reprezentuje plik prezentacji
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Ustawianie właściwości widoku prezentacji
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // Wartość powiększenia w procentach dla widoku slajdu
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // Wartość powiększenia w procentach dla widoku notatek
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metody

| Metoda | Opis |
| --- | --- |
| [getScale()](#getScale--) | Określa współczynnik skalowania widoku w procentach. |
| [setScale(int value)](#setScale-int-) | Określa współczynnik skalowania widoku w procentach. |
| [getVariableScale()](#getVariableScale--) | Określa, że zawartość widoku powinna automatycznie skalować się, aby najlepiej dopasować do aktualnego rozmiaru okna. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Określa, że zawartość widoku powinna automatycznie skalować się, aby najlepiej dopasować do aktualnego rozmiaru okna. |
| [getDrawingGuides()](#getDrawingGuides--) | Zwraca kolekcję prowadnic rysunkowych. |
### getScale() {#getScale--}
```
public final int getScale()
```


Określa współczynnik skalowania widoku w procentach. Odczyt/zapis int.

**Zwraca:**
int
### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Określa współczynnik skalowania widoku w procentach. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```


Określa, że zawartość widoku powinna automatycznie skalować się, aby najlepiej dopasować do aktualnego rozmiaru okna. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```


Określa, że zawartość widoku powinna automatycznie skalować się, aby najlepiej dopasować do aktualnego rozmiaru okna. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Zwraca kolekcję prowadnic rysunkowych. Tylko do odczytu [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Dodawanie nowej pionowej prowadnicy rysunkowej po prawej stronie centrum slajdu
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
>      // Dodawanie nowej poziomej prowadnicy rysunkowej poniżej centrum slajdu
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)