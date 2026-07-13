---
title: DocumentProperties
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje vlastnosti prezentace.
type: docs
url: /cs/com.aspose.slides/documentproperties/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

Reprezentuje vlastnosti prezentace.

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // Instancujte třídu Presentation, která představuje prezentaci
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // Vytvořte odkaz na objekt IDocumentProperties spojený s prezentací
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Zobrazte vestavěné vlastnosti
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
>  // Instancujte třídu Presentation, která představuje prezentaci
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // Vytvořte odkaz na objekt IDocumentProperties spojený s prezentací
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Nastavte vestavěné vlastnosti
>      documentProperties.setAuthor("Aspose.Slides for Android via Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // Uložte prezentaci do souboru
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | Inicializuje novou instanci třídy [DocumentProperties](../../com.aspose.slides/documentproperties). |
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
| [getHyperlinkBase()](#getHyperlinkBase--) | Vrací nebo nastavuje vlastnost HyperlinkBase dokumentu. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Vrací nebo nastavuje vlastnost HyperlinkBase dokumentu. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Vrací počet vlastních vlastností skutečně obsažených ve sbírce. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Vrátí název vlastní vlastnosti na zadaném indexu. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Odstraní vlastní vlastnost spojenou se zadaným názvem. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Zkontroluje, zda existuje vlastní vlastnost se zadaným názvem. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Vrací nebo nastavuje vlastní vlastnost spojenou se zadaným názvem. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Vrací nebo nastavuje vlastní vlastnost spojenou se zadaným názvem. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Získá pojmenovanou hodnotu typu boolean z vlastních vlastností. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Získá pojmenovanou celočíselnou hodnotu z vlastních vlastností. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Získá pojmenovanou hodnotu DateTime z vlastních vlastností. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Získá pojmenovanou řetězcovou hodnotu z vlastních vlastností. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Získá pojmenovanou hodnotu typu float z vlastních vlastností. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Získá pojmenovanou hodnotu typu double z vlastních vlastností. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Nastaví pojmenovanou vlastní vlastnost typu boolean. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Nastaví pojmenovanou vlastní vlastnost typu integer. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Nastaví pojmenovanou vlastní vlastnost typu DateTime. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Nastaví pojmenovanou vlastní vlastnost typu string. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Nastaví pojmenovanou vlastní vlastnost typu float. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Nastaví pojmenovanou vlastní vlastnost typu double. |
| [clearCustomProperties()](#clearCustomProperties--) | Odstraňuje všechny vlastní vlastnosti. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Získá pole označení citlivosti z vlastních vlastností dokumentu (metadata Microsoft Information Protection SDK). |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Vymaže a nastaví výchozí hodnoty pro všechny vestavěné vlastnosti. |
| [getScaleCrop()](#getScaleCrop--) | Určuje režim zobrazení náhledu dokumentu. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Určuje režim zobrazení náhledu dokumentu. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Určuje, zda jsou hypertextové odkazy v dokumentu aktuální. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Určuje, zda jsou hypertextové odkazy v dokumentu aktuální. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Určuje, že jeden nebo více hypertextových odkazů v této části byly aktualizovány výhradně v této části producentem. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Určuje, že jeden nebo více hypertextových odkazů v této části byly aktualizovány výhradně v této části producentem. |
| [getSlides()](#getSlides--) | Vrací celkový počet snímků v dokumentu prezentace. |
| [getHiddenSlides()](#getHiddenSlides--) | Vrací počet skrytých snímků v dokumentu prezentace. |
| [getNotes()](#getNotes--) | Vrací počet snímků v prezentaci obsahujících poznámky. |
| [getParagraphs()](#getParagraphs--) | Vrací celkový počet odstavců nalezených v dokumentu, pokud je to použitelné. |
| [getWords()](#getWords--) | Vrací celkový počet slov obsažených v dokumentu. |
| [getMultimediaClips()](#getMultimediaClips--) | Vrací celkový počet zvukových nebo video klipů, které jsou v dokumentu přítomny. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Určuje název každé části dokumentu. |
| [getHeadingPairs()](#getHeadingPairs--) | Určuje seskupení částí dokumentu a počet částí v každé skupině. |
| [deepClone()](#deepClone--) | Klonuje aktuální objekt. |
| [cloneT()](#cloneT--) | Klonuje aktuální objekt. |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

Inicializuje novou instanci třídy [DocumentProperties](../../com.aspose.slides/documentproperties).

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

Vrací verzi aplikace. Pouze pro čtení String.

**Vrací:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```

Vrací nebo nastavuje název aplikace. Čtení/zápis String.

**Vrací:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

Vrací nebo nastavuje název aplikace. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getCompany() {#getCompany--}
```
public final String getCompany()
```

Vrací nebo nastavuje vlastnost společnosti. Čtení/zápis String.

**Vrací:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

Vrací nebo nastavuje vlastnost společnosti. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getManager() {#getManager--}
```
public final String getManager()
```

Vrací nebo nastavuje vlastnost manažera. Čtení/zápis String.

**Vrací:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

Vrací nebo nastavuje vlastnost manažera. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

Vrací nebo nastavuje zamýšlený formát prezentace. Čtení/zápis String.

**Vrací:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

Vrací nebo nastavuje zamýšlený formát prezentace. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```

Určuje, zda je prezentace sdílena mezi více lidmi. Čtení/zápis boolean.

**Vrací:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```

Určuje, zda je prezentace sdílena mezi více lidmi. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```

Vrací nebo nastavuje šablonu aplikace. Čtení/zápis String.

**Vrací:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

Vrací nebo nastavuje šablonu aplikace. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```

Celkový čas úprav prezentace. Čtení/zápis double.

**Vrací:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```

Celkový čas úprav prezentace. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getTitle() {#getTitle--}
```
public final String getTitle()
```

Vrací nebo nastavuje název prezentace. Čtení/zápis String.

**Vrací:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

Vrací nebo nastavuje název prezentace. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getSubject() {#getSubject--}
```
public final String getSubject()
```

Vrací nebo nastavuje předmět prezentace. Čtení/zápis String.

**Vrací:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

Vrací nebo nastavuje předmět prezentace. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

Vrací nebo nastavuje autora prezentace. Čtení/zápis String.

**Vrací:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

Vrací nebo nastavuje autora prezentace. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

Vrací nebo nastavuje klíčová slova prezentace. Čtení/zápis String.

**Vrací:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```

Vrací nebo nastavuje klíčová slova prezentace. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public final String getComments()
```

Vrací nebo nastavuje komentáře prezentace. Čtení/zápis String.

**Vrací:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

Vrací nebo nastavuje komentáře prezentace. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getCategory() {#getCategory--}
```
public final String getCategory()
```

Vrací nebo nastavuje kategorii prezentace. Čtení/zápis String.

**Vrací:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

Vrací nebo nastavuje kategorii prezentace. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

Vrací datum vytvoření prezentace. Hodnoty jsou v UTC. Čtení/zápis java.util.Date.

**Vrací:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Vrací datum vytvoření prezentace. Hodnoty jsou v UTC. Čtení/zápis java.util.Date.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```

Vrací datum poslední úpravy prezentace. Hodnoty jsou v UTC. Pouze pro čtení v případě Presentation.DocumentProperties (protože je aktualizováno interně během ukládání objektu IPresentation). Lze změnit přes instanci DocumentProperties vrácenou metodou [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Viz příklad v metodě [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Vrací:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```

Vrací datum poslední úpravy prezentace. Hodnoty jsou v UTC. Pouze pro čtení v případě Presentation.DocumentProperties (protože je aktualizováno interně během ukládání objektu IPresentation). Lze změnit přes instanci DocumentProperties vrácenou metodou [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Viz příklad v metodě [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```

Vrací datum posledního tisku prezentace. Čtení/zápis java.util.Date.

**Vrací:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```

Vrací datum posledního tisku prezentace. Čtení/zápis java.util.Date.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```

Vrací nebo nastavuje jméno poslední osoby, která prezentaci upravila. Čtení/zápis String.

**Vrací:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```

Vrací nebo nastavuje jméno poslední osoby, která prezentaci upravila. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```

Vrací nebo nastavuje číslo revize prezentace. Čtení/zápis int.

**Vrací:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```

Vrací nebo nastavuje číslo revize prezentace. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```

Vrací nebo nastavuje stav obsahu prezentace. Čtení/zápis String.

**Vrací:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```

Vrací nebo nastavuje stav obsahu prezentace. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Vrací nebo nastavuje typ obsahu prezentace. Čtení/zápis String.

**Vrací:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Vrací nebo nastavuje typ obsahu prezentace. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```

Vrací nebo nastavuje vlastnost HyperlinkBase dokumentu. Čtení/zápis String.

**Vrací:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```

Vrací nebo nastavuje vlastnost HyperlinkBase dokumentu. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```

Vrací počet vlastních vlastností skutečně obsažených ve sbírce. Pouze pro čtení int.

**Vrací:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```

Vrátí název vlastní vlastnosti na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index (od nuly) vlastní vlastnosti, která se má získat. |

**Vrací:**
java.lang.String – Název vlastní vlastnosti na zadaném indexu.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```

Odstraní vlastní vlastnost spojenou se zadaným názvem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, která se má odstranit. |

**Vrací:**
boolean – Vrací true, pokud byla vlastnost odstraněna, jinak false.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```

Zkontroluje, zda existuje vlastní vlastnost se zadaným názvem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, která se má zkontrolovat. |

**Vrací:**
boolean – Vrací true, pokud vlastnost existuje, jinak false.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```

Vrací nebo nastavuje vlastní vlastnost spojenou se zadaným názvem. Čtení/zápis Object.

--------------------

Hodnota může být **int**, **float**, **String**, **boolean** nebo **Date**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String |  |

**Vrací:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public final void set_Item(String name, Object value)
```

Vrací nebo nastavuje vlastní vlastnost spojenou se zadaným názvem. Čtení/zápis Object.

--------------------

Hodnota může být **int**, **float**, **String**, **boolean** nebo **Date**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |
### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```

Získá pojmenovanou hodnotu typu boolean z vlastních vlastností.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, kterou chcete získat |
| value | boolean[] | Hodnota vlastní vlastnosti |
### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```

Získá pojmenovanou celočíselnou hodnotu z vlastních vlastností.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, kterou chcete získat |
| value | int[] | Hodnota vlastní vlastnosti |
### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```

Získá pojmenovanou hodnotu DateTime z vlastních vlastností.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, kterou chcete získat |
| value | java.util.Date[] | Hodnota vlastní vlastnosti |
### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```

Získá pojmenovanou řetězcovou hodnotu z vlastních vlastností.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, kterou chcete získat |
| value | java.lang.String[] | Hodnota vlastní vlastnosti |
### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```

Získá pojmenovanou hodnotu typu float z vlastních vlastností.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, kterou chcete získat |
| value | float[] | Hodnota vlastní vlastnosti |
### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```

Získá pojmenovanou hodnotu typu double z vlastních vlastností.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, kterou chcete získat. |
| value | double[] | Hodnota vlastní vlastnosti |
### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```

Nastaví pojmenovanou vlastní vlastnost typu boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, kterou chcete nastavit |
| value | boolean | Hodnota vlastní vlastnosti |
### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```

Nastaví pojmenovanou vlastní vlastnost typu integer.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, kterou chcete nastavit |
| value | int | Hodnota vlastní vlastnosti |
### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```

Nastaví pojmenovanou vlastní vlastnost typu DateTime.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, kterou chcete nastavit |
| value | java.util.Date | Hodnota vlastní vlastnosti |
### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```

Nastaví pojmenovanou vlastní vlastnost typu string.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, kterou chcete nastavit |
| value | java.lang.String | Hodnota vlastní vlastnosti |
### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```

Nastaví pojmenovanou vlastní vlastnost typu float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, kterou chcete nastavit |
| value | float | Hodnota vlastní vlastnosti |
### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```

Nastaví pojmenovanou vlastní vlastnost typu double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastní vlastnosti, kterou chcete nastavit |
| value | double | Hodnota vlastní vlastnosti |
### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```

Odstraňuje všechny vlastní vlastnosti.
### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```

Získá pole označení citlivosti z vlastních vlastností dokumentu (metadata Microsoft Information Protection SDK).

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
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public final void clearBuiltInProperties()
```

Vymaže a nastaví výchozí hodnoty pro všechny vestavěné vlastnosti.
### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```

Určuje režim zobrazení náhledu dokumentu. Nastavte tento prvek na **true**, aby se náhled dokumentu přizpůsobil zobrazení. Nastavte na **false**, aby se náhled ořízl tak, aby zobrazoval jen části, které se vejdou do zobrazení. Čtení/zápis boolean.

**Vrací:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```

Určuje režim zobrazení náhledu dokumentu. Nastavte tento prvek na **true**, aby se náhled dokumentu přizpůsobil zobrazení. Nastavte na **false**, aby se náhled ořízl tak, aby zobrazoval jen části, které se vejdou do zobrazení. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```

Určuje, zda jsou hypertextové odkazy v dokumentu aktuální. Nastavte tento prvek na **true**, aby odkaz byl označen jako aktualizovaný. Nastavte na **false**, aby byl označen jako neaktuální. Čtení/zápis boolean.

**Vrací:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```

Určuje, zda jsou hypertextové odkazy v dokumentu aktuální. Nastavte tento prvek na **true**, aby odkaz byl označen jako aktualizovaný. Nastavte na **false**, aby byl označen jako neaktuální. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

Určuje, že jeden nebo více hypertextových odkazů v této části byly aktualizovány výhradně v této části producentem. Další producent otevřou dokument a aktualizuje vztahy hypertextových odkazů s novými odkazy uvedenými v této části. Čtení/zápis boolean.

**Vrací:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

Určuje, že jeden nebo více hypertextových odkazů v této části byly aktualizovány výhradně v této části producentem. Další producent otevřou dokument a aktualizuje vztahy hypertextových odkazů s novými odkazy uvedenými v této části. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getSlides() {#getSlides--}
```
public   



Sorry















 



…













…









…










```

Vrací celkový počet snímků v dokumentu prezentace. Pouze pro čtení int.

**Vrací:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

Vrací počet skrytých snímků v dokumentu prezentace. Pouze pro čtení int.

**Vrací:**
int
### getNotes() {#getNotes--}
```
public final int getNotes()
```

Vrací počet snímků v prezentaci obsahujících poznámky. Pouze pro čtení int.

**Vrací:**
int
### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

Vrací celkový počet odstavců nalezených v dokumentu, pokud je to použitelné. Pouze pro čtení int.

**Vrací:**
int
### getWords() {#getWords--}
```
public final int getWords()
```

Vrací celkový počet slov obsažených v dokumentu. Pouze pro čtení int.

**Vrací:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

Vrací celkový počet zvukových nebo video klipů, které jsou v dokumentu přítomny. Pouze pro čtení int.

**Vrací:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

Určuje název každé části dokumentu. Tyto části nejsou skutečnými částmi dokumentu, ale konceptuálními reprezentacemi sekcí dokumentu. Pouze pro čtení String[].

**Vrací:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

Určuje seskupení částí dokumentu a počet částí v každé skupině. Pouze pro čtení IHeadingPair[].

**Vrací:**
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Klonuje aktuální objekt

**Vrací:**
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

Klonuje aktuální objekt

**Vrací:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone