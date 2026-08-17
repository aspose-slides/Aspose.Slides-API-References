---
title: IPortionFormat
second_title: Aspose.Slides für Java API Referenz
description: Diese Klasse enthält die Formatierungseigenschaften des Textabschnitts.
type: docs
url: /de/com.aspose.slides/iportionformat/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

Diese Klasse enthält die Formatierungseigenschaften des Textabschnitts. Im Gegensatz zu [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) sind alle Eigenschaften dieser Klasse schreibbar.

--------------------

Diese Klasse wird verwendet, um die für den jeweiligen Abschnitt definierten Formatierungseigenschaften des Textabschnitts zurückzugeben und zu bearbeiten. Das bedeutet, dass beim Abrufen von Werten keine Vererbung angewendet wird, sodass Sie in den meisten Fällen Werte erhalten, die „undefiniert“ bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich vererbter Werte zu erhalten, müssen Sie die Methode [getEffective](../../com.aspose.slides/iportionformat\#getEffective) verwenden, die eine [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)-Instanz zurückgibt.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Gibt den Bookmark-Identifikator zurück oder legt ihn fest. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Gibt den Bookmark-Identifikator zurück oder legt ihn fest. |
| [getSmartTagClean()](#getSmartTagClean--) | Bestimmt, ob das Smart-Tag bereinigt werden soll. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Bestimmt, ob das Smart-Tag bereinigt werden soll. |
| [getEffective()](#getEffective--) | Liefert die effektiven Formatierungsdaten des Abschnitts, wobei die Vererbung angewendet wird. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

Gibt den Bookmark-Identifikator zurück oder legt ihn fest. Lese/Schreib String.

**Rückgabe:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```

Gibt den Bookmark-Identifikator zurück oder legt ihn fest. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

Bestimmt, ob das Smart-Tag bereinigt werden soll. Keine Vererbung angewendet. Lese/Schreib boolean.

**Rückgabe:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

Bestimmt, ob das Smart-Tag bereinigt werden soll. Keine Vererbung angewendet. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

Liefert die effektiven Formatierungsdaten des Abschnitts, wobei die Vererbung angewendet wird.

**Rückgabe:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - Ein [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).