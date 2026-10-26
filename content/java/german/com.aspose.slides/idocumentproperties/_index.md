---
title: IDocumentProperties
second_title: Aspose.Slides for Java API Reference
description: Represents properties of a presentation.
type: docs
url: /de/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

Stellt die Eigenschaften einer Präsentation dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Gibt die App-Version zurück. |
| [getNameOfApplication()](#getNameOfApplication--) | Gibt den Namen der Anwendung zurück oder legt ihn fest. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Gibt den Namen der Anwendung zurück oder legt ihn fest. |
| [getCompany()](#getCompany--) | Gibt die Firmen-Eigenschaft zurück oder legt sie fest. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Gibt die Firmen-Eigenschaft zurück oder legt sie fest. |
| [getManager()](#getManager--) | Gibt die Manager-Eigenschaft zurück oder legt sie fest. |
| [setManager(String value)](#setManager-java.lang.String-) | Gibt die Manager-Eigenschaft zurück oder legt sie fest. |
| [getPresentationFormat()](#getPresentationFormat--) | Gibt das beabsichtigte Format einer Präsentation zurück oder legt es fest. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Gibt das beabsichtigte Format einer Präsentation zurück oder legt es fest. |
| [getSharedDoc()](#getSharedDoc--) | Bestimmt, ob die Präsentation zwischen mehreren Personen geteilt wird. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Bestimmt, ob die Präsentation zwischen mehreren Personen geteilt wird. |
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
| [getLastSavedTime()](#getLastSavedTime--) | Gibt das Datum zurück, an dem eine Präsentation zuletzt bearbeitet wurde. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Gibt das Datum zurück, an dem eine Präsentation zuletzt bearbeitet wurde. |
| [getLastPrinted()](#getLastPrinted--) | Gibt das Datum zurück, an dem eine Präsentation das letzte Mal gedruckt wurde. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Gibt das Datum zurück, an dem eine Präsentation das letzte Mal gedruckt wurde. |
| [getLastSavedBy()](#getLastSavedBy--) | Gibt den Namen der zuletzt die Präsentation bearbeitenden Person zurück oder legt ihn fest. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Gibt den Namen der zuletzt die Präsentation bearbeitenden Person zurück oder legt ihn fest. |
| [getRevisionNumber()](#getRevisionNumber--) | Gibt die Revisionsnummer der Präsentation zurück oder legt sie fest. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Gibt die Revisionsnummer der Präsentation zurück oder legt sie fest. |
| [getContentStatus()](#getContentStatus--) | Gibt den Inhaltsstatus einer Präsentation zurück oder legt ihn fest. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Gibt den Inhaltsstatus einer Präsentation zurück oder legt ihn fest. |
| [getContentType()](#getContentType--) | Gibt den Inhaltstyp einer Präsentation zurück oder legt ihn fest. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Gibt den Inhaltstyp einer Präsentation zurück oder legt ihn fest. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Gibt die Dokument-Eigenschaft HyperlinkBase zurück oder legt sie fest. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Gibt die Dokument-Eigenschaft HyperlinkBase zurück oder legt sie fest. |
| [getScaleCrop()](#getScaleCrop--) | Gibt den Anzeigemodus der Dokumentenvorschau an. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Gibt den Anzeigemodus der Dokumentenvorschau an. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Gibt an, ob Hyperlinks in einem Dokument aktuell sind. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Gibt an, ob Hyperlinks in einem Dokument aktuell sind. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Gibt an, dass ein oder mehrere Hyperlinks in diesem Teil ausschließlich von einem Produzenten in diesem Teil aktualisiert wurden. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Gibt an, dass ein oder mehrere Hyperlinks in diesem Teil ausschließlich von einem Produzenten in diesem Teil aktualisiert wurden. |
| [getSlides()](#getSlides--) | Gibt die Gesamtzahl der Folien in einem Präsentationsdokument an. |
| [getHiddenSlides()](#getHiddenSlides--) | Gibt die Anzahl der versteckten Folien in einem Präsentationsdokument an. |
| [getNotes()](#getNotes--) | Gibt die Anzahl der Folien in einer Präsentation mit Notizen an. |
| [getParagraphs()](#getParagraphs--) | Gibt die Gesamtzahl der im Dokument gefundenen Absätze an, falls zutreffend. |
| [getWords()](#getWords--) | Gibt die Gesamtzahl der Wörter im Dokument an. |
| [getMultimediaClips()](#getMultimediaClips--) | Gibt die Gesamtzahl der im Dokument vorhandenen Ton- oder Videoclips an. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Gibt den Titel jedes Dokumententeils an. |
| [getHeadingPairs()](#getHeadingPairs--) | Gibt die Gruppierung von Dokumententeilen und die Anzahl der Teile in jeder Gruppe an. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Gibt die tatsächlich in einer Sammlung enthaltene Anzahl benutzerdefinierter Eigenschaften zurück. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Gibt den Namen einer benutzerdefinierten Eigenschaft am angegebenen Index zurück. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Entfernt eine benutzerdefinierte Eigenschaft, die mit einem angegebenen Namen verknüpft ist. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Prüft das Vorhandensein einer benutzerdefinierten Eigenschaft mit einem angegebenen Namen. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Gibt die mit einem angegebenen Namen verknüpfte benutzerdefinierte Eigenschaft zurück oder legt sie fest. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Gibt die mit einem angegebenen Namen verknüpfte benutzerdefinierte Eigenschaft zurück oder legt sie fest. |
| [clearCustomProperties()](#clearCustomProperties--) | Entfernt alle benutzerdefinierten Eigenschaften. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Löscht und setzt Standardwerte für alle integrierten Eigenschaften. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Ruft einen benannten booleschen Wert aus den benutzerdefinierten Eigenschaften ab. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Ruft einen benannten ganzzahligen Wert aus den benutzerdefinierten Eigenschaften ab. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Ruft einen benannten DateTime-Wert aus den benutzerdefinierten Eigenschaften ab. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Ruft einen benannten Zeichenkettenwert aus den benutzerdefinierten Eigenschaften ab. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Ruft einen benannten Float-Wert aus den benutzerdefinierten Eigenschaften ab. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Ruft einen benannten Double-Wert aus den benutzerdefinierten Eigenschaften ab. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Setzt eine benannte boolesche benutzerdefinierte Eigenschaft. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Setzt eine benannte ganzzahlige benutzerdefinierte Eigenschaft. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Setzt eine benannte DateTime-benutzerdefinierte Eigenschaft. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Setzt eine benannte Zeichenketten-benutzerdefinierte Eigenschaft. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Setzt eine benannte Float-benutzerdefinierte Eigenschaft. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Setzt eine benannte Double-benutzerdefinierte Eigenschaft. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Ruft ein Array von Sensitivitätskennzeichnungen aus den benutzerdefinierten Dokumenteigenschaften ab (Microsoft Information Protection SDK-Metadaten). |
### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

Gibt die App-Version zurück. Nur lesender String.

--------------------

Der Inhalt dieses Elements muss die Form XX.YYYY haben, wobei X und Y numerische Werte darstellen; andernfalls gilt das Dokument als nicht konform. Aspose.Slides gibt seine Version im Format XX.YY.ZZ aus, wobei: XX – Hauptversion YY – Nebenversion ZZ – Patch-Version. Zum Beispiel bedeutet der Wert 23.0105 die Aspose.Slides-Version 23.1.5.

**Rückgabe:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

Gibt den Namen der Anwendung zurück oder legt ihn fest. Lese/Schreib String.

**Rückgabe:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```

Gibt den Namen der Anwendung zurück oder legt ihn fest. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getCompany() {#getCompany--}
```
public abstract String getCompany()
```

Gibt die Firmen-Eigenschaft zurück oder legt sie fest. Lese/Schreib String.

**Rückgabe:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

Gibt die Firmen-Eigenschaft zurück oder legt sie fest. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getManager() {#getManager--}
```
public abstract String getManager()
```

Gibt die Manager-Eigenschaft zurück oder legt sie fest. Lese/Schreib String.

**Rückgabe:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

Gibt die Manager-Eigenschaft zurück oder legt sie fest. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

Gibt das beabsichtigte Format einer Präsentation zurück oder legt es fest. Lese/Schreib String.

**Rückgabe:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

Gibt das beabsichtigte Format einer Präsentation zurück oder legt es fest. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

Bestimmt, ob die Präsentation zwischen mehreren Personen geteilt wird. Lese/Schreib boolean.

**Rückgabe:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

Bestimmt, ob die Präsentation zwischen mehreren Personen geteilt wird. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

Gibt die Vorlage einer Anwendung zurück oder legt sie fest. Lese/Schreib String.

**Rückgabe:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```

Gibt die Vorlage einer Anwendung zurück oder legt sie fest. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```

Gesamte Bearbeitungszeit einer Präsentation. Lese/Schreib double.

**Rückgabe:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

Gesamte Bearbeitungszeit einer Präsentation. Lese/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

Gibt den Titel einer Präsentation zurück oder legt ihn fest. Lese/Schreib String.

**Rückgabe:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

Gibt den Titel einer Präsentation zurück oder legt ihn fest. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getSubject() {#getSubject--}
```
public abstract String getSubject()
```

Gibt das Thema einer Präsentation zurück oder legt es fest. Lese/Schreib String.

**Rückgabe:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```

Gibt das Thema einer Präsentation zurück oder legt es fest. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```

Gibt den Autor einer Präsentation zurück oder legt ihn fest. Lese/Schreib String.

**Rückgabe:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```

Gibt den Autor einer Präsentation zurück oder legt ihn fest. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```

Gibt die Schlüsselwörter einer Präsentation zurück oder legt sie fest. Lese/Schreib String.

**Rückgabe:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

Gibt die Schlüsselwörter einer Präsentation zurück oder legt sie fest. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract String getComments()
```

Gibt die Kommentare einer Präsentation zurück oder legt sie fest. Lese/Schreib String.

**Rückgabe:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

Gibt die Kommentare einer Präsentation zurück oder legt sie fest. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getCategory() {#getCategory--}
```
public abstract String getCategory()
```

Gibt die Kategorie einer Präsentation zurück oder legt sie fest. Lese/Schreib String.

**Rückgabe:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```

Gibt die Kategorie einer Präsentation zurück oder legt sie fest. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
| Wert | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Gibt das Erstellungsdatum einer Präsentation zurück. Werte sind in UTC. Lese-/Schreib java.util.Date.

**Rückgabe:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Gibt das Erstellungsdatum einer Präsentation zurück. Werte sind in UTC. Lese-/Schreib java.util.Date.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```

Gibt das Datum zurück, an dem eine Präsentation zuletzt geändert wurde. Werte sind in UTC.P Nur-Lese im Fall von Presentation.DocumentProperties (weil es intern während des Speichervorgangs des IPresentation-Objekts aktualisiert wird). Kann über die DocumentProperties-Instanz geändert werden, die durch die Methode [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) zurückgegeben wird. Siehe das Beispiel in der Methode [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Rückgabe:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

Gibt das Datum zurück, an dem eine Präsentation zuletzt geändert wurde. Werte sind in UTC.P Nur-Lese im Fall von Presentation.DocumentProperties (weil es intern während des Speichervorgangs des IPresentation-Objekts aktualisiert wird). Kann über die DocumentProperties-Instanz geändert werden, die durch die Methode [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) zurückgegeben wird. Siehe das Beispiel in der Methode [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```

Gibt das Datum zurück, an dem eine Präsentation zuletzt gedruckt wurde. Lese-/Schreib java.util.Date.

**Rückgabe:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```

Gibt das Datum zurück, an dem eine Präsentation zuletzt gedruckt wurde. Lese-/Schreib java.util.Date.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```

Gibt den Namen der zuletzt die Präsentation änderten Person zurück oder setzt ihn. Lese-/Schreib String.

**Rückgabe:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

Gibt den Namen der zuletzt die Präsentation änderten Person zurück oder setzt ihn. Lese-/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```

Gibt die Revisionsnummer der Präsentation zurück oder setzt sie. Lese-/Schreib int.

**Rückgabe:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```

Gibt die Revisionsnummer der Präsentation zurück oder setzt sie. Lese-/Schreib int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```

Gibt den Inhaltsstatus einer Präsentation zurück oder setzt ihn. Lese-/Schreib String.

**Rückgabe:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```

Gibt den Inhaltsstatus einer Präsentation zurück oder setzt ihn. Lese-/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Gibt den Inhaltstyp einer Präsentation zurück oder setzt ihn. Lese-/Schreib String.

**Rückgabe:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```

Gibt den Inhaltstyp einer Präsentation zurück oder setzt ihn. Lese-/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```

Gibt die Dokumenteneigenschaft HyperlinkBase zurück oder setzt sie. Lese-/Schreib String.

**Rückgabe:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```

Gibt die Dokumenteneigenschaft HyperlinkBase zurück oder setzt sie. Lese-/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```

Gibt den Anzeigemodus der Dokumentenvorschau an. Setzen Sie dieses Element auf **true**, um die Skalierung der Dokumentenvorschau anzuzeigen. Setzen Sie dieses Element auf **false**, um das Zuschneiden der Dokumentenvorschau zu aktivieren, sodass nur Abschnitte angezeigt werden, die in die Anzeige passen. Lese-/Schreib boolean.

**Rückgabe:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

Gibt den Anzeigemodus der Dokumentenvorschau an. Setzen Sie dieses Element auf **true**, um die Skalierung der Dokumentenvorschau anzuzeigen. Setzen Sie dieses Element auf **false**, um das Zuschneiden der Dokumentenvorschau zu aktivieren, sodass nur Abschnitte angezeigt werden, die in die Anzeige passen. Lese-/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```

Gibt an, ob Hyperlinks in einem Dokument aktuell sind. Setzen Sie dieses Element auf **true**, um anzuzeigen, dass Hyperlinks aktualisiert wurden. Setzen Sie dieses Element auf **false**, um anzuzeigen, dass Hyperlinks veraltet sind. Lese-/Schreib boolean.

**Rückgabe:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

Gibt an, ob Hyperlinks in einem Dokument aktuell sind. Setzen Sie dieses Element auf **true**, um anzuzeigen, dass Hyperlinks aktualisiert wurden. Setzen Sie dieses Element auf **false**, um anzuzeigen, dass Hyperlinks veraltet sind. Lese-/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

Gibt an, dass ein oder mehrere Hyperlinks in diesem Teil ausschließlich von einem Produzenten in diesem Teil aktualisiert wurden. Der nächste Produzent, der dieses Dokument öffnet, soll die Hyperlink-Beziehungen mit den neuen Hyperlinks aus diesem Teil aktualisieren. Lese-/Schreib boolean.

**Rückgabe:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```

Gibt an, dass ein oder mehrere Hyperlinks in diesem Teil ausschließlich von einem Produzenten in diesem Teil aktualisiert wurden. Der nächste Produzent, der dieses Dokument öffnet, soll die Hyperlink-Beziehungen mit den neuen Hyperlinks aus diesem Teil aktualisieren. Lese-/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

Gibt die Gesamtzahl der Folien in einem Präsentationsdokument an. Nur-Lese int.

**Rückgabe:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

Gibt die Anzahl der ausgeblendeten Folien in einem Präsentationsdokument an. Nur-Lese int.

**Rückgabe:**
int
### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

Gibt die Anzahl der Folien in einer Präsentation an, die Notizen enthalten. Nur-Lese int.

**Rückgabe:**
int
### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```

Gibt die Gesamtzahl der Absätze im Dokument an, falls zutreffend. Nur-Lese int.

**Rückgabe:**
int
### getWords() {#getWords--}
```
public abstract int getWords()
```

Gibt die Gesamtzahl der Wörter im Dokument an. Nur-Lese int.

**Rückgabe:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

Gibt die Gesamtzahl der Audio- oder Videoclips im Dokument an. Nur-Lese int.

**Rückgabe:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

Gibt den Titel jedes Dokumententeils an. Diese Teile sind keine Dokumententeile, sondern konzeptuelle Darstellungen von Dokumentabschnitten. Nur-Lese java.lang.String[].

**Rückgabe:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

Gibt die Gruppierung von Dokumententeilen und die Anzahl der Teile in jeder Gruppe an. Nur-Lese com.aspose.slides.IHeadingPair[].

**Rückgabe:**
com.aspose.slides.IHeadingPair[]
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

Gibt die tatsächliche Anzahl benutzerdefinierter Eigenschaften in einer Sammlung zurück. Nur-Lese int.

**Rückgabe:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```

Gibt den Namen einer benutzerdefinierten Eigenschaft am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index der abzurufenden benutzerdefinierten Eigenschaft. |

**Rückgabe:**
java.lang.String - Name der benutzerdefinierten Eigenschaft am angegebenen Index.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```

Entfernt eine benutzerdefinierte Eigenschaft mit dem angegebenen Namen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der zu entfernenden benutzerdefinierten Eigenschaft. |

**Rückgabe:**
boolean - Gibt true zurück, wenn eine Eigenschaft entfernt wurde, andernfalls false.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```

Prüft das Vorhandensein einer benutzerdefinierten Eigenschaft mit dem angegebenen Namen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der zu prüfenden benutzerdefinierten Eigenschaft. |

**Rückgabe:**
boolean - Gibt true zurück, wenn die Eigenschaft existiert, andernfalls false.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```

Gibt die benutzerdefinierte Eigenschaft mit dem angegebenen Namen zurück oder setzt sie. Lese-/Schreib Object.

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

Gibt die benutzerdefinierte Eigenschaft mit dem angegebenen Namen zurück oder setzt sie. Lese-/Schreib Object.

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
public abstract void clearBuiltInProperties()
```

Löscht und setzt Standardwerte für alle integrierten Eigenschaften.

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

Liest einen benannten booleschen Wert aus den benutzerdefinierten Eigenschaften.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der abzurufenden benutzerdefinierten Eigenschaft |
| value | boolean[] | Wert der benutzerdefinierten Eigenschaft |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

Liest einen benannten ganzzahligen Wert aus den benutzerdefinierten Eigenschaften.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der abzurufenden benutzerdefinierten Eigenschaft |
| value | int[] | Wert der benutzerdefinierten Eigenschaft |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

Liest einen benannten DateTime-Wert aus den benutzerdefinierten Eigenschaften.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der abzurufenden benutzerdefinierten Eigenschaft |
| value | java.util.Date[] | Wert der benutzerdefinierten Eigenschaft |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

Liest einen benannten Zeichenfolgenwert aus den benutzerdefinierten Eigenschaften.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der abzurufenden benutzerdefinierten Eigenschaft |
| value | java.lang.String[] | Wert der benutzerdefinierten Eigenschaft |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

Liest einen benannten Fließkommawert aus den benutzerdefinierten Eigenschaften.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der abzurufenden benutzerdefinierten Eigenschaft |
| value | float[] | Wert der benutzerdefinierten Eigenschaft |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```

Liest einen benannten Double-Wert aus den benutzerdefinierten Eigenschaften.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der abzurufenden benutzerdefinierten Eigenschaft |
| value | double[] | Wert der benutzerdefinierten Eigenschaft |
| Name | java.lang.String | Name der abzurufenden benutzerdefinierten Eigenschaft. |
| Wert | double[] | Wert der benutzerdefinierten Eigenschaft |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

Setzt eine benannte boolean benutzerdefinierte Eigenschaft.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft, die gesetzt werden soll |
| value | boolean | Wert der benutzerdefinierten Eigenschaft |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

Setzt eine benannte int benutzerdefinierte Eigenschaft.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft, die gesetzt werden soll |
| value | int | Wert der benutzerdefinierten Eigenschaft |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

Setzt eine benannte DateTime benutzerdefinierte Eigenschaft.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft, die gesetzt werden soll |
| value | java.util.Date | Wert der benutzerdefinierten Eigenschaft |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

Setzt eine benannte string benutzerdefinierte Eigenschaft.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft, die gesetzt werden soll |
| value | java.lang.String | Wert der benutzerdefinierten Eigenschaft |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

Setzt eine benannte float benutzerdefinierte Eigenschaft.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft, die gesetzt werden soll |
| value | float | Wert der benutzerdefinierten Eigenschaft |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

Setzt eine benannte double benutzerdefinierte Eigenschaft.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft, die gesetzt werden soll |
| value | double | Wert der benutzerdefinierten Eigenschaft |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

Liefert ein Array von Sensitivitätskennzeichnungen aus den benutzerdefinierten Dokumenteigenschaften (Microsoft Information Protection SDK Metadata).

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