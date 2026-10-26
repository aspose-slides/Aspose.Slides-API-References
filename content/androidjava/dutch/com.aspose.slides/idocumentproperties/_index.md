---
title: IDocumentProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Stelt de eigenschappen van een presentatie voor.
type: docs
url: /nl/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

Stelt de eigenschappen van een presentatie voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Geeft de app-versie terug. |
| [getNameOfApplication()](#getNameOfApplication--) | Geeft de naam van de toepassing terug of stelt deze in. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Geeft de naam van de toepassing terug of stelt deze in. |
| [getCompany()](#getCompany--) | Geeft de bedrijfs-eigenschap terug of stelt deze in. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Geeft de bedrijfs-eigenschap terug of stelt deze in. |
| [getManager()](#getManager--) | Geeft de manager-eigenschap terug of stelt deze in. |
| [setManager(String value)](#setManager-java.lang.String-) | Geeft de manager-eigenschap terug of stelt deze in. |
| [getPresentationFormat()](#getPresentationFormat--) | Geeft het beoogde formaat van een presentatie terug of stelt dit in. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Geeft het beoogde formaat van een presentatie terug of stelt dit in. |
| [getSharedDoc()](#getSharedDoc--) | Geeft aan of de presentatie wordt gedeeld door meerdere personen. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Geeft aan of de presentatie wordt gedeeld door meerdere personen. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Geeft de sjabloon van een toepassing terug of stelt deze in. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Geeft de sjabloon van een toepassing terug of stelt deze in. |
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
| [getCreatedTime()](#getCreatedTime--) | Geeft de datum waarop een presentatie is gemaakt terug. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Geeft de datum waarop een presentatie is gemaakt terug. |
| [getLastSavedTime()](#getLastSavedTime--) | Geeft de datum waarop een presentatie voor het laatst is gewijzigd terug. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Geeft de datum waarop een presentatie voor het laatst is gewijzigd terug. |
| [getLastPrinted()](#getLastPrinted--) | Geeft de datum waarop een presentatie voor het laatst is afgedrukt terug. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Geeft de datum waarop een presentatie voor het laatst is afgedrukt terug. |
| [getLastSavedBy()](#getLastSavedBy--) | Geeft de naam van de laatste persoon die een presentatie heeft gewijzigd terug of stelt deze in. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Geeft de naam van de laatste persoon die een presentatie heeft gewijzigd terug of stelt deze in. |
| [getRevisionNumber()](#getRevisionNumber--) | Geeft het revisienummer van een presentatie terug of stelt dit in. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Geeft het revisienummer van een presentatie terug of stelt dit in. |
| [getContentStatus()](#getContentStatus--) | Geeft de inhoudsstatus van een presentatie terug of stelt deze in. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Geeft de inhoudsstatus van een presentatie terug of stelt deze in. |
| [getContentType()](#getContentType--) | Geeft het inhoudstype van een presentatie terug of stelt dit in. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Geeft het inhoudstype van een presentatie terug of stelt dit in. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Geeft de HyperlinkBase-documenteigenschap terug of stelt deze in. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Geeft de HyperlinkBase-documenteigenschap terug of stelt deze in. |
| [getScaleCrop()](#getScaleCrop--) | Geeft de weergavemodus van de miniatuur van het document aan. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Geeft de weergavemodus van de miniatuur van het document aan. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Geeft aan of hyperlinks in een document up-to-date zijn. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Geeft aan of hyperlinks in een document up-to-date zijn. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Specificeert dat een of meer hyperlinks in dit onderdeel uitsluitend in dit onderdeel door een producent zijn bijgewerkt. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Specificeert dat een of meer hyperlinks in dit onderdeel uitsluitend in dit onderdeel door een producent zijn bijgewerkt. |
| [getSlides()](#getSlides--) | Specificeert het totale aantal dia's in een presentatiedocument. |
| [getHiddenSlides()](#getHiddenSlides--) | Specificeert het aantal verborgen dia's in een presentatiedocument. |
| [getNotes()](#getNotes--) | Specificeert het aantal dia's in een presentatie met notities. |
| [getParagraphs()](#getParagraphs--) | Specificeert het totale aantal alinea's dat in een document is aangetroffen, indien van toepassing. |
| [getWords()](#getWords--) | Specificeert het totale aantal woorden dat in een document staat. |
| [getMultimediaClips()](#getMultimediaClips--) | Specificeert het totale aantal geluid- of videoclips dat in het document aanwezig is. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Specificeert de titel van elk documentonderdeel. |
| [getHeadingPairs()](#getHeadingPairs--) | Geeft de groepering van documentonderdelen en het aantal onderdelen in elke groep aan. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Geeft het aantal aangepaste eigenschappen dat daadwerkelijk in een collectie zit terug. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Retourneert een aangepaste eigenschapsnaam op de opgegeven index. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Verwijdert een aangepaste eigenschap die aan een opgegeven naam gekoppeld is. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Controleert de aanwezigheid van een aangepaste eigenschap met een opgegeven naam. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Geeft een aangepaste eigenschap terug of stelt deze in voor een opgegeven naam. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Geeft een aangepaste eigenschap terug of stelt deze in voor een opgegeven naam. |
| [clearCustomProperties()](#clearCustomProperties--) | Verwijdert alle aangepaste eigenschappen. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Leegt en stelt standaardwaarden in voor alle ingebouwde eigenschappen. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Haalt een benoemde boolean-waarde op uit de aangepaste eigenschappen. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Haalt een benoemde integer-waarde op uit de aangepaste eigenschappen. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Haalt een benoemde DateTime-waarde op uit de aangepaste eigenschappen. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Haalt een benoemde string-waarde op uit de aangepaste eigenschappen. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Haalt een benoemde float-waarde op uit de aangepaste eigenschappen. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Haalt een benoemde double-waarde op uit de aangepaste eigenschappen. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Stelt een benoemde boolean-aangepaste eigenschap in. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Stelt een benoemde integer-aangepaste eigenschap in. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Stelt een benoemde DateTime-aangepaste eigenschap in. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Stelt een benoemde string-aangepaste eigenschap in. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Stelt een benoemde float-aangepaste eigenschap in. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Stelt een benoemde double-aangepaste eigenschap in. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Haalt een array met gevoeligheidslabels op uit de aangepaste documenteigenschappen (Microsoft Information Protection SDK Metadata). |
### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```


Geeft de app-versie terug. Alleen-lezen String.

--------------------

De inhoud van dit element moet de vorm XX.YYYY hebben, waarbij X en Y numerieke waarden voorstellen; anders wordt het document als niet-conform beschouwd. Aspose.Slides geeft zijn versie weer in het formaat XX.YY.ZZ, waarbij: XX - hoofdversie YY - onderversie ZZ - patchversie. Bijvoorbeeld, de waarde 23.0105 betekent Aspose.Slides versie 23.1.5.

**Retourneert:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```


Geeft de naam van de toepassing terug of stelt deze in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```


Geeft de naam van de toepassing terug of stelt deze in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public abstract String getCompany()
```


Geeft de bedrijfs-eigenschap terug of stelt deze in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```


Geeft de bedrijfs-eigenschap terug of stelt deze in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public abstract String getManager()
```


Geeft de manager-eigenschap terug of stelt deze in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```


Geeft de manager-eigenschap terug of stelt deze in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```


Geeft het beoogde formaat van een presentatie terug of stelt dit in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```


Geeft het beoogde formaat van een presentatie terug of stelt dit in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```


Geeft aan of de presentatie wordt gedeeld door meerdere personen. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```


Geeft aan of de presentatie wordt gedeeld door meerdere personen. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```


Geeft de sjabloon van een toepassing terug of stelt deze in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```


Geeft de sjabloon van een toepassing terug of stelt deze in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```


Totale bewerkingstijd van een presentatie. Lezen/Schrijven double.

**Retourneert:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```


Totale bewerkingstijd van een presentatie. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public abstract String getTitle()
```


Geeft de titel van een presentatie terug of stelt deze in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```


Geeft de titel van een presentatie terug of stelt deze in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public abstract String getSubject()
```


Geeft het onderwerp van een presentatie terug of stelt dit in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```


Geeft het onderwerp van een presentatie terug of stelt dit in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```


Geeft de auteur van een presentatie terug of stelt deze in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```


Geeft de auteur van een presentatie terug of stelt deze in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```


Geeft de trefwoorden van een presentatie terug of stelt deze in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```


Geeft de trefwoorden van een presentatie terug of stelt deze in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract String getComments()
```


Geeft de opmerkingen van een presentatie terug of stelt deze in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```


Geeft de opmerkingen van een presentatie terug of stelt deze in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public abstract String getCategory()
```


Geeft de categorie van een presentatie terug of stelt deze in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```


Geeft de categorie van een presentatie terug of stelt deze in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```


Geeft de datum waarop een presentatie is gemaakt terug. Waarden zijn in UTC. Lezen/Schrijven java.util.Date.

**Retourneert:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```


Geeft de datum waarop een presentatie is gemaakt terug. Waarden zijn in UTC. Lezen/Schrijven java.util.Date.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```


Geeft de datum waarop een presentatie voor het laatst is gewijzigd terug. Waarden zijn in UTC. Alleen-lezen in het geval van Presentation.DocumentProperties (omdat deze intern wordt bijgewerkt tijdens het opslaan van het IPresentation-object). Kan worden gewijzigd via de DocumentProperties-instantie die wordt geretourneerd door methode [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Zie het voorbeeld in methode-samenvatting [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Retourneert:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```


Geeft de datum waarop een presentatie voor het laatst is gewijzigd terug. Waarden zijn in UTC. Alleen-lezen in het geval van Presentation.DocumentProperties (omdat deze intern wordt bijgewerkt tijdens het opslaan van het IPresentation-object). Kan worden gewijzigd via de DocumentProperties-instantie die wordt geretourneerd door methode [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Zie het voorbeeld in methode-samenvatting [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```


Geeft de datum waarop een presentatie voor het laatst is afgedrukt terug. Lezen/Schrijven java.util.Date.

**Retourneert:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```


Geeft de datum waarop een presentatie voor het laatst is afgedrukt terug. Lezen/Schrijven java.util.Date.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```


Geeft de naam van de laatste persoon die een presentatie heeft gewijzigd terug of stelt deze in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```


Geeft de naam van de laatste persoon die een presentatie heeft gewijzigd terug of stelt deze in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```


Geeft het revisienummer van een presentatie terug of stelt dit in. Lezen/Schrijven int.

**Retourneert:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```


Geeft het revisienummer van een presentatie terug of stelt dit in. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```


Geeft de inhoudsstatus van een presentatie terug of stelt deze in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentType()
```


Geeft de inhoudsstatus van een presentatie terug of stelt deze in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Geeft het inhoudstype van een presentatie terug of stelt dit in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```


Geeft het inhoudstype van een presentatie terug of stelt dit in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```


Geeft de HyperlinkBase-documenteigenschap terug of stelt deze in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```


Geeft de HyperlinkBase-documenteigenschap terug of stelt deze in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```


Geeft de weergavemodus van de miniatuur van het document aan. Stel dit element in op **true** om schalen van de miniatuur naar het scherm in te schakelen. Stel dit element in op **false** om bijsnijden van de miniatuur naar alleen secties die op het scherm passen in te schakelen. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```


Geeft de weergavemodus van de miniatuur van het document aan. Stel dit element in op **true** om schalen van de miniatuur naar het scherm in te schakelen. Stel dit element in op **false** om bijsnijden van de miniatuur naar alleen secties die op het scherm passen in te schakelen. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```


Geeft aan of hyperlinks in een document up-to-date zijn. Stel dit element in op **true** om aan te geven dat hyperlinks zijn bijgewerkt. Stel dit element in op **false** om aan te geven dat hyperlinks verouderd zijn. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```


Geeft aan of hyperlinks in een document up-to-date zijn. Stel dit element in op **true** om aan te geven dat hyperlinks zijn bijgewerkt. Stel dit element in op **false** om aan te geven dat hyperlinks verouderd zijn. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```


Specificeert dat een of meer hyperlinks in dit onderdeel uitsluitend in dit onderdeel door een producent zijn bijgewerkt. De volgende producent die dit document opent, zal de hyperlink-relaties bijwerken met de nieuwe hyperlinks die in dit onderdeel zijn gespecificeerd. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```


Specificeert dat een of meer hyperlinks in dit onderdeel uitsluitend in dit onderdeel door een producent zijn bijgewerkt. De volgende producent die dit document opent, zal de hyperlink-relaties bijwerken met de nieuwe hyperlinks die in dit onderdeel zijn gespecificeerd. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```


Specificeert het totale aantal dia's in een presentatiedocument. Alleen-lezen int.

**Retourneert:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```


Specificeert het aantal verborgen dia's in een presentatiedocument. Alleen-lezen int.

**Retourneert:**
int
### getNotes() {#getNotes--}
```
public abstract int getNotes()
```


Specificeert het aantal dia's in een presentatie met notities. Alleen-lezen int.

**Retourneert:**
int
### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```


Specificeert het totale aantal alinea's dat in een document is aangetroffen, indien van toepassing. Alleen-lezen int.

**Retourneert:**
int
### getWords() {#getWords--}
```
public abstract int getWords()
```


Specificeert het totale aantal woorden dat in een document staat. Alleen-lezen int.

**Retourneert:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```


Specificeert het totale aantal geluid- of videoclips dat in het document aanwezig is. Alleen-lezen int.

**Retourneert:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```


Specificeert de titel van elk documentonderdeel. Deze onderdelen zijn geen documentonderdelen maar conceptuele representaties van documentsecties. Alleen-lezen String[].

**Retourneert:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```


Geeft de groepering van documentonderdelen en het aantal onderdelen in elke groep aan. Alleen-lezen IHeadingPair[].

**Retourneert:**
com.aspose.slides.IHeadingPair[]
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```


Geeft het aantal aangepaste eigenschappen dat daadwerkelijk in een collectie zit terug. Alleen-lezen int.

**Retourneert:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```


Retourneert een aangepaste eigenschapsnaam op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index van een aangepaste eigenschap die opgehaald moet worden. |

**Retourneert:**
java.lang.String - Aangepaste eigenschapsnaam op de opgegeven index.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```


Verwijdert een aangepaste eigenschap die aan een opgegeven naam gekoppeld is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van een aangepaste eigenschap die verwijderd moet worden. |

**Retourneert:**
boolean - Retourneert true als een eigenschap is verwijderd, false anders.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```


Controleert de aanwezigheid van een aangepaste eigenschap met een opgegeven naam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van een aangepaste eigenschap die gecontroleerd moet worden. |

**Retourneert:**
boolean - Retourneert true als de eigenschap bestaat, false anders.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```


Geeft een aangepaste eigenschap terug of stelt deze in voor een opgegeven naam. Lezen/Schrijven Object.

--------------------

Waarde kan **int**, **float**, **double**, **String**, **boolean** of **Date** zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String |  |

**Retourneert:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```


Geeft een aangepaste eigenschap terug of stelt deze in voor een opgegeven naam. Lezen/Schrijven Object.

--------------------

Waarde kan **int**, **float**, **double**, **String**, **boolean** of **Date** zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### clearCustomProperties() {#clearCustomProperties--}
```
public abstract void clearCustomProperties()
```


Verwijdert alle aangepaste eigenschappen.

### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract void clearBuiltInProperties()
```


Leegt en stelt standaardwaarden in voor alle ingebouwde eigenschappen.

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```


Haalt een benoemde boolean-waarde op uit de aangepaste eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de aangepaste eigenschap die opgehaald moet worden |
| value | boolean[] | Aangepaste eigenschapswaarde |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```


Haalt een benoemde integer-waarde op uit de aangepaste eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de aangepaste eigenschap die opgehaald moet worden |
| value | int[] | Aangepaste eigenschapswaarde |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```


Haalt een benoemde DateTime-waarde op uit de aangepaste eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de aangepaste eigenschap die opgehaald moet worden |
| value | java.util.Date[] | Aangepaste eigenschapswaarde |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```


Haalt een benoemde string-waarde op uit de aangepaste eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de aangepaste eigenschap die opgehaald moet worden |
| value | java.lang.String[] | Aangepaste eigenschapswaarde |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```


Haalt een benoemde float-waarde op uit de aangepaste eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de aangepaste eigenschap die opgehaald moet worden |
| value | float[] | Aangepaste eigenschapswaarde |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```


Haalt een benoemde double-waarde op uit de aangepaste eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de aangepaste eigenschap die opgehaald moet worden. |
| value | double[] | Aangepaste eigenschapswaarde |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```


Stelt een benoemde boolean-aangepaste eigenschap in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de aangepaste eigenschap die ingesteld moet worden |
| value | boolean | Aangepaste eigenschapswaarde |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```


Stelt een benoemde integer-aangepaste eigenschap in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de aangepaste eigenschap die ingesteld moet worden |
| value | int | Aangepaste eigenschapswaarde |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```


Stelt een benoemde DateTime-aangepaste eigenschap in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de aangepaste eigenschap die ingesteld moet worden |
| value | java.util.Date | Aangepaste eigenschapswaarde |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```


Stelt een benoemde string-aangepaste eigenschap in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de aangepaste eigenschap die ingesteld moet worden |
| value | java.lang.String | Aangepaste eigenschapswaarde |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```


Stelt een benoemde float-aangepaste eigenschap in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de aangepaste eigenschap die ingesteld moet worden |
| value | float | Aangepaste eigenschapswaarde |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```


Stelt een benoemde double-aangepaste eigenschap in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de aangepaste eigenschap die ingesteld moet worden |
| value | double | Aangepaste eigenschapswaarde |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```


Haalt een array met gevoeligheidslabels op uit de aangepaste documenteigenschappen (Microsoft Information Protection SDK Metadata).

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

**Retourneert:**
com.aspose.slides.ISensitivityLabel[]