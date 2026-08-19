---
title: IDocumentProperties
second_title: Aspose.Slides for Java API Reference
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
| [getAppVersion()](#getAppVersion--) | Retourneert de app-versie. |
| [getNameOfApplication()](#getNameOfApplication--) | Retourneert of stelt de naam van de applicatie in. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Retourneert of stelt de naam van de applicatie in. |
| [getCompany()](#getCompany--) | Retourneert of stelt de bedrijfs-eigenschap in. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Retourneert of stelt de bedrijfs-eigenschap in. |
| [getManager()](#getManager--) | Retourneert of stelt de manager-eigenschap in. |
| [setManager(String value)](#setManager-java.lang.String-) | Retourneert of stelt de manager-eigenschap in. |
| [getPresentationFormat()](#getPresentationFormat--) | Retourneert of stelt het beoogde formaat van een presentatie in. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Retourneert of stelt het beoogde formaat van een presentatie in. |
| [getSharedDoc()](#getSharedDoc--) | Bepaalt of de presentatie door meerdere personen wordt gedeeld. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Bepaalt of de presentatie door meerdere personen wordt gedeeld. |
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
| [getCreatedTime()](#getCreatedTime--) | Retourneert de datum waarop een presentatie is gemaakt. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Retourneert de datum waarop een presentatie is gemaakt. |
| [getLastSavedTime()](#getLastSavedTime--) | Retourneert de datum waarop een presentatie voor het laatst is gewijzigd. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Retourneert de datum waarop een presentatie voor het laatst is gewijzigd. |
| [getLastPrinted()](#getLastPrinted--) | Retourneert de datum waarop een presentatie voor het laatst is afgedrukt. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Retourneert de datum waarop een presentatie voor het laatst is afgedrukt. |
| [getLastSavedBy()](#getLastSavedBy--) | Retourneert of stelt de naam van de laatste persoon die een presentatie heeft bewerkt in. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Retourneert of stelt de naam van de laatste persoon die een presentatie heeft bewerkt in. |
| [getRevisionNumber()](#getRevisionNumber--) | Retourneert of stelt het revisienummer van de presentatie in. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Retourneert of stelt het revisienummer van de presentatie in. |
| [getContentStatus()](#getContentStatus--) | Retourneert of stelt de inhoudsstatus van een presentatie in. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Retourneert of stelt de inhoudsstatus van een presentatie in. |
| [getContentType()](#getContentType--) | Retourneert of stelt het inhoudstype van een presentatie in. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Retourneert of stelt het inhoudstype van een presentatie in. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Retourneert of stelt de HyperlinkBase-documenteigenschap in. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Retourneert of stelt de HyperlinkBase-documenteigenschap in. |
| [getScaleCrop()](#getScaleCrop--) | Geeft de weergavemodus van de document-miniatuur aan. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Geeft de weergavemodus van de document-miniatuur aan. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Geeft aan of hyperlinks in een document actueel zijn. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Geeft aan of hyperlinks in een document actueel zijn. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Specificeert dat één of meer hyperlinks in dit onderdeel exclusief in dit onderdeel door een producer zijn bijgewerkt. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Specificeert dat één of meer hyperlinks in dit onderdeel exclusief in dit onderdeel door een producer zijn bijgewerkt. |
| [getSlides()](#getSlides--) | Specificeert het totale aantal dia's in een presentatiedocument. |
| [getHiddenSlides()](#getHiddenSlides--) | Specificeert het aantal verborgen dia's in een presentatiedocument. |
| [getNotes()](#getNotes--) | Specificeert het aantal dia's in een presentatie met notities. |
| [getParagraphs()](#getParagraphs--) | Specificeert het totale aantal alinea's in een document, indien van toepassing. |
| [getWords()](#getWords--) | Specificeert het totale aantal woorden in een document. |
| [getMultimediaClips()](#getMultimediaClips--) | Specificeert het totale aantal geluid- of videoclips in het document. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Specificeert de titel van elk documentonderdeel. |
| [getHeadingPairs()](#getHeadingPairs--) | Geeft de groepering van documentonderdelen en het aantal onderdelen per groep aan. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Retourneert het aantal aangepaste eigenschappen dat daadwerkelijk in een collectie zit. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Retourneert een aangepaste eigenschapsnaam op de opgegeven index. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Verwijdert een aangepaste eigenschap die aan een opgegeven naam is gekoppeld. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Controleert de aanwezigheid van een aangepaste eigenschap met een opgegeven naam. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Retourneert of stelt de aangepaste eigenschap in die aan een opgegeven naam is gekoppeld. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Retourneert of stelt de aangepaste eigenschap in die aan een opgegeven naam is gekoppeld. |
| [clearCustomProperties()](#clearCustomProperties--) | Verwijdert alle aangepaste eigenschappen. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Wis en stel standaardwaarden in voor alle ingebouwde eigenschappen. |
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
| [getSensitivityLabels()](#getSensitivityLabels--) | Haalt een array met gevoeligheidslabels op uit de aangepaste documenteigenschappen (Microsoft Information Protection SDK-metadata). |

### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

Retourneert de app-versie. Alleen-lezen String.

--------------------

De inhoud van dit element moet de vorm XX.YYYY hebben, waarbij X en Y numerieke waarden zijn; anders wordt het document als niet-conform beschouwd. Aspose.Slides geeft zijn versie weer in het formaat XX.YY.ZZ, waarbij: XX – hoofdversie YY – onderversie ZZ – patch-versie. Bijvoorbeeld, de waarde 23.0105 betekent Aspose.Slides versie 23.1.5.

**Retourneert:**
java.lang.String

### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

Retourneert of stelt de naam van de applicatie in. Lezen/schrijven String.

**Retourneert:**
java.lang.String

### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```

Retourneert of stelt de naam van de applicatie in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public abstract String getCompany()
```

Retourneert of stelt de bedrijfs-eigenschap in. Lezen/schrijven String.

**Retourneert:**
java.lang.String

### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

Retourneert of stelt de bedrijfs-eigenschap in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public abstract String getManager()
```

Retourneert of stelt de manager-eigenschap in. Lezen/schrijven String.

**Retourneert:**
java.lang.String

### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

Retourneert of stelt de manager-eigenschap in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

Retourneert of stelt het beoogde formaat van een presentatie in. Lezen/schrijven String.

**Retourneert:**
java.lang.String

### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

Retourneert of stelt het beoogde formaat van een presentatie in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

Bepaalt of de presentatie door meerdere personen wordt gedeeld. Lezen/schrijven boolean.

**Retourneert:**
boolean

### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

Bepaalt of de presentatie door meerdere personen wordt gedeeld. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

Retourneert of stelt het sjabloon van een applicatie in. Lezen/schrijven String.

**Retourneert:**
java.lang.String

### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```

Retourneert of stelt het sjabloon van een applicatie in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```

Totale bewerkingstijd van een presentatie. Lezen/schrijven double.

**Retourneert:**
double

### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

Totale bewerkingstijd van een presentatie. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

Retourneert of stelt de titel van een presentatie in. Lezen/schrijven String.

**Retourneert:**
java.lang.String

### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

Retourneert of stelt de titel van een presentatie in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public abstract String getSubject()
```

Retourneert of stelt het onderwerp van een presentatie in. Lezen/schrijven String.

**Retourneert:**
java.lang.String

### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```

Retourneert of stelt het onderwerp van een presentatie in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```

Retourneert of stelt de auteur van een presentatie in. Lezen/schrijven String.

**Retourneert:**
java.lang.String

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```

Retourneert of stelt de auteur van een presentatie in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```

Retourneert of stelt de trefwoorden van een presentatie in. Lezen/schrijven String.

**Retourneert:**
java.lang.String

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

Retourneert of stelt de trefwoorden van een presentatie in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract String getComments()
```

Retourneert of stelt de opmerkingen van een presentatie in. Lezen/schrijven String.

**Retourneert:**
java.lang.String

### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

Retourneert of stelt de opmerkingen van een presentatie in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public abstract String getCategory()
```

Retourneert of stelt de categorie van een presentatie in. Lezen/schrijven String.

**Retourneert:**
java.lang.String

### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```

Retourneert of stelt de categorie van een presentatie in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Retourneert de datum waarop een presentatie is gemaakt. Waarden zijn in UTC. Lezen/schrijven java.util.Date.

**Retour:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Retourneert de datum waarop een presentatie is gemaakt. Waarden zijn in UTC. Lezen/schrijven java.util.Date.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```

Retourneert de datum waarop een presentatie voor het laatst is gewijzigd. Waarden zijn in UTC. Alleen-lezen in het geval van Presentation.DocumentProperties (omdat deze intern wordt bijgewerkt tijdens het opslaan van het IPresentation-object). Kan worden gewijzigd via de DocumentProperties-instantie die wordt geretourneerd door methode [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Zie het voorbeeld in methode-samenvatting [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Retour:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

Retourneert de datum waarop een presentatie voor het laatst is gewijzigd. Waarden zijn in UTC. Alleen-lezen in het geval van Presentation.DocumentProperties (omdat deze intern wordt bijgewerkt tijdens het opslaan van het IPresentation-object). Kan worden gewijzigd via de DocumentProperties-instantie die wordt geretourneerd door methode [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Zie het voorbeeld in methode-samenvatting [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```

Retourneert de datum waarop een presentatie voor het laatst is afgedrukt. Lezen/schrijven java.util.Date.

**Retour:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```

Retourneert de datum waarop een presentatie voor het laatst is afgedrukt. Lezen/schrijven java.util.Date.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```

Retourneert of stelt de naam van de laatste persoon in die een presentatie heeft gewijzigd. Lezen/schrijven String.

**Retour:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

Retourneert of stelt de naam van de laatste persoon in die een presentatie heeft gewijzigd. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```

Retourneert of stelt het revisienummer van de presentatie in. Lezen/schrijven int.

**Retour:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```

Retourneert of stelt het revisienummer van de presentatie in. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```

Retourneert of stelt de inhoudsstatus van een presentatie in. Lezen/schrijven String.

**Retour:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```

Retourneert of stelt de inhoudsstatus van een presentatie in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Retourneert of stelt het inhoudstype van een presentatie in. Lezen/schrijven String.

**Retour:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```

Retourneert of stelt het inhoudstype van een presentatie in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```

Retourneert of stelt de HyperlinkBase-documenteigenschap in. Lezen/schrijven String.

**Retour:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```

Retourneert of stelt de HyperlinkBase-documenteigenschap in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```

Geeft de weergavemodus van de miniatuur van het document aan. Stel dit element in op **true** om schalen van de miniatuur naar het scherm mogelijk te maken. Stel dit element in op **false** om bijsnijden van de miniatuur mogelijk te maken zodat alleen secties die op het scherm passen worden getoond. Lezen/schrijven boolean.

**Retour:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

Geeft de weergavemodus van de miniatuur van het document aan. Stel dit element in op **true** om schalen van de miniatuur naar het scherm mogelijk te maken. Stel dit element in op **false** om bijsnijden van de miniatuur mogelijk te maken zodat alleen secties die op het scherm passen worden getoond. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```

Geeft aan of hyperlinks in een document up-to-date zijn. Stel dit element in op **true** om aan te geven dat hyperlinks zijn bijgewerkt. Stel dit element in op **false** om aan te geven dat hyperlinks verouderd zijn. Lezen/schrijven boolean.

**Retour:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

Geeft aan of hyperlinks in een document up-to-date zijn. Stel dit element in op **true** om aan te geven dat hyperlinks zijn bijgewerkt. Stel dit element in op **false** om aan te geven dat hyperlinks verouderd zijn. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

Specificeert dat een of meer hyperlinks in dit onderdeel uitsluitend in dit onderdeel door een produceur zijn bijgewerkt. De volgende produceur die dit document opent, moet de hyperlinkrelaties bijwerken met de nieuwe hyperlinks die in dit onderdeel zijn gespecificeerd. Lezen/schrijven boolean.

**Retour:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```

Specificeert dat een of meer hyperlinks in dit onderdeel uitsluitend in dit onderdeel door een produceur zijn bijgewerkt. De volgende produceur die dit document opent, moet de hyperlinkrelaties bijwerken met de nieuwe hyperlinks die in dit onderdeel zijn gespecificeerd. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

Specificeert het totale aantal dia’s in een presentatiedocument. Alleen-lezen int.

**Retour:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

Specificeert het aantal verborgen dia’s in een presentatiedocument. Alleen-lezen int.

**Retour:**
int
### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

Specificeert het aantal dia’s in een presentatie met notities. Alleen-lezen int.

**Retour:**
int
### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```

Specificeert het totale aantal alinea’s dat in een document voorkomt, indien van toepassing. Alleen-lezen int.

**Retour:**
int
### getWords() {#getWords--}
```
public abstract int getWords()
```

Specificeert het totale aantal woorden dat in een document staat. Alleen-lezen int.

**Retour:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

Specificeert het totale aantal geluid- of video-clips die in het document aanwezig zijn. Alleen-lezen int.

**Retour:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

Specificeert de titel van elk documentonderdeel. Deze onderdelen zijn geen documentonderdelen maar conceptuele representaties van documentsecties. Alleen-lezen String[].

**Retour:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

Geeft de groepering van documentonderdelen en het aantal onderdelen in elke groep aan. Alleen-lezen IHeadingPair[].

**Retour:**
com.aspose.slides.IHeadingPair[]
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

Retourneert het aantal aangepaste eigenschappen dat daadwerkelijk in een verzameling aanwezig is. Alleen-lezen int.

**Retour:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```

Retourneert een aangepaste eigenschapsnaam op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index van een aangepaste eigenschap om op te halen. |

**Retour:**
java.lang.String - Aangepaste eigenschapsnaam op de opgegeven index.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```

Verwijdert een aangepaste eigenschap die aan een opgegeven naam is gekoppeld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de te verwijderen aangepaste eigenschap. |

**Retour:**
boolean - Retourneert true als een eigenschap is verwijderd, false anders.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```

Controleert de aanwezigheid van een aangepaste eigenschap met een opgegeven naam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de te controleren aangepaste eigenschap. |

**Retour:**
boolean - Retourneert true als de eigenschap bestaat, false anders.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```

Retourneert of stelt de aangepaste eigenschap in die aan een opgegeven naam is gekoppeld. Lezen/schrijven Object.

--------------------

Waarde kan **int**, **float**, **double**, **String**, **boolean** of **Date** zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String |  |

**Retour:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```

Retourneert of stelt de aangepaste eigenschap in die aan een opgegeven naam is gekoppeld. Lezen/schrijven Object.

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

Wis en stel standaardwaarden in voor alle ingebouwde eigenschappen.

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

Haalt een benoemde booleaanse waarde op uit de aangepaste eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de op te halen aangepaste eigenschap |
| value | boolean[] | Waarde van de aangepaste eigenschap |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

Haalt een benoemde gehele-getalwaarde op uit de aangepaste eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de op te halen aangepaste eigenschap |
| value | int[] | Waarde van de aangepaste eigenschap |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

Haalt een benoemde DateTime-waarde op uit de aangepaste eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de op te halen aangepaste eigenschap |
| value | java.util.Date[] | Waarde van de aangepaste eigenschap |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

Haalt een benoemde tekenreekswaarde op uit de aangepaste eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de op te halen aangepaste eigenschap |
| value | java.lang.String[] | Waarde van de aangepaste eigenschap |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

Haalt een benoemde float-waarde op uit de aangepaste eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de op te halen aangepaste eigenschap |
| value | float[] | Waarde van de aangepaste eigenschap |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```

Haalt een benoemde double-waarde op uit de aangepaste eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de op te halen aangepaste eigenschap |
| value | double[] | Waarde van de aangepaste eigenschap |
| name | java.lang.String | Naam van de aangepaste eigenschap om op te halen. |
| value | double[] | Waarde van de aangepaste eigenschap |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

Stelt een benoemde booleaanse aangepaste eigenschap in.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Naam van de aangepaste eigenschap om in te stellen |
| value | boolean | Waarde van de aangepaste eigenschap |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

Stelt een benoemde gehele getal aangepaste eigenschap in.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Naam van de aangepaste eigenschap om in te stellen |
| value | int | Waarde van de aangepaste eigenschap |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

Stelt een benoemde datum-tijd aangepaste eigenschap in.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Naam van de aangepaste eigenschap om in te stellen |
| value | java.util.Date | Waarde van de aangepaste eigenschap |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

Stelt een benoemde tekenreeks aangepaste eigenschap in.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Naam van de aangepaste eigenschap om in te stellen |
| value | java.lang.String | Waarde van de aangepaste eigenschap |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

Stelt een benoemde float-aangepaste eigenschap in.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Naam van de aangepaste eigenschap om in te stellen |
| value | float | Waarde van de aangepaste eigenschap |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

Stelt een benoemde double-aangepaste eigenschap in.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Naam van de aangepaste eigenschap om in te stellen |
| value | double | Waarde van de aangepaste eigenschap |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

Haalt een array met gevoeligheidslabels op uit de aangepaste documenteigenschappen (Microsoft Information Protection SDK-metadata).

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