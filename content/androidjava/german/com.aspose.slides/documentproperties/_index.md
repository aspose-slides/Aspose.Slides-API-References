---
title: DocumentProperties
second_title: Aspose.Slides für Android über Java API-Referenz
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
>  // Instanziiere die Presentation-Klasse, die die Präsentation repräsentiert
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // Erstelle eine Referenz auf das IDocumentProperties-Objekt, das mit der Präsentation verknüpft ist
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Zeige die integrierten Eigenschaften an
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
>  // Instanziiere die Presentation-Klasse, die die Präsentation repräsentiert
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // Erstelle eine Referenz auf das IDocumentProperties-Objekt, das mit der Präsentation verknüpft ist
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Setze die integrierten Eigenschaften
>      documentProperties.setAuthor("Aspose.Slides for Android via Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // Speichere deine Präsentation in einer Datei
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
| [getNameOfApplication()](#getNameOfApplication--) | Gibt den Namen der Anwendung zurück oder legt ihn fest. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Gibt den Namen der Anwendung zurück oder legt ihn fest. |
| [getCompany()](#getCompany--) | Gibt die Firmen-eigenschaft zurück oder legt sie fest. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Gibt die Firmen-eigenschaft zurück oder legt sie fest. |
| [getManager()](#getManager--) | Gibt die Manager-eigenschaft zurück oder legt sie fest. |
| [setManager(String value)](#setManager-java.lang.String-) | Gibt die Manager-eigenschaft zurück oder legt sie fest. |
| [getPresentationFormat()](#getPresentationFormat--) | Gibt das vorgesehene Format einer Präsentation zurück oder legt es fest. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Gibt das vorgesehene Format einer Präsentation zurück oder legt es fest. |
| [getSharedDoc()](#getSharedDoc--) | Bestimmt, ob die Präsentation zwischen mehreren Personen geteilt wird. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Bestimmt, ob die Präsentation zwischen mehreren Personen geteilt wird. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Gibt die Vorlage einer Anwendung zurück oder legt sie fest. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Gibt die Vorlage einer Anwendung zurück oder legt sie fest. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Gesamtbearbeitungszeit einer Präsentation. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Gesamtbearbeitungszeit einer Präsentation. |
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
| [getLastSavedTime()](#getLastSavedTime--) | Gibt das Datum der letzten Änderung einer Präsentation zurück. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Gibt das Datum der letzten Änderung einer Präsentation zurück. |
| [getLastPrinted()](#getLastPrinted--) | Gibt das Datum zurück, an dem die Präsentation zuletzt gedruckt wurde. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Gibt das Datum zurück, an dem die Präsentation zuletzt gedruckt wurde. |
| [getLastSavedBy()](#getLastSavedBy--) | Gibt den Namen der letzten Person zurück, die die Präsentation geändert hat, oder legt ihn fest. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Gibt den Namen der letzten Person zurück, die die Präsentation geändert hat, oder legt ihn fest. |
| [getRevisionNumber()](#getRevisionNumber--) | Gibt die Revisionsnummer der Präsentation zurück oder legt sie fest. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Gibt die Revisionsnummer der Präsentation zurück oder legt sie fest. |
| [getContentStatus()](#getContentStatus--) | Gibt den Inhaltsstatus einer Präsentation zurück oder legt ihn fest. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Gibt den Inhaltsstatus einer Präsentation zurück oder legt ihn fest. |
| [getContentType()](#getContentType--) | Gibt den Inhaltstyp einer Präsentation zurück oder legt ihn fest. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Gibt den Inhaltstyp einer Präsentation zurück oder legt ihn fest. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Gibt die HyperlinkBase-Dokumenteigenschaft zurück oder legt sie fest. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Gibt die HyperlinkBase-Dokumenteigenschaft zurück oder legt sie fest. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Gibt die tatsächliche Anzahl benutzerdefinierter Eigenschaften in einer Sammlung zurück. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Gibt einen Namen einer benutzerdefinierten Eigenschaft am angegebenen Index zurück. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Entfernt eine benutzerdefinierte Eigenschaft, die mit einem angegebenen Namen verknüpft ist. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Überprüft das Vorhandensein einer benutzerdefinierten Eigenschaft mit einem angegebenen Namen. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Gibt die mit einem angegebenen Namen verknüpfte benutzerdefinierte Eigenschaft zurück oder legt sie fest. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Gibt die mit einem angegebenen Namen verknüpfte benutzerdefinierte Eigenschaft zurück oder legt sie fest. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Liest einen benannten booleschen Wert aus den benutzerdefinierten Eigenschaften. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Liest einen benannten ganzzahligen Wert aus den benutzerdefinierten Eigenschaften. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Liest einen benannten DateTime-Wert aus den benutzerdefinierten Eigenschaften. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Liest einen benannten Zeichenkettenwert aus den benutzerdefinierten Eigenschaften. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Liest einen benannten Float-Wert aus den benutzerdefinierten Eigenschaften. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Liest einen benannten Double-Wert aus den benutzerdefinierten Eigenschaften. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Setzt eine benannte boolesche benutzerdefinierte Eigenschaft. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Setzt eine benannte ganzzahlige benutzerdefinierte Eigenschaft. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Setzt eine benannte DateTime-benutzerdefinierte Eigenschaft. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Setzt eine benannte Zeichenketten-benutzerdefinierte Eigenschaft. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Setzt eine benannte Float-benutzerdefinierte Eigenschaft. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Setzt eine benannte Double-benutzerdefinierte Eigenschaft. |
| [clearCustomProperties()](#clearCustomProperties--) | Entfernt alle benutzerdefinierten Eigenschaften. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Erhält ein Array von Sensitivitätskennzeichnungen aus den benutzerdefinierten Dokumenteigenschaften (Microsoft Information Protection SDK-Metadaten). |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Löscht und setzt Standardwerte für alle integrierten Eigenschaften. |
| [getScaleCrop()](#getScaleCrop--) | Gibt den Anzeigemodus der Dokumentvorschau an. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Gibt den Anzeigemodus der Dokumentvorschau an. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Gibt an, ob Hyperlinks in einem Dokument aktuell sind. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Gibt an, ob Hyperlinks in einem Dokument aktuell sind. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Gibt an, dass ein oder mehrere Hyperlinks in diesem Abschnitt ausschließlich von einem Ersteller in diesem Abschnitt aktualisiert wurden. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Gibt an, dass ein oder mehrere Hyperlinks in diesem Abschnitt ausschließlich von einem Ersteller in diesem Abschnitt aktualisiert wurden. |
| [getSlides()](#getSlides--) | Gibt die Gesamtzahl der Folien in einem Präsentationsdokument zurück. |
| [getHiddenSlides()](#getHiddenSlides--) | Gibt die Anzahl versteckter Folien in einem Präsentationsdokument zurück. |
| [getNotes()](#getNotes--) | Gibt die Anzahl der Folien in einer Präsentation zurück, die Notizen enthalten. |
| [getParagraphs()](#getParagraphs--) | Gibt die Gesamtzahl der im Dokument gefundenen Absätze zurück, falls zutreffend. |
| [getWords()](#getWords--) | Gibt die Gesamtzahl der im Dokument enthaltenen Wörter zurück. |
| [getMultimediaClips()](#getMultimediaClips--) | Gibt die Gesamtzahl der im Dokument vorhandenen Ton- oder Videoclips zurück. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Gibt den Titel jedes Dokumentteils an. |
| [getHeadingPairs()](#getHeadingPairs--) | Gibt die Gruppierung von Dokumentteilen und die Anzahl der Teile in jeder Gruppe an. |
| [deepClone()](#deepClone--) | Klont das aktuelle Objekt |
| [cloneT()](#cloneT--) | Klont das aktuelle Objekt |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

Initialisiert neue Instanz der Klasse [DocumentProperties](../../com.aspose.slides/documentproperties).

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

Gibt den Namen der Anwendung zurück oder legt ihn fest. Lese-/Schreib-String.

**Rückgabe:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

Gibt den Namen der Anwendung zurück oder legt ihn fest. Lese-/Schreib-String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getCompany() {#getCompany--}
```
public final String getCompany()
```

Gibt die Firmen-eigenschaft zurück oder legt sie fest. Lese-/Schreib-String.

**Rückgabe:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

Gibt die Firmen-eigenschaft zurück oder legt sie fest. Lese-/Schreib-String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getManager() {#getManager--}
```
public final String getManager()
```

Gibt die Manager-eigenschaft zurück oder legt sie fest. Lese-/Schreib-String.

**Rückgabe:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

Gibt die Manager-eigenschaft zurück oder legt sie fest. Lese-/Schreib-String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

Gibt das vorgesehene Format einer Präsentation zurück oder legt es fest. Lese-/Schreib-String.

**Rückgabe:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

Gibt das vorgesehene Format einer Präsentation zurück oder legt es fest. Lese-/Schreib-String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```

Bestimmt, ob die Präsentation zwischen mehreren Personen geteilt wird. Lese-/Schreib-boolean.

**Rückgabe:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```

Bestimmt, ob die Präsentation zwischen mehreren Personen geteilt wird. Lese-/Schreib-boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```

Gibt die Vorlage einer Anwendung zurück oder legt sie fest. Lese-/Schreib-String.

**Rückgabe:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

Gibt die Vorlage einer Anwendung zurück oder legt sie fest. Lese-/Schreib-String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```

Gesamtbearbeitungszeit einer Präsentation. Lese-/Schreib-double.

**Rückgabe:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```

Gesamtbearbeitungszeit einer Präsentation. Lese-/Schreib-double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getTitle() {#getTitle--}
```
public final String getTitle()
```

Gibt den Titel einer Präsentation zurück oder legt ihn fest. Lese-/Schreib-String.

**Rückgabe:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

Gibt den Titel einer Präsentation zurück oder legt ihn fest. Lese-/Schreib-String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getSubject() {#getSubject--}
```
public final String getSubject()
```

Gibt das Thema einer Präsentation zurück oder legt es fest. Lese-/Schreib-String.

**Rückgabe:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

Gibt das Thema einer Präsentation zurück oder legt es fest. Lese-/Schreib-String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

Gibt den Autor einer Präsentation zurück oder legt ihn fest. Lese-/Schreib-String.

**Rückgabe:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

Gibt den Autor einer Präsentation zurück oder legt ihn fest. Lese-/Schreib-String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

Gibt die Schlüsselwörter einer Präsentation zurück oder legt sie fest. Lese-/Schreib-String.

**Rückgabe:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```

Gibt die Schlüsselwörter einer Präsentation zurück oder legt sie fest. Lese-/Schreib-String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public final String getComments()
```

Gibt die Kommentare einer Präsentation zurück oder legt sie fest. Lese-/Schreib-String.

**Rückgabe:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

Gibt die Kommentare einer Präsentation zurück oder legt sie fest. Lese-/Schreib-String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getCategory() {#getCategory--}
```
public final String getCategory()
```

Gibt die Kategorie einer Präsentation zurück oder legt sie fest. Lese-/Schreib-String.

**Rückgabe:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

Gibt die Kategorie einer Präsentation zurück oder legt sie fest. Lese-/Schreib-String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

Gibt das Erstellungsdatum einer Präsentation zurück. Werte sind in UTC angegeben. Lese-/Schreib-java.util.Date.

**Rückgabe:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Gibt das Erstellungsdatum einer Präsentation zurück. Werte sind in UTC angegeben. Lese-/Schreib-java.util.Date.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```

Gibt das Datum der letzten Änderung einer Präsentation zurück. Werte sind in UTC angegeben. Nur lesbar im Fall von Presentation.DocumentProperties (da es intern während des Speichervorgangs des IPresentation-Objekts aktualisiert wird). Kann über die von Methode [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) zurückgegebene DocumentProperties-Instanz geändert werden. Siehe das Beispiel in der Methodenzusammenfassung von [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Rückgabe:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```

Gibt das Datum der letzten Änderung einer Präsentation zurück. Werte sind in UTC angegeben. Nur lesbar im Fall von Presentation.DocumentProperties (da es intern während des Speichervorgangs des IPresentation-Objekts aktualisiert wird). Kann über die von Methode [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) zurückgegebene DocumentProperties-Instanz geändert werden. Siehe das Beispiel in der Methodenzusammenfassung von [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```

Gibt das Datum zurück, an dem die Präsentation zuletzt gedruckt wurde. Lese-/Schreib-java.util.Date.

**Rückgabe:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```

Gibt das Datum zurück, an dem die Präsentation zuletzt gedruckt wurde. Lese-/Schreib-java.util.Date.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedBy() {#getLastSavedBy--}
```
public final String get

```

Gibt den Namen der letzten Person zurück, die die Präsentation geändert hat, oder legt ihn fest. Lese-/Schreib-String.

**Rückgabe:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```

Gibt den Namen der letzten Person zurück, die die Präsentation geändert hat, oder legt ihn fest. Lese-/Schreib-String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```

Gibt die Revisionsnummer der Präsentation zurück oder legt sie fest. Lese-/Schreib-int.

**Rückgabe:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```

Gibt die Revisionsnummer der Präsentation zurück oder legt sie fest. Lese-/Schreib-int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```

Gibt den Inhaltsstatus einer Präsentation zurück oder legt ihn fest. Lese-/Schreib-String.

**Rückgabe:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```

Gibt den Inhaltsstatus einer Präsentation zurück oder legt ihn fest. Lese-/Schreib-String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Gibt den Inhaltstyp einer Präsentation zurück oder legt ihn fest. Lese-/Schreib-String.

**Rückgabe:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Gibt den Inhaltstyp einer Präsentation zurück oder legt ihn fest. Lese-/Schreib-String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```

Gibt die HyperlinkBase-Dokumenteigenschaft zurück oder legt sie fest. Lese-/Schreib-String.

**Rückgabe:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```

Gibt die HyperlinkBase-Dokumenteigenschaft zurück oder legt sie fest. Lese-/Schreib-String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```

Gibt die tatsächliche Anzahl benutzerdefinierter Eigenschaften zurück. Nur lesbarer int.

**Rückgabe:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```

Gibt einen Namen einer benutzerdefinierten Eigenschaft am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index einer benutzerdefinierten Eigenschaft zum Abrufen. |

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
boolean – gibt true zurück, wenn eine Eigenschaft entfernt wurde, sonst false.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```

Überprüft das Vorhandensein einer benutzerdefinierten Eigenschaft mit einem angegebenen Namen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name einer zu prüfenden benutzerdefinierten Eigenschaft. |

**Rückgabe:**
boolean – gibt true zurück, wenn die Eigenschaft existiert, sonst false.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```

Gibt die mit einem angegebenen Namen verknüpfte benutzerdefinierte Eigenschaft zurück oder legt sie fest. Lese-/Schreib-Object.

--------------------

Der Wert kann **int**, **float**, **String**, **boolean** oder **Date** sein.

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

Gibt die mit einem angegebenen Namen verknüpfte benutzerdefinierte Eigenschaft zurück oder legt sie fest. Lese-/Schreib-Object.

--------------------

Der Wert kann **int**, **float**, **String**, **boolean** oder **Date** sein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |
### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```

Liest einen benannten booleschen Wert aus den benutzerdefinierten Eigenschaften.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft zum Abrufen |
| value | boolean[] | Wert der benutzerdefinierten Eigenschaft |
### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```

Liest einen benannten ganzzahligen Wert aus den benutzerdefinierten Eigenschaften.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft zum Abrufen |
| value | int[] | Wert der benutzerdefinierten Eigenschaft |
### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```

Liest einen benannten DateTime-Wert aus den benutzerdefinierten Eigenschaften.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft zum Abrufen |
| value | java.util.Date[] | Wert der benutzerdefinierten Eigenschaft |
### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```

Liest einen benannten Zeichenkettenwert aus den benutzerdefinierten Eigenschaften.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft zum Abrufen |
| value | java.lang.String[] | Wert der benutzerdefinierten Eigenschaft |
### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```

Liest einen benannten Float-Wert aus den benutzerdefinierten Eigenschaften.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft zum Abrufen |
| value | float[] | Wert der benutzerdefinierten Eigenschaft |
### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```

Liest einen benannten Double-Wert aus den benutzerdefinierten Eigenschaften.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft zum Abrufen. |
| value | double[] | Wert der benutzerdefinierten Eigenschaft |
### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```

Setzt eine benannte boolesche benutzerdefinierte Eigenschaft.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft zum Setzen |
| value | boolean | Wert der benutzerdefinierten Eigenschaft |
### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```

Setzt eine benannte ganzzahlige benutzerdefinierte Eigenschaft.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft zum Setzen |
| value | int | Wert der benutzerdefinierten Eigenschaft |
### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```

Setzt eine benannte DateTime-benutzerdefinierte Eigenschaft.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft zum Setzen |
| value | java.util.Date | Wert der benutzerdefinierten Eigenschaft |
### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```

Setzt eine benannte Zeichenketten-benutzerdefinierte Eigenschaft.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft zum Setzen |
| value | java.lang.String | Wert der benutzerdefinierten Eigenschaft |
### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```

Setzt eine benannte Float-benutzerdefinierte Eigenschaft.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft zum Setzen |
| value | float | Wert der benutzerdefinierten Eigenschaft |
### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```

Setzt eine benannte Double-benutzerdefinierte Eigenschaft.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der benutzerdefinierten Eigenschaft zum Setzen |
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

Erhält ein Array von Sensitivitätskennzeichnungen aus den benutzerdefinierten Dokumenteigenschaften (Microsoft Information Protection SDK-Metadaten).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Holt die Sensitivitätskennzeichnungen aus den benutzerdefinierten Dokumenteigenschaften
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Fügt die Kennzeichnung zur Sammlung hinzu
>          // Hier können Sie eine Prüfung auf die Gültigkeit der Kennzeichnungsinformationen hinzufügen (die Kennzeichnung ist verfügbar, usw.)
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

Gibt den Anzeigemodus der Dokumentvorschau an. Setzen Sie dieses Element auf **true**, um die Skalierung der Dokumentvorschau an das Anzeigeformat zu aktivieren. Setzen Sie es auf **false**, um das Zuschneiden der Dokumentvorschau zu aktivieren, sodass nur Abschnitte angezeigt werden, die in das Anzeigeformat passen. Lese-/Schreib-boolean.

**Rückgabe:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value
```

Gibt den Anzeigemodus der Dokumentvorschau an. Setzen Sie dieses Element auf **true**, um die Skalierung der Dokumentvorschau an das Anzeigeformat zu aktivieren. Setzen Sie es auf **false**, um das Zuschneiden der Dokumentvorschau zu aktivieren, sodass nur Abschnitte angezeigt werden, die in das Anzeigeformat passen. Lese-/Schreib-boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```

Gibt an, ob Hyperlinks in einem Dokument aktuell sind. Setzen Sie dieses Element auf **true**, um anzuzeigen, dass Hyperlinks aktualisiert wurden. Setzen Sie es auf **false**, um anzuzeigen, dass Hyperlinks veraltet sind. Lese-/Schreib-boolean.

**Rückgabe:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```

Gibt an, ob Hyperlinks in einem Dokument aktuell sind. Setzen Sie dieses Element auf **true**, um anzuzeigen, dass Hyperlinks aktualisiert wurden. Setzen Sie es auf **false**, um anzuzeigen, dass Hyperlinks veraltet sind. Lese-/Schreib-boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

Gibt an, dass ein oder mehrere Hyperlinks in diesem Abschnitt ausschließlich von einem Ersteller in diesem Abschnitt aktualisiert wurden. Der nächste Ersteller, der dieses Dokument öffnet, soll die Hyperlink-Beziehungen mit den neuen Hyperlinks aus diesem Abschnitt aktualisieren. Lese-/Schreib-boolean.

**Rückgabe:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

Gibt an, dass ein oder mehrere Hyperlinks in diesem Abschnitt ausschließlich von einem Ersteller in diesem Abschnitt aktualisiert wurden. Der nächste Ersteller, der dieses Dokument öffnet, soll die Hyperlink-Beziehungen mit den neuen Hyperlinks aus diesem Abschnitt aktualisieren. Lese-/Schreib-boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getSlides() {#getSlides--}
```
public final int getSlides()
```

Gibt die Gesamtzahl der Folien in einem Präsentationsdokument zurück. Nur lesbarer int.

**Rückgabe:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

Gibt die Anzahl versteckter Folien in einem Präsentationsdokument zurück. Nur lesbarer int.

**Rückgabe:**
int
### getNotes() {#getNotes--}
```
public final int getNotes()
```

Gibt die Anzahl der Folien in einer Präsentation zurück, die Notizen enthalten. Nur lesbarer int.

**Rückgabe:**
int
### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

Gibt die Gesamtzahl der im Dokument gefundenen Absätze zurück, falls zutreffend. Nur lesbarer int.

**Rückgabe:**
int
### getWords() {#getWords--}
```
public final int getWords()
```

Gibt die Gesamtzahl der im Dokument enthaltenen Wörter zurück. Nur lesbarer int.

**Rückgabe:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

Gibt die Gesamtzahl der im Dokument vorhandenen Ton- oder Videoclips zurück. Nur lesbarer int.

**Rückgabe:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

Gibt den Titel jedes Dokumentteils an. Diese Teile sind keine physischen Dokumentteile, sondern konzeptuelle Darstellungen von Dokumentabschnitten. Nur lesbarer String[].

**Rückgabe:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

Gibt die Gruppierung von Dokumentteilen und die Anzahl der Teile in jeder Gruppe an. Nur lesbarer IHeadingPair[].

**Rückgabe:**
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Klont das aktuelle Objekt

**Rückgabe:**
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

Klont das aktuelle Objekt

**Rückgabe:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone