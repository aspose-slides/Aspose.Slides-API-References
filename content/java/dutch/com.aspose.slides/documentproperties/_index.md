---
title: DocumentProperties
second_title: Aspose.Slides voor Java API-referentie
description: Geeft de eigenschappen van een presentatie weer.
type: docs
url: /nl/com.aspose.slides/documentproperties/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

Stelt eigenschappen van een presentatie voor.

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // Instantieer de Presentation-klasse die de presentatie vertegenwoordigt
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // Maak een referentie naar het IDocumentProperties-object dat aan de presentatie is gekoppeld
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Geef de ingebouwde eigenschappen weer
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
>  // Instantieer de Presentation-klasse die de presentatie vertegenwoordigt
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // Maak een referentie naar het IDocumentProperties-object dat aan de presentatie is gekoppeld
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Stel de ingebouwde eigenschappen in
>      documentProperties.setAuthor("Aspose.Slides for Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // Sla uw presentatie op in een bestand
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | Initialiseert een nieuwe instantie van klasse [DocumentProperties](../../com.aspose.slides/documentproperties). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Geeft de app-versie terug. |
| [getNameOfApplication()](#getNameOfApplication--) | Geeft de naam van de applicatie terug of stelt deze in. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Geeft de naam van de applicatie terug of stelt deze in. |
| [getCompany()](#getCompany--) | Geeft de bedrijfs-eigenschap terug of stelt deze in. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Geeft de bedrijfs-eigenschap terug of stelt deze in. |
| [getManager()](#getManager--) | Geeft de manager-eigenschap terug of stelt deze in. |
| [setManager(String value)](#setManager-java.lang.String-) | Geeft de manager-eigenschap terug of stelt deze in. |
| [getPresentationFormat()](#getPresentationFormat--) | Geeft het beoogde formaat van een presentatie terug of stelt dit in. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Geeft het beoogde formaat van een presentatie terug of stelt dit in. |
| [getSharedDoc()](#getSharedDoc--) | Bepaalt of de presentatie wordt gedeeld tussen meerdere personen. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Bepaalt of de presentatie wordt gedeeld tussen meerdere personen. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Geeft de sjabloon van een applicatie terug of stelt deze in. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Geeft de sjabloon van een applicatie terug of stelt deze in. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Totale bewerkingstijd van een presentatie. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Totale bewerkingstijd van een presentatie. |
| [getTitle()](#getTitle--) | Geeft de titel van een presentatie terug of stelt deze in. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Geeft de titel van een presentatie terug of stelt deze in. |
| [getSubject()](#getSubject--) | Geeft het onderwerp van een presentatie terug of stelt dit in. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Geeft het onderwerp van een presentatie terug of stelt dit in. |
| [getAuthor()](#getAuthor--) | Geeft de auteur van een presentatie terug of stelt deze in. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Geeft de auteur van een presentatie terug of stelt deze in. |
| [getKeywords()](#getKeywords--) | Geeft de trefwoorden van een presentatie terug of stelt deze in. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Geeft de trefwoorden van een presentatie terug of stelt deze in. |
| [getComments()](#getComments--) | Geeft de opmerkingen van een presentatie terug of stelt deze in. |
| [setComments(String value)](#setComments-java.lang.String-) | Geeft de opmerkingen van een presentatie terug of stelt deze in. |
| [getCategory()](#getCategory--) | Geeft de categorie van een presentatie terug of stelt deze in. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Geeft de categorie van een presentatie terug of stelt deze in. |
| [getCreatedTime()](#getCreatedTime--) | Geeft de datum terug waarop een presentatie is gemaakt. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Geeft de datum terug waarop een presentatie is gemaakt. |
| [getLastSavedTime()](#getLastSavedTime--) | Geeft de datum terug waarop een presentatie voor het laatst is gewijzigd. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Geeft de datum terug waarop een presentatie voor het laatst is gewijzigd. |
| [getLastPrinted()](#getLastPrinted--) | Geeft de datum terug waarop een presentatie voor het laatst is afgedrukt. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Geeft de datum terug waarop een presentatie voor het laatst is afgedrukt. |
| [getLastSavedBy()](#getLastSavedBy--) | Geeft de naam van de laatste persoon die een presentatie heeft gewijzigd terug of stelt deze in. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Geeft de naam van de laatste persoon die een presentatie heeft gewijzigd terug of stelt deze in. |
| [getRevisionNumber()](#getRevisionNumber--) | Geeft het revisienummer van de presentatie terug of stelt dit in. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Geeft het revisienummer van de presentatie terug of stelt dit in. |
| [getContentStatus()](#getContentStatus--) | Geeft de inhoudsstatus van een presentatie terug of stelt deze in. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Geeft de inhoudsstatus van een presentatie terug of stelt deze in. |
| [getContentType()](#getContentType--) | Geeft het inhoudstype van een presentatie terug of stelt dit in. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Geeft het inhoudstype van een presentatie terug of stelt dit in. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Geeft de HyperlinkBase-documenteigenschap terug of stelt deze in. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Geeft de HyperlinkBase-documenteigenschap terug of stelt deze in. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Geeft het aantal aangepaste eigenschappen dat daadwerkelijk in een collectie zit terug. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Retourneert een aangepaste eigenschapsnaam op de opgegeven index. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Verwijdert een aangepaste eigenschap die is gekoppeld aan een opgegeven naam. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Controleert aanwezigheid van een aangepaste eigenschap met een opgegeven naam. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Geeft de aangepaste eigenschap die aan een opgegeven naam is gekoppeld terug of stelt deze in. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Geeft de aangepaste eigenschap die aan een opgegeven naam is gekoppeld terug of stelt deze in. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Haalt een benoemde booleaanse waarde op uit de aangepaste eigenschappen. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Haalt een benoemde gehele-getalwaarde op uit de aangepaste eigenschappen. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Haalt een benoemde datum-tijdwaarde op uit de aangepaste eigenschappen. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Haalt een benoemde tekenreekswaarde op uit de aangepaste eigenschappen. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Haalt een benoemde float-waarde op uit de aangepaste eigenschappen. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Haalt een benoemde double-waarde op uit de aangepaste eigenschappen. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Stelt een benoemde booleaanse aangepaste eigenschap in. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Stelt een benoemde gehele-getal aangepaste eigenschap in. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Stelt een benoemde datum-tijd aangepaste eigenschap in. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Stelt een benoemde tekenreeks aangepaste eigenschap in. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Stelt een benoemde float-aangepaste eigenschap in. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Stelt een benoemde double-aangepaste eigenschap in. |
| [clearCustomProperties()](#clearCustomProperties--) | Verwijdert alle aangepaste eigenschappen. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Haalt een array van gevoeligheidslabels op uit de aangepaste documenteigenschappen (Microsoft Information Protection SDK-metadata). |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Wis en stel standaardwaarden in voor alle ingebouwde eigenschappen. |
| [getScaleCrop()](#getScaleCrop--) | Geeft de weergavemodus van de miniatuur van het document aan. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Geeft de weergavemodus van de miniatuur van het document aan. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Geeft aan of hyperlinks in een document up-to-date zijn. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Geeft aan of hyperlinks in een document up-to-date zijn. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Specificeert dat één of meer hyperlinks in dit onderdeel uitsluitend in dit onderdeel door een producer zijn bijgewerkt. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Specificeert dat één of meer hyperlinks in dit onderdeel uitsluitend in dit onderdeel door een producer zijn bijgewerkt. |
| [getSlides()](#getSlides--) | Geeft het totale aantal dia's in een presentatiedocument terug. |
| [getHiddenSlides()](#getHiddenSlides--) | Geeft het aantal verborgen dia's in een presentatiedocument terug. |
| [getNotes()](#getNotes--) | Geeft het aantal dia's in een presentatie met notities terug. |
| [getParagraphs()](#getParagraphs--) | Geeft het totale aantal alinea's dat in een document is gevonden, indien van toepassing, terug. |
| [getWords()](#getWords--) | Geeft het totale aantal woorden in een document terug. |
| [getMultimediaClips()](#getMultimediaClips--) | Geeft het totale aantal geluids- of videoclips dat in het document aanwezig is terug. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Specificeert de titel van elk documentonderdeel. |
| [getHeadingPairs()](#getHeadingPairs--) | Geeft de groepering van documentonderdelen en het aantal onderdelen in elke groep aan. |
| [deepClone()](#deepClone--) | Kloont het huidige object |
| [cloneT()](#cloneT--) | Kloont het huidige object |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

Initialiseert een nieuwe instantie van klasse [DocumentProperties](../../com.aspose.slides/documentproperties).

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

Geeft de app-versie terug. Alleen-lezen String.

**Retour:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```

Geeft de naam van de applicatie terug of stelt deze in. Lezen/schrijven String.

**Retour:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

Stelt de naam van de applicatie in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getCompany() {#getCompany--}
```
public final String getCompany()
```

Geeft de bedrijfs-eigenschap terug of stelt deze in. Lezen/schrijven String.

**Retour:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

Stelt de bedrijfs-eigenschap in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getManager() {#getManager--}
```
public final String getManager()
```

Geeft de manager-eigenschap terug of stelt deze in. Lezen/schrijven String.

**Retour:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

Stelt de manager-eigenschap in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

Geeft het beoogde formaat van een presentatie terug of stelt dit in. Lezen/schrijven String.

**Retour:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

Stelt het beoogde formaat van een presentatie in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```

Bepaalt of de presentatie wordt gedeeld tussen meerdere personen. Lezen/schrijven boolean.

**Retour:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```

Stelt vast of de presentatie wordt gedeeld tussen meerdere personen. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```

Geeft de sjabloon van een applicatie terug of stelt deze in. Lezen/schrijven String.

**Retour:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

Stelt de sjabloon van een applicatie in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```

Totale bewerkingstijd van een presentatie. Lezen/schrijven double.

**Retour:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```

Stelt de totale bewerkingstijd van een presentatie in. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getTitle() {#getTitle--}
```
public final String getTitle()
```

Geeft de titel van een presentatie terug of stelt deze in. Lezen/schrijven String.

**Retour:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

Stelt de titel van een presentatie in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getSubject() {#getSubject--}
```
public final String getSubject()
```

Geeft het onderwerp van een presentatie terug of stelt dit in. Lezen/schrijven String.

**Retour:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

Stelt het onderwerp van een presentatie in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

Geeft de auteur van een presentatie terug of stelt deze in. Lezen/schrijven String.

**Retour:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```java
public final void setAuthor(String value)
```

Stelt de auteur van een presentatie in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

Geeft de trefwoorden van een presentatie terug of stelt deze in. Lezen/schrijven String.

**Retour:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```

Stelt de trefwoorden van een presentatie in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public final String getComments()
```

Geeft de opmerkingen van een presentatie terug of stelt deze in. Lezen/schrijven String.

**Retour:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

Stelt de opmerkingen van een presentatie in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getCategory() {#getCategory--}
```
public final String getCategory()
```

Geeft de categorie van een presentatie terug of stelt deze in. Lezen/schrijven String.

**Retour:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

Stelt de categorie van een presentatie in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```
Retourneert de datum waarop een presentatie is aangemaakt. De waarden zijn in UTC. Lezen/Schrijven java.util.Date.

**Retournen:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```


Retourneert de datum waarop een presentatie is aangemaakt. De waarden zijn in UTC. Lezen/Schrijven java.util.Date.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```


Retourneert de datum waarop een presentatie voor het laatst is gewijzigd. De waarden zijn in UTC. Alleen-lezen in het geval van Presentation.DocumentProperties (omdat deze intern wordt bijgewerkt tijdens het opslaan van het IPresentation-object). Kan worden gewijzigd via een DocumentProperties-instantie die wordt geretourneerd door methode [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Zie het voorbeeld in methode-samenvatting [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Retournen:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```


Retourneert de datum waarop een presentatie voor het laatst is gewijzigd. De waarden zijn in UTC. Alleen-lezen in het geval van Presentation.DocumentProperties (omdat deze intern wordt bijgewerkt tijdens het opslaan van het IPresentation-object). Kan worden gewijzigd via een DocumentProperties-instantie die wordt geretourneerd door methode [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Zie het voorbeeld in methode-samenvatting [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```


Retourneert de datum waarop een presentatie voor het laatst is afgedrukt. Lezen/Schrijven java.util.Date.

**Retournen:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```


Retourneert de datum waarop een presentatie voor het laatst is afgedrukt. Lezen/Schrijven java.util.Date.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```


Retourneert of stelt de naam in van de laatste persoon die een presentatie heeft gewijzigd. Lezen/Schrijven String.

**Retournen:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```


Retourneert of stelt de naam in van de laatste persoon die een presentatie heeft gewijzigd. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```


Retourneert of stelt het revisienummer van de presentatie in. Lezen/Schrijven int.

**Retournen:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```


Retourneert of stelt het revisienummer van de presentatie in. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```


Retourneert of stelt de inhoudsstatus van een presentatie in. Lezen/Schrijven String.

**Retournen:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```


Retourneert of stelt de inhoudsstatus van een presentatie in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```


Retourneert of stelt het inhoudstype van een presentatie in. Lezen/Schrijven String.

**Retournen:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```


Retourneert of stelt het inhoudstype van een presentatie in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```


Retourneert of stelt de HyperlinkBase-documenteigenschap in. Lezen/Schrijven String.

**Retournen:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```


Retourneert of stelt de HyperlinkBase-documenteigenschap in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```


Retourneert het aantal aangepaste eigenschappen dat daadwerkelijk in een collectie aanwezig is. Alleen-lezen int.

**Retournen:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```


Retourneert een aangepaste eigenschapsnaam op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van een aangepaste eigenschap die moet worden opgehaald. |

**Retournen:**
java.lang.String - Aangepaste eigenschapsnaam op de opgegeven index.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```


Verwijdert een aangepaste eigenschap die is gekoppeld aan een opgegeven naam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de te verwijderen aangepaste eigenschap. |

**Retournen:**
boolean - Retourneert true als een eigenschap is verwijderd, false anders.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```


Controleert of een aangepaste eigenschap met een opgegeven naam aanwezig is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de te controleren aangepaste eigenschap. |

**Retournen:**
boolean - Retourneert true als de eigenschap bestaat, false anders.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```


Retourneert of stelt de aangepaste eigenschap in die is gekoppeld aan een opgegeven naam. Lezen/Schrijven Object.

--------------------

Waarde kan **int**, **float**, **String**, **boolean** of **Date** zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String |  |

**Retournen:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public final void set_Item(String name, Object value)
```


Retourneert of stelt de aangepaste eigenschap in die is gekoppeld aan een opgegeven naam. Lezen/Schrijven Object.

--------------------

Waarde kan **int**, **float**, **String**, **boolean** of **Date** zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |
### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```


Haalt een benoemde booleaanse waarde op uit de aangepaste eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de op te halen aangepaste eigenschap |
| value | boolean[] | Aangepaste eigenschapswaarde |
### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```


Haalt een benoemde gehele getalwaarde op uit de aangepaste eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de op te halen aangepaste eigenschap |
| value | int[] | Aangepaste eigenschapswaarde |
### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```


Haalt een benoemde DateTime-waarde op uit de aangepaste eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de op te halen aangepaste eigenschap |
| value | java.util.Date[] | Aangepaste eigenschapswaarde |
### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```


Haalt een benoemde tekenreekswaarde op uit de aangepaste eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de op te halen aangepaste eigenschap |
| value | java.lang.String[] | Aangepaste eigenschapswaarde |
### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```


Haalt een benoemde float-waarde op uit de aangepaste eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de op te halen aangepaste eigenschap |
| value | float[] | Aangepaste eigenschapswaarde |
### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```


Haalt een benoemde double-waarde op uit de aangepaste eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de op te halen aangepaste eigenschap. |
| value | double[] | Aangepaste eigenschapswaarde |
### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```


Stelt een benoemde booleaanse aangepaste eigenschap in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de in te stellen aangepaste eigenschap |
| value | boolean | Aangepaste eigenschapswaarde |
### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```


Stelt een benoemde gehele getalwaarde in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de in te stellen aangepaste eigenschap |
| value | int | Aangepaste eigenschapswaarde |
### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```


Stelt een benoemde DateTime-eigenschap in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de in te stellen aangepaste eigenschap |
| value | java.util.Date | Aangepaste eigenschapswaarde |
### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```


Stelt een benoemde tekenreeks-eigenschap in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de in te stellen aangepaste eigenschap |
| value | java.lang.String | Aangepaste eigenschapswaarde |
### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```


Stelt een benoemde float-eigenschap in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de in te stellen aangepaste eigenschap |
| value | float | Aangepaste eigenschapswaarde |
### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```


Stelt een benoemde double-eigenschap in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de in te stellen aangepaste eigenschap |
| value | double | Aangepaste eigenschapswaarde |
### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```


Verwijdert alle aangepaste eigenschappen.

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```


Haalt een array met gevoeligheidslabels op uit de aangepaste documenteigenschappen (Microsoft Information Protection SDK-metadata).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Haal gevoeligheidslabels op uit de aangepaste documenteigenschappen
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Voeg label toe aan de collectie
>          // Hier kunt u een controle toevoegen voor de geldigheid van de labelinformatie (het label is beschikbaar, etc)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retournen:**
com.aspose.slides.ISensitivityLabel[]
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public final void clearBuiltInProperties()
```


Verwijdert alle ingebouwde eigenschappen en stelt standaardwaarden in.

### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```


Geeft de weergavemodus van de miniatuurfoto van het document aan. Stel dit element in op **true** om schalen van de miniatuurfoto naar het scherm mogelijk te maken. Stel dit element in op **false** om bijsnijden van de miniatuurfoto mogelijk te maken zodat alleen secties die op het scherm passen worden getoond. Lezen/Schrijven boolean.

**Retournen:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```


Geeft de weergavemodus van de miniatuurfoto van het document aan. Stel dit element in op **true** om schalen van de miniatuurfoto naar het scherm mogelijk te maken. Stel dit element in op **false** om bijsnijden van de miniatuurfoto mogelijk te maken zodat alleen secties die op het scherm passen worden getoond. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```


Geeft aan of hyperlinks in een document actueel zijn. Stel dit element in op **true** om aan te geven dat hyperlinks worden bijgewerkt. Stel dit element in op **false** om aan te geven dat hyperlinks verouderd zijn. Lezen/Schrijven boolean.

**Retournen:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```
Geeft aan of hyperlinks in een document up-to-date zijn. Stel dit element in op **true** om aan te geven dat hyperlinks zijn bijgewerkt. Stel dit element in op **false** om aan te geven dat hyperlinks verouderd zijn. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

Specificeert dat een of meer hyperlinks in dit onderdeel uitsluitend in dit onderdeel door een producer zijn bijgewerkt. De volgende producer die dit document opent, dient de hyperlinkrelaties bij te werken met de nieuwe hyperlinks die in dit onderdeel zijn gespecificeerd. Lezen/Schrijven boolean.

**Returns:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

Specificeert dat een of meer hyperlinks in dit onderdeel uitsluitend in dit onderdeel door een producer zijn bijgewerkt. De volgende producer die dit document opent, dient de hyperlinkrelaties bij te werken met de nieuwe hyperlinks die in dit onderdeel zijn gespecificeerd. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public final int getSlides()
```

Retour: het totale aantal dia's in een presentatiedocument. Alleen-lezen int.

**Returns:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

Retour: het aantal verborgen dia's in een presentatiedocument. Alleen-lezen int.

**Returns:**
int
### getNotes() {#getNotes--}
```
public final int getNotes()
```

Retour: het aantal dia's in een presentatie die notities bevatten. Alleen-lezen int.

**Returns:**
int
### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

Retour: het totale aantal alinea's dat in een document wordt gevonden, indien van toepassing. Alleen-lezen int.

**Returns:**
int
### getWords() {#getWords--}
```
public final int getWords()
```

Retour: het totale aantal woorden dat in een document staat. Alleen-lezen int.

**Returns:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

Retour: het totale aantal geluids- of videoclips dat in het document aanwezig is. Alleen-lezen int.

**Returns:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

Specificeert de titel van elk documentonderdeel. Deze onderdelen zijn geen documentonderdelen maar conceptuele weergaven van documentsecties. Alleen-lezen String[].

**Returns:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

Geeft de groepering van documentonderdelen en het aantal onderdelen in elke groep aan. Alleen-lezen IHeadingPair[].

**Returns:**
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Kloon huidig object

**Returns:**
java.lang.Object - Kloon
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

Kloon huidig object

**Returns:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Kloon