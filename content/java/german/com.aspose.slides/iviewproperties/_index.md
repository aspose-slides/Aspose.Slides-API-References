---
title: IViewProperties
second_title: Aspose.Slides for Java API Reference
description: Presentation wide view properties.
type: docs
url: /de/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

Ansichtseigenschaften für die gesamte Präsentation.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLastView()](#getLastView--) | Gibt den Ansichtmodus an, der beim letzten Speichern des Präsentationsdokuments verwendet wurde. |
| [setLastView(int value)](#setLastView-int-) | Gibt den Ansichtmodus an, der beim letzten Speichern des Präsentationsdokuments verwendet wurde. |
| [getShowComments()](#getShowComments--) | Gibt an, ob die Folienkommentare angezeigt werden sollen. |
| [setShowComments(byte value)](#setShowComments-byte-) | Gibt an, ob die Folienkommentare angezeigt werden sollen. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Gibt die mit dem Folienansichtsmodus verbundenen allgemeinen Ansichtseigenschaften an. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Gibt die mit dem Notizansichtsmodus verbundenen allgemeinen Ansichtseigenschaften an. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Stellt normale Ansichtseigenschaften dar. |
| [getGridSpacing()](#getGridSpacing--) | Gibt den Rasterabstand zurück oder legt ihn fest, der für das dem Präsentationsdokument zugrunde liegende Raster in Punkten verwendet werden soll. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Gibt den Rasterabstand zurück oder legt ihn fest, der für das dem Präsentationsdokument zugrunde liegende Raster in Punkten verwendet werden soll. |

### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

Gibt den Ansichtmodus an, der beim letzten Speichern des Präsentationsdokuments verwendet wurde. Lesen/Schreiben [ViewType](../../com.aspose.slides/viewtype).

**Rückgabewert:**
int

### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

Gibt den Ansichtmodus an, der beim letzten Speichern des Präsentationsdokuments verwendet wurde. Lesen/Schreiben [ViewType](../../com.aspose.slides/viewtype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

Gibt an, ob die Folienkommentare angezeigt werden sollen. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabewert:**
byte

### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

Gibt an, ob die Folienkommentare angezeigt werden sollen. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

Gibt die mit dem Folienansichtsmodus verbundenen allgemeinen Ansichtseigenschaften an. Nur lesen [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Rückgabewert:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)

### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

Gibt die mit dem Notizansichtsmodus verbundenen allgemeinen Ansichtseigenschaften an. Nur lesen [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Rückgabewert:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)

### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

Stellt normale Ansichtseigenschaften dar. Die Normalansicht besteht aus drei Inhaltsbereichen: der Folie selbst, einem seitlichen Inhaltsbereich und einem unteren Inhaltsbereich. Nur lesen [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Rückgabewert:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)

### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

Gibt den Rasterabstand zurück oder legt ihn fest, der für das dem Präsentationsdokument zugrunde liegende Raster in Punkten verwendet werden soll. Lesen/Schreiben float.

--------------------

> ```
> Der folgende Beispielcode zeigt, wie man den Rasterabstand in einer PowerPoint-Präsentation ändert.
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

Der Rasterabstand muss eine positive Zahl sein. Der typische Wertebereich liegt zwischen 1 mm (2,8349607 Punkte) und 2 Zoll (144 Punkte).

**Rückgabewert:**
float

### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

Gibt den Rasterabstand zurück oder legt ihn fest, der für das dem Präsentationsdokument zugrunde liegende Raster in Punkten verwendet werden soll. Lesen/Schreiben float.

--------------------

> ```
> Der folgende Beispielcode zeigt, wie man den Rasterabstand in einer PowerPoint-Präsentation ändert.
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

Der Rasterabstand muss eine positive Zahl sein. Der typische Wertebereich liegt zwischen 1 mm (2,8349607 Punkte) und 2 Zoll (144 Punkte).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |