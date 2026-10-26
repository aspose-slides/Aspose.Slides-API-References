---
title: Hyperlink
second_title: Aspose.Slides für Android über die Java API-Referenz
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
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | Erstellt eine Instanz eines Hyperlinks, der auf eine bestimmte Folie verweist. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | Erstellt eine Instanz eines Hyperlinks mittels eines anderen Hyperlinks als Quelle und überschreibt sekundäre Eigenschaften. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | Gibt einen speziellen "do nothing" Hyperlink zurück. |
| [getMedia()](#getMedia--) | Gibt einen speziellen "play mediafile" Hyperlink zurück. |
| [getNextSlide()](#getNextSlide--) | Gibt einen Hyperlink zur nächsten Folie zurück. |
| [getPreviousSlide()](#getPreviousSlide--) | Gibt einen Hyperlink zur vorherigen Folie zurück. |
| [getFirstSlide()](#getFirstSlide--) | Gibt einen Hyperlink zur ersten Folie der Präsentation zurück. |
| [getLastSlide()](#getLastSlide--) | Gibt einen Hyperlink zur letzten Folie der Präsentation zurück. |
| [getLastVievedSlide()](#getLastVievedSlide--) | Gibt einen Hyperlink zur zuletzt angesehenen Folie zurück. |
| [getEndShow()](#getEndShow--) | Gibt einen Hyperlink zurück, der die Show beendet. |
| [getActionType()](#getActionType--) | Gibt den Typ der Hyperlink-Aktion zurück. |
| [getExternalUrl()](#getExternalUrl--) | Gibt die externe URL an. |
| [getTargetSlide()](#getTargetSlide--) | Wenn der Hyperlink eine bestimmte Folie anspricht, wird diese Folie zurückgegeben. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Stellt einen Hyperlink dar, der für diesen Abschnitt festgelegt ist, ungeachtet des tatsächlichen Inhalts des Abschnitts. |
| [getTargetFrame()](#getTargetFrame--) | Gibt das Frame im übergeordneten HTML-Frameset für das Ziel des übergeordneten Hyperlinks zurück, sofern vorhanden. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Gibt das Frame im übergeordneten HTML-Frameset für das Ziel des übergeordneten Hyperlinks zurück, sofern vorhanden. |
| [getTooltip()](#getTooltip--) | Gibt die Zeichenkette zurück, die in einer Benutzeroberfläche in Verbindung mit dem übergeordneten Hyperlink angezeigt werden kann. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Gibt die Zeichenkette zurück, die in einer Benutzeroberfläche in Verbindung mit dem übergeordneten Hyperlink angezeigt werden kann. |
| [getHistory()](#getHistory--) | Bestimmt, ob das Ziel des übergeordneten Hyperlinks bei Aufruf zu einer Liste betrachteter Hyperlinks hinzugefügt wird. |
| [setHistory(boolean value)](#setHistory-boolean-) | Bestimmt, ob das Ziel des übergeordneten Hyperlinks bei Aufruf zu einer Liste betrachteter Hyperlinks hinzugefügt wird. |
| [getHighlightClick()](#getHighlightClick--) | Bestimmt, ob der Hyperlink beim Klicken hervorgehoben werden soll. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Bestimmt, ob der Hyperlink beim Klicken hervorgehoben werden soll. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Bestimmt, ob der Ton beim Klicken des Hyperlinks gestoppt werden soll. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Bestimmt, ob der Ton beim Klicken des Hyperlinks gestoppt werden soll. |
| [getSound()](#getSound--) | Stellt den abspielenden Ton des Hyperlinks dar. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Stellt den abspielenden Ton des Hyperlinks dar. |
| [getColorSource()](#getColorSource--) | Stellt die Quelle der Hyperlink-Farbe dar – entweder Stile oder Abschnittsformat. |
| [setColorSource(int value)](#setColorSource-int-) | Stellt die Quelle der Hyperlink-Farbe dar – entweder Stile oder Abschnittsformat. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob die beiden Hyperlink-Instanzen gleich sind. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Bestimmt, ob die beiden Hyperlink-Instanzen gleich sind. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Prüft zwei Hyperlinks auf Gleichheit. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Prüft zwei Hyperlinks auf Ungleichheit. |
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

Erstellt eine Instanz eines Hyperlinks, der auf eine bestimmte Folie verweist. Hinweis: Der erstellte Hyperlink sollte einem Objekt derselben Präsentation zugewiesen werden, andernfalls wird der Link als NoAction gespeichert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Ziel-Folie. |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

Erstellt eine Instanz eines Hyperlinks mittels eines anderen Hyperlinks als Quelle und überschreibt sekundäre Eigenschaften.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | Quell-Hyperlink |
| targetFrame | java.lang.String | Ziel-Frame |
| tooltip | java.lang.String | Tooltip-Text |
| history | boolean | Bestimmt, ob das Ziel des übergeordneten Hyperlinks bei Aufruf zu einer Liste betrachteter Hyperlinks hinzugefügt wird. |
| stopSoundsOnClick | boolean | Bestimmt, ob der Ton beim Klicken des Hyperlinks gestoppt werden soll. |
| highlightClick | boolean | Bestimmt, ob der Hyperlink beim Klicken hervorgehoben werden soll. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur-Lese long.

**Rückgabewert:**  
long

### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

Gibt einen speziellen "do nothing" Hyperlink zurück. Nur-Lese [Hyperlink](../../com.aspose.slides/hyperlink).

**Rückgabewert:**  
[Hyperlink](../../com.aspose.slides/hyperlink)

### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

Gibt einen speziellen "play mediafile" Hyperlink zurück. Verwendet in AudioFrame und VideoFrame. Nur-Lese [Hyperlink](../../com.aspose.slides/hyperlink).

**Rückgabewert:**  
[Hyperlink](../../com.aspose.slides/hyperlink)

### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

Gibt einen Hyperlink zur nächsten Folie zurück. Nur-Lese [Hyperlink](../../com.aspose.slides/hyperlink).

**Rückgabewert:**  
[Hyperlink](../../com.aspose.slides/hyperlink)

### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

Gibt einen Hyperlink zur vorherigen Folie zurück. Nur-Lese [Hyperlink](../../com.aspose.slides/hyperlink).

**Rückgabewert:**  
[Hyperlink](../../com.aspose.slides/hyperlink)

### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

Gibt einen Hyperlink zur ersten Folie der Präsentation zurück. Nur-Lese [Hyperlink](../../com.aspose.slides/hyperlink).

**Rückgabewert:**  
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

Gibt einen Hyperlink zur letzten Folie der Präsentation zurück. Nur-Lese [Hyperlink](../../com.aspose.slides/hyperlink).

**Rückgabewert:**  
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

Gibt einen Hyperlink zur zuletzt angesehenen Folie zurück. Nur-Lese [Hyperlink](../../com.aspose.slides/hyperlink).

**Rückgabewert:**  
[Hyperlink](../../com.aspose.slides/hyperlink)

### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

Gibt einen Hyperlink zurück, der die Show beendet. Nur-Lese [Hyperlink](../../com.aspose.slides/hyperlink).

**Rückgabewert:**  
[Hyperlink](../../com.aspose.slides/hyperlink)

### getActionType() {#getActionType--}
```
public final int getActionType()
```

Gibt den Typ der Hyperlink-Aktion zurück. Nur-Lese [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Rückgabewert:**  
int

### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

Gibt die externe URL an. Nur-Lese String.

**Rückgabewert:**  
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Wenn der Hyperlink eine bestimmte Folie anspricht, wird diese Folie zurückgegeben. Nur-Lese [ISlide](../../com.aspose.slides/islide).

**Rückgabewert:**  
[ISlide](../../com.aspose.slides/islide)

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

Stellt einen Hyperlink dar, der für diesen Abschnitt festgelegt ist, ungeachtet des tatsächlichen Inhalts des Abschnitts.

--------------------

PowerPoint verhält sich speziell für Links und den zugehörigen Text in einem Abschnitt. Es ermöglicht, den Text für den Hyperlink in Form einer gültigen URL zu erstellen, die von der tatsächlichen Adresse des Links abweicht. In diesem Fall wird beim Betrachten des Links im Bearbeitungsfenster der Textabschnitt angepasst. Diese Eigenschaft stellt den Originalwert des Hyperlinks dar.

**Rückgabewert:**  
java.lang.String

### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

Gibt das Frame im übergeordneten HTML-Frameset für das Ziel des übergeordneten Hyperlinks zurück, sofern vorhanden. Lese/Schreib String.

**Rückgabewert:**  
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

Gibt das Frame im übergeordneten HTML-Frameset für das Ziel des übergeordneten Hyperlinks zurück, sofern vorhanden. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

Gibt die Zeichenkette zurück, die in einer Benutzeroberfläche in Verbindung mit dem übergeordneten Hyperlink angezeigt werden kann. Lese/Schreib String.

**Rückgabewert:**  
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

Gibt die Zeichenkette zurück, die in einer Benutzeroberfläche in Verbindung mit dem übergeordneten Hyperlink angezeigt werden kann. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

Bestimmt, ob das Ziel des übergeordneten Hyperlinks bei Aufruf zu einer Liste betrachteter Hyperlinks hinzugefügt wird. Lese/Schreib boolean.

**Rückgabewert:**  
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

Bestimmt, ob das Ziel des übergeordneten Hyperlinks bei Aufruf zu einer Liste betrachteter Hyperlinks hinzugefügt wird. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

Bestimmt, ob der Hyperlink beim Klicken hervorgehoben werden soll. Lese/Schreib boolean.

**Rückgabewert:**  
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

Bestimmt, ob der Hyperlink beim Klicken hervorgehoben werden soll. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

Bestimmt, ob der Ton beim Klicken des Hyperlinks gestoppt werden soll. Lese/Schreib boolean.

**Rückgabewert:**  
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

Bestimmt, ob der Ton beim Klicken des Hyperlinks gestoppt werden soll. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Stellt den abspielenden Ton des Hyperlinks dar. Lese/Schreib [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Holt den Hyperlink der ersten Form
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extrahiert den Hyperlink Sound als Byte Array
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Rückgabewert:**  
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Stellt den abspielenden Ton des Hyperlinks dar. Lese/Schreib [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Holt den Hyperlink der ersten Form
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extrahiert den Hyperlink Sound als Byte Array
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

Stellt die Quelle der Hyperlink-Farbe dar – entweder Stile oder Abschnittsformat. Lese/Schreib [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Rückgabewert:**  
int

### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

Stellt die Quelle der Hyperlink-Farbe dar – entweder Stile oder Abschnittsformat. Lese/Schreib [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

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

**Rückgabewert:**  
boolean – **true**, wenn der angegebene Hyperlink dem aktuellen Hyperlink entspricht; sonst **false**.

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

Bestimmt, ob die beiden Hyperlink-Instanzen gleich sind.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Der Hyperlink, mit dem der aktuelle Hyperlink verglichen wird. |

**Rückgabewert:**  
boolean – **true**, wenn der angegebene Hyperlink dem aktuellen Hyperlink entspricht; sonst **false**.

### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

Prüft zwei Hyperlinks auf Gleichheit.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Erster zu testender Hyperlink. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Zweiter zu testender Hyperlink. |

**Rückgabewert:**  
boolean – **true**, wenn die Hyperlinks gleich sind.

### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

Prüft zwei Hyperlinks auf Ungleichheit.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Erster zu testender Hyperlink. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Zweiter zu testender Hyperlink. |

**Rückgabewert:**  
boolean – **false**, wenn die Hyperlinks gleich sind.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als Hashfunktion für einen bestimmten Typ, geeignet für den Einsatz in Hash-Algorithmen und Datenstrukturen wie einer Hashtabelle.

**Rückgabewert:**  
int – Hashcode für eine URL.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Nur-Lese IDOMObject.

**Rückgabewert:**  
com.aspose.slides.IDOMObject