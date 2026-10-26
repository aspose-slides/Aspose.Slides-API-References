---
title: DocumentProperties
second_title: Aspose.Slides Java API hivatkozás
description: A bemutató tulajdonságait képviseli.
type: docs
url: /hu/com.aspose.slides/documentproperties/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable  
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

A prezentáció tulajdonságait ábrázolja.

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // Instantiate the Presentation class that represents the presentation
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // Create a reference to IDocumentProperties object associated with Presentation
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Display the builtin properties
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
>  // Instantiate the Presentation class that represents the Presentation
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // Create a reference to IDocumentProperties object associated with Presentation
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Set the builtin properties
>      documentProperties.setAuthor("Aspose.Slides for Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // Save your presentation to a file
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | Új példányt inicializál a(z) [DocumentProperties](../../com.aspose.slides/documentproperties) osztályból. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Visszaadja az alkalmazás verzióját. |
| [getNameOfApplication()](#getNameOfApplication--) | Visszaadja vagy beállítja az alkalmazás nevét. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Visszaadja vagy beállítja az alkalmazás nevét. |
| [getCompany()](#getCompany--) | Visszaadja vagy beállítja a cég tulajdonságát. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Visszaadja vagy beállítja a cég tulajdonságát. |
| [getManager()](#getManager--) | Visszaadja vagy beállítja a menedzser tulajdonságát. |
| [setManager(String value)](#setManager-java.lang.String-) | Visszaadja vagy beállítja a menedzser tulajdonságát. |
| [getPresentationFormat()](#getPresentationFormat--) | Visszaadja vagy beállítja a prezentáció szándékolt formátumát. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Visszaadja vagy beállítja a prezentáció szándékolt formátumát. |
| [getSharedDoc()](#getSharedDoc--) | Megállapítja, hogy a prezentáció meg van-e osztva több személy között. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Megállapítja, hogy a prezentáció meg van-e osztva több személy között. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Visszaadja vagy beállítja egy alkalmazás sablonját. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Visszaadja vagy beállítja egy alkalmazás sablonját. |
| [getTotalEditingTime()](#getTotalEditingTime--) | A prezentáció teljes szerkesztési ideje. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | A prezentáció teljes szerkesztési ideje. |
| [getTitle()](#getTitle--) | Visszaadja vagy beállítja a prezentáció címét. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Visszaadja vagy beállítja a prezentáció címét. |
| [getSubject()](#getSubject--) | Visszaadja vagy beállítja a prezentáció tárgyát. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Visszaadja vagy beállítja a prezentáció tárgyát. |
| [getAuthor()](#getAuthor--) | Visszaadja vagy beállítja a prezentáció szerzőjét. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Visszaadja vagy beállítja a prezentáció szerzőjét. |
| [getKeywords()](#getKeywords--) | Visszaadja vagy beállítja a prezentáció kulcsszavait. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Visszaadja vagy beállítja a prezentáció kulcsszavait. |
| [getComments()](#getComments--) | Visszaadja vagy beállítja a prezentáció megjegyzéseit. |
| [setComments(String value)](#setComments-java.lang.String-) | Visszaadja vagy beállítja a prezentáció megjegyzéseit. |
| [getCategory()](#getCategory--) | Visszaadja vagy beállítja a prezentáció kategóriáját. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Visszaadja vagy beállítja a prezentáció kategóriáját. |
| [getCreatedTime()](#getCreatedTime--) | Visszaadja, hogy mikor készült a prezentáció. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Visszaadja, hogy mikor készült a prezentáció. |
| [getLastSavedTime()](#getLastSavedTime--) | Visszaadja, hogy mikor módosították utoljára a prezentációt. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Visszaadja, hogy mikor módosították utoljára a prezentációt. |
| [getLastPrinted()](#getLastPrinted--) | Visszaadja, mikor nyomtatták utoljára a prezentációt. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Visszaadja, mikor nyomtatták utoljára a prezentációt. |
| [getLastSavedBy()](#getLastSavedBy--) | Visszaadja vagy beállítja az utolsó módosítót nevét. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Visszaadja vagy beállítja az utolsó módosítót nevét. |
| [getRevisionNumber()](#getRevisionNumber--) | Visszaadja vagy beállítja a prezentáció revíziószámát. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Visszaadja vagy beállítja a prezentáció revíziószámát. |
| [getContentStatus()](#getContentStatus--) | Visszaadja vagy beállítja a prezentáció tartalom állapotát. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Visszaadja vagy beállítja a prezentáció tartalom állapotát. |
| [getContentType()](#getContentType--) | Visszaadja vagy beállítja a prezentáció tartalom típusát. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Visszaadja vagy beállítja a prezentáció tartalom típusát. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Visszaadja vagy beállítja a HyperlinkBase dokumentum tulajdonságát. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Visszaadja vagy beállítja a HyperlinkBase dokumentum tulajdonságát. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Visszaadja a gyűjteményben ténylegesen szereplő egyéni tulajdonságok számát. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Visszaad egy egyéni tulajdonság nevét a megadott indexen. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Eltávolít egy megadott névhez tartozó egyéni tulajdonságot. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Ellenőrzi egy megadott névvel rendelkező egyéni tulajdonság jelenlétét. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Visszaadja vagy beállítja a megadott névhez tartozó egyéni tulajdonságot. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Visszaadja vagy beállítja a megadott névhez tartozó egyéni tulajdonságot. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Gets a named boolean value from the custom properties. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Gets a named integer value from the custom properties. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Gets a named DateTime value from the custom properties. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Gets a named string value from the custom properties. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Gets a named float value from the custom properties. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Gets a named double value from the custom properties. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Beállít egy névvel ellátott logikai egyéni tulajdonságot. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Beállít egy névvel ellátott egész számú egyéni tulajdonságot. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Beállít egy névvel ellátott DateTime egyéni tulajdonságot. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Beállít egy névvel ellátott karakterlánc egyéni tulajdonságot. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Beállít egy névvel ellátott lebegőpontos egyéni tulajdonságot. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Beállít egy névvel ellátott dupla pontosságú egyéni tulajdonságot. |
| [clearCustomProperties()](#clearCustomProperties--) | Eltávolítja az összes egyéni tulajdonságot. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Lekéri a szenzitivitási címkéket az egyéni dokumentumtulajdonságokból (Microsoft Information Protection SDK Metadata). |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Törli és alapértelmezett értékekkel tölti fel az összes beépített tulajdonságot. |
| [getScaleCrop()](#getScaleCrop--) | Jeli a dokumentum előnézeti kép megjelenítési módját. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Jeli a dokumentum előnézeti kép megjelenítési módját. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Jeli, hogy a dokumentum hiperhivatkozásai naprakészek-e. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Jeli, hogy a dokumentum hiperhivatkozásai naprakészek-e. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Megadja, hogy egy vagy több hiperhivatkozást ebben a részben kizárólag egy producer frissített. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Megadja, hogy egy vagy több hiperhivatkozást ebben a részben kizárólag egy producer frissített. |
| [getSlides()](#getSlides--) | Visszaadja a diák teljes számát egy prezentációs dokumentumban. |
| [getHiddenSlides()](#getHiddenSlides--) | Visszaadja a rejtett diák számát egy prezentációs dokumentumban. |
| [getNotes()](#getNotes--) | Visszaadja a jegyzetekkel rendelkező diák számát a prezentációban. |
| [getParagraphs()](#getParagraphs--) | Visszaadja a dokumentumban talált bekezdések teljes számát, ha alkalmazható. |
| [getWords()](#getWords--) | Visszaadja a dokumentumban található szavak teljes számát. |
| [getMultimediaClips()](#getMultimediaClips--) | Visszaadja a dokumentumban lévő hang- vagy videóklipek teljes számát. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Megadja minden dokumentumrész címét. |
| [getHeadingPairs()](#getHeadingPairs--) | Jeli a dokumentumrészek csoportosítását és az egyes csoportokban lévő részek számát. |
| [deepClone()](#deepClone--) | Klónozza a jelenlegi objektumot. |
| [cloneT()](#cloneT--) | Klónozza a jelenlegi objektumot. |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```


Új példányt inicializál a(z) [DocumentProperties](../../com.aspose.slides/documentproperties) osztályból.

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```


Visszaadja az alkalmazás verzióját. Csak olvasható String.

**Returns:**  
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```


Visszaadja vagy beállítja az alkalmazás nevét. Olvasható/írható String.

**Returns:**  
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```


Visszaadja vagy beállítja az alkalmazás nevét. Olvasható/írható String.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getCompany() {#getCompany--}
```
public final String getCompany()
```


Visszaadja vagy beállítja a cég tulajdonságát. Olvasható/írható String.

**Returns:**  
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```


Visszaadja vagy beállítja a cég tulajdonságát. Olvasható/írható String.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getManager() {#getManager--}
```
public final String getManager()
```


Visszaadja vagy beállítja a menedzser tulajdonságát. Olvasható/írható String.

**Returns:**  
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```


Visszaadja vagy beállítja a menedzser tulajdonságát. Olvasható/írható String.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```


Visszaadja vagy beállítja a prezentáció szándékolt formátumát. Olvasható/írható String.

**Returns:**  
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```


Visszaadja vagy beállítja a prezentáció szándékolt formátumát. Olvasható/írható String.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```


Megállapítja, hogy a prezentáció meg van-e osztva több személy között. Olvasható/írható boolean.

**Returns:**  
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```


Megállapítja, hogy a prezentáció meg van-e osztva több személy között. Olvasható/írható boolean.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```


Visszaadja vagy beállítja egy alkalmazás sablonját. Olvasható/írható String.

**Returns:**  
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```


Visszaadja vagy beállítja egy alkalmazás sablonját. Olvasható/írható String.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```


A prezentáció teljes szerkesztési ideje. Olvasható/írható double.

**Returns:**  
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```


A prezentáció teljes szerkesztési ideje. Olvasható/írható double.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getTitle() {#getTitle--}
```
public final String getTitle()
```


Visszaadja vagy beállítja a prezentáció címét. Olvasható/írható String.

**Returns:**  
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Visszaadja vagy beállítja a prezentáció címét. Olvasható/írható String.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Visszaadja vagy beállítja a prezentáció tárgyát. Olvasható/írható String.

**Returns:**  
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Visszaadja vagy beállítja a prezentáció tárgyát. Olvasható/írható String.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


Visszaadja vagy beállítja a prezentáció szerzőjét. Olvasható/írható String.

**Returns:**  
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```


Visszaadja vagy beállítja a prezentáció szerzőjét. Olvasható/írható String.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```


Visszaadja vagy beállítja a prezentáció kulcsszavait. Olvasható/írható String.

**Returns:**  
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```


Visszaadja vagy beállítja a prezentáció kulcsszavait. Olvasható/írható String.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public final String getComments()
```


Visszaadja vagy beállítja a prezentáció megjegyzéseit. Olvasható/írható String.

**Returns:**  
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Visszaadja vagy beállítja a prezentáció megjegyzéseit. Olvasható/írható String.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getCategory() {#getCategory--}
```
public final String getCategory()
```


Visszaadja vagy beállítja a prezentáció kategóriáját. Olvasható/írható String.

**Returns:**  
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```


Visszaadja vagy beállítja a prezentáció kategóriáját. Olvasható/írható String.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```
Visszatér a bemutató létrehozásának dátumával. Az értékek UTC-ben vannak. Olvasás/írás java.util.Date.

**Visszatér:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```


Visszatér a bemutató létrehozásának dátumával. Az értékek UTC-ben vannak. Olvasás/írás java.util.Date.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```


Visszatér a bemutató legutóbbi módosításának dátumával. Az értékek UTC-ben vannak. Csak olvasható a Presentation.DocumentProperties esetén (mivel belsőleg frissül az IPresentation objektum mentési folyamatában). Módosítható a DocumentProperties példányon keresztül, amelyet a [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) metódus ad vissza. Lásd a példát a [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) metódus összefoglalójában.

**Visszatér:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```


Visszatér a bemutató legutóbbi módosításának dátumával. Az értékek UTC-ben vannak. Csak olvasható a Presentation.DocumentProperties esetén (mivel belsőleg frissül az IPresentation objektum mentési folyamatában). Módosítható a DocumentProperties példányon keresztül, amelyet a [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) metódus ad vissza. Lásd a példát a [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) metódus összefoglalójában.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```


Visszatér a bemutató legutóbbi nyomtatásának dátumával. Olvasás/írás java.util.Date.

**Visszatér:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```


Visszatér a bemutató legutóbbi nyomtatásának dátumával. Olvasás/írás java.util.Date.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```


Visszatér vagy beállítja az utolsó módosító személy nevét. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```


Visszatér vagy beállítja az utolsó módosító személy nevét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```


Visszatér vagy beállítja a bemutató revíziószámát. Olvasás/írás int.

**Visszatér:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```


Visszatér vagy beállítja a bemutató revíziószámát. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```


Visszatér vagy beállítja a bemutató tartalom státuszát. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```


Visszatér vagy beállítja a bemutató tartalom státuszát. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```


Visszatér vagy beállítja a bemutató tartalom típusát. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```


Visszatér vagy beállítja a bemutató tartalom típusát. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```


Visszatér vagy beállítja a HyperlinkBase dokumentum tulajdonságot. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```


Visszatér vagy beállítja a HyperlinkBase dokumentum tulajdonságot. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```


Visszatér a gyűjteményben ténylegesen lévő egyéni tulajdonságok számával. Csak olvasható int.

**Visszatér:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```


Visszaad egy egyéni tulajdonság nevét a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A lekérni kívánt egyéni tulajdonság nullától kezdődő indexe. |

**Visszatér:**
java.lang.String - Egyéni tulajdonság neve a megadott indexnél.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```


Eltávolít egy megadott névhez tartozó egyéni tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | Az eltávolítandó egyéni tulajdonság neve. |

**Visszatér:**
boolean - Visszatér true értékkel, ha a tulajdonság eltávolításra került, egyébként false.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```


Ellenőrzi egy megadott névvel rendelkező egyéni tulajdonság jelenlétét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A ellenőrzendő egyéni tulajdonság neve. |

**Visszatér:**
boolean - Visszatér true értékkel, ha a tulajdonság létezik, egyébként false.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```


Visszatér vagy beállítja a megadott névhez tartozó egyéni tulajdonságot. Olvasás/írás Object.

Value can be **int**, **float**, **String**, **boolean** or **Date**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String |  |

**Visszatér:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public final void set_Item(String name, Object value)
```


Visszatér vagy beállítja a megadott névhez tartozó egyéni tulajdonságot. Olvasás/írás Object.

Value can be **int**, **float**, **String**, **boolean** or **Date**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |
### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```


Lekér egy megadott névű logikai értéket az egyéni tulajdonságokból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A lekérni kívánt egyéni tulajdonság neve |
| value | boolean[] | Egyéni tulajdonság értéke |
### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```


Lekér egy megadott névű egész értéket az egyéni tulajdonságokból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A lekérni kívánt egyéni tulajdonság neve |
| value | int[] | Egyéni tulajdonság értéke |
### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```


Lekér egy megadott névű DateTime értéket az egyéni tulajdonságokból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A lekérni kívánt egyéni tulajdonság neve |
| value | java.util.Date[] | Egyéni tulajdonság értéke |
### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```


Lekér egy megadott névű karakterlánc értéket az egyéni tulajdonságokból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A lekérni kívánt egyéni tulajdonság neve |
| value | java.lang.String[] | Egyéni tulajdonság értéke |
### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```


Lekér egy megadott névű lebegőpontos értéket az egyéni tulajdonságokból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A lekérni kívánt egyéni tulajdonság neve |
| value | float[] | Egyéni tulajdonság értéke |
### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```


Lekér egy megadott névű dupla pontosságú értéket az egyéni tulajdonságokból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A lekérni kívánt egyéni tulajdonság neve. |
| value | double[] | Egyéni tulajdonság értéke |
### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```


Beállít egy megadott névű logikai egyéni tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A beállítandó egyéni tulajdonság neve |
| value | boolean | Egyéni tulajdonság értéke |
### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```


Beállít egy megadott névű egész egyéni tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A beállítandó egyéni tulajdonság neve |
| value | int | Egyéni tulajdonság értéke |
### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```


Beállít egy megadott névű DateTime egyéni tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A beállítandó egyéni tulajdonság neve |
| value | java.util.Date | Egyéni tulajdonság értéke |
### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```


Beállít egy megadott névű karakterlánc egyéni tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A beállítandó egyéni tulajdonság neve |
| value | java.lang.String | Egyéni tulajdonság értéke |
### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```


Beállít egy megadott névű lebegőpontos egyéni tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A beállítandó egyéni tulajdonság neve |
| value | float | Egyéni tulajdonság értéke |
### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```


Beállít egy megadott névű dupla pontosságú egyéni tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A beállítandó egyéni tulajdonság neve |
| value | double | Egyéni tulajdonság értéke |
### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```


Eltávolítja az összes egyéni tulajdonságot.

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```


Lekér egy tömböt a szenzitivitási címkékkel a saját dokumentumtulajdonságokból (Microsoft Information Protection SDK Metadata).

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // A érzékenységi címkéket lekéri az egyéni dokumentumtulajdonságokból
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Címke hozzáadása a gyűjteményhez
>          // Itt ellenőrizheted a címke információjának érvényességét (a címke elérhető, stb.)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
com.aspose.slides.ISensitivityLabel[]
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public final void clearBuiltInProperties()
```


Törli és alapértelmezett értékekkel tölti fel az összes beépített tulajdonságot.

### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```


Jelzi a dokumentum előnézetének megjelenítési módját. Állítsd ezt az elemet **true** értékre a dokumentum előnézetének méretezéséhez a képernyőn. Állítsd **false** értékre a körbevágáshoz, hogy csak a képernyőhöz illeszkedő részek jelenjenek meg. Olvasás/írás boolean.

**Visszatér:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```


Jelzi a dokumentum előnézetének megjelenítési módját. Állítsd ezt az elemet **true** értékre a dokumentum előnézetének méretezéséhez a képernyőn. Állítsd **false** értékre a körbevágáshoz, hogy csak a képernyőhöz illeszkedő részek jelenjenek meg. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```


Jelzi, hogy a dokumentum hiperhivatkozásai naprakészek-e. Állítsd **true** értékre a hiperhivatkozások frissítésének jelzésére. Állítsd **false** értékre a hiperhivatkozások elavultságának jelzésére. Olvasás/írás boolean.

**Visszatér:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```
Indicates whether hyperlinks in a document are up-to-date. Set this element to **true** to indicate that hyperlinks are updated. Set this element to **false** to indicate that hyperlinks are outdated. Olvasás/írás boolean.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

Megadja, hogy a részben egy vagy több hiperhivatkozást kizárólag ebben a részben frissített egy producer. A következő producer, aki megnyitja a dokumentumot, frissíti a hiperhivatkozáskapcsolatokat az ebben a részben megadott új hiperhivatkozásokkal. Olvasás/írás boolean.

Visszatérési érték:
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

Megadja, hogy a részben egy vagy több hiperhivatkozást kizárólag ebben a részben frissített egy producer. A következő producer, aki megnyitja a dokumentumot, frissíti a hiperhivatkozáskapcsolatokat az ebben a részben megadott új hiperhivatkozásokkal. Olvasás/írás boolean.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public final int getSlides()
```

Visszaadja a prezentációs dokumentumban található diák összes számát. Csak olvasás int.

Visszatérési érték:
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

Visszaadja a prezentációs dokumentumban rejtett diák számát. Csak olvasás int.

Visszatérési érték:
int
### getNotes() {#getNotes--}
```
public final int getNotes()
```

Visszaadja a jegyzetekkel rendelkező prezentációs diák számát. Csak olvasás int.

Visszatérési érték:
int
### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

Visszaadja a dokumentumban (ha releváns) található bekezdések teljes számát. Csak olvasás int.

Visszatérési érték:
int
### getWords() {#getWords--}
```
public final int getWords()
```

Visszaadja a dokumentumban található szavak teljes számát. Csak olvasás int.

Visszatérési érték:
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

Visszaadja a dokumentumban jelen lévő hang- vagy videoklipek teljes számát. Csak olvasás int.

Visszatérési érték:
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

Megadja minden dokumentumrész címét. Ezek a részek nem dokumentumrészek, hanem a dokumentumszakaszok koncepció szerinti ábrázolásai. Csak olvasás String[].

Visszatérési érték:
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

A dokumentumrészek csoportosítását és minden csoportban lévő részek számát jelzi. Csak olvasás IHeadingPair[].

Visszatérési érték:
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Klónozza a jelenlegi objektumot

Visszatérési érték:
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

Klónozza a jelenlegi objektumot

Visszatérési érték:
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone