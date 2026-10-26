---
title: INormalViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Stellt Normalansichtseigenschaften dar.
type: docs
url: /de/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

Stellt Normalansichtseigenschaften dar. Die Normalansicht besteht aus drei Inhaltsbereichen: der Folie selbst, einem seitlichen Inhaltsbereich und einem unteren Inhaltsbereich.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Gibt an, ob die Anwendung Symbole anzeigen soll, wenn Umrissinhalt in einem der Inhaltsbereiche des Normalansichtsmodus angezeigt wird. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Gibt an, ob die Anwendung Symbole anzeigen soll, wenn Umrissinhalt in einem der Inhaltsbereiche des Normalansichtsmodus angezeigt wird. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Gibt an, ob der vertikale Splitter in den minimierten Zustand springen soll, wenn der seitliche Bereich ausreichend klein ist. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Gibt an, ob der vertikale Splitter in den minimierten Zustand springen soll, wenn der seitliche Bereich ausreichend klein ist. |
| [getVerticalBarState()](#getVerticalBarState--) | Gibt den Zustand an, in dem die vertikale Splitterleiste angezeigt werden soll. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Gibt den Zustand an, in dem die vertikale Splitterleiste angezeigt werden soll. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Gibt den Zustand an, in dem die horizontale Splitterleiste angezeigt werden soll. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Gibt den Zustand an, in dem die horizontale Splitterleiste angezeigt werden soll. |
| [getPreferSingleView()](#getPreferSingleView--) | Gibt an, ob der Benutzer die Anzeige eines vollfensterigen Einzel-Inhaltsbereichs der Standard-Normalansicht mit drei Inhaltsbereichen bevorzugt. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Gibt an, ob der Benutzer die Anzeige eines vollfensterigen Einzel-Inhaltsbereichs der Standard-Normalansicht mit drei Inhaltsbereichen bevorzugt. |
| [getRestoredLeft()](#getRestoredLeft--) | Dieses Element gibt die Größe des seitlichen Inhaltsbereichs der Normalansicht an, wenn der Bereich eine variable wiederhergestellte Größe (weder minimiert noch maximiert) hat. |
| [getRestoredTop()](#getRestoredTop--) | Dieses Element gibt die Größe des oberen Folienbereichs der Normalansicht an, wenn der Bereich eine variable wiederhergestellte Größe (weder minimiert noch maximiert) hat. |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

Gibt an, ob die Anwendung Symbole anzeigen soll, wenn Umrissinhalt in einem der Inhaltsbereiche des Normalansichtsmodus angezeigt wird. Lese/Schreib boolean.

**Rückgabe:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

Gibt an, ob die Anwendung Symbole anzeigen soll, wenn Umrissinhalt in einem der Inhaltsbereiche des Normalansichtsmodus angezeigt wird. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

Gibt an, ob der vertikale Splitter in den minimierten Zustand springen soll, wenn der seitliche Bereich ausreichend klein ist. Lese/Schreib boolean.

**Rückgabe:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

Gibt an, ob der vertikale Splitter in den minimierten Zustand springen soll, wenn der seitliche Bereich ausreichend klein ist. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

Gibt den Zustand an, in dem die vertikale Splitterleiste angezeigt werden soll. Eine vertikale Splitterleiste trennt die Folie vom seitlichen Inhaltsbereich.

**Rückgabe:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

Gibt den Zustand an, in dem die vertikale Splitterleiste angezeigt werden soll. Eine vertikale Splitterleiste trennt die Folie vom seitlichen Inhaltsbereich.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

Gibt den Zustand an, in dem die horizontale Splitterleiste angezeigt werden soll. Eine horizontale Splitterleiste trennt die Folie vom Inhaltsbereich unterhalb der Folie.

**Rückgabe:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

Gibt den Zustand an, in dem die horizontale Splitterleiste angezeigt werden soll. Eine horizontale Splitterleiste trennt die Folie vom Inhaltsbereich unterhalb der Folie.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

Gibt an, ob der Benutzer die Anzeige eines vollfensterigen Einzel-Inhaltsbereichs der Standard-Normalansicht mit drei Inhaltsbereichen bevorzugt. Wenn aktiviert, kann die Anwendung einen der Inhaltsbereiche im gesamten Fenster anzeigen. Lese/Schreib boolean.

**Rückgabe:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

Gibt an, ob der Benutzer die Anzeige eines vollfensterigen Einzel-Inhaltsbereichs der Standard-Normalansicht mit drei Inhaltsbereichen bevorzugt. Wenn aktiviert, kann die Anwendung einen der Inhaltsbereiche im gesamten Fenster anzeigen. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

Dieses Element gibt die Größe des seitlichen Inhaltsbereichs der Normalansicht an, wenn der Bereich eine variable wiederhergestellte Größe (weder minimiert noch maximiert) hat. Nur lesend [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Rückgabe:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

Dieses Element gibt die Größe des oberen Folienbereichs der Normalansicht an, wenn der Bereich eine variable wiederhergestellte Größe (weder minimiert noch maximiert) hat. Nur lesend [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Rückgabe:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)