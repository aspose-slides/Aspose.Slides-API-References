---
title: IDocumentProperties
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar egenskaper för en presentation.
type: docs
url: /sv/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

Representerar egenskaper för en presentation.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Returnerar appversionen. |
| [getNameOfApplication()](#getNameOfApplication--) | Returnerar eller anger namnet på applikationen. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Returnerar eller anger namnet på applikationen. |
| [getCompany()](#getCompany--) | Returnerar eller anger företagsegenskapen. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Returnerar eller anger företagsegenskapen. |
| [getManager()](#getManager--) | Returnerar eller anger chef-egenskapen. |
| [setManager(String value)](#setManager-java.lang.String-) | Returnerar eller anger chef-egenskapen. |
| [getPresentationFormat()](#getPresentationFormat--) | Returnerar eller anger det avsedda formatet för en presentation. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Returnerar eller anger det avsedda formatet för en presentation. |
| [getSharedDoc()](#getSharedDoc--) | Avgör om presentationen är delad mellan flera personer. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Avgör om presentationen är delad mellan flera personer. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Returnerar eller anger mallen för en applikation. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Returnerar eller anger mallen för en applikation. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Total redigeringstid för en presentation. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Total redigeringstid för en presentation. |
| [getTitle()](#getTitle--) | Returnerar eller anger titeln på en presentation. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Returnerar eller anger titeln på en presentation. |
| [getSubject()](#getSubject--) | Returnerar eller anger ämnet för en presentation. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Returnerar eller anger ämnet för en presentation. |
| [getAuthor()](#getAuthor--) | Returnerar eller anger författaren till en presentation. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Returnerar eller anger författaren till en presentation. |
| [getKeywords()](#getKeywords--) | Returnerar eller anger nyckelorden för en presentation. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Returnerar eller anger nyckelorden för en presentation. |
| [getComments()](#getComments--) | Returnerar eller anger kommentarer till en presentation. |
| [setComments(String value)](#setComments-java.lang.String-) | Returnerar eller anger kommentarer till en presentation. |
| [getCategory()](#getCategory--) | Returnerar eller anger kategorin för en presentation. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Returnerar eller anger kategorin för en presentation. |
| [getCreatedTime()](#getCreatedTime--) | Returnerar datumet då en presentation skapades. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Returnerar datumet då en presentation skapades. |
| [getLastSavedTime()](#getLastSavedTime--) | Returnerar datumet då en presentation senast ändrades. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Returnerar datumet då en presentation senast ändrades. |
| [getLastPrinted()](#getLastPrinted--) | Returnerar datumet när en presentation senast skrevs ut. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Returnerar datumet när en presentation senast skrevs ut. |
| [getLastSavedBy()](#getLastSavedBy--) | Returnerar eller anger namnet på den sista personen som ändrade en presentation. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Returnerar eller anger namnet på den sista personen som ändrade en presentation. |
| [getRevisionNumber()](#getRevisionNumber--) | Returnerar eller anger revisionsnumret för presentationen. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Returnerar eller anger revisionsnumret för presentationen. |
| [getContentStatus()](#getContentStatus--) | Returnerar eller anger innehållsstatusen för en presentation. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Returnerar eller anger innehållsstatusen för en presentation. |
| [getContentType()](#getContentType--) | Returnerar eller anger innehållstypen för en presentation. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Returnerar eller anger innehållstypen för en presentation. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Returnerar eller anger HyperlinkBase-dokumentegenskapen. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Returnerar eller anger HyperlinkBase-dokumentegenskapen. |
| [getScaleCrop()](#getScaleCrop--) | Anger visningsläget för dokumentets miniatyr. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Anger visningsläget för dokumentets miniatyr. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Anger om hyperlänkar i ett dokument är aktuella. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Anger om hyperlänkar i ett dokument är aktuella. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Anger att en eller flera hyperlänkar i denna del uppdaterades exklusivt i denna del av en producent. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Anger att en eller flera hyperlänkar i denna del uppdaterades exklusivt i denna del av en producent. |
| [getSlides()](#getSlides--) | Anger det totala antalet bilder i ett presentationsdokument. |
| [getHiddenSlides()](#getHiddenSlides--) | Anger antalet dolda bilder i ett presentationsdokument. |
| [getNotes()](#getNotes--) | Anger antalet bilder i en presentation som innehåller anteckningar. |
| [getParagraphs()](#getParagraphs--) | Anger det totala antalet stycken som finns i ett dokument, om tillämpligt. |
| [getWords()](#getWords--) | Anger det totala antalet ord i ett dokument. |
| [getMultimediaClips()](#getMultimediaClips--) | Anger det totala antalet ljud- eller videoklipp som finns i dokumentet. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Anger titeln på varje dokumentdel. |
| [getHeadingPairs()](#getHeadingPairs--) | Anger gruppering av dokumentdelar och antalet delar i varje grupp. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Returnerar antalet anpassade egenskaper som faktiskt finns i en samling. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Returnerar ett anpassat egenskapsnamn på angivet index. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Tar bort en anpassad egenskap associerad med ett angivet namn. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Kontrollerar förekomsten av en anpassad egenskap med ett angivet namn. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Returnerar eller anger den anpassade egenskapen som är associerad med ett angivet namn. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Returnerar eller anger den anpassade egenskapen som är associerad med ett angivet namn. |
| [clearCustomProperties()](#clearCustomProperties--) | Tar bort alla anpassade egenskaper. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Rensar och sätter standardvärden för alla inbyggda egenskaper. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Retrieves a named boolean value from the custom properties. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Retrieves a named integer value from the custom properties. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Retrieves a named DateTime value from the custom properties. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Retrieves a named string value from the custom properties. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Retrieves a named float value from the custom properties. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Retrieves a named double value from the custom properties. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Sätter en namngiven boolean-egenskap. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Sätter en namngiven integer-egenskap. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Sätter en namngiven DateTime-egenskap. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Sätter en namngiven string-egenskap. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Sätter en namngiven float-egenskap. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Sätter en namngiven double-egenskap. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Hämtar en matris med känslighetsetiketter från de anpassade dokumentegenskaperna (Microsoft Information Protection SDK Metadata). |
### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

Returnerar appversionen. Läs-endast String.

--------------------

Innehållet i detta element ska ha formatet XX.YYYY, där X och Y representerar numeriska värden; annars ska dokumentet betraktas som icke-konformt. Aspose.Slides representerar sin version i formatet XX.YY.ZZ, där:  
XX – huvudversion  
YY – underordnad version  
ZZ – korrigeringsversion  

Till exempel betyder värdet 23.0105 Aspose.Slides version 23.1.5.

**Returnerar:**  
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

Returnerar eller anger namnet på applikationen. Läs/skriv String.

**Returnerar:**  
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```

Returnerar eller anger namnet på applikationen. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getCompany() {#getCompany--}
```
public abstract String getCompany()
```

Returnerar eller anger företagsegenskapen. Läs/skriv String.

**Returnerar:**  
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

Returnerar eller anger företagsegenskapen. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getManager() {#getManager--}
```
public abstract String getManager()
```

Returnerar eller anger chef-egenskapen. Läs/skriv String.

**Returnerar:**  
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

Returnerar eller anger chef-egenskapen. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

Returnerar eller anger det avsedda formatet för en presentation. Läs/skriv String.

**Returnerar:**  
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

Returnerar eller anger det avsedda formatet för en presentation. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

Avgör om presentationen är delad mellan flera personer. Läs/skriv boolean.

**Returnerar:**  
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

Avgör om presentationen är delad mellan flera personer. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

Returnerar eller anger mallen för en applikation. Läs/skriv String.

**Returnerar:**  
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```

Returnerar eller anger mallen för en applikation. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```

Total redigeringstid för en presentation. Läs/skriv double.

**Returnerar:**  
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

Total redigeringstid för en presentation. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

Returnerar eller anger titeln på en presentation. Läs/skriv String.

**Returnerar:**  
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

Returnerar eller anger titeln på en presentation. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getSubject() {#getSubject--}
```
public abstract String getSubject()
```

Returnerar eller anger ämnet för en presentation. Läs/skriv String.

**Returnerar:**  
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```

Returnerar eller anger ämnet för en presentation. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```

Returnerar eller anger författaren till en presentation. Läs/skriv String.

**Returnerar:**  
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```

Returnerar eller anger författaren till en presentation. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```

Returnerar eller anger nyckelorden för en presentation. Läs/skriv String.

**Returnerar:**  
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

Returnerar eller anger nyckelorden för en presentation. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract String getComments()
```

Returnerar eller anger kommentarer till en presentation. Läs/skriv String.

**Returnerar:**  
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

Returnerar eller anger kommentarer till en presentation. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getCategory() {#getCategory--}
```
public abstract String getCategory()
```

Returnerar eller anger kategorin för en presentation. Läs/skriv String.

**Returnerar:**  
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```

Returnerar eller anger kategorin för en presentation. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Returnerar datumet då en presentation skapades. Värdena är i UTC. Läs/skriv java.util.Date.

**Returnerar:**  
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Returnerar datumet då en presentation skapades. Värdena är i UTC. Läs/skriv java.util.Date.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```

Returnerar datumet då en presentation senast ändrades. Värdena är i UTC. Läs-endast i fallet Presentation.DocumentProperties (eftersom den uppdateras internt under sparningsprocessen för IPresentation-objektet). Kan ändras via DocumentProperties-instansen som returneras av metoden [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Se exempel i [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-)-metodsammanfattning.

**Returnerar:**  
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

Returnerar datumet då en presentation senast ändrades. Värdena är i UTC. Läs-endast i fallet Presentation.DocumentProperties (eftersom den uppdateras internt under sparningsprocessen för IPresentation-objektet). Kan ändras via DocumentProperties-instansen som returneras av metoden [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Se exempel i [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-)-metodsammanfattning.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```

Returnerar datumet när en presentation senast skrevs ut. Läs/skriv java.util.Date.

**Returnerar:**  
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```

Returnerar datumet när en presentation senast skrevs ut. Läs/skriv java.util.Date.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```

Returnerar eller anger namnet på den sista personen som ändrade en presentation. Läs/skriv String.

**Returnerar:**  
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

Returnerar eller anger namnet på den sista personen som ändrade en presentation. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```

Returnerar eller anger revisionsnumret för presentationen. Läs/skriv int.

**Returnerar:**  
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```

Returnerar eller anger revisionsnumret för presentationen. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```

Returnerar eller anger innehållsstatusen för en presentation. Läs/skriv String.

**Returnerar:**  
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```

Returnerar eller anger innehållsstatusen för en presentation. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Returnerar eller anger innehållstypen för en presentation. Läs/skriv String.

**Returnerar:**  
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```

Returnerar eller anger innehållstypen för en presentation. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```

Returnerar eller anger HyperlinkBase-dokumentegenskapen. Läs/skriv String.

**Returnerar:**  
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```

Returnerar eller anger HyperlinkBase-dokumentegenskapen. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```

Anger visningsläget för dokumentets miniatyr. Ställ in detta element till **true** för att aktivera skalning av miniatyren till displayen. Ställ in detta element till **false** för att aktivera beskärning av miniatyren så att endast sektioner som passar displayen visas. Läs/skriv boolean.

**Returnerar:**  
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

Anger visningsläget för dokumentets miniatyr. Ställ in detta element till **true** för att aktivera skalning av miniatyren till displayen. Ställ in detta element till **false** för att aktivera beskärning av miniatyren så att endast sektioner som passar displayen visas. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```

Anger om hyperlänkar i ett dokument är aktuella. Ställ in detta element till **true** för att indikera att hyperlänkar är uppdaterade. Ställ in detta element till **false** för att indikera att hyperlänkar är föråldrade. Läs/skriv boolean.

**Returnerar:**  
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

Anger om hyperlänkar i ett dokument är aktuella. Ställ in detta element till **true** för att indikera att hyperlänkar är uppdaterade. Ställ in detta element till **false** för att indikera att hyperlänkar är föråldrade. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

Anger att en eller flera hyperlänkar i denna del uppdaterades exklusivt i denna del av en producent. Nästa producent som öppnar detta dokument ska uppdatera hyperlänksförhållandena med de nya hyperlänkarna som anges i denna del. Läs/skriv boolean.

**Returnerar:**  
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```

Anger att en eller flera hyperlänkar i denna del uppdaterades exklusivt i denna del av en producent. Nästa producent som öppnar detta dokument ska uppdatera hyperlänksförhållandena med de nya hyperlänkarna som anges i denna del. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

Anger det totala antalet bilder i ett presentationsdokument. Läs-endast int.

**Returnerar:**  
int
### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

Anger antalet dolda bilder i ett presentationsdokument. Läs-endast int.

**Returnerar:**  
int
### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

Anger antalet bilder i en presentation som innehåller anteckningar. Läs-endast int.

**Returnerar:**  
int
### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```

Anger det totala antalet stycken som finns i ett dokument, om tillämpligt. Läs-endast int.

**Returnerar:**  
int
### getWords() {#getWords--}
```
public abstract int getWords()
```

Anger det totala antalet ord i ett dokument. Läs-endast int.

**Returnerar:**  
int
### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

Anger det totala antalet ljud- eller videoklipp som finns i dokumentet. Läs-endast int.

**Returnerar:**  
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

Anger titeln på varje dokumentdel. Dessa delar är inte fysiska dokumentdelar utan konceptuella representationer av dokumentsektioner. Läs-endast String[].

**Returnerar:**  
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

Anger gruppering av dokumentdelar och antalet delar i varje grupp. Läs-endast IHeadingPair[].

**Returnerar:**  
com.aspose.slides.IHeadingPair[]
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

Returnerar antalet anpassade egenskaper som faktiskt finns i en samling. Läs-endast int.

**Returnerar:**  
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```

Returnerar ett anpassat egenskapsnamn på angivet index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Nollbaserat index för den anpassade egenskapen som ska hämtas. |

**Returnerar:**  
java.lang.String - Anpassat egenskapsnamn på angivet index.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```

Tar bort en anpassad egenskap associerad med ett angivet namn.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen som ska tas bort. |

**Returnerar:**  
boolean - Returnerar true om en egenskap togs bort, annars false.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```

Kontrollerar förekomsten av en anpassad egenskap med ett angivet namn.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen som ska kontrolleras. |

**Returnerar:**  
boolean - Returnerar true om egenskapen finns, annars false.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```

Returnerar eller anger den anpassade egenskapen som är associerad med ett angivet namn. Läs/skriv Object.

--------------------

Värdet kan vara **int**, **float**, **double**, **String**, **boolean** eller **Date**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String |  |

**Returnerar:**  
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```

Returnerar eller anger den anpassade egenskapen som är associerad med ett angivet namn. Läs/skriv Object.

--------------------

Värdet kan vara **int**, **float**, **double**, **String**, **boolean** eller **Date**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |
### clearCustomProperties() {#clearCustomProperties--}
```
public abstract void clearCustomProperties()
```

Tar bort alla anpassade egenskaper.
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract void clearBuiltInProperties()
```

Rensar och sätter standardvärden för alla inbyggda egenskaper.
### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

Hämtar ett namngivet boolean-värde från de anpassade egenskaperna.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen som ska hämtas |
| value | boolean[] | Värde för den anpassade egenskapen |
### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

Hämtar ett namngivet integer-värde från de anpassade egenskaperna.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen som ska hämtas |
| value | int[] | Värde för den anpassade egenskapen |
### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

Hämtar ett namngivet DateTime-värde från de anpassade egenskaperna.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen som ska hämtas |
| value | java.util.Date[] | Värde för den anpassade egenskapen |
### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

Hämtar ett namngivet string-värde från de anpassade egenskaperna.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen som ska hämtas |
| value | java.lang.String[] | Värde för den anpassade egenskapen |
### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

Hämtar ett namngivet float-värde från de anpassade egenskaperna.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen som ska hämtas |
| value | float[] | Värde för den anpassade egenskapen |
### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public     one    ?
```

Hämtar ett namngivet double-värde från de anpassade egenskaperna.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen som ska hämtas. |
| value | double[] | Värde för den anpassade egenskapen |
### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

Sätter en namngiven boolean-egenskap.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen som ska sättas |
| value | boolean | Värde för den anpassade egenskapen |
### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

Sätter en namngiven integer-egenskap.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen som ska sättas |
| value | int | Värde för den anpassade egenskapen |
### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

Sätter en namngiven DateTime-egenskap.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen som ska sättas |
| value | java.util.Date | Värde för den anpassade egenskapen |
### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

Sätter en namngiven string-egenskap.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen som ska sättas |
| value | java.lang.String | Värde för den anpassade egenskapen |
### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

Sätter en namngiven float-egenskap.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen som ska sättas |
| value | float | Värde för den anpassade egenskapen |
### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

Sätter en namngiven double-egenskap.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen som ska sättas |
| value | double | Värde för den anpassade egenskapen |
### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

Hämtar en matris med känslighetsetiketter från de anpassade dokumentegenskaperna (Microsoft Information Protection SDK Metadata).

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

**Returnerar:**  
com.aspose.slides.ISensitivityLabel[]