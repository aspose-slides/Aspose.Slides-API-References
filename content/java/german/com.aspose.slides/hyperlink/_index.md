---
title: Hyperlink
second_title: Aspose.Slides für Java API Referenz
description: Stellt einen Hyperlink dar.
type: docs
url: /de/com.aspose.slides/hyperlink/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

Stellt einen Hyperlink dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | Erstellt eine Instanz eines Hyperlinks. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | Erstellt eine Instanz eines Hyperlinks, der auf eine bestimmte Folie zeigt. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | Erstellt eine Instanz eines Hyperlinks unter Verwendung eines anderen Hyperlinks als Quelle und überschreibt sekundäre Eigenschaften. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | Gibt einen speziellen „nichts tun“ Hyperlink zurück. |
| [getMedia()](#getMedia--) | Gibt einen speziellen „Mediendatei abspielen“ Hyperlink zurück. |
| [getNextSlide()](#getNextSlide--) | Gibt einen Hyperlink zur nächsten Folie zurück. |
| [getPreviousSlide()](#getPreviousSlide--) | Gibt einen Hyperlink zur vorherigen Folie zurück. |
| [getFirstSlide()](#getFirstSlide--) | Gibt einen Hyperlink zur ersten Folie der Präsentation zurück. |
| [getLastSlide()](#getLastSlide--) | Gibt einen Hyperlink zur letzten Folie der Präsentation zurück. |
| [getLastVievedSlide()](#getLastVievedSlide--) | Gibt einen Hyperlink zur zuletzt angezeigten Folie zurück. |
| [getEndShow()](#getEndShow--) | Gibt einen Hyperlink zurück, der die Show beendet. |
| [getActionType()](#getActionType--) | Gibt den Typ der Hyperlink-Aktion zurück. |
| [getExternalUrl()](#getExternalUrl--) | Legt die externe URL fest. |
| [getTargetSlide()](#getTargetSlide--) | Falls der Hyperlink eine bestimmte Folie anspricht, wird diese Folie zurückgegeben. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Stellt einen Hyperlink dar, der für diesen Abschnitt festgelegt ist, ohne Rücksicht auf den tatsächlichen Inhalt des Abschnitts. |
| [getTargetFrame()](#getTargetFrame--) | Gibt das Frame innerhalb des übergeordneten HTML-Framesets für das Ziel des übergeordneten Hyperlinks zurück, falls vorhanden. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Gibt das Frame innerhalb des übergeordneten HTML-Framesets für das Ziel des übergeordneten Hyperlinks zurück, falls vorhanden. |
| [getTooltip()](#getTooltip--) | Gibt die Zeichenkette zurück, die in einer Benutzeroberfläche als zugehörig zum übergeordneten Hyperlink angezeigt werden kann. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Gibt die Zeichenkette zurück, die in einer Benutzeroberfläche als zugehörig zum übergeordneten Hyperlink angezeigt werden kann. |
| [getHistory()](#getHistory--) | Bestimmt, ob das Ziel des übergeordneten Hyperlinks bei Aufruf zu einer Liste bereits angezeigter Hyperlinks hinzugefügt werden soll. |
| [setHistory(boolean value)](#setHistory-boolean-) | Bestimmt, ob das Ziel des übergeordneten Hyperlinks bei Aufruf zu einer Liste bereits angezeigter Hyperlinks hinzugefügt werden soll. |
| [getHighlightClick()](#getHighlightClick--) | Bestimmt, ob der Hyperlink beim Klick hervorgehoben werden soll. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Bestimmt, ob der Hyperlink beim Klick hervorgehoben werden soll. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Bestimmt, ob der Ton beim Klick auf den Hyperlink gestoppt werden soll. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Bestimmt, ob der Ton beim Klick auf den Hyperlink gestoppt werden soll. |
| [getSound()](#getSound--) | Stellt den abgespielten Ton des Hyperlinks dar. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Stellt den abgespielten Ton des Hyperlinks dar. |
| [getColorSource()](#getColorSource--) | Stellt die Quelle der Hyperlink-Farbe dar – entweder Stile oder Abschnittsformat. |
| [setColorSource(int value)](#setColorSource-int-) | Stellt die Quelle der Hyperlink-Farbe dar – entweder Stile oder Abschnittsformat. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob die beiden Hyperlink-Instanzen gleich sind. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Bestimmt, ob die beiden Hyperlink-Instanzen gleich sind. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Testet zwei Hyperlinks auf Gleichheit. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Testet zwei Hyperlinks auf Ungleichheit. |
| [hashCode()](#hashCode--) | Dient als Hashfunktion für einen bestimmten Typ, geeignet für den Einsatz in Hash-Algorithmen und Datenstrukturen wie einer Hashtabelle. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

Erstellt eine Instanz eines Hyperlinks.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | java.lang.String | Hyperlink-URL. |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

Erstellt eine Instanz eines Hyperlinks, der auf eine bestimmte Folie zeigt. Hinweis: Der erstellte Hyperlink sollte einem Objekt derselben Präsentation zugewiesen werden, andernfalls wird der Link als NoAction gespeichert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Ziel-Folie. |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

Erstellt eine Instanz eines Hyperlinks unter Verwendung eines anderen Hyperlinks als Quelle und überschreibt sekundäre Eigenschaften.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | Quell-Hyperlink |
| targetFrame | java.lang.String | Ziel-Frame |
| tooltip | java.lang.String | Tooltip-Text |
| history | boolean | Bestimmt, ob das Ziel des übergeordneten Hyperlinks bei Aufruf zu einer Liste bereits angezeigter Hyperlinks hinzugefügt werden soll. |
| stopSoundsOnClick | boolean | Bestimmt, ob der Ton beim Klick auf den Hyperlink gestoppt werden soll. |
| highlightClick | boolean | Bestimmt, ob der Hyperlink beim Klick hervorgehoben werden soll. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur-Lesen long.

**Rückgabe:**
long

### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

Gibt einen speziellen „nichts tun“ Hyperlink zurück. Nur-Lesen [Hyperlink](../../com.aspose.slides/hyperlink).

**Rückgabe:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

Gibt einen speziellen „Mediendatei abspielen“ Hyperlink zurück. Verwendet in AudioFrame und VideoFrame. Nur-Lesen [Hyperlink](../../com.aspose.slides/hyperlink).

**Rückgabe:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

Gibt einen Hyperlink zur nächsten Folie zurück. Nur-Lesen [Hyperlink](../../com.aspose.slides/hyperlink).

**Rückgabe:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

Gibt einen Hyperlink zur vorherigen Folie zurück. Nur-Lesen [Hyperlink](../../com.aspose.slides/hyperlink).

**Rückgabe:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

Gibt einen Hyperlink zur ersten Folie der Präsentation zurück. Nur-Lesen [Hyperlink](../../com.aspose.slides/hyperlink).

**Rückgabe:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

Gibt einen Hyperlink zur letzten Folie der Präsentation zurück. Nur-Lesen [Hyperlink](../../com.aspose.slides/hyperlink).

**Rückgabe:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

Gibt einen Hyperlink zur zuletzt angezeigten Folie zurück. Nur-Lesen [Hyperlink](../../com.aspose.slides/hyperlink).

**Rückgabe:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

Gibt einen Hyperlink zurück, der die Show beendet. Nur-Lesen [Hyperlink](../../com.aspose.slides/hyperlink).

**Rückgabe:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getActionType() {#getActionType--}
```
public final int getActionType()
```

Gibt den Typ der Hyperlink-Aktion zurück. Nur-Lesen [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Rückgabe:**
int

### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

Legt die externe URL fest. Nur-Lesen String.

**Rückgabe:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Falls der Hyperlink eine bestimmte Folie anspricht, wird diese Folie zurückgegeben. Nur-Lesen [ISlide](../../com.aspose.slides/islide).

**Rückgabe:**
[ISlide](../../com.aspose.slides/islide)

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

Stellt einen Hyperlink dar, der für diesen Abschnitt festgelegt ist, ohne Rücksicht auf den tatsächlichen Inhalt des Abschnitts.

**Rückgabe:**
java.lang.String

### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

Gibt das Frame innerhalb des übergeordneten HTML-Framesets für das Ziel des übergeordneten Hyperlinks zurück, falls vorhanden. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

Gibt das Frame innerhalb des übergeordneten HTML-Framesets für das Ziel des übergeordneten Hyperlinks zurück, falls vorhanden. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

Gibt die Zeichenkette zurück, die in einer Benutzeroberfläche als zugehörig zum übergeordneten Hyperlink angezeigt werden kann. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

Gibt die Zeichenkette zurück, die in einer Benutzeroberfläche als zugehörig zum übergeordneten Hyperlink angezeigt werden kann. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

Bestimmt, ob das Ziel des übergeordneten Hyperlinks bei Aufruf zu einer Liste bereits angezeigter Hyperlinks hinzugefügt werden soll. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

Bestimmt, ob das Ziel des übergeordneten Hyperlinks bei Aufruf zu einer Liste bereits angezeigter Hyperlinks hinzugefügt werden soll. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

Bestimmt, ob der Hyperlink beim Klick hervorgehoben werden soll. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

Bestimmt, ob der Hyperlink beim Klick hervorgehoben werden soll. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

Bestimmt, ob der Ton beim Klick auf den Hyperlink gestoppt werden soll. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

Bestimmt, ob der Ton beim Klick auf den Hyperlink gestoppt werden soll. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Stellt den abgespielten Ton des Hyperlinks dar. Lesen/Schreiben [IAudio](../../com.aspose.slides/iaudio).

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Holt den ersten Shape-Hyperlink
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extrahiert den Hyperlink-Sound in ein Byte-Array
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Rückgabe:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Stellt den abgespielten Ton des Hyperlinks dar. Lesen/Schreiben [IAudio](../../com.aspose.slides/iaudio).

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Holt den ersten Shape-Hyperlink
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extrahiert den Hyperlink-Sound in ein Byte-Array
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public final int getColorSource()
```

Stellt die Quelle der Hyperlink-Farbe dar – entweder Stile oder Abschnittsformat. Lesen/Schreiben [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Rückgabe:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

Stellt die Quelle der Hyperlink-Farbe dar – entweder Stile oder Abschnittsformat. Lesen/Schreiben [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bestimmt, ob die beiden Hyperlink-Instanzen gleich sind.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Der Hyperlink, mit dem der aktuelle Hyperlink verglichen wird. |

**Rückgabe:**
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

Bestimmt, ob die beiden Hyperlink-Instanzen gleich sind.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Der Hyperlink, mit dem der aktuelle Hyperlink verglichen wird. |

**Rückgabe:**
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.

### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

Testet zwei Hyperlinks auf Gleichheit.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Erster zu testender Hyperlink. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Zweiter zu testender Hyperlink. |

**Rückgabe:**
boolean - **true** if hyperlinks are equal.

### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

Testet zwei Hyperlinks auf Ungleichheit.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Erster zu testender Hyperlink. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Zweiter zu testender Hyperlink. |

**Rückgabe:**
boolean - **false** if hyperlinks are equal.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als Hashfunktion für einen bestimmten Typ, geeignet für den Einsatz in Hash-Algorithmen und Datenstrukturen wie einer Hashtabelle.

**Rückgabe:**
int - Hash code for an URL.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Nur-Lesen IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject