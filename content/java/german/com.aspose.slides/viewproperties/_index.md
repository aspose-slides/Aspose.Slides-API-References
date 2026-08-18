---
title: ViewProperties
second_title: Aspose.Slides für Java API-Referenz
description: Präsentationsweite Ansichtseigenschaften.
type: docs
url: /de/com.aspose.slides/viewproperties/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

Ansichtseigenschaften für die gesamte Präsentation.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLastView()](#getLastView--) | Gibt den Ansichtsmodus an, der verwendet wurde, als das Präsentationsdokument zuletzt gespeichert wurde. |
| [setLastView(int value)](#setLastView-int-) | Gibt den Ansichtsmodus an, der verwendet wurde, als das Präsentationsdokument zuletzt gespeichert wurde. |
| [getShowComments()](#getShowComments--) | Gibt an, ob die Folienkommentare angezeigt werden sollen. |
| [setShowComments(byte value)](#setShowComments-byte-) | Gibt an, ob die Folienkommentare angezeigt werden sollen. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Stellt normale Ansichtseigenschaften dar. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Gibt gemeinsame Ansichtseigenschaften an, die mit dem Folienansichtsmodus verbunden sind. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Gibt gemeinsame Ansichtseigenschaften an, die mit dem Notizansichtsmodus verbunden sind. |
| [getGridSpacing()](#getGridSpacing--) | Gibt den Rasterabstand zurück oder legt ihn fest, der für das dem Präsentationsdokument zugrunde liegende Raster in Punkten verwendet werden soll. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Gibt den Rasterabstand zurück oder legt ihn fest, der für das dem Präsentationsdokument zugrunde liegende Raster in Punkten verwendet werden soll. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getLastView() {#getLastView--}
```
public final int getLastView()
```

Gibt den Ansichtsmodus an, der verwendet wurde, als das Präsentationsdokument zuletzt gespeichert wurde. Lese/Schreiben [ViewType](../../com.aspose.slides/viewtype).

**Rückgabewert:**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

Gibt den Ansichtsmodus an, der verwendet wurde, als das Präsentationsdokument zuletzt gespeichert wurde. Lese/Schreiben [ViewType](../../com.aspose.slides/viewtype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

Gibt an, ob die Folienkommentare angezeigt werden sollen. Lese/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabewert:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```

Gibt an, ob die Folienkommentare angezeigt werden sollen. Lese/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```

Stellt normale Ansichtseigenschaften dar. Die normale Ansicht besteht aus drei Inhaltsbereichen: der Folie selbst, einem seitlichen Inhaltsbereich und einem unteren Inhaltsbereich. Nur-Lesen [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Rückgabewert:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```

Gibt gemeinsame Ansichtseigenschaften an, die mit dem Folienansichtsmodus verbunden sind. Nur-Lesen [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Rückgabewert:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```

Gibt gemeinsame Ansichtseigenschaften an, die mit dem Notizansichtsmodus verbunden sind. Nur-Lesen [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Rückgabewert:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```

Gibt den Rasterabstand zurück oder legt ihn fest, der für das dem Präsentationsdokument zugrunde liegende Raster in Punkten verwendet werden soll. Lese/Schreiben float.

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

Der Wert des Rasterabstands muss eine positive Zahl sein. Der typische Wertebereich liegt zwischen 1 mm (2,8349607 Punkte) und 2 Zoll (144 Punkte).

**Rückgabewert:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```

Gibt den Rasterabstand zurück oder legt ihn fest, der für das dem Präsentationsdokument zugrunde liegende Raster in Punkten verwendet werden soll. Lese/Schreiben float.

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

Der Wert des Rasterabstands muss eine positive Zahl sein. Der typische Wertebereich liegt zwischen 1 mm (2,8349607 Punkte) und 2 Zoll (144 Punkte).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Nur-Lesen IDOMObject.

**Rückgabewert:**
com.aspose.slides.IDOMObject