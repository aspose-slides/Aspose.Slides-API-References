---
title: NormalViewProperties
second_title: Aspose.Slides für Java API-Referenz
description: Stellt normale Ansichtseigenschaften dar.
type: docs
url: /de/com.aspose.slides/normalviewproperties/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
```
public class NormalViewProperties implements INormalViewProperties
```

Stellt normale Ansichtseigenschaften dar. Die normale Ansicht besteht aus drei Inhaltsbereichen: der Folie selbst, einem seitlichen Inhaltsbereich und einem unteren Inhaltsbereich.

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //Instanziieren Sie ein Präsentationsobjekt, das eine Präsentationsdatei darstellt
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      pres.getViewProperties().getNormalViewProperties().setHorizontalBarState(SplitterBarStateType.Restored);
>      pres.getViewProperties().getNormalViewProperties().setVerticalBarState(SplitterBarStateType.Maximized);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setAutoAdjust(true);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setDimensionSize(80);
>      pres.getViewProperties().getNormalViewProperties().setShowOutlineIcons(true);
>      pres.save("presentation_normal_view_state.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Gibt an, ob die Anwendung Symbole anzeigen soll, wenn Outline-Inhalte in einem der Inhaltsbereiche des normalen Ansichtsmodus angezeigt werden. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Gibt an, ob die Anwendung Symbole anzeigen soll, wenn Outline-Inhalte in einem der Inhaltsbereiche des normalen Ansichtsmodus angezeigt werden. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Gibt an, ob der vertikale Trenner in den minimierten Zustand springen soll, wenn der Seitenbereich ausreichend klein ist. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Gibt an, ob der vertikale Trenner in den minimierten Zustand springen soll, wenn der Seitenbereich ausreichend klein ist. |
| [getVerticalBarState()](#getVerticalBarState--) | Gibt den Zustand an, in dem die vertikale Trennleiste angezeigt werden soll. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Gibt den Zustand an, in dem die vertikale Trennleiste angezeigt werden soll. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Gibt den Zustand an, in dem die horizontale Trennleiste angezeigt werden soll. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Gibt den Zustand an, in dem die horizontale Trennleiste angezeigt werden soll. |
| [getPreferSingleView()](#getPreferSingleView--) | Gibt an, ob der Benutzer es bevorzugt, einen Vollfenster-Einzel-Inhaltsbereich anstelle der Standard-Normalansicht mit drei Inhaltsbereichen zu sehen. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Gibt an, ob der Benutzer es bevorzugt, einen Vollfenster-Einzel-Inhaltsbereich anstelle der Standard-Normalansicht mit drei Inhaltsbereichen zu sehen. |
| [getRestoredLeft()](#getRestoredLeft--) | Dieses Element legt die Größe des seitlichen Inhaltsbereichs der normalen Ansicht fest, wenn der Bereich eine variable wiederhergestellte Größe hat (weder minimiert noch maximiert). |
| [getRestoredTop()](#getRestoredTop--) | Dieses Element legt die Größe des oberen Folienbereichs der normalen Ansicht fest, wenn der Bereich eine variable wiederhergestellte Größe hat (weder minimiert noch maximiert). |

### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

Gibt an, ob die Anwendung Symbole anzeigen soll, wenn Outline-Inhalte in einem der Inhaltsbereiche des normalen Ansichtsmodus angezeigt werden. Lese-/Schreib-Boolean.

**Rückgabewert:**
boolean

### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

Gibt an, ob die Anwendung Symbole anzeigen soll, wenn Outline-Inhalte in einem der Inhaltsbereiche des normalen Ansichtsmodus angezeigt werden. Lese-/Schreib-Boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

Gibt an, ob der vertikale Trenner in den minimierten Zustand springen soll, wenn der Seitenbereich ausreichend klein ist. Lese-/Schreib-Boolean.

**Rückgabewert:**
boolean

### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

Gibt an, ob der vertikale Trenner in den minimierten Zustand springen soll, wenn der Seitenbereich ausreichend klein ist. Lese-/Schreib-Boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

Gibt den Zustand an, in dem die vertikale Trennleiste angezeigt werden soll. Eine vertikale Trennleiste trennt die Folie vom seitlichen Inhaltsbereich.

**Rückgabewert:**
int

### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

Gibt den Zustand an, in dem die vertikale Trennleiste angezeigt werden soll. Eine vertikale Trennleiste trennt die Folie vom seitlichen Inhaltsbereich.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

Gibt den Zustand an, in dem die horizontale Trennleiste angezeigt werden soll. Eine horizontale Trennleiste trennt die Folie vom Inhaltsbereich unterhalb der Folie.

**Rückgabewert:**
int

### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

Gibt den Zustand an, in dem die horizontale Trennleiste angezeigt werden soll. Eine horizontale Trennleiste trennt die Folie vom Inhaltsbereich unterhalb der Folie.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

Gibt an, ob der Benutzer es bevorzugt, einen Vollfenster-Einzel-Inhaltsbereich anstelle der Standard-Normalansicht mit drei Inhaltsbereichen zu sehen. Wenn aktiviert, kann die Anwendung wählen, einen der Inhaltsbereiche im gesamten Fenster anzuzeigen. Lese-/Schreib-Boolean.

**Rückgabewert:**
boolean

### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

Gibt an, ob der Benutzer es bevorzugt, einen Vollfenster-Einzel-Inhaltsbereich anstelle der Standard-Normalansicht mit drei Inhaltsbereichen zu sehen. Wenn aktiviert, kann die Anwendung wählen, einen der Inhaltsbereiche im gesamten Fenster anzuzeigen. Lese-/Schreib-Boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

Dieses Element legt die Größe des seitlichen Inhaltsbereichs der normalen Ansicht fest, wenn der Bereich eine variable wiederhergestellte Größe hat (weder minimiert noch maximiert). Nur lesbar [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Rückgabewert:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)

### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

Dieses Element legt die Größe des oberen Folienbereichs der normalen Ansicht fest, wenn der Bereich eine variable wiederhergestellte Größe hat (weder minimiert noch maximiert). Nur lesbar [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Rückgabewert:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)