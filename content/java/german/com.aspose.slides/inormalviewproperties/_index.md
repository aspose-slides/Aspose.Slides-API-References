---
title: INormalViewProperties
second_title: Aspose.Slides für Java API-Referenz
description: Stellt Normalansicht-Eigenschaften dar.
type: docs
url: /de/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

Stellt Normalansicht-Eigenschaften dar. Die Normalansicht besteht aus drei Inhaltsbereichen: der Folie selbst, einem seitlichen Inhaltsbereich und einem unteren Inhaltsbereich.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Gibt an, ob die Anwendung Symbole anzeigen soll, wenn Outline-Inhalte in einem der Inhaltsbereiche des Normalansichtsmodus angezeigt werden. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Gibt an, ob die Anwendung Symbole anzeigen soll, wenn Outline-Inhalte in einem der Inhaltsbereiche des Normalansichtsmodus angezeigt werden. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Gibt an, ob der vertikale Trennbalken in einen minimierten Zustand einrasten soll, wenn der seitliche Bereich ausreichend klein ist. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Gibt an, ob der vertikale Trennbalken in einen minimierten Zustand einrasten soll, wenn der seitliche Bereich ausreichend klein ist. |
| [getVerticalBarState()](#getVerticalBarState--) | Gibt den Zustand an, in dem der vertikale Trennbalken angezeigt werden soll. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Gibt den Zustand an, in dem der vertikale Trennbalken angezeigt werden soll. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Gibt den Zustand an, in dem der horizontale Trennbalken angezeigt werden soll. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Gibt den Zustand an, in dem der horizontale Trennbalken angezeigt werden soll. |
| [getPreferSingleView()](#getPreferSingleView--) | Gibt an, ob der Benutzer es vorzieht, einen ein-Inhaltsbereich im Vollfenster gegenüber der standardmäßigen Normalansicht mit drei Inhaltsbereichen zu sehen. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Gibt an, ob der Benutzer es vorzieht, einen ein-Inhaltsbereich im Vollfenster gegenüber der standardmäßigen Normalansicht mit drei Inhaltsbereichen zu sehen. |
| [getRestoredLeft()](#getRestoredLeft--) | Dieses Element gibt die Größe des seitlichen Inhaltsbereichs der Normalansicht an, wenn der Bereich eine variable wiederhergestellte Größe hat (weder minimiert noch maximiert). |
| [getRestoredTop()](#getRestoredTop--) | Dieses Element gibt die Größe des oberen Folienbereichs der Normalansicht an, wenn der Bereich eine variable wiederhergestellte Größe hat (weder minimiert noch maximiert). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

Gibt an, ob die Anwendung Symbole anzeigen soll, wenn Outline-Inhalte in einem der Inhaltsbereiche des Normalansichtsmodus angezeigt werden. Lese/Schreib Boolean.

**Rückgabe:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

Gibt an, ob die Anwendung Symbole anzeigen soll, wenn Outline-Inhalte in einem der Inhaltsbereiche des Normalansichtsmodus angezeigt werden. Lese/Schreib Boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

Gibt an, ob der vertikale Trennbalken in einen minimierten Zustand einrasten soll, wenn der seitliche Bereich ausreichend klein ist. Lese/Schreib Boolean.

**Rückgabe:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

Gibt an, ob der vertikale Trennbalken in einen minimierten Zustand einrasten soll, wenn der seitliche Bereich ausreichend klein ist. Lese/Schreib Boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

Gibt den Zustand an, in dem der vertikale Trennbalken angezeigt werden soll. Ein vertikaler Trennbalken trennt die Folie vom seitlichen Inhaltsbereich.

**Rückgabe:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

Gibt den Zustand an, in dem der vertikale Trennbalken angezeigt werden soll. Ein vertikaler Trennbalken trennt die Folie vom seitlichen Inhaltsbereich.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

Gibt den Zustand an, in dem der horizontale Trennbalken angezeigt werden soll. Ein horizontaler Trennbalken trennt die Folie vom Inhaltsbereich unterhalb der Folie.

**Rückgabe:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

Gibt den Zustand an, in dem der horizontale Trennbalken angezeigt werden soll. Ein horizontaler Trennbalken trennt die Folie vom Inhaltsbereich unterhalb der Folie.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

Gibt an, ob der Benutzer es vorzieht, einen ein-Inhaltsbereich im Vollfenster gegenüber der standardmäßigen Normalansicht mit drei Inhaltsbereichen zu sehen. Wenn aktiviert, kann die Anwendung wählen, einen der Inhaltsbereiche im gesamten Fenster anzuzeigen. Lese/Schreib Boolean.

**Rückgabe:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

Gibt an, ob der Benutzer es vorzieht, einen ein-Inhaltsbereich im Vollfenster gegenüber der standardmäßigen Normalansicht mit drei Inhaltsbereichen zu sehen. Wenn aktiviert, kann die Anwendung wählen, einen der Inhaltsbereiche im gesamten Fenster anzuzeigen. Lese/Schreib Boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

Dieses Element gibt die Größe des seitlichen Inhaltsbereichs der Normalansicht an, wenn der Bereich eine variable wiederhergestellte Größe hat (weder minimiert noch maximiert). Nur lesen [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Rückgabe:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

Dieses Element gibt die Größe des oberen Folienbereichs der Normalansicht an, wenn der Bereich eine variable wiederhergestellte Größe hat (weder minimiert noch maximiert). Nur lesen [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Rückgabe:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)