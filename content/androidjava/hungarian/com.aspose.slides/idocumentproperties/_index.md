---
title: IDocumentProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Represents properties of a presentation.
type: docs
url: /hu/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

Ábrázolja egy prezentáció tulajdonságait.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Visszaadja az alkalmazás verzióját. |
| [getNameOfApplication()](#getNameOfApplication--) | Visszaadja vagy beállítja az alkalmazás nevét. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Visszaadja vagy beállítja az alkalmazás nevét. |
| [getCompany()](#getCompany--) | Visszaadja vagy beállítja a cég tulajdonságát. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Visszaadja vagy beállítja a cég tulajdonságát. |
| [getManager()](#getManager--) | Visszaadja vagy beállítja a vezető tulajdonságát. |
| [setManager(String value)](#setManager-java.lang.String-) | Visszaadja vagy beállítja a vezető tulajdonságát. |
| [getPresentationFormat()](#getPresentationFormat--) | Visszaadja vagy beállítja a prezentáció kívánt formátumát. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Visszaadja vagy beállítja a prezentáció kívánt formátumát. |
| [getSharedDoc()](#getSharedDoc--) | Megállapítja, hogy a prezentáció több ember között van-e megosztva. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Megállapítja, hogy a prezentáció több ember között van-e megosztva. |
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
| [getLastSavedBy()](#getLastSavedBy--) | Visszaadja vagy beállítja az utolsó módosítót. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Visszaadja vagy beállítja az utolsó módosítót. |
| [getRevisionNumber()](#getRevisionNumber--) | Visszaadja vagy beállítja a prezentáció revíziószámát. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Visszaadja vagy beállítja a prezentáció revíziószámát. |
| [getContentStatus()](#getContentStatus--) | Visszaadja vagy beállítja a prezentáció tartalomállapotát. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Visszaadja vagy beállítja a prezentáció tartalomállapotát. |
| [getContentType()](#getContentType--) | Visszaadja vagy beállítja a prezentáció tartalomtípusát. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Visszaadja vagy beállítja a prezentáció tartalomtípusát. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Visszaadja vagy beállítja a HyperlinkBase dokumentumtulajdonságot. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Visszaadja vagy beállítja a HyperlinkBase dokumentumtulajdonságot. |
| [getScaleCrop()](#getScaleCrop--) | Jelzi a dokumentum bélyegkép megjelenítési módját. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Jelzi a dokumentum bélyegkép megjelenítési módját. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Jelzi, hogy a dokumentum hiperhivatkozásai naprakészek-e. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Jelzi, hogy a dokumentum hiperhivatkozásai naprakészek-e. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Meghatározza, hogy egy vagy több hiperhivatkozás kizárólag ebben a részben került frissítésre egy gyártó által. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Meghatározza, hogy egy vagy több hiperhivatkozás kizárólag ebben a részben került frissítésre egy gyártó által. |
| [getSlides()](#getSlides--) | Megadja a prezentáció dokumentum összes diájának számát. |
| [getHiddenSlides()](#getHiddenSlides--) | Megadja a rejtett diák számát a prezentációban. |
| [getNotes()](#getNotes--) | Megadja a prezentációhoz jegyzetekkel ellátott diák számát. |
| [getParagraphs()](#getParagraphs--) | Megadja a dokumentumban megtalálható bekezdések teljes számát, ha alkalmazható. |
| [getWords()](#getWords--) | Megadja a dokumentumban található szavak teljes számát. |
| [getMultimediaClips()](#getMultimediaClips--) | Megadja a dokumentumban található hang- vagy videoklipek teljes számát. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Megadja minden dokumentumrész címét. |
| [getHeadingPairs()](#getHeadingPairs--) | Jelzi a dokumentumrészek csoportosítását és a csoportonkénti részek számát. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Visszaadja a gyűjteményben ténylegesen lévő egyedi tulajdonságok számát. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Visszaad egy egyedi tulajdonság nevét a megadott indexen. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Egy megadott névhez tartozó egyedi tulajdonság eltávolítása. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Ellenőrzi egy megadott névvel rendelkező egyedi tulajdonság meglétét. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Visszaadja vagy beállítja a megadott névhez tartozó egyedi tulajdonságot. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Visszaadja vagy beállítja a megadott névhez tartozó egyedi tulajdonságot. |
| [clearCustomProperties()](#clearCustomProperties--) | Minden egyedi tulajdonság eltávolítása. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Minden beépített tulajdonság törlése és alapértelmezett értékek beállítása. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Egy névhez tartozó bool érték lekérése az egyedi tulajdonságokból. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Egy névhez tartozó egész érték lekérése az egyedi tulajdonságokból. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Egy névhez tartozó DateTime érték lekérése az egyedi tulajdonságokból. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Egy névhez tartozó karakterlánc lekérése az egyedi tulajdonságokból. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Egy névhez tartozó float érték lekérése az egyedi tulajdonságokból. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Egy névhez tartozó double érték lekérése az egyedi tulajdonságokból. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Egy névhez tartozó bool egyedi tulajdonság beállítása. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Egy névhez tartozó egész egyedi tulajdonság beállítása. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Egy névhez tartozó DateTime egyedi tulajdonság beállítása. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Egy névhez tartozó karakterlánc egyedi tulajdonság beállítása. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Egy névhez tartozó float egyedi tulajdonság beállítása. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Egy névhez tartozó double egyedi tulajdonság beállítása. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Érzékenységi címkék tömbjének lekérése az egyedi dokumentumtulajdonságokból (Microsoft Information Protection SDK Metadata). |
### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

Visszaadja az alkalmazás verzióját. Csak olvasható String.

--------------------

Az elem tartalma a következő formátumban kell, hogy legyen: XX.YYYY, ahol az X és Y numerikus értékek; egyébként a dokumentum nem tekinthető szabványnak megfelelőnek. Az Aspose.Slides verzióját az XX.YY.ZZ formában ábrázolja, ahol: XX – főverzió, YY – alverzió, ZZ – javítóverzió. Például a 23.0105 érték a 23.1.5 verziót jelenti.

**Visszatér:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

Visszaadja vagy beállítja az alkalmazás nevét. Olvasás/írás String.

**Visszatér:**
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

**Visszatér:**
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

Visszaadja vagy beállítja a vezető tulajdonságát. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

Visszaadja vagy beállítja a vezető tulajdonságát. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

Visszaadja vagy beállítja a prezentáció kívánt formátumát. Olvasás/írás String.

**Visszatér:**
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

Megállapítja, hogy a prezentáció több ember között van-e megosztva. Olvasás/írás boolean.

**Visszatér:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

Megállapítja, hogy a prezentáció több ember között van-e megosztva. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

Visszaadja vagy beállítja egy alkalmazás sablonját. Olvasás/írás String.

**Visszatér:**
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

**Visszatér:**
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

**Visszatér:**
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

**Visszatér:**
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

**Visszatér:**
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

**Visszatér:**
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

**Visszatér:**
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

**Visszatér:**
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

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Visszaadja a prezentáció létrehozásának dátumát. Az értékek UTC-ben vannak. Olvasás/írás java.util.Date.

**Visszatér:**
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

Visszaadja a prezentáció legutóbbi módosításának dátumát. Az értékek UTC-ben vannak. Csak olvasható a Presentation.DocumentProperties esetén (mert a mentési folyamat során frissül belsőleg). Módosítható a [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) által visszaadott DocumentProperties példányon keresztül. Lásd a példát a [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) metódus összefoglalójában.

**Visszatér:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

Visszaadja a prezentáció legutóbbi módosításának dátumát. Az értékek UTC-ben vannak. Csak olvasható a Presentation.DocumentProperties esetén (mert a mentési folyamat során frissül belsőleg). Módosítható a [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) által visszaadott DocumentProperties példányon keresztül. Lásd a példát a [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) metódus összefoglalójában.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```

Visszaadja a prezentáció legutóbbi nyomtatásának dátumát. Olvasás/írás java.util.Date.

**Visszatér:**
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

Visszaadja vagy beállítja az utolsó módosító nevét. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

Visszaadja vagy beállítja az utolsó módosító nevét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```

Visszaadja vagy beállítja a prezentáció revíziószámát. Olvasás/írás int.

**Visszatér:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```

Visszaadja vagy beállítja a prezentáció revíziószámát. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```

Visszaadja vagy beállítja a prezentáció tartalomállapotát. Olvasás/írás String.

**Visszatér:**
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

**Visszatér:**
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

**Visszatér:**
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

Jelzi a dokumentum bélyegkép megjelenítési módját. Állítsd ezt az elemet **true**-ra a bélyegkép méretezésének engedélyezéséhez a kijelzőhöz. Állítsd **false**-ra a bélyegkép vágásához, hogy csak a kijelzőnek megfelelő részek jelenjenek meg. Olvasás/írás boolean.

**Visszatér:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

Jelzi a dokumentum bélyegkép megjelenítési módját. Állítsd ezt az elemet **true**-ra a bélyegkép méretezésének engedélyezéséhez a kijelzőhöz. Állítsd **false**-ra a bélyegkép vágásához, hogy csak a kijelzőnek megfelelő részek jelenjenek meg. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```

Jelzi, hogy egy dokumentum hiperhivatkozásai naprakészek-e. Állítsd **true**-ra a frissített hiperhivatkozások jelzéséhez. Állítsd **false**-ra a elavult hiperhivatkozások jelzéséhez. Olvasás/írás boolean.

**Visszatér:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

Jelzi, hogy egy dokumentum hiperhivatkozásai naprakészek-e. Állítsd **true**-ra a frissített hiperhivatkozások jelzéséhez. Állítsd **false**-ra a elavult hiperhivatkozások jelzéséhez. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

Meghatározza, hogy egy vagy több hiperhivatkozás kizárólag ebben a részben került frissítésre egy gyártó által. A következő gyártó, amely megnyitja a dokumentumot, frissíti a hiperhivatkozási kapcsolatokat a részben megadott új hiperhivatkozásokkal. Olvasás/írás boolean.

**Visszatér:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```

Meghatározza, hogy egy vagy több hiperhivatkozás kizárólag ebben a részben került frissítésre egy gyártó által. A következő gyártó, amely megnyitja a dokumentumot, frissíti a hiperhivatkozási kapcsolatokat a részben megadott új hiperhivatkozásokkal. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

Megadja a prezentáció dokumentumban szereplő diák teljes számát. Csak olvasható int.

**Visszatér:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

Megadja a rejtett diák számát a prezentációban. Csak olvasható int.

**Visszatér:**
int
### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

Megadja a prezentációban jegyzetekkel ellátott diák számát. Csak olvasható int.

**Visszatér:**
int
### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```

Megadja a dokumentumban megtalálható bekezdések teljes számát, ha alkalmazható. Csak olvasható int.

**Visszatér:**
int
### getWords() {#getWords--}
```
public abstract int getWords()
```

Megadja a dokumentumban található szavak teljes számát. Csak olvasható int.

**Visszatér:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

Megadja a dokumentumban jelenlévő hang- vagy videoklipek teljes számát. Csak olvasható int.

**Visszatér:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

Megadja minden dokumentumrész címét. Ezek a részek nem dokumentumrészek, hanem a dokumentum szakaszainak elképzelt reprezentációi. Csak olvasható String[].

**Visszatér:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

Jelzi a dokumentumrészek csoportosítását és a csoportonkénti részek számát. Csak olvasható IHeadingPair[].

**Visszatér:**
com.aspose.slides.IHeadingPair[]
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

Visszaadja a gyűjteményben ténylegesen lévő egyedi tulajdonságok számát. Csak olvasható int.

**Visszatér:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```

Visszaad egy egyedi tulajdonság nevét a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullaalapú index a lekérni kívánt egyedi tulajdonsághoz. |

**Visszatér:**
java.lang.String - Egyedi tulajdonság név a megadott indexen.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```

Eltávolít egy megadott névhez tartozó egyedi tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | Az eltávolítandó egyedi tulajdonság neve. |

**Visszatér:**
boolean - True, ha a tulajdonságot eltávolították, egyébként false.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```

Ellenőrzi egy megadott névvel rendelkező egyedi tulajdonság meglétét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | Az ellenőrizendő egyedi tulajdonság neve. |

**Visszatér:**
boolean - True, ha a tulajdonság létezik, egyébként false.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```

Visszaadja vagy beállítja a megadott névhez tartozó egyedi tulajdonságot. Olvasás/írás Object.

--------------------

Az érték lehet **int**, **float**, **double**, **String**, **boolean** vagy **Date**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String |  |

**Visszatér:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```

Visszaadja vagy beállítja a megadott névhez tartozó egyedi tulajdonságot. Olvasás/írás Object.

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

Eltávolít minden egyedi tulajdonságot.
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract void clearBuiltInProperties()
```

Törli és alapértelmezett értékeket állít be minden beépített tulajdonsághoz.
### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

Egy névhez tartozó bool érték lekérése az egyedi tulajdonságokból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A lekérni kívánt egyedi tulajdonság neve |
| value | boolean[] | Egyedi tulajdonság értéke |
### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

Egy névhez tartozó egész érték lekérése az egyedi tulajdonságokból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A lekérni kívánt egyedi tulajdonság neve |
| value | int[] | Egyedi tulajdonság értéke |
### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

Egy névhez tartozó DateTime érték lekérése az egyedi tulajdonságokból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A lekérni kívánt egyedi tulajdonság neve |
| value | java.util.Date[] | Egyedi tulajdonság értéke |
### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

Egy névhez tartozó karakterlánc lekérése az egyedi tulajdonságokból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A lekérni kívánt egyedi tulajdonság neve |
| value | java.lang.String[] | Egyedi tulajdonság értéke |
### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

Egy névhez tartozó float érték lekérése az egyedi tulajdonságokból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A lekérni kívánt egyedi tulajdonság neve |
| value | float[] | Egyedi tulajdonság értéke |
### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```

Egy névhez tartozó double érték lekérése az egyedi tulajdonságokból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A lekérni kívánt egyedi tulajdonság neve. |
| value | double[] | Egyedi tulajdonság értéke |
### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

Egy névhez tartozó bool egyedi tulajdonság beállítása.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A beállítandó egyedi tulajdonság neve |
| value | boolean | Egyedi tulajdonság értéke |
### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

Egy névhez tartozó egész egyedi tulajdonság beállítása.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A beállítandó egyedi tulajdonság neve |
| value | int | Egyedi tulajdonság értéke |
### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

Egy névhez tartozó DateTime egyedi tulajdonság beállítása.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A beállítandó egyedi tulajdonság neve |
| value | java.util.Date | Egyedi tulajdonság értéke |
### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

Egy névhez tartozó karakterlánc egyedi tulajdonság beállítása.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A beállítandó egyedi tulajdonság neve |
| value | java.lang.String | Egyedi tulajdonság értéke |
### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

Egy névhez tartozó float egyedi tulajdonság beállítása.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A beállítandó egyedi tulajdonság neve |
| value | float | Egyedi tulajdonság értéke |
### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

Egy névhez tartozó double egyedi tulajdonság beállítása.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A beállítandó egyedi tulajdonság neve |
| value | double | Egyedi tulajdonság értéke |
### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

Egy érzékenységi címkék tömbjének lekérése az egyedi dokumentumtulajdonságokból (Microsoft Information Protection SDK Metadata).

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

**Visszatér:**
com.aspose.slides.ISensitivityLabel[]