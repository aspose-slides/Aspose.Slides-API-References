---
title: DocumentProperties
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar egenskaper för en presentation.
type: docs
url: /sv/com.aspose.slides/documentproperties/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

Representerar egenskaper för en presentation.

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // Instansiera Presentation-klassen som representerar presentationen
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // Skapa en referens till IDocumentProperties-objektet som är associerat med Presentation
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Visa de inbyggda egenskaperna
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
>  // Instansiera Presentation-klassen som representerar Presentationen
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // Skapa en referens till IDocumentProperties-objektet som är associerat med Presentation
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Ange de inbyggda egenskaperna
>      documentProperties.setAuthor("Aspose.Slides for Android via Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // Spara din presentation till en fil
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | Initierar en ny instans av klassen [DocumentProperties](../../com.aspose.slides/documentproperties). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Returnerar appversionen. |
| [getNameOfApplication()](#getNameOfApplication--) | Returnerar eller anger namnet på applikationen. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Returnerar eller anger namnet på applikationen. |
| [getCompany()](#getCompany--) | Returnerar eller anger företags-egenskapen. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Returnerar eller anger företags-egenskapen. |
| [getManager()](#getManager--) | Returnerar eller anger chef-egenskapen. |
| [setManager(String value)](#setManager-java.lang.String-) | Returnerar eller anger chef-egenskapen. |
| [getPresentationFormat()](#getPresentationFormat--) | Returnerar eller anger det avsedda formatet för en presentation. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Returnerar eller anger det avsedda formatet för en presentation. |
| [getSharedDoc()](#getSharedDoc--) | Indikerar om presentationen delas mellan flera personer. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Indikerar om presentationen delas mellan flera personer. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Returnerar eller anger mallen för en applikation. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Returnerar eller anger mallen för en applikation. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Total redigeringstid för en presentation. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Total redigeringstid för en presentation. |
| [getTitle()](#getTitle--) | Returnerar eller anger titeln för en presentation. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Returnerar eller anger titeln för en presentation. |
| [getSubject()](#getSubject--) | Returnerar eller anger ämnet för en presentation. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Returnerar eller anger ämnet för en presentation. |
| [getAuthor()](#getAuthor--) | Returnerar eller anger författaren för en presentation. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Returnerar eller anger författaren för en presentation. |
| [getKeywords()](#getKeywords--) | Returnerar eller anger nyckelorden för en presentation. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Returnerar eller anger nyckelorden för en presentation. |
| [getComments()](#getComments--) | Returnerar eller anger kommentarer för en presentation. |
| [setComments(String value)](#setComments-java.lang.String-) | Returnerar eller anger kommentarer för en presentation. |
| [getCategory()](#getCategory--) | Returnerar eller anger kategorin för en presentation. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Returnerar eller anger kategorin för en presentation. |
| [getCreatedTime()](#getCreatedTime--) | Returnerar datumet då en presentation skapades. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Returnerar datumet då en presentation skapades. |
| [getLastSavedTime()](#getLastSavedTime--) | Returnerar datumet då en presentation senast ändrades. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Returnerar datumet då en presentation senast ändrades. |
| [getLastPrinted()](#getLastPrinted--) | Returnerar datumet då en presentation senast trycktes. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Returnerar datumet då en presentation senast trycktes. |
| [getLastSavedBy()](#getLastSavedBy--) | Returnerar eller anger namnet på den sista personen som modifierade en presentation. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Returnerar eller anger namnet på den sista personen som modifierade en presentation. |
| [getRevisionNumber()](#getRevisionNumber--) | Returnerar eller anger revisionsnumret för presentationen. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Returnerar eller anger revisionsnumret för presentationen. |
| [getContentStatus()](#getContentStatus--) | Returnerar eller anger innehållsstatus för en presentation. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Returnerar eller anger innehållsstatus för en presentation. |
| [getContentType()](#getContentType--) | Returnerar eller anger innehållstyp för en presentation. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Returnerar eller anger innehållstyp för en presentation. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Returnerar eller anger HyperlinkBase-dokumentegenskapen. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Returnerar eller anger HyperlinkBase-dokumentegenskapen. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Returnerar antalet anpassade egenskaper som faktiskt finns i en samling. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Returnerar ett anpassat egenskapsnamn på det angivna indexet. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Tar bort en anpassad egenskap som är kopplad till ett angivet namn. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Kontrollerar förekomsten av en anpassad egenskap med ett angivet namn. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Returnerar eller anger den anpassade egenskap som är kopplad till ett angivet namn. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Returnerar eller anger den anpassade egenskap som är kopplad till ett angivet namn. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Gets a named boolean value from the custom properties. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Gets a named integer value from the custom properties. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Gets a named DateTime value from the custom properties. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Gets a named string value from the custom properties. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Gets a named float value from the custom properties. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Gets a named double value from the custom properties. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Anger en namngiven boolesk anpassad egenskap. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Anger en namngiven heltals-anpassad egenskap. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Anger en namngiven DateTime-anpassad egenskap. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Anger en namngiven sträng-anpassad egenskap. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Anger en namngiven flyttals-anpassad egenskap. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Anger en namngiven dubbel-anpassad egenskap. |
| [clearCustomProperties()](#clearCustomProperties--) | Tar bort alla anpassade egenskaper. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Hämtar en matris med känslighetsetiketter från de anpassade dokumentegenskaperna (Microsoft Information Protection SDK Metadata). |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Rensar och ställer in standardvärden för alla inbyggda egenskaper. |
| [getScaleCrop()](#getScaleCrop--) | Indikerar visningsläget för dokumentets miniatyrbild. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Indikerar visningsläget för dokumentets miniatyrbild. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Indikerar om hyperlänkar i ett dokument är aktuella. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Indikerar om hyperlänkar i ett dokument är aktuella. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Specificerar att en eller flera hyperlänkar i denna del uppdaterades uteslutande i denna del av en producent. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Specificerar att en eller flera hyperlänkar i denna del uppdaterades uteslutande i denna del av en producent. |
| [getSlides()](#getSlides--) | Returnerar det totala antalet bilder i ett presentationsdokument. |
| [getHiddenSlides()](#getHiddenSlides--) | Returnerar antalet dolda bilder i ett presentationsdokument. |
| [getNotes()](#getNotes--) | Returnerar antalet bilder i en presentation som innehåller anteckningar. |
| [getParagraphs()](#getParagraphs--) | Returnerar det totala antalet stycken som finns i ett dokument om tillämpligt. |
| [getWords()](#getWords--) | Returnerar det totala antalet ord i ett dokument. |
| [getMultimediaClips()](#getMultimediaClips--) | Returnerar det totala antalet ljud- eller videoklipp som finns i dokumentet. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Specificerar titeln för varje dokumentdel. |
| [getHeadingPairs()](#getHeadingPairs--) | Indikerar gruppering av dokumentdelar och antalet delar i varje grupp. |
| [deepClone()](#deepClone--) | Klonar aktuellt objekt |
| [cloneT()](#cloneT--) | Klonar aktuellt objekt |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

Initierar en ny instans av klassen [DocumentProperties](../../com.aspose.slides/documentproperties).

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

Returnerar appversionen. Skrivskyddad String.

**Returnerar:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```

Returnerar eller anger namnet på applikationen. Läs/skriv String.

**Returnerar:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

Returnerar eller anger namnet på applikationen. Läs/skriv String.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getCompany() {#getCompany--}
```
public final String getCompany()
```

Returnerar eller anger företags-egenskapen. Läs/skriv String.

**Returnerar:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

Returnerar eller anger företags-egenskapen. Läs/skriv String.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getManager() {#getManager--}
```
public final String getManager()
```

Returnerar eller anger chef-egenskapen. Läs/skriv String.

**Returnerar:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

Returnerar eller anger chef-egenskapen. Läs/skriv String.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

Returnerar eller anger det avsedda formatet för en presentation. Läs/skriv String.

**Returnerar:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

Returnerar eller anger det avsedda formatet för en presentation. Läs/skriv String.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```

Indikerar om presentationen delas mellan flera personer. Läs/skriv boolean.

**Returnerar:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```

Indikerar om presentationen delas mellan flera personer. Läs/skriv boolean.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```

Returnerar eller anger mallen för en applikation. Läs/skriv String.

**Returnerar:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

Returnerar eller anger mallen för en applikation. Läs/skriv String.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```

Total redigeringstid för en presentation. Läs/skriv double.

**Returnerar:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```

Total redigeringstid för en presentation. Läs/skriv double.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getTitle() {#getTitle--}
```
public final String getTitle()
```

Returnerar eller anger titeln för en presentation. Läs/skriv String.

**Returnerar:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

Returnerar eller anger titeln för en presentation. Läs/skriv String.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getSubject() {#getSubject--}
```
public final String getSubject()
```

Returnerar eller anger ämnet för en presentation. Läs/skriv String.

**Returnerar:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

Returnerar eller anger ämnet för en presentation. Läs/skriv String.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

Returnerar eller anger författaren för en presentation. Läs/skriv String.

**Returnerar:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

Returnerar eller anger författaren för en presentation. Läs/skriv String.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

Returnerar eller anger nyckelorden för en presentation. Läs/skriv String.

**Returnerar:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```

Returnerar eller anger nyckelorden för en presentation. Läs/skriv String.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public final String getComments()
```

Returnerar eller anger kommentarer för en presentation. Läs/skriv String.

**Returnerar:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

Returnerar eller anger kommentarer för en presentation. Läs/skriv String.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getCategory() {#getCategory--}
```
public final String getCategory()
```

Returnerar eller anger kategorin för en presentation. Läs/skriv String.

**Returnerar:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

Returnerar eller anger kategorin för en presentation. Läs/skriv String.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

Returnerar datumet då en presentation skapades. Värdena är i UTC. Läs/skriv java.util.Date.

**Returnerar:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Returnerar datumet då en presentation skapades. Värdena är i UTC. Läs/skriv java.util.Date.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```

Returnerar datumet då en presentation senast ändrades. Värdena är i UTC. Skrivskyddad i fallet Presentation.DocumentProperties (eftersom den uppdateras internt under IPresentation-objektets sparprocess). Kan ändras via DocumentProperties-instansen som returneras av metoden [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Se exempel i metoden [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Returnerar:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```

Returnerar datumet då en presentation senast ändrades. Värdena är i UTC. Skrivskyddad i fallet Presentation.DocumentProperties (eftersom den uppdateras internt under IPresentation-objektets sparprocess). Kan ändras via DocumentProperties-instansen som returneras av metoden [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Se exempel i metoden [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```

Returnerar datumet då en presentation senast trycktes. Läs/skriv java.util.Date.

**Returnerar:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```

Returnerar datumet då en presentation senast trycktes. Läs/skriv java.util.Date.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedBy() {#getLastSavedBy--}
```
public final String get
```

Returnerar eller anger namnet på den sista personen som modifierade en presentation. Läs/skriv String.

**Returnerar:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```

Returnerar eller anger namnet på den sista personen som modifierade en presentation. Läs/skriv String.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```

Returnerar eller anger revisionsnumret för presentationen. Läs/skriv int.

**Returnerar:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```

Returnerar eller anger revisionsnumret för presentationen. Läs/skriv int.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```

Returnerar eller anger innehållsstatus för en presentation. Läs/skriv String.

**Returnerar:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```

Returnerar eller anger innehållsstatus för en presentation. Läs/skriv String.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Returnerar eller anger innehållstyp för en presentation. Läs/skriv String.

**Returnerar:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Returnerar eller anger innehållstyp för en presentation. Läs/skriv String.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```

Returnerar eller anger HyperlinkBase-dokumentegenskapen. Läs/skriv String.

**Returnerar:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```

Returnerar eller anger HyperlinkBase-dokumentegenskapen. Läs/skriv String.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```

Returnerar antalet anpassade egenskaper som faktiskt finns i en samling. Skrivskyddad int.

**Returnerar:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```

Returnerar ett anpassat egenskapsnamn på det angivna indexet.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för den anpassade egenskapen att hämta. |

**Returnerar:**
java.lang.String - Användarnamn för anpassad egenskap på angivet index.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```

Tar bort en anpassad egenskap som är kopplad till ett angivet namn.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen att ta bort. |

**Returnerar:**
boolean - Return true if a property was removed, false otherwise.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```

Kontrollerar förekomsten av en anpassad egenskap med ett angivet namn.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen att kontrollera. |

**Returnerar:**
boolean - Return true if property exists, false otherwise.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```

Returnerar eller anger den anpassade egenskap som är kopplad till ett angivet namn. Läs/skriv Object.

--------------------

Value can be **int**, **float**, **String**, **boolean** or **Date**.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String |  |

**Returnerar:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public final void set_Item(String name, Object value)
```

Returnerar eller anger den anpassade egenskap som är kopplad till ett angivet namn. Läs/skriv Object.

--------------------

Value can be **int**, **float**, **String**, **boolean** or **Date**.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |
### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```

Hämtar ett namngivet booleskt värde från de anpassade egenskaperna.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen att hämta |
| value | boolean[] | Användarvärde för anpassad egenskap |
### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```

Hämtar ett namngivet heltalsvärde från de anpassade egenskaperna.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen att hämta |
| value | int[] | Användarvärde för anpassad egenskap |
### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```

Hämtar ett namngivet DateTime-värde från de anpassade egenskaperna.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen att hämta |
| value | java.util.Date[] | Användarvärde för anpassad egenskap |
### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```

Hämtar ett namngivet strängvärde från de anpassade egenskaperna.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen att hämta |
| value | java.lang.String[] | Användarvärde för anpassad egenskap |
### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```

Hämtar ett namngivet flyttalsvärde från de anpassade egenskaperna.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen att hämta |
| value | float[] | Användarvärde för anpassad egenskap |
### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```

Hämtar ett namngivet dubbeltvärde från de anpassade egenskaperna.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen att hämta. |
| value | double[] | Användarvärde för anpassad egenskap |
### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```

Anger en namngiven boolesk anpassad egenskap.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen att sätta |
| value | boolean | Användarvärde för anpassad egenskap |
### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```

Anger en namngiven heltals-anpassad egenskap.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen att sätta |
| value | int | Användarvärde för anpassad egenskap |
### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```

Anger en namngiven DateTime-anpassad egenskap.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen att sätta |
| value | java.util.Date | Användarvärde för anpassad egenskap |
### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```

Anger en namngiven sträng-anpassad egenskap.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen att sätta |
| value | java.lang.String | Användarvärde för anpassad egenskap |
### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```

Anger en namngiven flyttals-anpassad egenskap.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen att sätta |
| value | float | Användarvärde för anpassad egenskap |
### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```

Anger en namngiven dubbel-anpassad egenskap.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på den anpassade egenskapen att sätta |
| value | double | Användarvärde för anpassad egenskap |
### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```

Tar bort alla anpassade egenskaper.
### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```

Hämtar en matris med känslighetsetiketter från de anpassade dokumentegenskaperna (Microsoft Information Protection SDK Metadata).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Hämta känslighetsetiketter från de anpassade dokumentegenskaperna
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Lägg till etikett i samlingen
>          // Här kan du lägga till en kontroll för giltigheten av etikettinformationen (etiketten är tillgänglig, osv)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
com.aspose.slides.ISensitivityLabel[]
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public  



```

Rensar och ställer in standardvärden för alla inbyggda egenskaper.
### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```

Indikerar visningsläget för dokumentets miniatyrbild. Sätt detta element till **true** för att möjliggöra skalning av miniatyrbilden till visningen. Sätt detta element till **false** för att möjliggöra beskärning av miniatyrbilden så att endast sektioner som passar visningen visas. Läs/skriv boolean.

**Returnerar:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```

Indikerar visningsläget för dokumentets miniatyrbild. Sätt detta element till **true** för att möjliggöra skalning av miniatyrbilden till visningen. Sätt detta element till **false** för att möjliggöra beskärning av miniatyrbilden så att endast sektioner som passar visningen visas. Läs/skriv boolean.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```

Indikerar om hyperlänkar i ett dokument är aktuella. Sätt detta element till **true** för att indikera att hyperlänkar är uppdaterade. Sätt detta element till **false** för att indikera att hyperlänkar är föråldrade. Läs/skriv boolean.

**Returnerar:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```

Indikerar om hyperlänkar i ett dokument är aktuella. Sätt detta element till **true** för att indikera att hyperlänkar är uppdaterade. Sätt detta element till **false** för att indikera att hyperlänkar är föråldrade. Läs/skriv boolean.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

Specificerar att en eller flera hyperlänkar i denna del uppdaterades uteslutande i denna del av en producent. Nästa producent som öppnar detta dokument ska uppdatera hyperlänksrelationerna med de nya hyperlänkarna som är specificerade i denna del. Läs/skriv boolean.

**Returnerar:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

Specificerar att en eller flera hyperlänkar i denna del uppdaterades uteslutande i denna del av en producent. Nästa producent som öppnar detta dokument ska uppdatera hyperlänksrelationerna med de nya hyperlänkarna som är specificerade i denna del. Läs/skriv boolean.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getSlides() {#getSlides--}
```
public final int getSlides()
```

Returnerar det totala antalet bilder i ett presentationsdokument. Skrivskyddad int.

**Returnerar:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

Returnerar antalet dolda bilder i ett presentationsdokument. Skrivskyddad int.

**Returnerar:**
int
### getNotes() {#getNotes--}
```
public final int getNotes()
```

Returnerar antalet bilder i en presentation som innehåller anteckningar. Skrivskyddad int.

**Returnerar:**
int
### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

Returnerar det totala antalet stycken som finns i ett dokument om tillämpligt. Skrivskyddad int.

**Returnerar:**
int
### getWords() {#getWords--}
```
public final int getWords()
```

Returnerar det totala antalet ord i ett dokument. Skrivskyddad int.

**Returnerar:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

Returnerar det totala antalet ljud- eller videoklipp som finns i dokumentet. Skrivskyddad int.

**Returnerar:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

Specificerar titeln för varje dokumentdel. Dessa delar är inte faktiska dokumentdelar utan konceptuella representationer av dokumentsektioner. Skrivskyddad String[].

**Returnerar:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

Indikerar gruppering av dokumentdelar och antalet delar i varje grupp. Skrivskyddad IHeadingPair[].

**Returnerar:**
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Klonar aktuellt objekt

**Returnerar:**
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

Klonar aktuellt objekt

**Returnerar:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone