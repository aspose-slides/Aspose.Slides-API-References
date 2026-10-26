---
title: IDocumentProperties
second_title: Aspose.Slides for Java API Reference
description: Represents properties of a presentation.
type: docs
url: /hu/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

A prezentáció tulajdonságait képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Visszaadja az alkalmazás verzióját. |
| [getNameOfApplication()](#getNameOfApplication--) | Visszaadja vagy beállítja az alkalmazás nevét. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Visszaadja vagy beállítja az alkalmazás nevét. |
| [getCompany()](#getCompany--) | Visszaadja vagy beállítja a cég tulajdonságát. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Visszaadja vagy beállítja a cég tulajdonságát. |
| [getManager()](#getManager--) | Visszaadja vagy beállítja a menedzser tulajdonságát. |
| [setManager(String value)](#setManager-java.lang.String-) | Visszaadja vagy beállítja a menedzser tulajdonságát. |
| [getPresentationFormat()](#getPresentationFormat--) | Visszaadja vagy beállítja a prezentáció kívánt formátumát. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Visszaadja vagy beállítja a prezentáció kívánt formátumát. |
| [getSharedDoc()](#getSharedDoc--) | Meghatározza, hogy a prezentáció több ember között megosztott-e. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Meghatározza, hogy a prezentáció több ember között megosztott-e. |
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
| [getLastSavedTime()](#getLastSavedTime--) | Visszaadja a prezentáció legutóbbi módosításának dátumát. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Visszaadja a prezentáció legutóbbi módosításának dátumát. |
| [getLastPrinted()](#getLastPrinted--) | Visszaadja a prezentáció legutóbbi nyomtatásának dátumát. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Visszaadja a prezentáció legutóbbi nyomtatásának dátumát. |
| [getLastSavedBy()](#getLastSavedBy--) | Visszaadja vagy beállítja a prezentációt legutóbb módosító személy nevét. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Visszaadja vagy beállítja a prezentációt legutóbb módosító személy nevét. |
| [getRevisionNumber()](#getRevisionNumber--) | Visszaadja vagy beállítja a prezentáció revíziószámát. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Visszaadja vagy beállítja a prezentáció revíziószámát. |
| [getContentStatus()](#getContentStatus--) | Visszaadja vagy beállítja a prezentáció tartalomállapotát. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Visszaadja vagy beállítja a prezentáció tartalomállapotát. |
| [getContentType()](#getContentType--) | Visszaadja vagy beállítja a prezentáció tartalomtípusát. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Visszaadja vagy beállítja a prezentáció tartalomtípusát. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Visszaadja vagy beállítja a HyperlinkBase dokumentum tulajdonságát. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Visszaadja vagy beállítja a HyperlinkBase dokumentum tulajdonságát. |
| [getScaleCrop()](#getScaleCrop--) | Jelzi a dokumentum bélyegkép megjelenítési módját. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Jelzi a dokumentum bélyegkép megjelenítési módját. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Jelzi, hogy a dokumentum hivatkozásai naprakészek-e. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Jelzi, hogy a dokumentum hivatkozásai naprakészek-e. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Megadja, hogy egy vagy több hivatkozás ezt a részt kizárólag a termelő által frissítette. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Megadja, hogy egy vagy több hivatkozás ezt a részt kizárólag a termelő által frissítette. |
| [getSlides()](#getSlides--) | Megadja a prezentáció dokumentum diáinak teljes számát. |
| [getHiddenSlides()](#getHiddenSlides--) | Megadja a prezentáció rejtett diáinak számát. |
| [getNotes()](#getNotes--) | Megadja a megjegyzéseket tartalmazó diák számát. |
| [getParagraphs()](#getParagraphs--) | Megadja a dokumentumban található bekezdések teljes számát, ha alkalmazható. |
| [getWords()](#getWords--) | Megadja a dokumentumban található szavak teljes számát. |
| [getMultimediaClips()](#getMultimediaClips--) | Megadja a dokumentumban jelen lévő hang- vagy videoklipek teljes számát. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Megadja az egyes dokumentumrészek címét. |
| [getHeadingPairs()](#getHeadingPairs--) | Jelzi a dokumentumrészek csoportosítását és a csoportonkénti részek számát. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Visszaadja a gyűjteményben ténylegesen lévő egyedi tulajdonságok számát. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Visszaad egy egyedi tulajdonság nevét a megadott indexnél. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Eltávolít egy megadott névhez tartozó egyedi tulajdonságot. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Ellenőrzi egy megadott névű egyedi tulajdonság meglétét. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Visszaadja vagy beállítja a megadott névhez tartozó egyedi tulajdonságot. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Visszaadja vagy beállítja a megadott névhez tartozó egyedi tulajdonságot. |
| [clearCustomProperties()](#clearCustomProperties--) | Eltávolítja az összes egyedi tulajdonságot. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Törli és alapértelmezett értékekre állítja az összes beépített tulajdonságot. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Egy névvel jelölt logikai értéket kér le az egyedi tulajdonságok közül. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Egy névvel jelölt egész értéket kér le az egyedi tulajdonságok közül. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Egy névvel jelölt DateTime értéket kér le az egyedi tulajdonságok közül. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Egy névvel jelölt string értéket kér le az egyedi tulajdonságok közül. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Egy névvel jelölt float értéket kér le az egyedi tulajdonságok közül. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Egy névvel jelölt double értéket kér le az egyedi tulajdonságok közül. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Beállít egy névvel jelölt logikai egyedi tulajdonságot. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Beállít egy névvel jelölt egész egyedi tulajdonságot. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Beállít egy névvel jelölt DateTime egyedi tulajdonságot. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Beállít egy névvel jelölt string egyedi tulajdonságot. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Beállít egy névvel jelölt float egyedi tulajdonságot. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Beállít egy névvel jelölt double egyedi tulajdonságot. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Egy tömböt ad vissza az egyedi dokumentumtulajdonságok érzékenységi címkéiből (Microsoft Information Protection SDK Metadata). |

### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

Visszaadja az alkalmazás verzióját. Csak olvasható String.

--------------------

Ennek az elemnek a tartalma a XX.YYYY formátumban kell, hogy legyen, ahol az X és Y numerikus értékeket jelentenek; ellenkező esetben a dokumentum nem tekinthető szabványosnak. Az Aspose.Slides a verzióját a XX.YY.ZZ formátumban jeleníti meg, ahol: XX – fő verzió, YY – alverzió, ZZ – javítási verzió. Például a 23.0105 érték az Aspose.Slides 23.1.5 verzióját jelenti.

**Visszaad:**
java.lang.String

### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

Visszaadja vagy beállítja az alkalmazás nevét. Olvasás/írás String.

**Visszaad:**
java.lang.String

### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```

Visszaadja vagy beállítja az alkalmazás nevét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public abstract String getCompany()
```

Visszaadja vagy beállítja a cég tulajdonságát. Olvasás/írás String.

**Visszaad:**
java.lang.String

### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

Visszaadja vagy beállítja a cég tulajdonságát. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public abstract String getManager()
```

Visszaadja vagy beállítja a menedzser tulajdonságát. Olvasás/írás String.

**Visszaad:**
java.lang.String

### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

Visszaadja vagy beállítja a menedzser tulajdonságát. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

Visszaadja vagy beállítja a prezentáció kívánt formátumát. Olvasás/írás String.

**Visszaad:**
java.lang.String

### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

Visszaadja vagy beállítja a prezentáció kívánt formátumát. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

Meghatározza, hogy a prezentáció több ember között megosztott-e. Olvasás/írás boolean.

**Visszaad:**
boolean

### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

Meghatározza, hogy a prezentáció több ember között megosztott-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

Visszaadja vagy beállítja egy alkalmazás sablonját. Olvasás/írás String.

**Visszaad:**
java.lang.String

### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```

Visszaadja vagy beállítja egy alkalmazás sablonját. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```

A prezentáció teljes szerkesztési ideje. Olvasás/írás double.

**Visszaad:**
double

### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

A prezentáció teljes szerkesztési ideje. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

Visszaadja vagy beállítja a prezentáció címét. Olvasás/írás String.

**Visszaad:**
java.lang.String

### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

Visszaadja vagy beállítja a prezentáció címét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public abstract String getSubject()
```

Visszaadja vagy beállítja a prezentáció tárgyát. Olvasás/írás String.

**Visszaad:**
java.lang.String

### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```

Visszaadja vagy beállítja a prezentáció tárgyát. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```

Visszaadja vagy beállítja a prezentáció szerzőjét. Olvasás/írás String.

**Visszaad:**
java.lang.String

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```

Visszaadja vagy beállítja a prezentáció szerzőjét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```

Visszaadja vagy beállítja a prezentáció kulcsszavait. Olvasás/írás String.

**Visszaad:**
java.lang.String

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

Visszaadja vagy beállítja a prezentáció kulcsszavait. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract String getComments()
```

Visszaadja vagy beállítja a prezentáció megjegyzéseit. Olvasás/írás String.

**Visszaad:**
java.lang.String

### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

Visszaadja vagy beállítja a prezentáció megjegyzéseit. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public abstract String getCategory()
```

Visszaadja vagy beállítja a prezentáció kategóriáját. Olvasás/írás String.

**Visszaad:**
java.lang.String

### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```

Visszaadja vagy beállítja a prezentáció kategóriáját. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
| érték | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Visszaadja a prezentáció létrehozásának dátumát. Az értékek UTC-ben vannak. Olvasás/írás java.util.Date.

**Visszatérési érték:**  
java.util.Date

### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Visszaadja a prezentáció létrehozásának dátumát. Az értékek UTC-ben vannak. Olvasás/írás java.util.Date.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```

Visszaadja a prezentáció legutóbbi módosításának dátumát. Az értékek UTC-ben vannak. P Olvasás csak a Presentation.DocumentProperties esetén (mert a mentési folyamat során belsőleg frissül). Változtatható a [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) metódussal visszaadott DocumentProperties példányon keresztül. Lásd a példát a [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) metódus összefoglalójában.

**Visszatérési érték:**  
java.util.Date

### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

Visszaadja a prezentáció legutóbbi módosításának dátumát. Az értékek UTC-ben vannak. P Olvasás csak a Presentation.DocumentProperties esetén (mert a mentési folyamat során belsőleg frissül). Változtatható a [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) metódussal visszaadott DocumentProperties példányon keresztül. Lásd a példát a [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) metódus összefoglalójában.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```

Visszaadja a prezentáció legutóbbi nyomtatásának dátumát. Olvasás/írás java.util.Date.

**Visszatérési érték:**  
java.util.Date

### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```

Visszaadja a prezentáció legutóbbi nyomtatásának dátumát. Olvasás/írás java.util.Date.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```

Visszaadja vagy beállítja az utolsó módosító személy nevét. Olvasás/írás String.

**Visszatérési érték:**  
java.lang.String

### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

Visszaadja vagy beállítja az utolsó módosító személy nevét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```

Visszaadja vagy beállítja a prezentáció verziószámát. Olvasás/írás int.

**Visszatérési érték:**  
int

### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```

Visszaadja vagy beállítja a prezentáció verziószámát. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```

Visszaadja vagy beállítja a prezentáció tartalomállapotát. Olvasás/írás String.

**Visszatérési érték:**  
java.lang.String

### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```

Visszaadja vagy beállítja a prezentáció tartalomállapotát. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Visszaadja vagy beállítja a prezentáció tartalomtípusát. Olvasás/írás String.

**Visszatérési érték:**  
java.lang.String

### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```

Visszaadja vagy beállítja a prezentáció tartalomtípusát. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```

Visszaadja vagy beállítja a HyperlinkBase dokumentumtulajdonságot. Olvasás/írás String.

**Visszatérési érték:**  
java.lang.String

### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```

Visszaadja vagy beállítja a HyperlinkBase dokumentumtulajdonságot. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```

Jelzi a dokumentum bélyegképének megjelenítési módját. Állítsa ezt az elemet **true**-ra a bélyegkép skálázásának engedélyezéséhez a megjelenítőhöz. Állítsa **false**-ra a bélyegkép vágásának engedélyezéséhez, hogy csak a megjelenítőhöz illeszkedő részek jelenjenek meg. Olvasás/írás boolean.

**Visszatérési érték:**  
boolean

### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

Jelzi a dokumentum bélyegképének megjelenítési módját. Állítsa ezt az elemet **true**-ra a bélyegkép skálázásának engedélyezéséhez a megjelenítőhöz. Állítsa **false**-ra a bélyegkép vágásának engedélyezéséhez, hogy csak a megjelenítőhöz illeszkedő részek jelenjenek meg. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```

Jelzi, hogy a dokumentumban található hiperhivatkozások naprakészek-e. Állítsa ezt az elemet **true**-ra, ha a hiperhivatkozások frissítve vannak. Állítsa **false**-ra, ha a hiperhivatkozások elavultak. Olvasás/írás boolean.

**Visszatérési érték:**  
boolean

### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

Jelzi, hogy a dokumentumban található hiperhivatkozások naprakészek-e. Állítsa ezt az elemet **true**-ra, ha a hiperhivatkozások frissítve vannak. Állítsa **false**-ra, ha a hiperhivatkozások elavultak. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

Megadja, hogy egy vagy több hiperhivatkozás ebben a részben kizárólag egy termelő által lett frissítve. A következő termelő, aki megnyitja a dokumentumot, frissíti a hiperhivatkozáskapcsolatokat az ebben a részben megadott új hiperhivatkozásokkal. Olvasás/írás boolean.

**Visszatérési érték:**  
boolean

### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```

Megadja, hogy egy vagy több hiperhivatkozás ebben a részben kizárólag egy termelő által lett frissítve. A következő termelő, aki megnyitja a dokumentumot, frissíti a hiperhivatkozáskapcsolatokat az ebben a részben megadott új hiperhivatkozásokkal. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

Megadja a prezentáció dokumentumban lévő diák teljes számát. Csak olvasható int.

**Visszatérési érték:**  
int

### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

Megadja a skryté diák számát a prezentáció dokumentumban. Csak olvasható int.

**Visszatérési érték:**  
int

### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

Megadja a megjegyzéseket tartalmazó diák számát a prezentációban. Csak olvasható int.

**Visszatérési érték:**  
int

### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```

Megadja a dokumentumban (ha alkalmazható) található bekezdések teljes számát. Csak olvasható int.

**Visszatérési érték:**  
int

### getWords() {#getWords--}
```
public abstract int getWords()
```

Megadja a dokumentumban található szavak teljes számát. Csak olvasható int.

**Visszatérési érték:**  
int

### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

Megadja a dokumentumban lévő hang- vagy videoklipek teljes számát. Csak olvasható int.

**Visszatérési érték:**  
int

### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

Megadja minden dokumentumrész címét. Ezek a részek nem dokumentum részek, hanem a dokumentum szakaszainak koncepcionális ábrázolásai. Csak olvasható String[].

**Visszatérési érték:**  
java.lang.String[]

### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

Jelzi a dokumentumrészek csoportosítását és a részek számát minden csoportban. Csak olvasható IHeadingPair[].

**Visszatérési érték:**  
com.aspose.slides.IHeadingPair[]

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

Visszaadja a gyűjteményben ténylegesen megtalálható egyéni tulajdonságok számát. Csak olvasható int.

**Visszatérési érték:**  
int

### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```

Visszaad egy egyéni tulajdonság nevét a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A lekérdezni kívánt egyéni tulajdonság nulla alapú indexe. |

**Visszatérési érték:**  
java.lang.String - Egyéni tulajdonság neve a megadott indexen.

### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```

Eltávolít egy megadott névhez kapcsolódó egyéni tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | Az eltávolítandó egyéni tulajdonság neve. |

**Visszatérési érték:**  
boolean - Igaz, ha a tulajdonságot eltávolították, hamis egyébként.

### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```

Ellenőrzi egy megadott névhez tartozó egyéni tulajdonság jelenlétét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | Az ellenőrzendő egyéni tulajdonság neve. |

**Visszatérési érték:**  
boolean - Igaz, ha a tulajdonság létezik, hamis egyébként.

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```

Visszaadja vagy beállítja a megadott névhez kapcsolódó egyéni tulajdonságot. Olvasás/írás Object.

--------------------

Az érték lehet **int**, **float**, **double**, **String**, **boolean** vagy **Date**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String |  |

**Visszatérési érték:**  
java.lang.Object

### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```

Visszaadja vagy beállítja a megadott névhez kapcsolódó egyéni tulajdonságot. Olvasás/írás Object.

--------------------

Az érték lehet **int**, **float**, **double**, **String**, **boolean** vagy **Date**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### clearCustomProperties() {#clearCustomProperties--}
```
public abstract void clearCustomProperties()
```

Eltávolítja az összes egyéni tulajdonságot.

### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract void clearBuiltInProperties()
```

Törli és alapértelmezett értékekkel tölti fel az összes beépített tulajdonságot.

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

Lekéri a megnevezett logikai értéket az egyéni tulajdonságokból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A lekérdezni kívánt egyéni tulajdonság neve |
| value | boolean[] | Egyéni tulajdonság értéke |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

Lekéri a megnevezett egész értéket az egyéni tulajdonságokból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A lekérdezni kívánt egyéni tulajdonság neve |
| value | int[] | Egyéni tulajdonság értéke |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

Lekéri a megnevezett DateTime értéket az egyéni tulajdonságokból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A lekérdezni kívánt egyéni tulajdonság neve |
| value | java.util.Date[] | Egyéni tulajdonság értéke |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

Lekéri a megnevezett szöveges értéket az egyéni tulajdonságokból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A lekérdezni kívánt egyéni tulajdonság neve |
| value | java.lang.String[] | Egyéni tulajdonság értéke |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

Lekéri a megnevezett lebegőpontos értéket az egyéni tulajdonságokból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A lekérdezni kívánt egyéni tulajdonság neve |
| value | float[] | Egyéni tulajdonság értéke |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```

Lekéri a megnevezett dupla pontosságú értéket az egyéni tulajdonságokból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A lekérdezni kívánt egyéni tulajdonság neve |
| value | double[] | Egyéni tulajdonság értéke |
| név | java.lang.String | A lekérdezendő egyéni tulajdonság neve. |
| érték | double[] | Egyéni tulajdonság értéke |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

Beállít egy megnevezett logikai egyéni tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A beállítandó egyéni tulajdonság neve |
| value | boolean | Egyéni tulajdonság értéke |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

Beállít egy megnevezett egész egyéni tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A beállítandó egyéni tulajdonság neve |
| value | int | Egyéni tulajdonság értéke |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

Beállít egy megnevezett DateTime egyéni tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A beállítandó egyéni tulajdonság neve |
| value | java.util.Date | Egyéni tulajdonság értéke |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

Beállít egy megnevezett szöveges egyéni tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A beállítandó egyéni tulajdonság neve |
| value | java.lang.String | Egyéni tulajdonság értéke |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

Beállít egy megnevezett lebegőpontos egyéni tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A beállítandó egyéni tulajdonság neve |
| value | float | Egyéni tulajdonság értéke |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

Beállít egy megnevezett dupla pontosságú egyéni tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A beállítandó egyéni tulajdonság neve |
| value | double | Egyéni tulajdonság értéke |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

Lekér egy tömböt érzékenységi címkékkel a dokumentum egyéni tulajdonságaiból (Microsoft Information Protection SDK Metadata).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Szerezze meg az érzékenységi címkéket az egyedi dokumentumtulajdonságokból
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Címke hozzáadása a gyűjteményhez
>          // Itt ellenőrizhet a címke információk érvényességét (a címke elérhető, stb.)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
com.aspose.slides.ISensitivityLabel[]