---
title: IViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Präsentationsweite Ansichtseigenschaften.
type: docs
url: /de/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

Präsentationsweite Ansichtseigenschaften.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLastView()](#getLastView--) | Gibt den Ansichtsmodus an, der beim letzten Speichern des Präsentationsdokuments verwendet wurde. |
| [setLastView(int value)](#setLastView-int-) | Gibt den Ansichtsmodus an, der beim letzten Speichern des Präsentationsdokuments verwendet wurde. |
| [getShowComments()](#getShowComments--) | Gibt an, ob die Folienkommentare angezeigt werden sollen. |
| [setShowComments(byte value)](#setShowComments-byte-) | Gibt an, ob die Folienkommentare angezeigt werden sollen. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Gibt die mit dem Folienansichtsmodus verbundenen allgemeinen Ansichtseigenschaften an. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Gibt die mit dem Notizansichtsmodus verbundenen allgemeinen Ansichtseigenschaften an. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Stellt normale Ansichtseigenschaften dar. |
| [getGridSpacing()](#getGridSpacing--) | Gibt den Rasterabstand zurück oder legt ihn fest, der für das Raster zugrunde liegend des Präsentationsdokuments verwendet werden soll, in Punkten. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Gibt den Rasterabstand zurück oder legt ihn fest, der für das Raster zugrunde liegend des Präsentationsdokuments verwendet werden soll, in Punkten. |

### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

Gibt den Ansichtsmodus an, der beim letzten Speichern des Präsentationsdokuments verwendet wurde. Lese/Schreib [ViewType](../../com.aspose.slides/viewtype).

**Rückgabe:**
int

### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

Gibt den Ansichtsmodus an, der beim letzten Speichern des Präsentationsdokuments verwendet wurde. Lese/Schreib [ViewType](../../com.aspose.slides/viewtype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

Gibt an, ob die Folienkommentare angezeigt werden sollen. Lese/Schreib [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte

### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

Gibt an, ob die Folienkommentare angezeigt werden sollen. Lese/Schreib [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

Gibt die mit dem Folienansichtsmodus verbundenen allgemeinen Ansichtseigenschaften an. Nur-Lesen [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Rückgabe:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)

### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

Gibt die mit dem Notizansichtsmodus verbundenen allgemeinen Ansichtseigenschaften an. Nur-Lesen [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Rückgabe:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)

### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

Stellt normale Ansichtseigenschaften dar. Die normale Ansicht besteht aus drei Inhaltsbereichen: der Folie selbst, einem seitlichen Inhaltsbereich und einem unteren Inhaltsbereich. Nur-Lesen [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Rückgabe:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)

### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

Gibt den Rasterabstand zurück oder legt ihn fest, der für das Raster zugrunde liegend des Präsentationsdokuments verwendet werden soll, in Punkten. Lese/Schreib float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Der Wert des Rasterabstands muss eine positive Zahl sein. Der typische Wertebereich liegt zwischen 1 mm (2.8349607 Punkte) und 2 Zoll (144 Punkte).

**Rückgabe:**
float

### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

Gibt den Rasterabstand zurück oder legt ihn fest, der für das Raster zugrunde liegend des Präsentationsdokuments verwendet werden soll, in Punkten. Lese/Schreib float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Der Wert des Rasterabstands muss eine positive Zahl sein. Der typische Wertebereich liegt zwischen 1 mm (2.8349607 Punkte) und 2 Zoll (144 Punkte).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |