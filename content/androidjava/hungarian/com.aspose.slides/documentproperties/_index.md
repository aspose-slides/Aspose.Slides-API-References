---
title: DocumentProperties
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: A prezentáció tulajdonságait képviseli.
type: docs
url: /hu/com.aspose.slides/documentproperties/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

A prezentáció tulajdonságait képviseli.

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // Példányosítja a Presentation osztályt, amely a prezentációt képviseli
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // Hivatkozást hoz létre az IDocumentProperties objektumra, amely a Presentation-hez kapcsolódik
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Megjeleníti a beépített tulajdonságokat
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
>  // Példányosítja a Presentation osztályt, amely a Presentation-t képviseli
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // Hivatkozást hoz létre az IDocumentProperties objektumra, amely a Presentation-hez kapcsolódik
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Beállítja a beépített tulajdonságokat
>      documentProperties.setAuthor("Aspose.Slides for Android via Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // Elmenti a prezentációt egy fájlba
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | Új példányt inicializál a(z) [DocumentProperties](../../com.aspose.slides/documentproperties) osztályban. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Visszaadja az alkalmazás verzióját. |
| [getNameOfApplication()](#getNameOfApplication--) | Visszaadja vagy beállítja az alkalmazás nevét. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Visszaadja vagy beállítja az alkalmazás nevét. |
| [getCompany()](#getCompany--) | Visszaadja vagy beállítja a cég tulajdonságát. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Visszaadja vagy beállítja a cég tulajdonságát. |
| [getManager()](#getManager--) | Visszaadja vagy beállítja a vezető tulajdonságát. |
| [setManager(String value)](#setManager-java.lang.String-) | Visszaadja vagy beállítja a vezető tulajdonságát. |
| [getPresentationFormat()](#getPresentationFormat--) | Visszaadja vagy beállítja a prezentáció tervezett formátumát. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Visszaadja vagy beállítja a prezentáció tervezett formátumát. |
| [getSharedDoc()](#getSharedDoc--) | Megállapítja, hogy a prezentáció több személy között megosztott-e. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Megállapítja, hogy a prezentáció több személy között megosztott-e. |
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
| [getCreatedTime()](#getCreatedTime--) | Visszaadja a prezentáció létrehozásának dátumát. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Visszaadja a prezentáció létrehozásának dátumát. |
| [getLastSavedTime()](#getLastSavedTime--) | Visszaadja a prezentáció utolsó módosításának dátumát. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Visszaadja a prezentáció utolsó módosításának dátumát. |
| [getLastPrinted()](#getLastPrinted--) | Visszaadja a prezentáció legutóbbi nyomtatási dátumát. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Visszaadja a prezentáció legutóbbi nyomtatási dátumát. |
| [getLastSavedBy()](#getLastSavedBy--) | Visszaadja vagy beállítja az utolsó módosító személy nevét. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Visszaadja vagy beállítja az utolsó módosító személy nevét. |
| [getRevisionNumber()](#getRevisionNumber--) | Visszaadja vagy beállítja a prezentáció revíziószámát. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Visszaadja vagy beállítja a prezentáció revíziószámát. |
| [getContentStatus()](#getContentStatus--) | Visszaadja vagy beállítja a prezentáció tartalomállapotát. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Visszaadja vagy beállítja a prezentáció tartalomállapotát. |
| [getContentType()](#getContentType--) | Visszaadja vagy beállítja a prezentáció tartalomtípusát. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Visszaadja vagy beállítja a prezentáció tartalomtípusát. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Visszaadja vagy beállítja a HyperlinkBase dokumentum-tulajdonságot. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Visszaadja vagy beállítja a HyperlinkBase dokumentum-tulajdonságot. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Visszaadja a gyűjteményben ténylegesen lévő egyedi tulajdonságok számát. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Egyedi tulajdonság nevét adja vissza a megadott indexnél. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Eltávolít egy megadott névhez tartozó egyedi tulajdonságot. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Ellenőrzi, hogy egy egyedi tulajdonság létezik-e a megadott névvel. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Visszaadja vagy beállítja a megadott névhez tartozó egyedi tulajdonságot. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Visszaadja vagy beállítja a megadott névhez tartozó egyedi tulajdonságot. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Lekéri a név szerint egy logikai értéket az egyedi tulajdonságok közül. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Lekéri a név szerint egy egész szám értéket az egyedi tulajdonságok közül. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Lekéri a név szerint egy DateTime értéket az egyedi tulajdonságok közül. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Lekéri a név szerint egy karakterlánc értéket az egyedi tulajdonságok közül. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Lekéri a név szerint egy float értéket az egyedi tulajdonságok közül. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Lekéri a név szerint egy double értéket az egyedi tulajdonságok közül. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Beállít egy név szerint egy logikai egyedi tulajdonságot. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Beállít egy név szerint egy egész számú egyedi tulajdonságot. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Beállít egy név szerint egy DateTime egyedi tulajdonságot. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Beállít egy név szerint egy karakterlánc egyedi tulajdonságot. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Beállít egy név szerint egy float egyedi tulajdonságot. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Beállít egy név szerint egy double egyedi tulajdonságot. |
| [clearCustomProperties()](#clearCustomProperties--) | Eltávolítja az összes egyedi tulajdonságot. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Egyedi dokumentumtulajdonságokból érzékenységi címkéket (Microsoft Information Protection SDK Metadata) ad vissza. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Kitörli és alapértelmezett értékekkel tölti fel az összes beépített tulajdonságot. |
| [getScaleCrop()](#getScaleCrop--) | Jelzi a dokumentum bélyegkép megjelenítési módját. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Jelzi a dokumentum bélyegkép megjelenítési módját. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Jelzi, hogy a dokumentumban lévő hiperhivatkozások naprakészek-e. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Jelzi, hogy a dokumentumban lévő hiperhivatkozások naprakészek-e. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Megadja, hogy egy vagy több hiperhivatkozás ebben a részben kizárólag a termelő által lett frissítve. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Megadja, hogy egy vagy több hiperhivatkozás ebben a részben kizárólag a termelő által lett frissítve. |
| [getSlides()](#getSlides--) | Visszaadja a prezentációdokumentum összes dia számát. |
| [getHiddenSlides()](#getHiddenSlides--) | Visszaadja a rejtett diák számát egy prezentációdokumentumban. |
| [getNotes()](#getNotes--) | Visszaadja a jegyzetelt diák számát egy prezentációban. |
| [getParagraphs()](#getParagraphs--) | Visszaadja a dokumentumban talált bekezdések összes számát, ha alkalmazható. |
| [getWords()](#getWords--) | Visszaadja a dokumentumban található szavak teljes számát. |
| [getMultimediaClips()](#getMultimediaClips--) | Visszaadja a dokumentumban jelen lévő hang- vagy videoklipek teljes számát. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Megadja minden dokumentumrész címét. |
| [getHeadingPairs()](#getHeadingPairs--) | Jelzi a dokumentumrészek csoportosítását és az egyes csoportokban lévő részek számát. |
| [deepClone()](#deepClone--) | Klónozza a jelenlegi objektumot |
| [cloneT()](#cloneT--) | Klónozza a jelenlegi objektumot |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

Új példányt inicializál a(z) [DocumentProperties](../../com.aspose.slides/documentproperties) osztályban.

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

Visszaadja az alkalmazás verzióját. Csak olvasható String.

**Visszatér:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```

Visszaadja vagy beállítja az alkalmazás nevét. Olvasható/írható String.

**Visszatér:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

Visszaadja vagy beállítja az alkalmazás nevét. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public final String getCompany()
```

Visszaadja vagy beállítja a cég tulajdonságát. Olvasható/írható String.

**Visszatér:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

Visszaadja vagy beállítja a cég tulajdonságát. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public final String getManager()
```

Visszaadja vagy beállítja a vezető tulajdonságát. Olvasható/írható String.

**Visszatér:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

Visszaadja vagy beállítja a vezető tulajdonságát. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

Visszaadja vagy beállítja a prezentáció tervezett formátumát. Olvasható/írható String.

**Visszatér:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

Visszaadja vagy beállítja a prezentáció tervezett formátumát. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```

Megállapítja, hogy a prezentáció több személy között megosztott-e. Olvasható/írható boolean.

**Visszatér:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```

Megállapítja, hogy a prezentáció több személy között megosztott-e. Olvasható/írható boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```

Visszaadja vagy beállítja egy alkalmazás sablonját. Olvasható/írható String.

**Visszatér:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

Visszaadja vagy beállítja egy alkalmazás sablonját. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```

A prezentáció teljes szerkesztési ideje. Olvasható/írható double.

**Visszatér:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```

A prezentáció teljes szerkesztési ideje. Olvasható/írható double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```

Visszaadja vagy beállítja a prezentáció címét. Olvasható/írható String.

**Visszatér:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

Visszaadja vagy beállítja a prezentáció címét. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```

Visszaadja vagy beállítja a prezentáció tárgyát. Olvasható/írható String.

**Visszatér:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

Visszaadja vagy beállítja a prezentáció tárgyát. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

Visszaadja vagy beállítja a prezentáció szerzőjét. Olvasható/írható String.

**Visszatér:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

Visszaadja vagy beállítja a prezentáció szerzőjét. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

Visszaadja vagy beállítja a prezentáció kulcsszavait. Olvasható/írható String.

**Visszatér:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```

Visszaadja vagy beállítja a prezentáció kulcsszavait. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```

Visszaadja vagy beállítja a prezentáció megjegyzéseit. Olvasható/írható String.

**Visszatér:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

Visszaadja vagy beállítja a prezentáció megjegyzéseit. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public final String getCategory()
```

Visszaadja vagy beállítja a prezentáció kategóriáját. Olvasható/írható String.

**Visszatér:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

Visszaadja vagy beállítja a prezentáció kategóriáját. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

Visszaadja a prezentáció létrehozásának dátumát. Az értékek UTC-ben vannak. Olvasható/írható java.util.Date.

**Visszatér:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Visszaadja a prezentáció létrehozásának dátumát. Az értékek UTC-ben vannak. Olvasható/írható java.util.Date.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```

Visszaadja a prezentáció utolsó módosításának dátumát. Az értékek UTC-ben vannak. Csak olvasható, ha a Presentation.DocumentProperties-ról van szó (mert a mentés során frissül belsőleg). Változtatható a [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) által visszaadott DocumentProperties példányon keresztül. Lásd a [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) metódus-összefoglalót a példában.

**Visszatér:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```

Visszaadja a prezentáció utolsó módosításának dátumát. Az értékek UTC-ben vannak. Csak olvasható, ha a Presentation.DocumentProperties-ról van szó (mert a mentés során frissül belsőleg). Változtatható a [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) által visszaadott DocumentProperties példányon keresztül. Lásd a [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) metódus-összefoglalót a példában.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```

Visszaadja a prezentáció legutóbbi nyomtatási dátumát. Olvasható/írható java.util.Date.

**Visszatér:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```

Visszaadja a prezentáció legutóbbi nyomtatási dátumát. Olvasható/írható java.util.Date.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```

Visszaadja vagy beállítja az utolsó módosító személy nevét. Olvasható/írható String.

**Visszatér:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```

Visszaadja vagy beállítja az utolsó módosító személy nevét. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```

Visszaadja vagy beállítja a prezentáció revíziószámát. Olvasható/írható int.

**Visszatér:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```

Visszaadja vagy beállítja a prezentáció revíziószámát. Olvasható/írható int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```

Visszaadja vagy beállítja a prezentáció tartalomállapotát. Olvasható/írható String.

**Visszatér:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```

Visszaadja vagy beállítja a prezentáció tartalomállapotát. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

Visszaadja vagy beállítja a prezentáció tartalomtípusát. Olvasható/írható String.

**Visszatér:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Visszaadja vagy beállítja a prezentáció tartalomtípusát. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```

Visszaadja vagy beállítja a HyperlinkBase dokumentum-tulajdonságot. Olvasható/írható String.

**Visszatér:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```

Visszaadja vagy beállítja a HyperlinkBase dokumentum-tulajdonságot. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```

Visszaadja a gyűjteményben ténylegesen lévő egyedi tulajdonságok számát. Csak olvasható int.

**Visszatér:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```

Egyedi tulajdonság nevét adja vissza a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulla-alapú index a lekérendő egyedi tulajdonsághoz. |

**Visszatér:**
java.lang.String - Egyedi tulajdonság neve a megadott indexnél.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```

Eltávolít egy megadott névhez tartozó egyedi tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | Az eltávolítandó egyedi tulajdonság neve. |

**Visszatér:**
boolean - Igaz, ha a tulajdonság eltávolításra került, különben hamis.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```

Ellenőrzi, hogy egy megadott névvel rendelkező egyedi tulajdonság létezik-e.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | Az ellenőrzendő egyedi tulajdonság neve. |

**Visszatér:**
boolean - Igaz, ha a tulajdonság létezik, különben hamis.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```

Visszaadja vagy beállítja a megadott névhez tartozó egyedi tulajdonságot. Olvasható/írható Object.

--------------------

Az érték lehet **int**, **float**, **String**, **boolean** vagy **Date**.

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

Visszaadja vagy beállítja a megadott névhez tartozó egyedi tulajdonságot. Olvasható/írható Object.

--------------------

Az érték lehet **int**, **float**, **String**, **boolean** vagy **Date**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```

Lekéri a név szerint egy logikai értéket az egyedi tulajdonságok közül.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A lekérendő egyedi tulajdonság neve |
| value | boolean[] | Egyedi tulajdonság értéke |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```

Lekéri a név szerint egy egész szám értéket az egyedi tulajdonságok közül.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A lekérendő egyedi tulajdonság neve |
| value | int[] | Egyedi tulajdonság értéke |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```

Lekéri a név szerint egy DateTime értéket az egyedi tulajdonságok közül.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A lekérendő egyedi tulajdonság neve |
| value | java.util.Date[] | Egyedi tulajdonság értéke |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```

Lekéri a név szerint egy karakterlánc értéket az egyedi tulajdonságok közül.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A lekérendő egyedi tulajdonság neve |
| value | java.lang.String[] | Egyedi tulajdonság értéke |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```

Lekéri a név szerint egy float értéket az egyedi tulajdonságok közül.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A lekérendő egyedi tulajdonság neve |
| value | float[] | Egyedi tulajdonság értéke |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```

Lekéri a név szerint egy double értéket az egyedi tulajdonságok közül.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A lekérendő egyedi tulajdonság neve. |
| value | double[] | Egyedi tulajdonság értéke |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```

Beállít egy név szerint logikai egyedi tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A beállítandó egyedi tulajdonság neve |
| value | boolean | Egyedi tulajdonság értéke |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```

Beállít egy név szerint egész számú egyedi tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A beállítandó egyedi tulajdonság neve |
| value | int | Egyedi tulajdonság értéke |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```

Beállít egy név szerint DateTime egyedi tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A beállítandó egyedi tulajdonság neve |
| value | java.util.Date | Egyedi tulajdonság értéke |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```

Beállít egy név szerint karakterlánc egyedi tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A beállítandó egyedi tulajdonság neve |
| value | java.lang.String | Egyedi tulajdonság értéke |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```

Beállít egy név szerint float egyedi tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A beállítandó egyedi tulajdonság neve |
| value | float | Egyedi tulajdonság értéke |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```

Beállít egy név szerint double egyedi tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A beállítandó egyedi tulajdonság neve |
| value | double | Egyedi tulajdonság értéke |

### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```

Eltávolítja az összes egyedi tulajdonságot.

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```

Egyedi dokumentumtulajdonságokból érzékenységi címkéket (Microsoft Information Protection SDK Metadata) ad vissza.

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Szerezze be az érzékenységi címkéket az egyedi dokumentumtulajdonságokból
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Címke hozzáadása a gyűjteményhez
>          // Itt ellenőrzést adhat hozzá a címkeinformáció érvényességére (a címke elérhető, stb.)
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

Alapértelmezett értékekkel tölti fel az összes beépített tulajdonságot.

### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```

Jelzi a dokumentum bélyegkép megjelenítési módját. Állítsd **true**-ra a dokumentum bélyegkép skálázásához, **false**-ra a vágáshoz. Olvasható/írható boolean.

**Visszatér:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```

Jelzi a dokumentum bélyegkép megjelenítési módját. Állítsd **true**-ra a dokumentum bélyegkép skálázásához, **false**-ra a vágáshoz. Olvasható/írható boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```

Jelzi, hogy a dokumentumban lévő hiperhivatkozások naprakészek-e. Állítsd **true**-ra a frissített hiperhivatkozások jelzéséhez, **false**-ra a elavultak jelzéséhez. Olvasható/írható boolean.

**Visszatér:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```

Jelzi, hogy a dokumentumban lévő hiperhivatkozások naprakészek-e. Állítsd **true**-ra a frissített hiperhivatkozások jelzéséhez, **false**-ra a elavultak jelzéséhez. Olvasható/írható boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

Megadja, hogy egy vagy több hiperhivatkozás ebben a részben kizárólag a termelő által lett frissítve. A következő termelő, aki megnyitja a dokumentumot, frissíti a hiperhivatkozási kapcsolatokat az új hiperhivatkozásokkal. Olvasható/írható boolean.

**Visszatér:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

Megadja, hogy egy vagy több hiperhivatkozás ebben a részben kizárólag a termelő által lett frissítve. A következő termelő, aki megnyitja a dokumentumot, frissíti a hiperhivatkozási kapcsolatokat az új hiperhivatkozásokkal. Olvasható/írható boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public final int getSlides()
```

Visszaadja a prezentációdokumentum teljes diaszámát. Csak olvasható int.

**Visszatér:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

Visszaadja a rejtett diák számát egy prezentációdokumentumban. Csak olvasható int.

**Visszatér:**
int
### getNotes() {#getNotes--}
```
public final int getNotes()
```

Visszaadja a jegyzetekkel rendelkező diák számát egy prezentációban. Csak olvasható int.

**Visszatér:**
int
### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

Visszaadja a dokumentumban található bekezdések összes számát, ha alkalmazható. Csak olvasható int.

**Visszatér:**
int
### getWords() {#getWords--}
```
public final int getWords()
```

Visszaadja a dokumentumban található szavak teljes számát. Csak olvasható int.

**Visszatér:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

Visszaadja a dokumentumban jelen lévő hang- vagy videoklipek teljes számát. Csak olvasható int.

**Visszatér:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

Megadja minden dokumentumrész címét. Ezek a részek nem dokumentumrészek, hanem a dokumentum szakaszainak fogalmi reprezentációi. Csak olvasható String[].

**Visszatér:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

Jelzi a dokumentumrészek csoportosítását és az egyes csoportokban lévő részek számát. Csak olvasható IHeadingPair[].

**Visszatér:**
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Klónozza a jelenlegi objektumot

**Visszatér:**
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

Klónozza a jelenlegi objektumot

**Visszatér:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone