---
title: ViewProperties
second_title: Aspose.Slides für Android über die Java API Referenz
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

Präsentationsweite Ansichtseigenschaften.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLastView()](#getLastView--) | Gibt den Ansichtsmodus an, der beim letzten Speichern des Präsentationsdokuments verwendet wurde. |
| [setLastView(int value)](#setLastView-int-) | Gibt den Ansichtsmodus an, der beim letzten Speichern des Präsentationsdokuments verwendet wurde. |
| [getShowComments()](#getShowComments--) | Gibt an, ob die Folienkommentare angezeigt werden sollen. |
| [setShowComments(byte value)](#setShowComments-byte-) | Gibt an, ob die Folienkommentare angezeigt werden sollen. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Stellt normale Ansichtseigenschaften dar. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Gibt gemeinsame Ansichtseigenschaften an, die mit dem Folienansichtsmodus verknüpft sind. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Gibt gemeinsame Ansichtseigenschaften an, die mit dem Notizansichtsmodus verknüpft sind. |
| [getGridSpacing()](#getGridSpacing--) | Gibt den Rasterabstand zurück oder legt ihn fest, der für das dem Präsentationsdokument zugrunde liegende Raster in Punkten verwendet werden soll. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Gibt den Rasterabstand zurück oder legt ihn fest, der für das dem Präsentationsdokument zugrunde liegende Raster in Punkten verwendet werden soll. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getLastView() {#getLastView--}
```
public final int getLastView()
```

Gibt den Ansichtsmodus an, der beim letzten Speichern des Präsentationsdokuments verwendet wurde. Lesen/Schreiben [ViewType](../../com.aspose.slides/viewtype).

**Rückgabe:**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

Gibt den Ansichtsmodus an, der beim letzten Speichern des Präsentationsdokuments verwendet wurde. Lesen/Schreiben [ViewType](../../com.aspose.slides/viewtype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

Gibt an, ob die Folienkommentare angezeigt werden sollen. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```

Gibt an, ob die Folienkommentare angezeigt werden sollen. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```

Stellt normale Ansichtseigenschaften dar. Die normale Ansicht besteht aus drei Inhaltsbereichen: der Folie selbst, einem seitlichen Inhaltsbereich und einem unteren Inhaltsbereich. Nur lesen [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Rückgabe:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```

Gibt gemeinsame Ansichtseigenschaften an, die mit dem Folienansichtsmodus verknüpft sind. Nur lesen [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Rückgabe:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```

Gibt gemeinsame Ansichtseigenschaften an, die mit dem Notizansichtsmodus verknüpft sind. Nur lesen [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Rückgabe:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```

Gibt den Rasterabstand zurück oder legt ihn fest, der für das dem Präsentationsdokument zugrunde liegende Raster in Punkten verwendet werden soll. Lesen/Schreiben float.

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

Der Rasterabstand muss eine positive Zahl sein. Der typische Wertebereich liegt zwischen 1 mm (2,8349607 Punkte) und 2 Zoll (144 Punkte).

**Rückgabe:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
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
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Objekt Parent_Immediate zurück. Nur lesen IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject