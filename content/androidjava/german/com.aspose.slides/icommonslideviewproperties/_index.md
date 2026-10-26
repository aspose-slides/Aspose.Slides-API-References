---
title: ICommonSlideViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Stellt gemeinsame Folienansichtseigenschaften dar.
type: docs
url: /de/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

Stellt gemeinsame Folienansichtseigenschaften dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getScale()](#getScale--) | Gibt das Ansichtsskalierungsverhältnis in Prozent an. |
| [setScale(int value)](#setScale-int-) | Gibt das Ansichtsskalierungsverhältnis in Prozent an. |
| [getVariableScale()](#getVariableScale--) | Gibt an, dass der Inhalt der Ansicht automatisch skaliert werden soll, um optimal in die aktuelle Fenstergröße zu passen. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Gibt an, dass der Inhalt der Ansicht automatisch skaliert werden soll, um optimal in die aktuelle Fenstergröße zu passen. |
| [getDrawingGuides()](#getDrawingGuides--) | Gibt die Sammlung der Zeichenhilfen zurück. |
### getScale() {#getScale--}
```
public abstract int getScale()
```

Gibt das Ansichtsskalierungsverhältnis in Prozent an. Lese/Schreib int.

**Rückgabe:**
int
### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```

Gibt das Ansichtsskalierungsverhältnis in Prozent an. Lese/Schreib int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```

Gibt an, dass der Inhalt der Ansicht automatisch skaliert werden soll, um optimal in die aktuelle Fenstergröße zu passen. Lese/Schreib boolean.

**Rückgabe:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```

Gibt an, dass der Inhalt der Ansicht automatisch skaliert werden soll, um optimal in die aktuelle Fenstergröße zu passen. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Gibt die Sammlung der Zeichenhilfen zurück. Nur lesen [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Fügt die neue vertikale Zeichenhilfe rechts von der Folienmitte hinzu
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
>      // Fügt die neue horizontale Zeichenhilfe unterhalb der Folienmitte hinzu
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)