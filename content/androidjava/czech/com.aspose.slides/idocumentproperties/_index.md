---
title: IDocumentProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Represents properties of a presentation.
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
| [getCompany()](#getCompany--) | Vrací nebo nastavuje vlastnost společnosti. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Vrací nebo nastavuje vlastnost společnosti. |
| [getManager()](#getManager--) | Vrací nebo nastavuje vlastnost manažera. |
| [setManager(String value)](#setManager-java.lang.String-) | Vrací nebo nastavuje vlastnost manažera. |
| [getPresentationFormat()](#getPresentationFormat--) | Vrací nebo nastavuje zamýšlený formát prezentace. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Vrací nebo nastavuje zamýšlený formát prezentace. |
| [getSharedDoc()](#getSharedDoc--) | Určuje, zda je prezentace sdílena mezi více lidmi. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Určuje, zda je prezentace sdílena mezi více lidmi. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Vrací nebo nastavuje šablonu aplikace. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Vrací nebo nastavuje šablonu aplikace. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Celkový čas úprav prezentace. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Celkový čas úprav prezentace. |
| [getTitle()](#getTitle--) | Vrací název prezentace. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Vrací název prezentace. |
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
| [getCreatedTime()](#getCreatedTime--) | Vrací datum vytvoření prezentace. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Vrací datum vytvoření prezentace. |
| [getLastSavedTime()](#getLastSavedTime--) | Vrací datum poslední úpravy prezentace. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Vrací datum poslední úpravy prezentace. |
| [getLastPrinted()](#getLastPrinted--) | Vrací datum posledního tisku prezentace. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Vrací datum posledního tisku prezentace. |
| [getLastSavedBy()](#getLastSavedBy--) | Vrací nebo nastavuje jméno poslední osoby, která prezentaci upravila. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Vrací nebo nastavuje jméno poslední osoby, která prezentaci upravila. |
| [getRevisionNumber()](#getRevisionNumber--) | Vrací nebo nastavuje číslo revize prezentace. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Vrací nebo nastavuje číslo revize prezentace. |
| [getContentStatus()](#getContentStatus--) | Vrací nebo nastavuje stav obsahu prezentace. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Vrací nebo nastavuje stav obsahu prezentace. |
| [getContentType()](#getContentType--) | Vrací nebo nastavuje typ obsahu prezentace. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Vrací nebo nastavuje typ obsahu prezentace. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Vrací nebo nastavuje vlastnost dokumentu HyperlinkBase. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Vrací nebo nastavuje vlastnost dokumentu HyperlinkBase. |
| [getScaleCrop()](#getScaleCrop--) | Udává režim zobrazení miniatury dokumentu. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Udává režim zobrazení miniatury dokumentu. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Udává, zda jsou hypertextové odkazy v dokumentu aktuální. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Udává, zda jsou hypertextové odkazy v dokumentu aktuální. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Specifikuje, že jeden nebo více hypertextových odkazů v této části byly aktualizovány výhradně v této části výrobcem. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Specifikuje, že jeden nebo více hypertextových odkazů v této části byly aktualizovány výhradně v této části výrobcem. |
| [getSlides()](#getSlides--) | Udává celkový počet snímků v dokumentu prezentace. |
| [getHiddenSlides()](#getHiddenSlides--) | Udává počet skrytých snímků v dokumentu prezentace. |
| [getNotes()](#getNotes--) | Udává počet snímků v prezentaci obsahujících poznámky. |
| [getParagraphs()](#getParagraphs--) | Udává celkový počet odstavců nalezených v dokumentu, pokud je to relevantní. |
| [getWords()](#getWords--) | Udává celkový počet slov v dokumentu. |
| [getMultimediaClips()](#getMultimediaClips--) | Udává celkový počet zvukových nebo video klipů, které jsou v dokumentu. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Udává název každé části dokumentu. |
| [getHeadingPairs()](#getHeadingPairs--) | Udává seskupení částí dokumentu a počet částí v každé skupině. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Vrací počet vlastních vlastností skutečně obsažených v kolekci. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Vrátí název vlastní vlastnosti na zadaném indexu. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Odstraní vlastní vlastnost spojenou se zadaným názvem. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Zkontroluje přítomnost vlastní vlastnosti se zadaným názvem. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Vrací nebo nastavuje vlastní vlastnost spojenou se zadaným názvem. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Vrací nebo nastavuje vlastní vlastnost spojenou se zadaným názvem. |
| [clearCustomProperties()](#clearCustomProperties--) | Odstraní všechny vlastní vlastnosti. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Vymaže a nastaví výchozí hodnoty pro všechny vestavěné vlastnosti. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Gets a named boolean value from the custom properties. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Gets a named integer value from the custom properties. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Gets a named DateTime value from the custom properties. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Gets a named string value from the custom properties. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Gets a named float value from the custom properties. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Gets a named double value from the custom properties. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Sets a named boolean custom property. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Sets a named integer custom property. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Sets a named DateTime custom property. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Sets a named string custom property. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Sets a named float custom property. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Sets a named double custom property. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Gets an array of sensitivity labels from the custom document properties (Microsoft Information Protection SDK Metadata). |
### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

**Vrací:** java.lang.String

Vrací verzi aplikace. Pouze pro čtení String.

--------------------

Obsah tohoto elementu musí být ve formátu **XX.YYYY**, kde **X** a **Y** představují číselné hodnoty; jinak bude dokument považován za nevyhovující. **Aspose.Slides** reprezentuje svou verzi ve formátu **XX.YY.ZZ**, kde: **XX** – hlavní verze **YY** – podverze **ZZ** – oprava. Například hodnota **23.0105** znamená verzi **Aspose.Slides 23.1.5**.

**Vrací:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

**Vrací nebo nastavuje:** java.lang.String

Vrací nebo nastavuje název aplikace. Čtení/zápis String.

**Vrací:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```

**Vrací nebo nastavuje:** java.lang.String

Vrací nebo nastavuje název aplikace. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getCompany() {#getCompany--}
```
public abstract String getCompany()
```

**Vrací nebo nastavuje:** java.lang.String

Vrací nebo nastavuje vlastnost společnosti. Čtení/zápis String.

**Vrací:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

**Vrací nebo nastavuje:** java.lang.String

Vrací nebo nastavuje vlastnost společnosti. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getManager() {#getManager--}
```
public abstract String getManager()
```

**Vrací nebo nastavuje:** java.lang.String

Vrací nebo nastavuje vlastnost manažera. Čtení/zápis String.

**Vrací:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

**Vrací nebo nastavuje:** java.lang.String

Vrací nebo nastavuje vlastnost manažera. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

**Vrací nebo nastavuje:** java.lang.String

Vrací nebo nastavuje zamýšlený formát prezentace. Čtení/zápis String.

**Vrací:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

**Vrací nebo nastavuje:** java.lang.String

Vrací nebo nastavuje zamýšlený formát prezentace. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

**Vrací nebo nastavuje:** boolean

Určuje, zda je prezentace sdílena mezi více lidmi. Čtení/zápis boolean.

**Vrací:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

**Vrací nebo nastavuje:** boolean

Určuje, zda je prezentace sdílena mezi více lidmi. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

**Vrací nebo nastavuje:** java.lang.String

Vrací nebo nastavuje šablonu aplikace. Čtení/zápis String.

**Vrací:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```

**Vrací nebo nastavuje:** java.lang.String

Vrací nebo nastavuje šablonu aplikace. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```

**Vrací:** double

Celkový čas úprav prezentace. Čtení/zápis double.

**Vrací:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

**Vrací:** double

Celkový čas úprav prezentace. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

**Vrací nebo nastavuje:** java.lang.String

Vrací nebo nastavuje název prezentace. Čtení/zápis String.

**Vrací:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

**Vrací nebo nastavuje:** java.lang.String

Vrací nebo nastavuje název prezentace. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getSubject() {#getSubject--}
```
public abstract String getSubject()
```

**Vrací nebo nastavuje:** java.lang.String

Vrací nebo nastavuje předmět prezentace. Čtení/zápis String.

**Vrací:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```

**Vrací nebo nastavuje:** java.lang.String

Vrací nebo nastavuje předmět prezentace. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```

**Vrací nebo nastavuje:** java.lang.String

Vrací nebo nastavuje autora prezentace. Čtení/zápis String.

**Vrací:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```

**Vrací nebo nastavuje:** java.lang.String

Vrací nebo nastavuje autora prezentace. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```

**Vrací nebo nastavuje:** java.lang.String

Vrací nebo nastavuje klíčová slova prezentace. Čtení/zápis String.

**Vrací:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

**Vrací nebo nastavuje:** java.lang.String

Vrací nebo nastavuje klíčová slova prezentace. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract String getComments()
```

**Vrací nebo nastavuje:** java.lang.String

Vrací nebo nastavuje komentáře prezentace. Čtení/zápis String.

**Vrací:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

**Vrací nebo nastavuje:** java.lang.String

Vrací nebo nastavuje komentáře prezentace. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getCategory() {#getCategory--}
```
public abstract String getCategory()
```

**Vrací nebo nastavuje:** java.lang.String

Vrací nebo nastavuje kategorii prezentace. Čtení/zápis String.

**Vrací:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory
```

**Vrací nebo nastavuje:** java.lang.String

Vrací nebo nastavuje kategorii prezentace. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

**Vrací:** java.util.Date

Vrací datum vytvoření prezentace. Hodnoty jsou v UTC. Čtení/zápis java.util.Date.

**Vrací:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

**Vrací:** java.util.Date

Vrací datum vytvoření prezentace. Hodnoty jsou v UTC. Čtení/zápis java.util.Date.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```

**Vrací:** java.util.Date

Vrací datum poslední úpravy prezentace. Hodnoty jsou v UTC. Pouze pro čtení v případě **Presentation.DocumentProperties** (protože bude interně aktualizováno během ukládacího procesu **IPresentation**). Lze změnit přes instanci **DocumentProperties**, kterou vrací metoda [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Viz příklad v souhrnu metody [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Vrací:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

**Vrací:** java.util.Date

Vrací datum poslední úpravy prezentace. Hodnoty jsou v UTC. Pouze pro čtení v případě **Presentation.DocumentProperties** (protože bude interně aktualizováno během ukládacího procesu **IPresentation**). Lze změnit přes instanci **DocumentProperties**, kterou vrací metoda [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Viz příklad v souhrnu metody [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```

**Vrací:** java.util.Date

Vrací datum posledního tisku prezentace. Čtení/zápis java.util.Date.

**Vrací:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```

**Vrací:** java.util.Date

Vrací datum posledního tisku prezentace. Čtení/zápis java.util.Date.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```

**Vrací nebo nastavuje:** java.lang.String

Vrací nebo nastavuje jméno poslední osoby, která prezentaci upravila. Čtení/zápis String.

**Vrací:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

**Vrací nebo nastavuje:** java.lang.String

Vrací nebo nastavuje jméno poslední osoby, která prezentaci upravila. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```

**Vrací:** int

Vrací nebo nastavuje číslo revize prezentace. Čtení/zápis int.

**Vrací:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```

**Vrací:** int

Vrací nebo nastavuje číslo revize prezentace. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```

**Vrací nebo nastavuje:** java.lang.String

Vrací nebo nastavuje stav obsahu prezentace. Čtení/zápis String.

**Vrací:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```

**Vrací:** java.lang.String

Vrací nebo nastavuje stav obsahu prezentace. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

**Vrací nebo nastavuje:** java.lang.String

Vrací nebo nastavuje typ obsahu prezentace. Čtení/zápis String.

**Vrací:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```

**Vrací:** java.lang.String

Vrací nebo nastavuje typ obsahu prezentace. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```

**Vrací nebo nastavuje:** java.lang.String

Vrací nebo nastavuje vlastnost dokumentu HyperlinkBase. Čtení/zápis String.

**Vrací:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```

**Vrací:** java.lang.String

Vrací nebo nastavuje vlastnost dokumentu HyperlinkBase. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```

**Vrací nebo nastavuje:** boolean

Udává režim zobrazení miniatury dokumentu. Nastavte tento prvek na **true**, aby se miniatura dokumentu přizpůsobila displeji. Nastavte na **false**, aby se miniatura ořízl a zobrazily se pouze části, které se vejdou na displej. Čtení/zápis boolean.

**Vrací:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

**Vrací nebo nastavuje:** boolean

Udává režim zobrazení miniatury dokumentu. Nastavte tento prvek na **true**, aby se miniatura dokumentu přizpůsobila displeji. Nastavte na **false**, aby se miniatura ořízl a zobrazily se pouze části, které se vejdou na displej. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```

**Vrací nebo nastavuje:** boolean

Udává, zda jsou hypertextové odkazy v dokumentu aktuální. Nastavte tento prvek na **true**, aby odkazy byly označeny jako aktualizované. Nastavte na **false**, aby byly označeny jako neaktuální. Čtení/zápis boolean.

**Vrací:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

**Vrací nebo nastavuje:** boolean

Udává, zda jsou hypertextové odkazy v dokumentu aktuální. Nastavte tento prvek na **true**, aby odkazy byly označeny jako aktualizované. Nastavte na **false**, aby byly označeny jako neaktuální. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

**Vrací nebo nastavuje:** boolean

Specifikuje, že jeden nebo více hypertextových odkazů v této části byly aktualizovány výhradně v této části výrobcem. Další výrobce, který dokument otevře, aktualizuje vztahy odkazů novými odkazy uvedenými v této části. Čtení/zápis boolean.

**Vrací:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```

**Vrací nebo nastavuje:** boolean

Specifikuje, že jeden nebo více hypertextových odkazů v této části byly aktualizovány výhradně v této části výrobcem. Další výrobce, který dokument otevře, aktualizuje vztahy odkazů novými odkazy uvedenými v této části. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

**Vrací:** int

Udává celkový počet snímků v dokumentu prezentace. Pouze pro čtení int.

**Vrací:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

**Vrací:** int

Udává počet skrytých snímků v dokumentu prezentace. Pouze pro čtení int.

**Vrací:**
int
### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

**Vrací:** int

Udává počet snímků v prezentaci obsahujících poznámky. Pouze pro čtení int.

**Vrací:**
int
### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```

**Vrací:** int

Udává celkový počet odstavců nalezených v dokumentu, pokud je to relevantní. Pouze pro čtení int.

**Vrací:**
int
### getWords() {#getWords--}
```
public abstract int getWords()
```

**Vrací:** int

Udává celkový počet slov v dokumentu. Pouze pro čtení int.

**Vrací:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

**Vrací:** int

Udává celkový počet zvukových nebo video klipů, které jsou v dokumentu. Pouze pro čtení int.

**Vrací:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

**Vrací:** java.lang.String[]

Udává název každé části dokumentu. Tyto části nejsou skutečnými částmi dokumentu, ale konceptuálními reprezentacemi sekcí dokumentu. Pouze pro čtení String[].

**Vrací:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

**Vrací:** com.aspose.slides.IHeadingPair[]

Udává seskupení částí dokumentu a počet částí v každé skupině. Pouze pro čtení IHeadingPair[].

**Vrací:**
com.aspose.slides.IHeadingPair[]
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

**Vrací:** int

Vrací počet vlastních vlastností skutečně obsažených v kolekci. Pouze pro čtení int.

**Vrací:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```

**Vrací:** java.lang.String

Vrátí název vlastní vlastnosti na zadaném indexu.

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

**Vrací:** boolean

Odstraní vlastní vlastnost spojenou se zadaným názvem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, kterou chcete odstranit. |

**Vrací:**
boolean - Vrátí true, pokud byla vlastnost odstraněna, false jinak.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```

**Vrací:** boolean

Zkontroluje přítomnost vlastní v

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, kterou chcete zkontrolovat. |

**Vrací:**
boolean - Vrátí true, pokud vlastnost existuje, false jinak.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```

**Vrací nebo nastavuje:** java.lang.Object

Vrací nebo nastavuje vlastní vlastnost spojenou se zadaným názvem. Čtení/zápis Object.

--------------------

Hodnota může být **int**, **float**, **double**, **String**, **boolean** nebo **Date**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String |  |

**Vrací:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```

**Vrací nebo nastavuje:** java.lang.Object

Vrací nebo nastavuje vlastní vlastnost spojenou se zadaným názvem. Čtení/zápis Object.

--------------------

Hodnota může být **int**, **float**, **double**, **String**, **boolean** nebo **Date**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |
### clearCustomProperties() {#clearCustomProperties--}
```
public abstract void clearCustomProperties()
```

Odstraní všechny vlastní vlastnosti.
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract void clearBuiltInProperties()
```

Vymaže a nastaví výchozí hodnoty pro všechny vestavěné vlastnosti.
### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

Získá pojmenovanou boolean hodnotu z vlastních vlastností.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, kterou chcete získat |
| value | boolean[] | Hodnota vlastní vlastnosti |
### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

Získá pojmenovanou integer hodnotu z vlastních vlastností.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, kterou chcete získat |
| value | int[] | Hodnota vlastní vlastnosti |
### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

Získá pojmenovanou DateTime hodnotu z vlastních vlastností.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, kterou chcete získat |
| value | java.util.Date[] | Hodnota vlastní vlastnosti |
### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

Získá pojmenovanou string hodnotu z vlastních vlastností.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, kterou chcete získat |
| value | java.lang.String[] | Hodnota vlastní vlastnosti |
### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

Získá pojmenovanou float hodnotu z vlastních vlastností.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, kterou chcete získat |
| value | float[] | Hodnota vlastní vlastnosti |
### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```

Získá pojmenovanou double hodnotu z vlastních vlastností.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, kterou chcete získat. |
| value | double[] | Hodnota vlastní vlastnosti |
### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

Nastaví pojmenovanou boolean vlastní vlastnost.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, kterou chcete nastavit |
| value | boolean | Hodnota vlastní vlastnosti |
### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

Nastaví pojmenovanou integer vlastní vlastnost.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, kterou chcete nastavit |
| value | int | Hodnota vlastní vlastnosti |
### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

Nastaví pojmenovanou DateTime vlastní vlastnost.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, kterou chcete nastavit |
| value | java.util.Date | Hodnota vlastní vlastnosti |
### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

Nastaví pojmenovanou string vlastní vlastnost.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, kterou chcete nastavit |
| value | java.lang.String | Hodnota vlastní vlastnosti |
### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

Nastaví pojmenovanou float vlastní vlastnost.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, kterou chcete nastavit |
| value | float | Hodnota vlastní vlastnosti |
### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

Nastaví pojmenovanou double vlastní vlastnost.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, kterou chcete nastavit |
| value | double | Hodnota vlastní vlastnosti |
### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

Získá pole citlivostních štítků z vlastních vlastností dokumentu (Microsoft Information Protection SDK Metadata).

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