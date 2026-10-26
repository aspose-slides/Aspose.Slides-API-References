---
title: DocumentProperties
second_title: Aspose.Slides für Java API-Referenz
description: Stellt die Eigenschaften einer Präsentation dar.
type: docs
url: /de/com.aspose.slides/documentproperties/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

Stellt Eigenschaften einer Präsentation dar.

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // Instanziieren Sie die Presentation-Klasse, die die Präsentation darstellt
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // Erstellen Sie eine Referenz zum IDocumentProperties-Objekt, das mit der Präsentation verknüpft ist
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Zeigen Sie die integrierten Eigenschaften an
>      System.out.println("Category : " + documentProperties.getCategory());
>      System.out.println("Current Status : " + documentProperties.getContentStatus());
>      System.out.println("Creation Date : " + documentProperties.getCreatedTime());
>      System.out.println("Author : " + documentProperties.getAuthor());
>      System.out.println("Description : " + documentProperties.getComments());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to modify built-in Properties of PowerPoint Presentation.
>  
>  // Instanziieren Sie die Presentation-Klasse, die die Präsentation darstellt
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // Erstellen Sie eine Referenz zum IDocumentProperties-Objekt, das mit der Präsentation verknüpft ist
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Setzen Sie die integrierten Eigenschaften
>      documentProperties.setAuthor("Aspose.Slides for Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // Speichern Sie Ihre Präsentation in einer Datei
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | Initialisiert eine neue Instanz der Klasse [DocumentProperties](../../com.aspose.slides/documentproperties). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Gibt die App-Version zurück. |
| [getNameOfApplication()](#getNameOfApplication--) | Gibt den Namen der Anwendung zurück oder setzt ihn. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Gibt den Namen der Anwendung zurück oder setzt ihn. |
| [getCompany()](#getCompany--) | Gibt die Unternehmens-Eigenschaft zurück oder setzt sie. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Gibt die Unternehmens-Eigenschaft zurück oder setzt sie. |
| [getManager()](#getManager--) | Gibt die Manager-Eigenschaft zurück oder setzt sie. |
| [setManager(String value)](#setManager-java.lang.String-) | Gibt die Manager-Eigenschaft zurück oder setzt sie. |
| [getPresentationFormat()](#getPresentationFormat--) | Gibt das beabsichtigte Format einer Präsentation zurück oder setzt es. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Gibt das beabsichtigte Format einer Präsentation zurück oder setzt es. |
| [getSharedDoc()](#getSharedDoc--) | Bestimmt, ob die Präsentation zwischen mehreren Personen geteilt wird. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Bestimmt, ob die Präsentation zwischen mehreren Personen geteilt wird. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Gibt die Vorlage einer Anwendung zurück oder setzt sie. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Gibt die Vorlage einer Anwendung zurück oder setzt sie. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Gesamte Bearbeitungszeit einer Präsentation. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Gesamte Bearbeitungszeit einer Präsentation. |
| [getTitle()](#getTitle--) | Gibt den Titel einer Präsentation zurück oder setzt ihn. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Gibt den Titel einer Präsentation zurück oder setzt ihn. |
| [getSubject()](#getSubject--) | Gibt den Betreff einer Präsentation zurück oder setzt ihn. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Gibt den Betreff einer Präsentation zurück oder setzt ihn. |
| [getAuthor()](#getAuthor--) | Gibt den Autor einer Präsentation zurück oder setzt ihn. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Gibt den Autor einer Präsentation zurück oder setzt ihn. |
| [getKeywords()](#getKeywords--) | Gibt die Schlüsselwörter einer Präsentation zurück oder setzt sie. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Gibt die Schlüsselwörter einer Präsentation zurück oder setzt sie. |
| [getComments()](#getComments--) | Gibt die Kommentare einer Präsentation zurück oder setzt sie. |
| [setComments(String value)](#setComments-java.lang.String-) | Gibt die Kommentare einer Präsentation zurück oder setzt sie. |
| [getCategory()](#getCategory--) | Gibt die Kategorie einer Präsentation zurück oder setzt sie. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Gibt die Kategorie einer Präsentation zurück oder setzt sie. |
| [getCreatedTime()](#getCreatedTime--) | Gibt das Erstellungsdatum einer Präsentation zurück. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Gibt das Erstellungsdatum einer Präsentation zurück. |
| [getLastSavedTime()](#getLastSavedTime--) | Gibt das Datum zurück, an dem eine Präsentation zuletzt geändert wurde. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Gibt das Datum zurück, an dem eine Präsentation zuletzt geändert wurde. |
| [getLastPrinted()](#getLastPrinted--) | Gibt das Datum zurück, an dem eine Präsentation das letzte Mal gedruckt wurde. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Gibt das Datum zurück, an dem eine Präsentation das letzte Mal gedruckt wurde. |
| [getLastSavedBy()](#getLastSavedBy--) | Gibt den Namen der letzten Person zurück, die eine Präsentation bearbeitet hat, oder setzt ihn. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Gibt den Namen der letzten Person zurück, die eine Präsentation bearbeitet hat, oder setzt ihn. |
| [getRevisionNumber()](#getRevisionNumber--) | Gibt die Überarbeitungsnummer der Präsentation zurück oder setzt sie. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Gibt die Überarbeitungsnummer der Präsentation zurück oder setzt sie. |
| [getContentStatus()](#getContentStatus--) | Gibt den Inhaltsstatus einer Präsentation zurück oder setzt ihn. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Gibt den Inhaltsstatus einer Präsentation zurück oder setzt ihn. |
| [getContentType()](#getContentType--) | Gibt den Inhaltstyp einer Präsentation zurück oder setzt ihn. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Gibt den Inhaltstyp einer Präsentation zurück oder setzt ihn. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Gibt die HyperlinkBase-Dokumenteneigenschaft zurück oder setzt sie. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Gibt die HyperlinkBase-Dokumenteneigenschaft zurück oder setzt sie. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Gibt die tatsächliche Anzahl benutzerdefinierter Eigenschaften in einer Sammlung zurück. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Gibt einen benutzerdefinierten Eigenschaftsnamen am angegebenen Index zurück. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Entfernt eine benutzerdefinierte Eigenschaft, die mit einem angegebenen Namen verknüpft ist. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Prüft das Vorhandensein einer benutzerdefinierten Eigenschaft mit einem angegebenen Namen. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Gibt die benutzerdefinierte Eigenschaft zurück, die mit einem angegebenen Namen verknüpft ist, oder setzt sie. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Gibt die benutzerdefinierte Eigenschaft zurück, die mit einem angegebenen Namen verknüpft ist, oder setzt sie. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Gets a named boolean value from the custom properties. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Gets a named integer value from the custom properties. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Gets a named DateTime value from the custom properties. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Gets a named string value from the custom properties. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Gets a named float value from the custom properties. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Gets a named double value from the custom properties. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Setzt eine benannte boolesche benutzerdefinierte Eigenschaft. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Setzt eine benannte ganzzahlige benutzerdefinierte Eigenschaft. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Setzt eine benannte DateTime-benutzerdefinierte Eigenschaft. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Setzt eine benannte Zeichenfolgen-benutzerdefinierte Eigenschaft. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Setzt eine benannte Gleitkomma-benutzerdefinierte Eigenschaft. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Setzt eine benannte Double-benutzerdefinierte Eigenschaft. |
| [clearCustomProperties()](#clearCustomProperties--) | Entfernt alle benutzerdefinierten Eigenschaften. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Ermittelt ein Array von Sensitivitätslabels aus den benutzerdefinierten Dokumenteigenschaften (Microsoft Information Protection SDK Metadata). |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Löscht und setzt Standardwerte für alle integrierten Eigenschaften. |
| [getScaleCrop()](#getScaleCrop--) | Gibt den Anzeigemodus der Dokumentvorschau an. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Gibt den Anzeigemodus der Dokumentvorschau an. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Gibt an, ob Hyperlinks in einem Dokument aktuell sind. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Gibt an, ob Hyperlinks in einem Dokument aktuell sind. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Gibt an, dass ein oder mehrere Hyperlinks in diesem Teil ausschließlich von einem Ersteller in diesem Teil aktualisiert wurden. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Gibt an, dass ein oder mehrere Hyperlinks in diesem Teil ausschließlich von einem Ersteller in diesem Teil aktualisiert wurden. |
| [getSlides()](#getSlides--) | Gibt die Gesamtzahl der Folien in einem Präsentationsdokument zurück. |
| [getHiddenSlides()](#getHiddenSlides--) | Gibt die Anzahl versteckter Folien in einem Präsentationsdokument zurück. |
| [getNotes()](#getNotes--) | Gibt die Anzahl der Folien in einer Präsentation mit Notizen zurück. |
| [getParagraphs()](#getParagraphs--) | Gibt die Gesamtzahl der im Dokument gefundenen Absätze zurück, falls zutreffend. |
| [getWords()](#getWords--) | Gibt die Gesamtzahl der Wörter im Dokument zurück. |
| [getMultimediaClips()](#getMultimediaClips--) | Gibt die Gesamtzahl der im Dokument vorhandenen Audio- oder Videoclips zurück. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Gibt den Titel jedes Dokumentteils an. |
| [getHeadingPairs()](#getHeadingPairs--) | Gibt die Gruppierung der Dokumentteile und die Anzahl der Teile in jeder Gruppe an. |
| [deepClone()](#deepClone--) | Klont das aktuelle Objekt |
| [cloneT()](#cloneT--) | Klont das aktuelle Objekt |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```


Initialisiert eine neue Instanz der Klasse [DocumentProperties](../../com.aspose.slides/documentproperties).

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```


Gibt die App-Version zurück. Nur lesbarer String.

**Rückgabe:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```


Gibt den Namen der Anwendung zurück oder setzt ihn. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```


Gibt den Namen der Anwendung zurück oder setzt ihn. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getCompany() {#getCompany--}
```
public final String getCompany()
```


Gibt die Unternehmens-Eigenschaft zurück oder setzt sie. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```


Gibt die Unternehmens-Eigenschaft zurück oder setzt sie. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getManager() {#getManager--}
```
public final String getManager()
```


Gibt die Manager-Eigenschaft zurück oder setzt sie. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```


Gibt die Manager-Eigenschaft zurück oder setzt sie. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```


Gibt das beabsichtigte Format einer Präsentation zurück oder setzt es. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```


Gibt das beabsichtigte Format einer Präsentation zurück oder setzt es. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```


Bestimmt, ob die Präsentation zwischen mehreren Personen geteilt wird. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```


Bestimmt, ob die Präsentation zwischen mehreren Personen geteilt wird. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```


Gibt die Vorlage einer Anwendung zurück oder setzt sie. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```


Gibt die Vorlage einer Anwendung zurück oder setzt sie. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```


Gesamte Bearbeitungszeit einer Präsentation. Lesen/Schreiben double.

**Rückgabe:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```


Gesamte Bearbeitungszeit einer Präsentation. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getTitle() {#getTitle--}
```
public final String getTitle()
```


Gibt den Titel einer Präsentation zurück oder setzt ihn. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Gibt den Titel einer Präsentation zurück oder setzt ihn. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gibt den Betreff einer Präsentation zurück oder setzt ihn. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Gibt den Betreff einer Präsentation zurück oder setzt ihn. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


Gibt den Autor einer Präsentation zurück oder setzt ihn. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```


Gibt den Autor einer Präsentation zurück oder setzt ihn. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```


Gibt die Schlüsselwörter einer Präsentation zurück oder setzt sie. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```


Gibt die Schlüsselwörter einer Präsentation zurück oder setzt sie. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public final String getComments()
```


Gibt die Kommentare einer Präsentation zurück oder setzt sie. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Gibt die Kommentare einer Präsentation zurück oder setzt sie. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getCategory() {#getCategory--}
```
public final String getCategory()
```


Gibt die Kategorie einer Präsentation zurück oder setzt sie. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```


Gibt die Kategorie einer Präsentation zurück oder setzt sie. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```
Gibt das Erstellungsdatum einer Präsentation zurück. Die Werte sind in UTC. Lese/Schreib java.util.Date.

**Rückgabe:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```


Gibt das Erstellungsdatum einer Präsentation zurück. Die Werte sind in UTC. Lese/Schreib java.util.Date.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```


Gibt das Datum zurück, an dem eine Präsentation zuletzt geändert wurde. Die Werte sind in UTC. Nur lesbar im Fall von Presentation.DocumentProperties (weil es intern während des Speicherprozesses des IPresentation-Objekts aktualisiert wird). Kann über die von der Methode [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) zurückgegebene DocumentProperties-Instanz geändert werden. Bitte siehe das Beispiel in der [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) Methodenzusammenfassung.

**Rückgabe:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```


Gibt das Datum zurück, an dem eine Präsentation zuletzt geändert wurde. Die Werte sind in UTC. Nur lesbar im Fall von Presentation.DocumentProperties (weil es intern während des Speicherprozesses des IPresentation-Objekts aktualisiert wird). Kann über die von der Methode [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) zurückgegebene DocumentProperties-Instanz geändert werden. Bitte siehe das Beispiel in der [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) Methodenzusammenfassung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```


Gibt das Datum zurück, an dem eine Präsentation zuletzt gedruckt wurde. Lese/Schreib java.util.Date.

**Rückgabe:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```


Gibt das Datum zurück, an dem eine Präsentation zuletzt gedruckt wurde. Lese/Schreib java.util.Date.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```


Gibt den Namen der zuletzt die Präsentation ändernden Person zurück oder legt ihn fest. Lese/Schreib String.

**Rückgabe:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```


Gibt den Namen der zuletzt die Präsentation ändernden Person zurück oder legt ihn fest. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```


Gibt die Versionsnummer der Präsentation zurück oder legt sie fest. Lese/Schreib int.

**Rückgabe:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```


Gibt die Versionsnummer der Präsentation zurück oder legt sie fest. Lese/Schreib int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```


Gibt den Inhaltsstatus einer Präsentation zurück oder legt ihn fest. Lese/Schreib String.

**Rückgabe:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```


Gibt den Inhaltsstatus einer Präsentation zurück oder legt ihn fest. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```


Gibt den Inhaltstyp einer Präsentation zurück oder legt ihn fest. Lese/Schreib String.

**Rückgabe:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```


Gibt den Inhaltstyp einer Präsentation zurück oder legt ihn fest. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```


Gibt die HyperlinkBase-Dokumenteneigenschaft zurück oder legt sie fest. Lese/Schreib String.

**Rückgabe:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```


Gibt die HyperlinkBase-Dokumenteneigenschaft zurück oder legt sie fest. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```


Gibt die tatsächliche Anzahl benutzerdefinierter Eigenschaften zurück, die in einer Sammlung enthalten sind. Nur lesbar int.

**Rückgabe:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```


Gibt den Namen einer benutzerdefinierten Eigenschaft am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index einer benutzerdefinierten Eigenschaft, die abgerufen werden soll. |

**Rückgabe:**
java.lang.String - Name der benutzerdefinierten Eigenschaft am angegebenen Index.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```


Entfernt eine benutzerdefinierte Eigenschaft, die mit einem angegebenen Namen verknüpft ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name einer zu entfernenden benutzerdefinierten Eigenschaft. |

**Rückgabe:**
boolean - Gibt true zurück, wenn eine Eigenschaft entfernt wurde, sonst false.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```


Prüft das Vorhandensein einer benutzerdefinierten Eigenschaft mit einem angegebenen Namen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name einer zu prüfenden benutzerdefinierten Eigenschaft. |

**Rückgabe:**
boolean - Gibt true zurück, wenn die Eigenschaft existiert, sonst false.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```


Gibt die mit einem angegebenen Namen verknüpfte benutzerdefinierte Eigenschaft zurück oder legt sie fest. Lese/Schreib Object.

--------------------

Wert kann **int**, **float**, **String**, **boolean** oder **Date** sein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String |  |

**Rückgabe:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public final void set_Item(String name, Object value)
```


Gibt die mit einem angegebenen Namen verknüpfte benutzerdefinierte Eigenschaft zurück oder legt sie fest. Lese/Schreib Object.

--------------------

Wert kann **int**, **float**, **String**, **boolean** oder **Date** sein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```


Ruft einen benannten booleschen Wert aus den benutzerdefinierten Eigenschaften ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft, die abgerufen werden soll |
| value | boolean[] | Wert der benutzerdefinierten Eigenschaft |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```


Ruft einen benannten ganzzahligen Wert aus den benutzerdefinierten Eigenschaften ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft, die abgerufen werden soll |
| value | int[] | Wert der benutzerdefinierten Eigenschaft |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```


Ruft einen benannten DateTime-Wert aus den benutzerdefinierten Eigenschaften ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft, die abgerufen werden soll |
| value | java.util.Date[] | Wert der benutzerdefinierten Eigenschaft |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```


Ruft einen benannten Zeichenkettenwert aus den benutzerdefinierten Eigenschaften ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft, die abgerufen werden soll |
| value | java.lang.String[] | Wert der benutzerdefinierten Eigenschaft |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```


Ruft einen benannten Gleitkommawert aus den benutzerdefinierten Eigenschaften ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft, die abgerufen werden soll |
| value | float[] | Wert der benutzerdefinierten Eigenschaft |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```


Ruft einen benannten Double-Wert aus den benutzerdefinierten Eigenschaften ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft, die abgerufen werden soll. |
| value | double[] | Wert der benutzerdefinierten Eigenschaft |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```


Setzt eine benannte boolesche benutzerdefinierte Eigenschaft.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft, die gesetzt werden soll |
| value | boolean | Wert der benutzerdefinierten Eigenschaft |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```


Setzt eine benannte ganzzahlige benutzerdefinierte Eigenschaft.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft, die gesetzt werden soll |
| value | int | Wert der benutzerdefinierten Eigenschaft |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```


Setzt eine benannte DateTime-benutzerdefinierte Eigenschaft.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft, die gesetzt werden soll |
| value | java.util.Date | Wert der benutzerdefinierten Eigenschaft |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```


Setzt eine benannte Zeichenketten-benutzerdefinierte Eigenschaft.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft, die gesetzt werden soll |
| value | java.lang.String | Wert der benutzerdefinierten Eigenschaft |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```


Setzt eine benannte Gleitkomma-benutzerdefinierte Eigenschaft.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft, die gesetzt werden soll |
| value | float | Wert der benutzerdefinierten Eigenschaft |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```


Setzt eine benannte Double-benutzerdefinierte Eigenschaft.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft, die gesetzt werden soll |
| value | double | Wert der benutzerdefinierten Eigenschaft |

### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```


Entfernt alle benutzerdefinierten Eigenschaften.

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```


Ruft ein Array von Sensitivitätskennzeichnungen aus den benutzerdefinierten Dokumenteneigenschaften ab (Microsoft Information Protection SDK Metadaten).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Hole Sensitivitätskennzeichnungen aus den benutzerdefinierten Dokumenteigenschaften
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Kennzeichnung zur Sammlung hinzufügen
>          // Hier können Sie eine Prüfung der Gültigkeit der Kennzeichnungsinformationen hinzufügen (die Kennzeichnung ist verfügbar usw.)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
com.aspose.slides.ISensitivityLabel[]
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public final void clearBuiltInProperties()
```


Löscht und setzt Standardwerte für alle integrierten Eigenschaften.

### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```


Gibt den Anzeigemodus der Dokumentvorschau an. Setzen Sie dieses Element auf **true**, um das Skalieren der Dokumentvorschau an die Anzeige zu aktivieren. Setzen Sie es auf **false**, um das Zuschneiden der Dokumentvorschau zu aktivieren, sodass nur Abschnitte angezeigt werden, die in die Anzeige passen. Lese/Schreib boolean.

**Rückgabe:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```


Gibt den Anzeigemodus der Dokumentvorschau an. Setzen Sie dieses Element auf **true**, um das Skalieren der Dokumentvorschau an die Anzeige zu aktivieren. Setzen Sie es auf **false**, um das Zuschneiden der Dokumentvorschau zu aktivieren, sodass nur Abschnitte angezeigt werden, die in die Anzeige passen. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```


Gibt an, ob Hyperlinks in einem Dokument aktuell sind. Setzen Sie dieses Element auf **true**, um anzuzeigen, dass Hyperlinks aktualisiert sind. Setzen Sie es auf **false**, um anzuzeigen, dass Hyperlinks veraltet sind. Lese/Schreib boolean.

**Rückgabe:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```
Gibt an, ob Hyperlinks in einem Dokument aktuell sind. Setzen Sie dieses Element auf **true**, um anzuzeigen, dass Hyperlinks aktualisiert wurden. Setzen Sie dieses Element auf **false**, um anzuzeigen, dass Hyperlinks veraltet sind. Lese-/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

Gibt an, dass ein oder mehrere Hyperlinks in diesem Teil ausschließlich von einem Erzeuger in diesem Teil aktualisiert wurden. Der nächste Erzeuger, der dieses Dokument öffnet, soll die Hyperlink-Beziehungen mit den in diesem Teil angegebenen neuen Hyperlinks aktualisieren. Lese-/Schreib boolean.

**Rückgabewert:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

Gibt an, dass ein oder mehrere Hyperlinks in diesem Teil ausschließlich von einem Erzeuger in diesem Teil aktualisiert wurden. Der nächste Erzeuger, der dieses Dokument öffnet, soll die Hyperlink-Beziehungen mit den in diesem Teil angegebenen neuen Hyperlinks aktualisieren. Lese-/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public final int getSlides()
```

Gibt die Gesamtzahl der Folien in einem Präsentationsdokument zurück. Nur lesend int.

**Rückgabewert:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

Gibt die Anzahl der ausgeblendeten Folien in einem Präsentationsdokument zurück. Nur lesend int.

**Rückgabewert:**
int
### getNotes() {#getNotes--}
```
public final int getNotes()
```

Gibt die Anzahl der Folien in einer Präsentation zurück, die Notizen enthalten. Nur lesend int.

**Rückgabewert:**
int
### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

Gibt die Gesamtzahl der Absätze im Dokument zurück, falls zutreffend. Nur lesend int.

**Rückgabewert:**
int
### getWords() {#getWords--}
```
public final int getWords()
```

Gibt die Gesamtzahl der Wörter im Dokument zurück. Nur lesend int.

**Rückgabewert:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

Gibt die Gesamtzahl der im Dokument vorhandenen Audio- oder Videoclips zurück. Nur lesend int.

**Rückgabewert:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

Gibt den Titel jedes Dokumententeils an. Diese Teile sind keine Dokumententeile, sondern konzeptuelle Darstellungen von Dokumentabschnitten. Nur lesend String[].

**Rückgabewert:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

Gibt die Gruppierung von Dokumententeilen und die Anzahl der Teile in jeder Gruppe an. Nur lesend IHeadingPair[].

**Rückgabewert:**
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Klont das aktuelle Objekt

**Rückgabewert:**
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

Klont das aktuelle Objekt

**Rückgabewert:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Klone