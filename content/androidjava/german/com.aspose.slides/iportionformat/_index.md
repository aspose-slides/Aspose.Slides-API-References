---
title: IPortionFormat
second_title: Aspose.Slides für Android über Java API-Referenz
description: Diese Klasse enthält die Textabschnitt-Formatierungseigenschaften.
type: docs
url: /de/com.aspose.slides/iportionformat/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

Diese Klasse enthält die Formatierungseigenschaften des Textabschnitts. Im Gegensatz zu [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) sind alle Eigenschaften dieser Klasse beschreibbar.

--------------------

Diese Klasse wird verwendet, um die für den jeweiligen Abschnitt definierten Formatierungseigenschaften des Textabschnitts zurückzugeben und zu manipulieren. Das bedeutet, dass beim Abrufen von Werten keine Vererbung angewendet wird, sodass Sie in den meisten Fällen Werte erhalten, die „undefiniert“ bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich vererbter Werte zu erhalten, müssen Sie die Methode [getEffective](../../com.aspose.slides/iportionformat\#getEffective) verwenden, die eine [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)-Instanz zurückgibt.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Gibt die Bookmark-ID zurück oder setzt sie. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Gibt die Bookmark-ID zurück oder setzt sie. |
| [getSmartTagClean()](#getSmartTagClean--) | Bestimmt, ob das Smart-Tag bereinigt werden soll. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Bestimmt, ob das Smart-Tag bereinigt werden soll. |
| [getEffective()](#getEffective--) | Ermittelt die effektiven Formatierungsdaten des Abschnitts mit angewandter Vererbung. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

Gibt die Bookmark-ID zurück oder setzt sie. Lesen/Schreiben String.

**Rückgabewert:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```

Gibt die Bookmark-ID zurück oder setzt sie. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

Bestimmt, ob das Smart-Tag bereinigt werden soll. Keine Vererbung angewendet. Lesen/Schreiben boolean.

**Rückgabewert:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

Bestimmt, ob das Smart-Tag bereinigt werden soll. Keine Vererbung angewendet. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

Ermittelt die effektiven Formatierungsdaten des Abschnitts mit angewandter Vererbung.

**Rückgabewert:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - ein [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).