---
title: IDocumentProperties
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt die Eigenschaften einer Präsentation dar.
type: docs
url: /de/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

Stellt die Eigenschaften einer Präsentation dar.
## Methoden

| Method | Description |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Gibt die App-Version zurück. |
| [getNameOfApplication()](#getNameOfApplication--) | Gibt den Namen der Anwendung zurück oder legt ihn fest. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Gibt den Namen der Anwendung zurück oder legt ihn fest. |
| [getCompany()](#getCompany--) | Gibt die Unternehmens-Eigenschaft zurück oder legt sie fest. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Gibt die Unternehmens-Eigenschaft zurück oder legt sie fest. |
| [getManager()](#getManager--) | Gibt die Manager-Eigenschaft zurück oder legt sie fest. |
| [setManager(String value)](#setManager-java.lang.String-) | Gibt die Manager-Eigenschaft zurück oder legt sie fest. |
| [getPresentationFormat()](#getPresentationFormat--) | Gibt das beabsichtigte Format einer Präsentation zurück oder legt es fest. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Gibt das beabsichtigte Format einer Präsentation zurück oder legt es fest. |
| [getSharedDoc()](#getSharedDoc--) | Bestimmt, ob die Präsentation von mehreren Personen gemeinsam genutzt wird. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Bestimmt, ob die Präsentation von mehreren Personen gemeinsam genutzt wird. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Gibt die Vorlage einer Anwendung zurück oder legt sie fest. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Gibt die Vorlage einer Anwendung zurück oder legt sie fest. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Gesamte Bearbeitungszeit einer Präsentation. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Gesamte Bearbeitungszeit einer Präsentation. |
| [getTitle()](#getTitle--) | Gibt den Titel einer Präsentation zurück oder legt ihn fest. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Gibt den Titel einer Präsentation zurück oder legt ihn fest. |
| [getSubject()](#getSubject--) | Gibt das Thema einer Präsentation zurück oder legt es fest. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Gibt das Thema einer Präsentation zurück oder legt es fest. |
| [getAuthor()](#getAuthor--) | Gibt den Autor einer Präsentation zurück oder legt ihn fest. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Gibt den Autor einer Präsentation zurück oder legt ihn fest. |
| [getKeywords()](#getKeywords--) | Gibt die Schlüsselwörter einer Präsentation zurück oder legt sie fest. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Gibt die Schlüsselwörter einer Präsentation zurück oder legt sie fest. |
| [getComments()](#getComments--) | Gibt die Kommentare einer Präsentation zurück oder legt sie fest. |
| [setComments(String value)](#setComments-java.lang.String-) | Gibt die Kommentare einer Präsentation zurück oder legt sie fest. |
| [getCategory()](#getCategory--) | Gibt die Kategorie einer Präsentation zurück oder legt sie fest. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Gibt die Kategorie einer Präsentation zurück oder legt sie fest. |
| [getCreatedTime()](#getCreatedTime--) | Gibt das Erstellungsdatum einer Präsentation zurück. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Gibt das Erstellungsdatum einer Präsentation zurück. |
| [getLastSavedTime()](#getLastSavedTime--) | Gibt das Datum zurück, an dem eine Präsentation zuletzt geändert wurde. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Gibt das Datum zurück, an dem eine Präsentation zuletzt geändert wurde. |
| [getLastPrinted()](#getLastPrinted--) | Gibt das Datum zurück, an dem eine Präsentation zuletzt gedruckt wurde. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Gibt das Datum zurück, an dem eine Präsentation zuletzt gedruckt wurde. |
| [getLastSavedBy()](#getLastSavedBy--) | Gibt den Namen der letzten Person zurück, die eine Präsentation geändert hat, oder legt ihn fest. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Gibt den Namen der letzten Person zurück, die eine Präsentation geändert hat, oder legt ihn fest. |
| [getRevisionNumber()](#getRevisionNumber--) | Gibt die Versionsnummer der Präsentation zurück oder legt sie fest. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Gibt die Versionsnummer der Präsentation zurück oder legt sie fest. |
| [getContentStatus()](#getContentStatus--) | Gibt den Inhaltsstatus einer Präsentation zurück oder legt ihn fest. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Gibt den Inhaltsstatus einer Präsentation zurück oder legt ihn fest. |
| [getContentType()](#getContentType--) | Gibt den Inhaltstyp einer Präsentation zurück oder legt ihn fest. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Gibt den Inhaltstyp einer Präsentation zurück oder legt ihn fest. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Gibt die HyperlinkBase-Dokumenteigenschaft zurück oder legt sie fest. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Gibt die HyperlinkBase-Dokumenteigenschaft zurück oder legt sie fest. |
| [getScaleCrop()](#getScaleCrop--) | Gibt den Anzeigemodus der Dokumentvorschau an. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Gibt den Anzeigemodus der Dokumentvorschau an. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Gibt an, ob Hyperlinks in einem Dokument aktuell sind. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Gibt an, ob Hyperlinks in einem Dokument aktuell sind. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Gibt an, dass ein oder mehrere Hyperlinks in diesem Teil ausschließlich von einem Erzeuger in diesem Teil aktualisiert wurden. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Gibt an, dass ein oder mehrere Hyperlinks in diesem Teil ausschließlich von einem Erzeuger in diesem Teil aktualisiert wurden. |
| [getSlides()](#getSlides--) | Gibt die Gesamtzahl der Folien in einem Präsentationsdokument an. |
| [getHiddenSlides()](#getHiddenSlides--) | Gibt die Anzahl der ausgeblendeten Folien in einem Präsentationsdokument an. |
| [getNotes()](#getNotes--) | Gibt die Anzahl der Folien in einer Präsentation mit Notizen an. |
| [getParagraphs()](#getParagraphs--) | Gibt die Gesamtzahl der in einem Dokument gefundenen Absätze an, falls zutreffend. |
| [getWords()](#getWords--) | Gibt die Gesamtzahl der Wörter in einem Dokument an. |
| [getMultimediaClips()](#getMultimediaClips--) | Gibt die Gesamtzahl der im Dokument vorhandenen Ton- oder Videoclips an. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Gibt den Titel jedes Dokumententeils an. |
| [getHeadingPairs()](#getHeadingPairs--) | Gibt die Gruppierung von Dokumententeilen und die Anzahl der Teile in jeder Gruppe an. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Gibt die Anzahl der tatsächlich in einer Sammlung enthaltenen benutzerdefinierten Eigenschaften zurück. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Gibt einen benutzerdefinierten Eigenschaftsnamen am angegebenen Index zurück. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Entfernt eine benutzerdefinierte Eigenschaft, die mit einem angegebenen Namen verknüpft ist. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Überprüft das Vorhandensein einer benutzerdefinierten Eigenschaft mit einem angegebenen Namen. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Gibt die mit einem angegebenen Namen verknüpfte benutzerdefinierte Eigenschaft zurück oder legt sie fest. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Gibt die mit einem angegebenen Namen verknüpfte benutzerdefinierte Eigenschaft zurück oder legt sie fest. |
| [clearCustomProperties()](#clearCustomProperties--) | Entfernt alle benutzerdefinierten Eigenschaften. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Löscht und setzt Standardwerte für alle integrierten Eigenschaften. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Ruft einen benannten Booleschen Wert aus den benutzerdefinierten Eigenschaften ab. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Ruft einen benannten Ganzzahlwert aus den benutzerdefinierten Eigenschaften ab. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Ruft einen benannten DateTime-Wert aus den benutzerdefinierten Eigenschaften ab. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Ruft einen benannten Zeichenfolgenwert aus den benutzerdefinierten Eigenschaften ab. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Ruft einen benannten Float-Wert aus den benutzerdefinierten Eigenschaften ab. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Ruft einen benannten Double-Wert aus den benutzerdefinierten Eigenschaften ab. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Setzt eine benannte Boolesche benutzerdefinierte Eigenschaft. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Setzt eine benannte Ganzzahl-benutzerdefinierte Eigenschaft. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Setzt eine benannte DateTime-benutzerdefinierte Eigenschaft. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Setzt eine benannte Zeichenfolgen-benutzerdefinierte Eigenschaft. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Setzt eine benannte Float-benutzerdefinierte Eigenschaft. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Setzt eine benannte Double-benutzerdefinierte Eigenschaft. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Ruft ein Array von Sensitivitätslabels aus den benutzerdefinierten Dokumenteigenschaften ab (Microsoft Information Protection SDK Metadata). |
### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

Gibt die App-Version zurück. Schreibgeschützt String.

--------------------

Der Inhalt dieses Elements muss das Format XX.YYYY haben, wobei X und Y numerische Werte darstellen; andernfalls gilt das Dokument als nicht konform. Aspose.Slides stellt seine Version im Format XX.YY.ZZ dar, wobei: XX – Hauptversion YY – Nebenversion ZZ – Patch-Version. Zum Beispiel bedeutet der Wert 23.0105 die Aspose.Slides-Version 23.1.5.

**Rückgabe:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

Gibt den Namen der Anwendung zurück oder legt ihn fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```

Gibt den Namen der Anwendung zurück oder legt ihn fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getCompany() {#getCompany--}
```
public abstract String getCompany()
```

Gibt die Unternehmens-Eigenschaft zurück oder legt sie fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

Gibt die Unternehmens-Eigenschaft zurück oder legt sie fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getManager() {#getManager--}
```
public abstract String getManager()
```

Gibt die Manager-Eigenschaft zurück oder legt sie fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

Gibt die Manager-Eigenschaft zurück oder legt sie fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

Gibt das beabsichtigte Format einer Präsentation zurück oder legt es fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

Gibt das beabsichtigte Format einer Präsentation zurück oder legt es fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

Bestimmt, ob die Präsentation von mehreren Personen gemeinsam genutzt wird. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

Bestimmt, ob die Präsentation von mehreren Personen gemeinsam genutzt wird. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

Gibt die Vorlage einer Anwendung zurück oder legt sie fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```

Gibt die Vorlage einer Anwendung zurück oder legt sie fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```

Gesamte Bearbeitungszeit einer Präsentation. Lesen/Schreiben double.

**Rückgabe:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

Gesamte Bearbeitungszeit einer Präsentation. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

Gibt den Titel einer Präsentation zurück oder legt ihn fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

Gibt den Titel einer Präsentation zurück oder legt ihn fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getSubject() {#getSubject--}
```
public abstract String getSubject()
```

Gibt das Thema einer Präsentation zurück oder legt es fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```

Gibt das Thema einer Präsentation zurück oder legt es fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```

Gibt den Autor einer Präsentation zurück oder legt ihn fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```

Gibt den Autor einer Präsentation zurück oder legt ihn fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```

Gibt die Schlüsselwörter einer Präsentation zurück oder legt sie fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

Gibt die Schlüsselwörter einer Präsentation zurück oder legt sie fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract String getComments()
```

Gibt die Kommentare einer Präsentation zurück oder legt sie fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

Gibt die Kommentare einer Präsentation zurück oder legt sie fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getCategory() {#getCategory--}
```
public abstract String getCategory()
```

Gibt die Kategorie einer Präsentation zurück oder legt sie fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```

Gibt die Kategorie einer Präsentation zurück oder legt sie fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Gibt das Erstellungsdatum einer Präsentation zurück. Werte sind in UTC. Lesen/Schreiben java.util.Date.

**Rückgabe:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Gibt das Erstellungsdatum einer Präsentation zurück. Werte sind in UTC. Lesen/Schreiben java.util.Date.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```

Gibt das Datum zurück, an dem eine Präsentation zuletzt geändert wurde. Werte sind in UTC. Nur-Lesen im Fall von Presentation.DocumentProperties (weil es intern während des Speichervorgangs des IPresentation-Objekts aktualisiert wird). Kann über die von Methode [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) zurückgegebene DocumentProperties-Instanz geändert werden. Siehe das Beispiel in der Methodenzusammenfassung von [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Rückgabe:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

Gibt das Datum zurück, an dem eine Präsentation zuletzt geändert wurde. Werte sind in UTC. Nur-Lesen im Fall von Presentation.DocumentProperties (weil es intern während des Speichervorgangs des IPresentation-Objekts aktualisiert wird). Kann über die von Methode [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) zurückgegebene DocumentProperties-Instanz geändert werden. Siehe das Beispiel in der Methodenzusammenfassung von [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```

Gibt das Datum zurück, an dem eine Präsentation zuletzt gedruckt wurde. Lesen/Schreiben java.util.Date.

**Rückgabe:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```

Gibt das Datum zurück, an dem eine Präsentation zuletzt gedruckt wurde. Lesen/Schreiben java.util.Date.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```

Gibt den Namen der letzten Person zurück, die eine Präsentation geändert hat, oder legt ihn fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

Gibt den Namen der letzten Person zurück, die eine Präsentation geändert hat, oder legt ihn fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```

Gibt die Versionsnummer der Präsentation zurück oder legt sie fest. Lesen/Schreiben int.

**Rückgabe:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```

Gibt die Versionsnummer der Präsentation zurück oder legt sie fest. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```

Gibt den Inhaltsstatus einer Präsentation zurück oder legt ihn fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```

Gibt den Inhaltsstatus einer Präsentation zurück oder legt ihn fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Gibt den Inhaltstyp einer Präsentation zurück oder legt ihn fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```

Gibt den Inhaltstyp einer Präsentation zurück oder legt ihn fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```

Gibt die HyperlinkBase-Dokumenteigenschaft zurück oder legt sie fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```

Gibt die HyperlinkBase-Dokumenteigenschaft zurück oder legt sie fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```

Gibt den Anzeigemodus der Dokumentvorschau an. Setzen Sie dieses Element auf **true**, um das Skalieren der Dokumentvorschau an das Display zu aktivieren. Setzen Sie es auf **false**, um das Zuschneiden der Dokumentvorschau zu aktivieren, sodass nur Abschnitte angezeigt werden, die zum Display passen. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

Gibt den Anzeigemodus der Dokumentvorschau an. Setzen Sie dieses Element auf **true**, um das Skalieren der Dokumentvorschau an das Display zu aktivieren. Setzen Sie es auf **false**, um das Zuschneiden der Dokumentvorschau zu aktivieren, sodass nur Abschnitte angezeigt werden, die zum Display passen. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```

Gibt an, ob Hyperlinks in einem Dokument aktuell sind. Setzen Sie dieses Element auf **true**, um anzugeben, dass Hyperlinks aktualisiert wurden. Setzen Sie es auf **false**, um anzugeben, dass Hyperlinks veraltet sind. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

Gibt an, ob Hyperlinks in einem Dokument aktuell sind. Setzen Sie dieses Element auf **true**, um anzugeben, dass Hyperlinks aktualisiert wurden. Setzen Sie es auf **false**, um anzugeben, dass Hyperlinks veraltet sind. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

Gibt an, dass ein oder mehrere Hyperlinks in diesem Teil ausschließlich von einem Erzeuger in diesem Teil aktualisiert wurden. Der nächste Erzeuger, der dieses Dokument öffnet, soll die Hyperlink-Beziehungen mit den in diesem Teil angegebenen neuen Hyperlinks aktualisieren. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```

Gibt an, dass ein oder mehrere Hyperlinks in diesem Teil ausschließlich von einem Erzeuger in diesem Teil aktualisiert wurden. Der nächste Erzeuger, der dieses Dokument öffnet, soll die Hyperlink-Beziehungen mit den in diesem Teil angegebenen neuen Hyperlinks aktualisieren. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

Gibt die Gesamtzahl der Folien in einem Präsentationsdokument an. Schreibgeschützt int.

**Rückgabe:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

Gibt die Anzahl der ausgeblendeten Folien in einem Präsentationsdokument an. Schreibgeschützt int.

**Rückgabe:**
int
### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

Gibt die Anzahl der Folien in einer Präsentation mit Notizen an. Schreibgeschützt int.

**Rückgabe:**
int
### getParagraphs() {#getParagraphs--}
```
public
```

Gibt die Gesamtzahl der in einem Dokument gefundenen Absätze an, falls zutreffend. Schreibgeschützt int.

**Rückgabe:**
int
### getWords() {#getWords--}
```
public abstract int getWords()
```

Gibt die Gesamtzahl der Wörter in einem Dokument an. Schreibgeschützt int.

**Rückgabe:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

Gibt die Gesamtzahl der im Dokument vorhandenen Ton- oder Videoclips an. Schreibgeschützt int.

**Rückgabe:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

Gibt den Titel jedes Dokumententeils an. Diese Teile sind keine Dokumententeile, sondern konzeptuelle Darstellungen von Dokumentabschnitten. Schreibgeschützt String[].

**Rückgabe:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

Gibt die Gruppierung von Dokumententeilen und die Anzahl der Teile in jeder Gruppe an. Schreibgeschützt IHeadingPair[].

**Rückgabe:**
com.aspose.slides.IHeadingPair[]
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

Gibt die Anzahl der tatsächlich in einer Sammlung enthaltenen benutzerdefinierten Eigenschaften zurück. Schreibgeschützt int.

**Rückgabe:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```

Gibt einen benutzerdefinierten Eigenschaftsnamen am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index einer benutzerdefinierten Eigenschaft, die abgerufen werden soll. |

**Rückgabe:**
java.lang.String - Benutzerdefinierter Eigenschaftsname am angegebenen Index.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```

Entfernt eine benutzerdefinierte Eigenschaft, die mit einem angegebenen Namen verknüpft ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der zu entfernenden benutzerdefinierten Eigenschaft. |

**Rückgabe:**
boolean - Gibt true zurück, wenn eine Eigenschaft entfernt wurde, sonst false.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```

Überprüft das Vorhandensein einer benutzerdefinierten Eigenschaft mit einem angegebenen Namen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der zu überprüfenden benutzerdefinierten Eigenschaft. |

**Rückgabe:**
boolean - Gibt true zurück, wenn die Eigenschaft existiert, sonst false.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```

Gibt die mit einem angegebenen Namen verknüpfte benutzerdefinierte Eigenschaft zurück oder legt sie fest. Lesen/Schreiben Object.

--------------------

Der Wert kann **int**, **float**, **double**, **String**, **boolean** oder **Date** sein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String |  |

**Rückgabe:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```

Gibt die mit einem angegebenen Namen verknüpfte benutzerdefinierte Eigenschaft zurück oder legt sie fest. Lesen/Schreiben Object.

--------------------

Der Wert kann **int**, **float**, **double**, **String**, **boolean** oder **Date** sein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |
### clearCustomProperties() {#clearCustomProperties--}
```
public abstract void clearCustomProperties()
```

Entfernt alle benutzerdefinierten Eigenschaften.
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract
```

Löscht und setzt Standardwerte für alle integrierten Eigenschaften.
### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

Ruft einen benannten Booleschen Wert aus den benutzerdefinierten Eigenschaften ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der abzurufenden benutzerdefinierten Eigenschaft |
| value | boolean[] | Wert der benutzerdefinierten Eigenschaft |
### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

Ruft einen benannten Ganzzahlwert aus den benutzerdefinierten Eigenschaften ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der abzurufenden benutzerdefinierten Eigenschaft |
| value | int[] | Wert der benutzerdefinierten Eigenschaft |
### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

Ruft einen benannten DateTime-Wert aus den benutzerdefinierten Eigenschaften ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der abzurufenden benutzerdefinierten Eigenschaft |
| value | java.util.Date[] | Wert der benutzerdefinierten Eigenschaft |
### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

Ruft einen benannten Zeichenfolgenwert aus den benutzerdefinierten Eigenschaften ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der abzurufenden benutzerdefinierten Eigenschaft |
| value | java.lang.String[] | Wert der benutzerdefinierten Eigenschaft |
### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

Ruft einen benannten Float-Wert aus den benutzerdefinierten Eigenschaften ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der abzurufenden benutzerdefinierten Eigenschaft |
| value | float[] | Wert der benutzerdefinierten Eigenschaft |
### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```

Ruft einen benannten Double-Wert aus den benutzerdefinierten Eigenschaften ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der abzurufenden benutzerdefinierten Eigenschaft. |
| value | double[] | Wert der benutzerdefinierten Eigenschaft |
### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

Setzt eine benannte Boolesche benutzerdefinierte Eigenschaft.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der zu setzenden benutzerdefinierten Eigenschaft |
| value | boolean | Wert der benutzerdefinierten Eigenschaft |
### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

Setzt eine benannte Ganzzahl-benutzerdefinierte Eigenschaft.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der zu setzenden benutzerdefinierten Eigenschaft |
| value | int | Wert der benutzerdefinierten Eigenschaft |
### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

Setzt eine benannte DateTime-benutzerdefinierte Eigenschaft.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der zu setzenden benutzerdefinierten Eigenschaft |
| value | java.util.Date | Wert der benutzerdefinierten Eigenschaft |
### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

Setzt eine benannte Zeichenfolgen-benutzerdefinierte Eigenschaft.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der zu setzenden benutzerdefinierten Eigenschaft |
| value | java.lang.String | Wert der benutzerdefinierten Eigenschaft |
### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

Setzt eine benannte Float-benutzerdefinierte Eigenschaft.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der zu setzenden benutzerdefinierten Eigenschaft |
| value | float | Wert der benutzerdefinierten Eigenschaft |
### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

Setzt eine benannte Double-benutzerdefinierte Eigenschaft.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der zu setzenden benutzerdefinierten Eigenschaft |
| value | double | Wert der benutzerdefinierten Eigenschaft |
### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

Ruft ein Array von Sensitivitätslabels aus den benutzerdefinierten Dokumenteigenschaften ab (Microsoft Information Protection SDK Metadata).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Get sensitivity labels from the custom document properties
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Add label to the collection
>          // Here you can add a check for the validity of the label information (the label is available, etc)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabe:**
com.aspose.slides.ISensitivityLabel[]