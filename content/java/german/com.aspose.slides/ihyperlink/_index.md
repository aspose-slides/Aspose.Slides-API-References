---
title: IHyperlink
second_title: Aspose.Slides for Java API Reference
description: Stellt einen Hyperlink dar.
type: docs
url: /de/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

Stellt einen Hyperlink dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getActionType()](#getActionType--) | Gibt den Typ der Aktion von HyperLinkEx zurück. |
| [getExternalUrl()](#getExternalUrl--) | Gibt die externe URL an. Wenn diese Eigenschaft nicht null wird, wird die Eigenschaft TargetSlide null. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Stellt einen Hyperlink dar, der für diesen Abschnitt festgelegt ist, unabhängig vom tatsächlichen Inhalt des Abschnitts. |
| [getTargetSlide()](#getTargetSlide--) | Gibt diese Folie zurück, wenn HyperLinkEx eine bestimmte Folie anvisiert. |
| [getTargetFrame()](#getTargetFrame--) | Gibt das Frame im übergeordneten HTML-Frameset für das Ziel des übergeordneten Hyperlinks zurück, falls vorhanden. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Gibt das Frame im übergeordneten HTML-Frameset für das Ziel des übergeordneten Hyperlinks zurück, falls vorhanden. |
| [getTooltip()](#getTooltip--) | Gibt die Zeichenkette zurück, die in einer Benutzeroberfläche in Verbindung mit dem übergeordneten Hyperlink angezeigt werden kann. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Gibt die Zeichenkette zurück, die in einer Benutzeroberfläche in Verbindung mit dem übergeordneten Hyperlink angezeigt werden kann. |
| [getHistory()](#getHistory--) | Bestimmt, ob das Ziel des übergeordneten Hyperlinks einer Liste betrachteter Hyperlinks hinzugefügt werden soll, wenn es aufgerufen wird. |
| [setHistory(boolean value)](#setHistory-boolean-) | Bestimmt, ob das Ziel des übergeordneten Hyperlinks einer Liste betrachteter Hyperlinks hinzugefügt werden soll, wenn es aufgerufen wird. |
| [getHighlightClick()](#getHighlightClick--) | Bestimmt, ob der Hyperlink beim Klicken hervorgehoben werden soll. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Bestimmt, ob der Hyperlink beim Klicken hervorgehoben werden soll. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Bestimmt, ob der Klang beim Klicken auf den Hyperlink gestoppt werden soll. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Bestimmt, ob der Klang beim Klicken auf den Hyperlink gestoppt werden soll. |
| [getSound()](#getSound--) | Stellt den abgespielten Klang des Hyperlinks dar. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Stellt den abgespielten Klang des Hyperlinks dar. |
| [getColorSource()](#getColorSource--) | Stellt die Quelle der Hyperlink-Farbe dar – entweder Stile oder Abschnittsformat. |
| [setColorSource(int value)](#setColorSource-int-) | Stellt die Quelle der Hyperlink-Farbe dar – entweder Stile oder Abschnittsformat. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Bestimmt, ob die beiden Hyperlink-Instanzen gleich sind. |
### getActionType() {#getActionType--}
```
public abstract int getActionType()
```


Gibt den Typ der Aktion von HyperLinkEx zurück. Nur Lesezugriff [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Rückgabe:**
int
### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```


Gibt die externe URL an. Wenn diese Eigenschaft nicht null wird, wird die Eigenschaft TargetSlide null. Nur Lesezugriff String.

**Rückgabe:**
java.lang.String
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```


Stellt einen Hyperlink dar, der für diesen Abschnitt festgelegt ist, unabhängig vom tatsächlichen Inhalt des Abschnitts.

--------------------

PowerPoint verhält sich bei Links und dem zugehörigen Text in einem Abschnitt speziell. Es ermöglicht, für den Hyperlink einen Text in Form einer gültigen URL zu erstellen, die von der tatsächlichen Adresse des Links abweicht. In diesem Fall wird beim Betrachten des Links im Bearbeitungsfenster der Textabschnitt angepasst. Diese Eigenschaft stellt den ursprünglichen Wert des Hyperlinks dar.

**Rückgabe:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```


Gibt diese Folie zurück, wenn HyperLinkEx eine bestimmte Folie anvisiert. Wenn diese Eigenschaft nicht null wird, wird die Eigenschaft ExternalUrl null. Nur Lesezugriff [ISlide](../../com.aspose.slides/islide).

**Rückgabe:**
[ISlide](../../com.aspose.slides/islide)
### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```


Gibt das Frame im übergeordneten HTML-Frameset für das Ziel des übergeordneten Hyperlinks zurück, falls vorhanden. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```


Gibt das Frame im übergeordneten HTML-Frameset für das Ziel des übergeordneten Hyperlinks zurück, falls vorhanden. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```


Gibt die Zeichenkette zurück, die in einer Benutzeroberfläche in Verbindung mit dem übergeordneten Hyperlink angezeigt werden kann. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```


Gibt die Zeichenkette zurück, die in einer Benutzeroberfläche in Verbindung mit dem übergeordneten Hyperlink angezeigt werden kann. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```


Bestimmt, ob das Ziel des übergeordneten Hyperlinks einer Liste betrachteter Hyperlinks hinzugefügt werden soll, wenn es aufgerufen wird. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```


Bestimmt, ob das Ziel des übergeordneten Hyperlinks einer Liste betrachteter Hyperlinks hinzugefügt werden soll, wenn es aufgerufen wird. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```


Bestimmt, ob der Hyperlink beim Klicken hervorgehoben werden soll. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```


Bestimmt, ob der Hyperlink beim Klicken hervorgehoben werden soll. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```


Bestimmt, ob der Klang beim Klicken auf den Hyperlink gestoppt werden soll. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```


Bestimmt, ob der Klang beim Klicken auf den Hyperlink gestoppt werden soll. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


Stellt den abgespielten Klang des Hyperlinks dar. Lesen/Schreiben [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Hole den Hyperlink der ersten Form
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extrahiere den Hyperlink-Sound in ein Byte-Array
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
public abstract void setSound(IAudio value)
```


Stellt den abgespielten Klang des Hyperlinks dar. Lesen/Schreiben [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Hole den Hyperlink der ersten Form
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extrahiere den Hyperlink-Sound in ein Byte-Array
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
public abstract int getColorSource()
```


Stellt die Quelle der Hyperlink-Farbe dar – entweder Stile oder Abschnittsformat. Lesen/Schreiben [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Rückgabe:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```


Stellt die Quelle der Hyperlink-Farbe dar – entweder Stile oder Abschnittsformat. Lesen/Schreiben [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```


Bestimmt, ob die beiden Hyperlink-Instanzen gleich sind.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Der Hyperlink, mit dem der aktuelle Hyperlink verglichen wird. |

**Rückgabe:**
boolean – **true**, wenn der angegebene Hyperlink dem aktuellen Hyperlink entspricht; andernfalls **false**.