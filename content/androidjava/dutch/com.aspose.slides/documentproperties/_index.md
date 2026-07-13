---
title: DocumentProperties
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt de eigenschappen van een presentatie voor.
type: docs
url: /nl/com.aspose.slides/documentproperties/
---
**Erfelijkheid:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

Stelt de eigenschappen van een presentatie voor.

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // Instantieer de Presentation-klasse die de presentatie representeert
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // Maak een referentie naar het IDocumentProperties-object dat aan de Presentation is gekoppeld
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
>  // Instantieer de Presentation-klasse die de Presentation representeert
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // Maak een referentie naar het IDocumentProperties-object dat aan de Presentation is gekoppeld
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Stel de ingebouwde eigenschappen in
>      documentProperties.setAuthor("Aspose.Slides for Android via Java");
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
| [DocumentProperties()](#DocumentProperties--) | Initialiseert een nieuw exemplaar van klasse [DocumentProperties](../../com.aspose.slides/documentproperties). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Retourneert de appversie. |
| [getNameOfApplication()](#getNameOfApplication--) | Retourneert of stelt de naam van de applicatie in. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Retourneert of stelt de naam van de applicatie in. |
| [getCompany()](#getCompany--) | Retourneert of stelt de bedrijfsproperty in. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Retourneert of stelt de bedrijfsproperty in. |
| [getManager()](#getManager--) | Retourneert of stelt de managerproperty in. |
| [setManager(String value)](#setManager-java.lang.String-) | Retourneert of stelt de managerproperty in. |
| [getPresentationFormat()](#getPresentationFormat--) | Retourneert of stelt het beoogde formaat van een presentatie in. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Retourneert of stelt het beoogde formaat van een presentatie in. |
| [getSharedDoc()](#getSharedDoc--) | Bepaalt of de presentatie gedeeld wordt door meerdere personen. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Bepaalt of de presentatie gedeeld wordt door meerdere personen. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Retourneert of stelt het sjabloon van een applicatie in. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Retourneert of stelt het sjabloon van een applicatie in. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Totale bewerkingstijd van een presentatie. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Totale bewerkingstijd van een presentatie. |
| [getTitle()](#getTitle--) | Retourneert of stelt de titel van een presentatie in. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Retourneert of stelt de titel van een presentatie in. |
| [getSubject()](#getSubject--) | Retourneert of stelt het onderwerp van een presentatie in. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Retourneert of stelt het onderwerp van een presentatie in. |
| [getAuthor()](#getAuthor--) | Retourneert of stelt de auteur van een presentatie in. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Retourneert of stelt de auteur van een presentatie in. |
| [getKeywords()](#getKeywords--) | Retourneert of stelt de trefwoorden van een presentatie in. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Retourneert of stelt de trefwoorden van een presentatie in. |
| [getComments()](#getComments--) | Retourneert of stelt de opmerkingen van een presentatie in. |
| [setComments(String value)](#setComments-java.lang.String-) | Retourneert of stelt de opmerkingen van een presentatie in. |
| [getCategory()](#getCategory--) | Retourneert of stelt de categorie van een presentatie in. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Retourneert of stelt de categorie van een presentatie in. |
| [getCreatedTime()](#getCreatedTime--) | Retourneert de datum waarop een presentatie werd aangemaakt. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Retourneert de datum waarop een presentatie werd aangemaakt. |
| [getLastSavedTime()](#getLastSavedTime--) | Retourneert de datum waarop een presentatie voor het laatst werd gewijzigd. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Retourneert de datum waarop een presentatie voor het laatst werd gewijzigd. |
| [getLastPrinted()](#getLastPrinted--) | Retourneert de datum waarop een presentatie voor het laatst werd afgedrukt. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Retourneert de datum waarop een presentatie voor het laatst werd afgedrukt. |
| [getLastSavedBy()](#getLastSavedBy--) | Retourneert of stelt de naam van de laatste persoon die een presentatie heeft gewijzigd in. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Retourneert of stelt de naam van de laatste persoon die een presentatie heeft gewijzigd in. |
| [getRevisionNumber()](#getRevisionNumber--) | Retourneert of stelt het revisienummer van de presentatie in. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Retourneert of stelt het revisienummer van de presentatie in. |
| [getContentStatus()](#getContentStatus--) | Retourneert of stelt de inhoudsstatus van een presentatie in. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Retourneert of stelt de inhoudsstatus van een presentatie in. |
| [getContentType()](#getContentType--) | Retourneert of stelt het inhoudstype van een presentatie in. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Retourneert of stelt het inhoudstype van een presentatie in. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Retourneert of stelt de HyperlinkBase-documenteigenschap in. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Retourneert of stelt de HyperlinkBase-documenteigenschap in. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Retourneert het aantal aangepaste eigenschappen dat werkelijk in een collectie voorkomt. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Retourneert een naam van een aangepaste eigenschap op de opgegeven index. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Verwijdert een aangepaste eigenschap die aan een opgegeven naam is gekoppeld. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Controleert de aanwezigheid van een aangepaste eigenschap met een opgegeven naam. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Retourneert of stelt de aangepaste eigenschap die aan een opgegeven naam is gekoppeld in. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Retourneert of stelt de aangepaste eigenschap die aan een opgegeven naam is gekoppeld in. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Haalt een benoemde booleaanse waarde op uit de aangepaste eigenschappen. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Haalt een benoemde gehele getalwaarde op uit de aangepaste eigenschappen. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Haalt een benoemde DateTime-waarde op uit de aangepaste eigenschappen. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Haalt een benoemde tekenreekswaarde op uit de aangepaste eigenschappen. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Haalt een benoemde float-waarde op uit de aangepaste eigenschappen. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Haalt een benoemde double-waarde op uit de aangepaste eigenschappen. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Stelt een benoemde booleaanse aangepaste eigenschap in. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Stelt een benoemde gehele getalwaarde aangepaste eigenschap in. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Stelt een benoemde DateTime aangepaste eigenschap in. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Stelt een benoemde tekenreeks aangepaste eigenschap in. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Stelt een benoemde float aangepaste eigenschap in. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Stelt een benoemde double aangepaste eigenschap in. |
| [clearCustomProperties()](#clearCustomProperties--) | Verwijdert alle aangepaste eigenschappen. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Haalt een array met gevoeligheidslabels op uit de aangepaste documenteigenschappen (Microsoft Information Protection SDK Metadata). |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Wis t en stelt standaardwaarden in voor alle ingebouwde eigenschappen. |
| [getScaleCrop()](#getScaleCrop--) | Geeft de weergavemodus van de miniatuur van het document aan. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Geeft de weergavemodus van de miniatuur van het document aan. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Geeft aan of hyperlinks in een document actueel zijn. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Geeft aan of hyperlinks in een document actueel zijn. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Specificeert dat een of meer hyperlinks in dit onderdeel exclusief in dit onderdeel door een producer werden bijgewerkt. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Specificeert dat een of meer hyperlinks in dit onderdeel exclusief in dit onderdeel door een producer werden bijgewerkt. |
| [getSlides()](#getSlides--) | Retourneert het totale aantal dia's in een presentatiedocument. |
| [getHiddenSlides()](#getHiddenSlides--) | Retourneert het aantal verborgen dia's in een presentatiedocument. |
| [getNotes()](#getNotes--) | Retourneert het aantal dia's in een presentatie die notities bevatten. |
| [getParagraphs()](#getParagraphs--) | Retourneert het totale aantal alinea's dat in een document is gevonden, indien van toepassing. |
| [getWords()](#getWords--) | Retourneert het totale aantal woorden dat in een document staat. |
| [getMultimediaClips()](#getMultimediaClips--) | Retourneert het totale aantal geluid- of videoclips dat in het document aanwezig is. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Specificeert de titel van elk documentonderdeel. |
| [getHeadingPairs()](#getHeadingPairs--) | Geeft de groepering van documentonderdelen en het aantal onderdelen in elke groep aan. |
| [deepClone()](#deepClone--) | Kloont het huidige object |
| [cloneT()](#cloneT--) | Kloont het huidige object |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

Initialiseert een nieuw exemplaar van klasse [DocumentProperties](../../com.aspose.slides/documentproperties).

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

Retourneert de appversie. Alleen-lezen String.

**Retourneert:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```

Retourneert of stelt de naam van de applicatie in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setNameOfApplication(java.lang.String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

Retourneert of stelt de naam van de applicatie in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public final String getCompany()
```

Retourneert of stelt de bedrijfsproperty in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setCompany(java.lang.String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

Retourneert of stelt de bedrijfsproperty in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public final String getManager()
```

Retourneert of stelt de managerproperty in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setManager(java.lang.String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

Retourneert of stelt de managerproperty in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

Retourneert of stelt het beoogde formaat van een presentatie in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setPresentationFormat(java.lang.String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

Retourneert of stelt het beoogde formaat van een presentatie in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```

Bepaalt of de presentatie gedeeld wordt door meerdere personen. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```

Bepaalt of de presentatie gedeeld wordt door meerdere personen. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```

Retourneert of stelt het sjabloon van een applicatie in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setApplicationTemplate(java.lang.String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

Retourneert of stelt het sjabloon van een applicatie in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```

Totale bewerkingstijd van een presentatie. Lezen/Schrijven double.

**Retourneert:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```

Totale bewerkingstijd van een presentatie. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```

Retourneert of stelt de titel van een presentatie in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setTitle(java.lang.String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

Retourneert of stelt de titel van een presentatie in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```

Retourneert of stelt het onderwerp van een presentatie in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setSubject(java.lang.String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

Retourneert of stelt het onderwerp van een presentatie in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

Retourneert of stelt de auteur van een presentatie in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setAuthor(java.lang.String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

Retourneert of stelt de auteur van een presentatie in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

Retourneert of stelt de trefwoorden van een presentatie in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setKeywords(java.lang.String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```

Retourneert of stelt de trefwoorden van een presentatie in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```

Retourneert of stelt de opmerkingen van een presentatie in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setComments(java.lang.String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

Retourneert of stelt de opmerkingen van een presentatie in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public final String getCategory()
```

Retourneert of stelt de categorie van een presentatie in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setCategory(java.lang.String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

Retourneert of stelt de categorie van een presentatie in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

Retourneert de datum waarop een presentatie werd aangemaakt. Waarden zijn in UTC. Lezen/Schrijven java.util.Date.

**Retourneert:**
java.util.Date
### setCreatedTime(java.util.Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Retourneert de datum waarop een presentatie werd aangemaakt. Waarden zijn in UTC. Lezen/Schrijven java.util.Date.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```

Retourneert de datum waarop een presentatie voor het laatst werd gewijzigd. Waarden zijn in UTC. Alleen-lezen in het geval van Presentation.DocumentProperties (omdat deze intern wordt bijgewerkt tijdens het opslaan van het IPresentation-object). Kan worden gewijzigd via de DocumentProperties-instantie die wordt geretourneerd door methode [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Zie het voorbeeld in [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-)-samenvatting.

**Retourneert:**
java.util.Date
### setLastSavedTime(java.util.Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```

Retourneert de datum waarop een presentatie voor het laatst werd gewijzigd. Waarden zijn in UTC. Alleen-lezen in het geval van Presentation.DocumentProperties (omdat deze intern wordt bijgewerkt tijdens het opslaan van het IPresentation-object). Kan worden gewijzigd via de DocumentProperties-instantie die wordt geretourneerd door methode [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Zie het voorbeeld in [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-)-samenvatting.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```

Retourneert de datum waarop een presentatie voor het laatst werd afgedrukt. Lezen/Schrijven java.util.Date.

**Retourneert:**
java.util.Date
### setLastPrinted(java.util.Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```

Retourneert de datum waarop een presentatie voor het laatst werd afgedrukt. Lezen/Schrijven java.util.Date.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```

Retourneert of stelt de naam van de laatste persoon die een presentatie heeft gewijzigd in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setLastSavedBy(java.lang.String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```

Retourneert of stelt de naam van de laatste persoon die een presentatie heeft gewijzigd in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```

Retourneert of stelt het revisienummer van de presentatie in. Lezen/Schrijven int.

**Retourneert:**
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

**Retourneert:**
java.lang.String
### setContentStatus(java.lang.String value) {#setContentStatus-java.lang.String-}
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

**Retourneert:**
java.lang.String
### setContentType(java.lang.String value) {#setContentType-java.lang.String-}
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

**Retourneert:**
java.lang.String
### setHyperlinkBase(java.lang.String value) {#setHyperlinkBase-java.lang.String-}
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

Retourneert het aantal aangepaste eigenschappen dat werkelijk in een collectie voorkomt. Alleen-lezen int.

**Retourneert:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```

Retourneert een naam van een aangepaste eigenschap op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index van een aangepaste eigenschap die opgehaald moet worden. |

**Retourneert:**
java.lang.String - Aangepaste eigenschapsnaam op de opgegeven index.
### removeCustomProperty(java.lang.String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```

Verwijdert een aangepaste eigenschap die aan een opgegeven naam is gekoppeld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de te verwijderen aangepaste eigenschap. |

**Retourneert:**
boolean - Retourneert true als een eigenschap is verwijderd, anders false.
### containsCustomProperty(java.lang.String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean 
```

Controleert de aanwezigheid van een aangepaste eigenschap met een opgegeven naam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de te controleren aangepaste eigenschap. |

**Retourneert:**
boolean - Retourneert true als de eigenschap bestaat, anders false.
### get_Item(java.lang.String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```

Retourneert of stelt de aangepaste eigenschap die aan een opgegeven naam is gekoppeld in. Lezen/Schrijven Object.

--------------------

Waarde kan **int**, **float**, **String**, **boolean** of **Date** zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String |  |

**Retourneert:**
java.lang.Object
### set_Item(java.lang.String name, java.lang.Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public final void set_Item(String name, Object value)
```

Retourneert of stelt de aangepaste eigenschap die aan een opgegeven naam is gekoppeld in. Lezen/Schrijven Object.

--------------------

Waarde kan **int**, **float**, **String**, **boolean** of **Date** zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### getCustomPropertyValue(java.lang.String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```

Haalt een benoemde booleaanse waarde op uit de aangepaste eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de op te halen aangepaste eigenschap |
| value | boolean[] | Waarde van de aangepaste eigenschap |

### getCustomPropertyValue(java.lang.String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```

Haalt een benoemde gehele getalwaarde op uit de aangepaste eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de op te halen aangepaste eigenschap |
| value | int[] | Waarde van de aangepaste eigenschap |

### getCustomPropertyValue(java.lang.String name, java.util.Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```

Haalt een benoemde DateTime-waarde op uit de aangepaste eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de op te halen aangepaste eigenschap |
| value | java.util.Date[] | Waarde van de aangepaste eigenschap |

### getCustomPropertyValue(java.lang.String name, java.lang.String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```

Haalt een benoemde tekenreekswaarde op uit de aangepaste eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de op te halen aangepaste eigenschap |
| value | java.lang.String[] | Waarde van de aangepaste eigenschap |

### getCustomPropertyValue(java.lang.String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```

Haalt een benoemde float-waarde op uit de aangepaste eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de op te halen aangepaste eigenschap |
| value | float[] | Waarde van de aangepaste eigenschap |

### getCustomPropertyValue(java.lang.String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```

Haalt een benoemde double-waarde op uit de aangepaste eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de op te halen aangepaste eigenschap. |
| value | double[] | Waarde van de aangepaste eigenschap |

### setCustomPropertyValue(java.lang.String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```

Stelt een benoemde booleaanse aangepaste eigenschap in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de aan te stellen aangepaste eigenschap |
| value | boolean | Waarde van de aangepaste eigenschap |

### setCustomPropertyValue(java.lang.String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```

Stelt een benoemde gehele getalwaarde aangepaste eigenschap in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de aan te stellen aangepaste eigenschap |
| value | int | Waarde van de aangepaste eigenschap |

### setCustomPropertyValue(java.lang.String name, java.util.Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```

Stelt een benoemde DateTime-aangepaste eigenschap in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de aan te stellen aangepaste eigenschap |
| value | java.util.Date | Waarde van de aangepaste eigenschap |

### setCustomPropertyValue(java.lang.String name, java.lang.String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```

Stelt een benoemde tekenreeks aangepaste eigenschap in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de aan te stellen aangepaste eigenschap |
| value | java.lang.String | Waarde van de aangepaste eigenschap |

### setCustomPropertyValue(java.lang.String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```

Stelt een benoemde float aangepaste eigenschap in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de aan te stellen aangepaste eigenschap |
| value | float | Waarde van de aangepaste eigenschap |

### setCustomPropertyValue(java.lang.String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```

Stelt een benoemde double aangepaste eigenschap in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de aan te stellen aangepaste eigenschap |
| value | double | Waarde van de aangepaste eigenschap |

### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```

Verwijdert alle aangepaste eigenschappen.

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```

Haalt een array met gevoeligheidslabels op uit de aangepaste documenteigenschappen (Microsoft Information Protection SDK Metadata).

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
>          // Hier kunt u een controle toevoegen voor de geldigheid van de labelinformatie (het label is beschikbaar, enz.)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourneert:**
com.aspose.slides.ISensitivityLabel[]
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public final void clearBuiltInProperties()
```

Wis t en stelt standaardwaarden in voor alle ingebouwde eigenschappen.

### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```

Geeft de weergavemodus van de miniatuur van het document aan. Stel dit element in op **true** om het schalen van de miniatuur naar het display mogelijk te maken. Stel dit element in op **false** om bijsnijden van de miniatuur mogelijk te maken zodat alleen secties die op het display passen worden getoond. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```

Geeft de weergavemodus van de miniatuur van het document aan. Stel dit element in op **true** om het schalen van de miniatuur naar het display mogelijk te maken. Stel dit element in op **false** om bijsnijden van de miniatuur mogelijk te maken zodat alleen secties die op het display passen worden getoond. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```

Geeft aan of hyperlinks in een document actueel zijn. Stel dit element in op **true** om aan te geven dat hyperlinks zijn bijgewerkt. Stel dit element in op **false** om aan te geven dat hyperlinks verouderd zijn. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```

Geeft aan of hyperlinks in een document actueel zijn. Stel dit element in op **true** om aan te geven dat hyperlinks zijn bijgewerkt. Stel dit element in op **false** om aan te geven dat hyperlinks verouderd zijn. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

Specificeert dat een of meer hyperlinks in dit onderdeel exclusief in dit onderdeel door een producer werden bijgewerkt. De volgende producer die dit document opent, zal de hyperlinkrelaties bijwerken met de nieuwe hyperlinks die in dit onderdeel zijn gespecificeerd. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

Specificeert dat een of meer hyperlinks in dit onderdeel exclusief in dit onderdeel door een producer werden bijgewerkt. De volgende producer die dit document opent, zal de hyperlinkrelaties bijwerken met de nieuwe hyperlinks die in dit onderdeel zijn gespecificeerd. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public final int getSlides()
```

Retourneert het totale aantal dia's in een presentatiedocument. Alleen-lezen int.

**Retourneert:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

Retourneert het aantal verborgen dia's in een presentatiedocument. Alleen-lezen int.

**Retourneert:**
int
### getNotes() {#getNotes--}
```
public final int getNotes()
```

Retourneert het aantal dia's in een presentatie die notities bevatten. Alleen-lezen int.

**Retourneert:**
int
### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

Retourneert het totale aantal alinea's dat in een document is gevonden, indien van toepassing. Alleen-lezen int.

**Retourneert:**
int
### getWords() {#getWords--}
```
public final int getWords()
```

Retourneert het totale aantal woorden dat in een document staat. Alleen-lezen int.

**Retourneert:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

Retourneert het totale aantal geluid- of videoclips dat in het document aanwezig is. Alleen-lezen int.

**Retourneert:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

Specificeert de titel van elk documentonderdeel. Deze onderdelen zijn geen documentonderdelen maar conceptuele representaties van documentsecties. Alleen-lezen String[].

**Retourneert:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

Geeft de groepering van documentonderdelen en het aantal onderdelen in elke groep aan. Alleen-lezen IHeadingPair[].

**Retourneert:**
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Kloont het huidige object

**Retourneert:**
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

Kloont het huidige object

**Retourneert:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone