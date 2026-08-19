---
title: IDocumentProperties
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje vlastnosti prezentace.
type: docs
url: /cs/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

Reprezentuje vlastnosti prezentace.
## Metody

| Metoda | Popis |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Vrací verzi aplikace. |
| [getNameOfApplication()](#getNameOfApplication--) | Vrací nebo nastavuje název aplikace. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Vrací nebo nastavuje název aplikace. |
| [getCompany()](#getCompany--) | Vrací nebo nastavuje vlastnost company. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Vrací nebo nastavuje vlastnost company. |
| [getManager()](#getManager--) | Vrací nebo nastavuje vlastnost manager. |
| [setManager(String value)](#setManager-java.lang.String-) | Vrací nebo nastavuje vlastnost manager. |
| [getPresentationFormat()](#getPresentationFormat--) | Vrací nebo nastavuje zamýšlený formát prezentace. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Vrací nebo nastavuje zamýšlený formát prezentace. |
| [getSharedDoc()](#getSharedDoc--) | Určuje, zda je prezentace sdílena mezi více lidmi. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Určuje, zda je prezentace sdílena mezi více lidmi. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Vrací nebo nastavuje šablonu aplikace. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Vrací nebo nastavuje šablonu aplikace. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Celkový čas úprav prezentace. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Celkový čas úprav prezentace. |
| [getTitle()](#getTitle--) | Vrací nebo nastavuje název prezentace. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Vrací nebo nastavuje název prezentace. |
| [getSubject()](#getSubject--) | Vrací nebo nastavuje předmět prezentace. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Vrací nebo nastavuje předmět prezentace. |
| [getAuthor()](#getAuthor--) | Vrací nebo nastavuje autora prezentace. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Vrací nebo nastavuje autora prezentace. |
| [getKeywords()](#getKeywords--) | Vrací nebo nastavuje klíčová slova prezentace. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Vrací nebo nastavuje klíčová slova prezentace. |
| [getComments()](#getComments--) | Vrací nebo nastavuje komentáře prezentace. |
| [setComments(String value)](#setComments-java.lang.String-) | Vrací nebo nastavuje komentáře prezentace. |
| [getCategory()](#getCategory--) | Vrací nebo nastavuje kategorii prezentace. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Vrací nebo nastavuje kategorii prezentace. |
| [getCreatedTime()](#getCreatedTime--) | Vrací datum, kdy byla prezentace vytvořena. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Vrací datum, kdy byla prezentace vytvořena. |
| [getLastSavedTime()](#getLastSavedTime--) | Vrací datum, kdy byla prezentace naposledy upravena. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Vrací datum, kdy byla prezentace naposledy upravena. |
| [getLastPrinted()](#getLastPrinted--) | Vrací datum, kdy byla prezentace naposledy vytištěna. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Vrací datum, kdy byla prezentace naposledy vytištěna. |
| [getLastSavedBy()](#getLastSavedBy--) | Vrací nebo nastavuje jméno poslední osoby, která prezentaci upravila. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Vrací nebo nastavuje jméno poslední osoby, která prezentaci upravila. |
| [getRevisionNumber()](#getRevisionNumber--) | Vrací nebo nastavuje číslo revize prezentace. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Vrací nebo nastavuje číslo revize prezentace. |
| [getContentStatus()](#getContentStatus--) | Vrací nebo nastavuje stav obsahu prezentace. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Vrací nebo nastavuje stav obsahu prezentace. |
| [getContentType()](#getContentType--) | Vrací nebo nastavuje typ obsahu prezentace. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Vrací nebo nastavuje typ obsahu prezentace. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Vrací nebo nastavuje vlastnost HyperlinkBase dokumentu. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Vrací nebo nastavuje vlastnost HyperlinkBase dokumentu. |
| [getScaleCrop()](#getScaleCrop--) | Udává režim zobrazení miniatury dokumentu. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Udává režim zobrazení miniatury dokumentu. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Udává, zda jsou hypertextové odkazy v dokumentu aktuální. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Udává, zda jsou hypertextové odkazy v dokumentu aktuální. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Určuje, že jeden nebo více hypertextových odkazů v této části byly aktualizovány výhradně v této části výrobcem. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Určuje, že jeden nebo více hypertextových odkazů v této části byly aktualizovány výhradně v této části výrobcem. |
| [getSlides()](#getSlides--) | Určuje celkový počet snímků v dokumentu prezentace. |
| [getHiddenSlides()](#getHiddenSlides--) | Určuje počet skrytých snímků v dokumentu prezentace. |
| [getNotes()](#getNotes--) | Určuje počet snímků v prezentaci obsahujících poznámky. |
| [getParagraphs()](#getParagraphs--) | Určuje celkový počet odstavců nalezených v dokumentu, pokud je to použitelné. |
| [getWords()](#getWords--) | Určuje celkový počet slov obsažených v dokumentu. |
| [getMultimediaClips()](#getMultimediaClips--) | Určuje celkový počet zvukových nebo video klipů, které jsou v dokumentu přítomny. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Určuje název každé části dokumentu. |
| [getHeadingPairs()](#getHeadingPairs--) | Udává seskupení částí dokumentu a počet částí v každé skupině. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Vrací počet vlastních vlastností skutečně obsažených v kolekci. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Vrací název vlastní vlastnosti na zadaném indexu. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Odstraňuje vlastní vlastnost spojenou se zadaným názvem. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Kontroluje přítomnost vlastní vlastnosti se zadaným názvem. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Vrací nebo nastavuje vlastní vlastnost spojenou se zadaným názvem. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Vrací nebo nastavuje vlastní vlastnost spojenou se zadaným názvem. |
| [clearCustomProperties()](#clearCustomProperties--) | Odstraňuje všechny vlastní vlastnosti. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Vymaže a nastaví výchozí hodnoty pro všechny vestavěné vlastnosti. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Získá pojmenovanou hodnotu boolean z vlastních vlastností. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Získá pojmenovanou celočíselnou hodnotu z vlastních vlastností. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Získá pojmenovanou hodnotu DateTime z vlastních vlastností. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Získá pojmenovanou řetězcovou hodnotu z vlastních vlastností. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Získá pojmenovanou hodnotu float z vlastních vlastností. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Získá pojmenovanou hodnotu double z vlastních vlastností. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Nastaví pojmenovanou boolean vlastní vlastnost. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Nastaví pojmenovanou celočíselnou vlastní vlastnost. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Nastaví pojmenovanou DateTime vlastní vlastnost. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Nastaví pojmenovanou řetězcovou vlastní vlastnost. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Nastaví pojmenovanou float vlastní vlastnost. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Nastaví pojmenovanou double vlastní vlastnost. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Získá pole štítků citlivosti z vlastních vlastností dokumentu (Microsoft Information Protection SDK Metadata). |

### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

Vrací verzi aplikace. Pouze pro čtení String.

--------------------

Obsah tohoto elementu má mít tvar XX.YYYY, kde X a Y představují číselné hodnoty; jinak bude dokument považován za nevyhovující. Aspose.Slides reprezentuje svou verzi ve formátu XX.YY.ZZ, kde: XX – hlavní verze, YY – vedlejší verze, ZZ – oprava. Například hodnota 23.0105 znamená verzi Aspose.Slides 23.1.5.

**Vrací:**
java.lang.String

### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

Vrací nebo nastavuje název aplikace. Čtení/Zápis String.

**Vrací:**
java.lang.String

### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```

Vrací nebo nastavuje název aplikace. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public abstract String getCompany()
```

Vrací nebo nastavuje vlastnost company. Čtení/Zápis String.

**Vrací:**
java.lang.String

### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

Vrací nebo nastavuje vlastnost company. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public abstract String getManager()
```

Vrací nebo nastavuje vlastnost manager. Čtení/Zápis String.

**Vrací:**
java.lang.String

### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

Vrací nebo nastavuje vlastnost manager. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

Vrací nebo nastavuje zamýšlený formát prezentace. Čtení/Zápis String.

**Vrací:**
java.lang.String

### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

Vrací nebo nastavuje zamýšlený formát prezentace. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

Určuje, zda je prezentace sdílena mezi více lidmi. Čtení/Zápis boolean.

**Vrací:**
boolean

### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

Určuje, zda je prezentace sdílena mezi více lidmi. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

Vrací nebo nastavuje šablonu aplikace. Čtení/Zápis String.

**Vrací:**
java.lang.String

### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```

Vrací nebo nastavuje šablonu aplikace. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```

Celkový čas úprav prezentace. Čtení/Zápis double.

**Vrací:**
double

### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

Celkový čas úprav prezentace. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

Vrací nebo nastavuje název prezentace. Čtení/Zápis String.

**Vrací:**
java.lang.String

### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

Vrací nebo nastavuje název prezentace. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public abstract String getSubject()
```

Vrací nebo nastavuje předmět prezentace. Čtení/Zápis String.

**Vrací:**
java.lang.String

### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```

Vrací nebo nastavuje předmět prezentace. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```

Vrací nebo nastavuje autora prezentace. Čtení/Zápis String.

**Vrací:**
java.lang.String

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```

Vrací nebo nastavuje autora prezentace. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```

Vrací nebo nastavuje klíčová slova prezentace. Čtení/Zápis String.

**Vrací:**
java.lang.String

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

Vrací nebo nastavuje klíčová slova prezentace. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract String getComments()
```

Vrací nebo nastavuje komentáře prezentace. Čtení/Zápis String.

**Vrací:**
java.lang.String

### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

Vrací nebo nastavuje komentáře prezentace. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public abstract String getCategory()
```

Vrací nebo nastavuje kategorii prezentace. Čtení/Zápis String.

**Vrací:**
java.lang.String

### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```

Vrací nebo nastavuje kategorii prezentace. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
| hodnota | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Vrací datum, kdy byla prezentace vytvořena. Hodnoty jsou v UTC. Čtení/Zápis java.util.Date.

**Vrací:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Vrací datum, kdy byla prezentace vytvořena. Hodnoty jsou v UTC. Čtení/Zápis java.util.Date.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hodnota | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```

Vrací datum, kdy byla prezentace naposledy upravena. Hodnoty jsou v UTC. Pouze pro čtení v případě Presentation.DocumentProperties (protože bude aktualizováno interně během ukládání objektu IPresentation). Lze změnit pomocí instance DocumentProperties vrácené metodou [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Viz příklad v metodě [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) souhrnu.

**Vrací:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

Vrací datum, kdy byla prezentace naposledy upravena. Hodnoty jsou v UTC. Pouze pro čtení v případě Presentation.DocumentProperties (protože bude aktualizováno interně během ukládání objektu IPresentation). Lze změnit pomocí instance DocumentProperties vrácené metodou [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Viz příklad v metodě [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) souhrnu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hodnota | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```

Vrací datum, kdy byla prezentace naposledy vytištěna. Čtení/Zápis java.util.Date.

**Vrací:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```

Vrací datum, kdy byla prezentace naposledy vytištěna. Čtení/Zápis java.util.Date.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hodnota | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```

Vrací nebo nastavuje jméno poslední osoby, která upravila prezentaci. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

Vrací nebo nastavuje jméno poslední osoby, která upravila prezentaci. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hodnota | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```

Vrací nebo nastavuje číslo revize prezentace. Čtení/Zápis int.

**Vrací:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```

Vrací nebo nastavuje číslo revize prezentace. Čtení/Zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hodnota | int |  |

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```

Vrací nebo nastavuje stav obsahu prezentace. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```

Vrací nebo nastavuje stav obsahu prezentace. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hodnota | java.lang.String |  |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Vrací nebo nastavuje typ obsahu prezentace. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```

Vrací nebo nastavuje typ obsahu prezentace. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hodnota | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```

Vrací nebo nastavuje dokumentovou vlastnost HyperlinkBase. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```

Vrací nebo nastavuje dokumentovou vlastnost HyperlinkBase. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hodnota | java.lang.String |  |

### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```

Určuje režim zobrazení náhledu dokumentu. Nastavte tento prvek na **true**, aby se umožnilo škálování náhledu dokumentu na displej. Nastavte tento prvek na **false**, aby se umožnilo oříznutí náhledu dokumentu, aby se zobrazily pouze části, které se vejdou na displej. Čtení/Zápis boolean.

**Vrací:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

Určuje režim zobrazení náhledu dokumentu. Nastavte tento prvek na **true**, aby se umožnilo škálování náhledu dokumentu na displej. Nastavte tento prvek na **false**, aby se umožnilo oříznutí náhledu dokumentu, aby se zobrazily pouze části, které se vejdou na displej. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hodnota | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```

Určuje, zda jsou hypertextové odkazy v dokumentu aktuální. Nastavte tento prvek na **true**, aby označoval, že odkazy jsou aktualizovány. Nastavte tento prvek na **false**, aby označoval, že odkazy jsou zastaralé. Čtení/Zápis boolean.

**Vrací:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

Určuje, zda jsou hypertextové odkazy v dokumentu aktuální. Nastavte tento prvek na **true**, aby označoval, že odkazy jsou aktualizovány. Nastavte tento prvek na **false**, aby označoval, že odkazy jsou zastaralé. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hodnota | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

Určuje, že jeden nebo více hypertextových odkazů v této části byly aktualizovány výhradně v této části producentem. Další producent, který otevře tento dokument, by měl aktualizovat vztahy odkazů novými odkazy uvedenými v této části. Čtení/Zápis boolean.

**Vrací:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```

Určuje, že jeden nebo více hypertextových odkazů v této části byly aktualizovány výhradně v této části producentem. Další producent, který otevře tento dokument, by měl aktualizovat vztahy odkazů novými odkazy uvedenými v této části. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hodnota | boolean |  |

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

Určuje celkový počet snímků v dokumentu prezentace. Pouze pro čtení int.

**Vrací:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

Určuje počet skrytých snímků v dokumentu prezentace. Pouze pro čtení int.

**Vrací:**
int
### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

Určuje počet snímků v prezentaci obsahujících poznámky. Pouze pro čtení int.

**Vrací:**
int
### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```

Určuje celkový počet odstavců nalezených v dokumentu, pokud jsou použitelné. Pouze pro čtení int.

**Vrací:**
int
### getWords() {#getWords--}
```
public abstract int getWords()
```

Určuje celkový počet slov obsažených v dokumentu. Pouze pro čtení int.

**Vrací:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

Určuje celkový počet zvukových nebo video klipů, které jsou v dokumentu. Pouze pro čtení int.

**Vrací:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

Určuje název každé části dokumentu. Tyto části nejsou skutečnými částmi dokumentu, ale konceptuálními reprezentacemi sekcí dokumentu. Pouze pro čtení String[].

**Vrací:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

Určuje seskupení částí dokumentu a počet částí v každé skupině. Pouze pro čtení IHeadingPair[].

**Vrací:**
com.aspose.slides.IHeadingPair[]
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

Vrací počet vlastních vlastností skutečně obsažených v kolekci. Pouze pro čtení int.

**Vrací:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```

Vrací název vlastní vlastnosti na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index vlastní vlastnosti, kterou chcete získat. |

**Vrací:**
java.lang.String - Název vlastní vlastnosti na zadaném indexu.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```

Odstraní vlastní vlastnost spojenou se zadaným názvem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| název | java.lang.String | Název vlastní vlastnosti, která se má odstranit. |

**Vrací:**
boolean - Vrátí true, pokud byla vlastnost odstraněna, jinak false.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```

Zkontroluje přítomnost vlastní vlastnosti se zadaným názvem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| název | java.lang.String | Název vlastní vlastnosti, kterou chcete zkontrolovat. |

**Vrací:**
boolean - Vrátí true, pokud vlastnost existuje, jinak false.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```

Vrací nebo nastavuje vlastní vlastnost spojenou se zadaným názvem. Čtení/Zápis Object.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| název | java.lang.String |  |

**Vrací:**
java.lang.Object

--------------------

Hodnota může být **int**, **float**, **double**, **String**, **boolean** nebo **Date**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| název | java.lang.String |  |

**Vrací:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```

Vrací nebo nastavuje vlastní vlastnost spojenou se zadaným názvem. Čtení/Zápis Object.

--------------------

Hodnota může být **int**, **float**, **double**, **String**, **boolean** nebo **Date**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| název | java.lang.String |  |
| hodnota | java.lang.Object |  |

### clearCustomProperties() {#clearCustomProperties--}
```
public abstract void clearCustomProperties()
```

Odstraňuje všechny vlastní vlastnosti.

### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract void clearBuiltInProperties()
```

Vymaže a nastaví výchozí hodnoty pro všechny vestavěné (builtIn) vlastnosti.

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

Získá pojmenovanou boolean hodnotu z vlastních vlastností.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| název | java.lang.String | Název vlastní vlastnosti, kterou chcete získat |
| hodnota | boolean[] | Hodnota vlastní vlastnosti |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

Získá pojmenovanou celočíselnou (integer) hodnotu z vlastních vlastností.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| název | java.lang.String | Název vlastní vlastnosti, kterou chcete získat |
| hodnota | int[] | Hodnota vlastní vlastnosti |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

Získá pojmenovanou hodnotu typu DateTime z vlastních vlastností.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| název | java.lang.String | Název vlastní vlastnosti, kterou chcete získat |
| hodnota | java.util.Date[] | Hodnota vlastní vlastnosti |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

Získá pojmenovanou řetězcovou hodnotu z vlastních vlastností.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| název | java.lang.String | Název vlastní vlastnosti, kterou chcete získat |
| hodnota | java.lang.String[] | Hodnota vlastní vlastnosti |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

Získá pojmenovanou float hodnotu z vlastních vlastností.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| název | java.lang.String | Název vlastní vlastnosti, kterou chcete získat |
| hodnota | float[] | Hodnota vlastní vlastnosti |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```

Získá pojmenovanou double hodnotu z vlastních vlastností.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| název | java.lang.String | Název vlastní vlastnosti, kterou chcete získat |
| hodnota | double[] | Hodnota vlastní vlastnosti |
| název | java.lang.String | Název vlastní vlastnosti k získání. |
| hodnota | double[] | Hodnota vlastní vlastnosti |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

Nastaví pojmenovanou boolean vlastní vlastnost.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti k nastavení |
| value | boolean | Hodnota vlastní vlastnosti |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

Nastaví pojmenovanou integer vlastní vlastnost.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti k nastavení |
| value | int | Hodnota vlastní vlastnosti |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

Nastaví pojmenovanou DateTime vlastní vlastnost.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti k nastavení |
| value | java.util.Date | Hodnota vlastní vlastnosti |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

Nastaví pojmenovanou string vlastní vlastnost.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti k nastavení |
| value | java.lang.String | Hodnota vlastní vlastnosti |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

Nastaví pojmenovanou float vlastní vlastnost.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti k nastavení |
| value | float | Hodnota vlastní vlastnosti |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

Nastaví pojmenovanou double vlastní vlastnost.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti k nastavení |
| value | double | Hodnota vlastní vlastnosti |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

Získá pole štítků citlivosti z vlastních vlastností dokumentu (Microsoft Information Protection SDK Metadata).

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

**Vrací:**
com.aspose.slides.ISensitivityLabel[]