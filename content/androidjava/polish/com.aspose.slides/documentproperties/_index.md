---
title: DocumentProperties
second_title: Aspose.Slides dla Androida poprzez odniesienie do API Java
description: Reprezentuje właściwości prezentacji.
type: docs
url: /pl/com.aspose.slides/documentproperties/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

Reprezentuje właściwości prezentacji.

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // Utwórz instancję klasy Presentation, która reprezentuje prezentację
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // Utwórz odwołanie do obiektu IDocumentProperties powiązanego z prezentacją
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Wyświetl wbudowane właściwości
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
>  // Utwórz instancję klasy Presentation, która reprezentuje prezentację
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // Utwórz odwołanie do obiektu IDocumentProperties powiązanego z prezentacją
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Ustaw wbudowane właściwości
>      documentProperties.setAuthor("Aspose.Slides for Android via Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // Save your presentation to a file
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | Inicjalizuje nową instancję klasy [DocumentProperties](../../com.aspose.slides/documentproperties). |
## Metody

| Metoda | Opis |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Zwraca wersję aplikacji. |
| [getNameOfApplication()](#getNameOfApplication--) | Zwraca lub ustawia nazwę aplikacji. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Zwraca lub ustawia nazwę aplikacji. |
| [getCompany()](#getCompany--) | Zwraca lub ustawia własność firmy. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Zwraca lub ustawia własność firmy. |
| [getManager()](#getManager--) | Zwraca lub ustawia własność menedżera. |
| [setManager(String value)](#setManager-java.lang.String-) | Zwraca lub ustawia własność menedżera. |
| [getPresentationFormat()](#getPresentationFormat--) | Zwraca lub ustawia docelowy format prezentacji. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Zwraca lub ustawia docelowy format prezentacji. |
| [getSharedDoc()](#getSharedDoc--) | Określa, czy prezentacja jest współdzielona przez wiele osób. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Określa, czy prezentacja jest współdzielona przez wiele osób. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Zwraca lub ustawia szablon aplikacji. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Zwraca lub ustawia szablon aplikacji. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Łączny czas edycji prezentacji. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Łączny czas edycji prezentacji. |
| [getTitle()](#getTitle--) | Zwraca lub ustawia tytuł prezentacji. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Zwraca lub ustawia tytuł prezentacji. |
| [getSubject()](#getSubject--) | Zwraca lub ustawia temat prezentacji. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Zwraca lub ustawia temat prezentacji. |
| [getAuthor()](#getAuthor--) | Zwraca lub ustawia autora prezentacji. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Zwraca lub ustawia autora prezentacji. |
| [getKeywords()](#getKeywords--) | Zwraca lub ustawia słowa kluczowe prezentacji. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Zwraca lub ustawia słowa kluczowe prezentacji. |
| [getComments()](#getComments--) | Zwraca lub ustawia komentarze prezentacji. |
| [setComments(String value)](#setComments-java.lang.String-) | Zwraca lub ustawia komentarze prezentacji. |
| [getCategory()](#getCategory--) | Zwraca lub ustawia kategorię prezentacji. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Zwraca lub ustawia kategorię prezentacji. |
| [getCreatedTime()](#getCreatedTime--) | Zwraca datę utworzenia prezentacji. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Zwraca datę utworzenia prezentacji. |
| [getLastSavedTime()](#getLastSavedTime--) | Zwraca datę ostatniej modyfikacji prezentacji. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Zwraca datę ostatniej modyfikacji prezentacji. |
| [getLastPrinted()](#getLastPrinted--) | Zwraca datę ostatniego wydruku prezentacji. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Zwraca datę ostatniego wydruku prezentacji. |
| [getLastSavedBy()](#getLastSavedBy--) | Zwraca lub ustawia nazwę ostatniej osoby, która zmodyfikowała prezentację. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Zwraca lub ustawia nazwę ostatniej osoby, która zmodyfikowała prezentację. |
| [getRevisionNumber()](#getRevisionNumber--) | Zwraca lub ustawia numer wersji prezentacji. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Zwraca lub ustawia numer wersji prezentacji. |
| [getContentStatus()](#getContentStatus--) | Zwraca lub ustawia status zawartości prezentacji. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Zwraca lub ustawia status zawartości prezentacji. |
| [getContentType()](#getContentType--) | Zwraca lub ustawia typ zawartości prezentacji. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Zwraca lub ustawia typ zawartości prezentacji. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Zwraca lub ustawia własność dokumentu HyperlinkBase. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Zwraca lub ustawia własność dokumentu HyperlinkBase. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Zwraca liczbę rzeczywistych własności niestandardowych w kolekcji. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Zwraca nazwę własności niestandardowej pod określonym indeksem. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Usuwa własność niestandardową o podanej nazwie. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Sprawdza istnienie własności niestandardowej o podanej nazwie. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Zwraca lub ustawia własność niestandardową o podanej nazwie. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Zwraca lub ustawia własność niestandardową o podanej nazwie. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Pobiera nazwany wartość typu boolean z własności niestandardowych. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Pobiera nazwany wartość typu int z własności niestandardowych. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Pobiera nazwany wartość typu DateTime z własności niestandardowych. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Pobiera nazwany wartość typu string z własności niestandardowych. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Pobiera nazwany wartość typu float z własności niestandardowych. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Pobiera nazwany wartość typu double z własności niestandardowych. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Ustawia nazwany własność niestandardową typu boolean. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Ustawia nazwany własność niestandardową typu int. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Ustawia nazwany własność niestandardową typu DateTime. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Ustawia nazwany własność niestandardową typu string. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Ustawia nazwany własność niestandardową typu float. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Ustawia nazwany własność niestandardową typu double. |
| [clearCustomProperties()](#clearCustomProperties--) | Usuwa wszystkie własności niestandardowe. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Pobiera tablicę etykiet wrażliwości z własności niestandardowych dokumentu (Microsoft Information Protection SDK Metadata). |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Czyści i ustawia domyślne wartości wszystkich własności wbudowanych. |
| [getScaleCrop()](#getScaleCrop--) | Określa tryb wyświetlania miniatury dokumentu. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Określa tryb wyświetlania miniatury dokumentu. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Określa, czy hiperłącza w dokumencie są aktualne. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Określa, czy hiperłącza w dokumencie są aktualne. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Określa, że jeden lub więcej hiperłączy w tej części zostało wyłącznie zaktualizowane w tej części przez producenta. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Określa, że jeden lub więcej hiperłączy w tej części zostało wyłącznie zaktualizowane w tej części przez producenta. |
| [getSlides()](#getSlides--) | Zwraca łączną liczbę slajdów w dokumencie prezentacji. |
| [getHiddenSlides()](#getHiddenSlides--) | Zwraca liczbę ukrytych slajdów w dokumencie prezentacji. |
| [getNotes()](#getNotes--) | Zwraca liczbę slajdów w prezentacji zawierających notatki. |
| [getParagraphs()](#getParagraphs--) | Zwraca łączną liczbę akapitów w dokumencie, jeśli ma to zastosowanie. |
| [getWords()](#getWords--) | Zwraca łączną liczbę słów w dokumencie. |
| [getMultimediaClips()](#getMultimediaClips--) | Zwraca łączną liczbę klipów dźwiękowych lub wideo w dokumencie. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Określa tytuł każdej części dokumentu. |
| [getHeadingPairs()](#getHeadingPairs--) | Określa grupowanie części dokumentu i liczbę części w każdej grupie. |
| [deepClone()](#deepClone--) | Klonuje bieżący obiekt |
| [cloneT()](#cloneT--) | Klonuje bieżący obiekt |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

Inicjalizuje nową instancję klasy [DocumentProperties](../../com.aspose.slides/documentproperties).

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

Zwraca wersję aplikacji. Tylko do odczytu String.

**Zwraca:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```

Zwraca lub ustawia nazwę aplikacji. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

Zwraca lub ustawia nazwę aplikacji. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public final String getCompany()
```

Zwraca lub ustawia własność firmy. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

Zwraca lub ustawia własność firmy. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public final String getManager()
```

Zwraca lub ustawia własność menedżera. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

Zwraca lub ustawia własność menedżera. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

Zwraca lub ustawia docelowy format prezentacji. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

Zwraca lub ustawia docelowy format prezentacji. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```

Określa, czy prezentacja jest współdzielona przez wiele osób. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```

Określa, czy prezentacja jest współdzielona przez wiele osób. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```

Zwraca lub ustawia szablon aplikacji. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

Zwraca lub ustawia szablon aplikacji. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```

Łączny czas edycji prezentacji. Odczyt/zapis double.

**Zwraca:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```

Łączny czas edycji prezentacji. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```

Zwraca lub ustawia tytuł prezentacji. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

Zwraca lub ustawia tytuł prezentacji. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```

Zwraca lub ustawia temat prezentacji. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

Zwraca lub ustawia temat prezentacji. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

Zwraca lub ustawia autora prezentacji. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

Zwraca lub ustawia autora prezentacji. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

Zwraca lub ustawia słowa kluczowe prezentacji. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```

Zwraca lub ustawia słowa kluczowe prezentacji. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```

Zwraca lub ustawia komentarze prezentacji. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

Zwraca lub ustawia komentarze prezentacji. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public final String getCategory()
```

Zwraca lub ustawia kategorię prezentacji. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

Zwraca lub ustawia kategorię prezentacji. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

Zwraca datę utworzenia prezentacji. Wartości w UTC. Odczyt/zapis java.util.Date.

**Zwraca:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Zwraca datę utworzenia prezentacji. Wartości w UTC. Odczyt/zapis java.util.Date.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```

Zwraca datę ostatniej modyfikacji prezentacji. Wartości w UTC. Tylko do odczytu w przypadku Presentation.DocumentProperties (ponieważ jest aktualizowana wewnętrznie podczas procesu zapisu obiektu IPresentation). Może być zmieniona poprzez instancję DocumentProperties zwracaną przez metodę [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Zobacz przykład w podsumowaniu metody [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Zwraca:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```

Zwraca datę ostatniej modyfikacji prezentacji. Wartości w UTC. Tylko do odczytu w przypadku Presentation.DocumentProperties (ponieważ jest aktualizowana wewnętrznie podczas procesu zapisu obiektu IPresentation). Może być zmieniona poprzez instancję DocumentProperties zwracaną przez metodę [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Zobacz przykład w podsumowaniu metody [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```

Zwraca datę ostatniego wydruku prezentacji. Odczyt/zapis java.util.Date.

**Zwraca:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```

Zwraca datę ostatniego wydruku prezentacji. Odczyt/zapis java.util.Date.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```

Zwraca lub ustawia nazwę ostatniej osoby, która zmodyfikowała prezentację. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```

Zwraca lub ustawia nazwę ostatniej osoby, która zmodyfikowała prezentację. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```

Zwraca lub ustawia numer wersji prezentacji. Odczyt/zapis int.

**Zwraca:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```

Zwraca lub ustawia numer wersji prezentacji. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```

Zwraca lub ustawia status zawartości prezentacji. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```

Zwraca lub ustawia status zawartości prezentacji. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

Zwraca lub ustawia typ zawartości prezentacji. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Zwraca lub ustawia typ zawartości prezentacji. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```

Zwraca lub ustawia własność dokumentu HyperlinkBase. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```

Zwraca lub ustawia własność dokumentu HyperlinkBase. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```

Zwraca liczbę rzeczywistych własności niestandardowych w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```

Zwraca nazwę własności niestandardowej pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy własności niestandardowej do pobrania. |

**Zwraca:**
java.lang.String - Nazwa własności niestandardowej pod określonym indeksem.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```

Usuwa własność niestandardową o podanej nazwie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa własności niestandardowej do usunięcia. |

**Zwraca:**
boolean - Zwraca true, jeśli własność została usunięta, false w przeciwnym razie.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```

Sprawdza obecność własności niestandardowej o podanej nazwie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa własności niestandardowej do sprawdzenia. |

**Zwraca:**
boolean - Zwraca true, jeśli własność istnieje, false w przeciwnym razie.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```

Zwraca lub ustawia własność niestandardową o podanej nazwie. Odczyt/zapis Object.

--------------------

Wartość może być **int**, **float**, **String**, **boolean** lub **Date**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String |  |

**Zwraca:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public final void set_Item(String name, Object value)
```

Zwraca lub ustawia własność niestandardową o podanej nazwie. Odczyt/zapis Object.

--------------------

Wartość może być **int**, **float**, **String**, **boolean** lub **Date**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```

Pobiera nazwany wartość typu boolean z własności niestandardowych.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa własności niestandardowej do pobrania |
| value | boolean[] | Wartość własności niestandardowej |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```

Pobiera nazwany wartość typu int z własności niestandardowych.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa własności niestandardowej do pobrania |
| value | int[] | Wartość własności niestandardowej |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```

Pobiera nazwany wartość typu DateTime z własności niestandardowych.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa własności niestandardowej do pobrania |
| value | java.util.Date[] | Wartość własności niestandardowej |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```

Pobiera nazwany wartość typu string z własności niestandardowych.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa własności niestandardowej do pobrania |
| value | java.lang.String[] | Wartość własności niestandardowej |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```

Pobiera nazwany wartość typu float z własności niestandardowych.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa własności niestandardowej do pobrania |
| value | float[] | Wartość własności niestandardowej |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```

Pobiera nazwany wartość typu double z własności niestandardowych.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa własności niestandardowej do pobrania. |
| value | double[] | Wartość własności niestandardowej |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```

Ustawia nazwany własność niestandardową typu boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa własności niestandardowej do ustawienia |
| value | boolean | Wartość własności niestandardowej |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```

Ustawia nazwany własność niestandardową typu int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa własności niestandardowej do ustawienia |
| value | int | Wartość własności niestandardowej |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```

Ustawia nazwany własność niestandardową typu DateTime.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa własności niestandardowej do ustawienia |
| value | java.util.Date | Wartość własności niestandardowej |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```

Ustawia nazwany własność niestandardową typu string.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa własności niestandardowej do ustawienia |
| value | java.lang.String | Wartość własności niestandardowej |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```

Ustawia nazwany własność niestandardową typu float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa własności niestandardowej do ustawienia |
| value | float | Wartość własności niestandardowej |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```

Ustawia nazwany własność niestandardową typu double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa własności niestandardowej do ustawienia |
| value | double | Wartość własności niestandardowej |

### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```

Usuwa wszystkie własności niestandardowe.

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```

Pobiera tablicę etykiet wrażliwości z własności niestandardowych dokumentu (Microsoft Information Protection SDK Metadata).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Pobierz etykiety wrażliwości z własności niestandardowych dokumentu
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Dodaj etykietę do kolekcji
>          // Tutaj możesz dodać sprawdzenie poprawności informacji o etykiecie (etykieta jest dostępna, itp.)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
com.aspose.slides.ISensitivityLabel[]
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public final void clearBuiltInProperties()
```

Czyści i ustawia domyślne wartości wszystkich własności wbudowanych.

### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```

Wskazuje tryb wyświetlania miniatury dokumentu. Ustaw ten element na **true**, aby włączyć skalowanie miniatury dokumentu do wyświetlacza. Ustaw ten element na **false**, aby włączyć przycinanie miniatury dokumentu, aby pokazać tylko sekcje pasujące do wyświetlacza. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```

Wskazuje tryb wyświetlania miniatury dokumentu. Ustaw ten element na **true**, aby włączyć skalowanie miniatury dokumentu do wyświetlacza. Ustaw ten element na **false**, aby włączyć przycinanie miniatury dokumentu, aby pokazać tylko sekcje pasujące do wyświetlacza. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```

Określa, czy hiperłącza w dokumencie są aktualne. Ustaw ten element na **true**, aby wskazać, że hiperłącza są zaktualizowane. Ustaw ten element na **false**, aby wskazać, że hiperłącza są nieaktualne. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```

Określa, czy hiperłącza w dokumencie są aktualne. Ustaw ten element na **true**, aby wskazać, że hiperłącza są zaktualizowane. Ustaw ten element na **false**, aby wskazać, że hiperłącza są nieaktualne. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

Określa, że jeden lub więcej hiperłączy w tej części zostało wyłącznie zaktualizowane w tej części przez producenta. Następny producent otwierający ten dokument powinien zaktualizować relacje hiperłączy do nowych hiperłączy określonych w tej części. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

Określa, że jeden lub więcej hiperłączy w tej części zostało wyłącznie zaktualizowane w tej części przez producenta. Następny producent otwierający ten dokument powinien zaktualizować relacje hiperłączy do nowych hiperłączy określonych w tej części. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public final int getSlides()
```

Zwraca łączną liczbę slajdów w dokumencie prezentacji. Tylko do odczytu int.

**Zwraca:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

Zwraca liczbę ukrytych slajdów w dokumencie prezentacji. Tylko do odczytu int.

**Zwraca:**
int
### getNotes() {#getNotes--}
```
public final int getNotes()
```

Zwraca liczbę slajdów w prezentacji zawierających notatki. Tylko do odczytu int.

**Zwraca:**
int
### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

Zwraca łączną liczbę akapitów w dokumencie, jeśli ma to zastosowanie. Tylko do odczytu int.

**Zwraca:**
int
### getWords() {#getWords--}
```
public final int getWords()
```

Zwraca łączną liczbę słów w dokumencie. Tylko do odczytu int.

**Zwraca:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

Zwraca łączną liczbę klipów dźwiękowych lub wideo w dokumencie. Tylko do odczytu int.

**Zwraca:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

Określa tytuł każdej części dokumentu. Te części nie są rzeczywistymi częściami dokumentu, lecz koncepcyjnymi reprezentacjami sekcji dokumentu. Tylko do odczytu String[].

**Zwraca:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

Określa grupowanie części dokumentu i liczbę części w każdej grupie. Tylko do odczytu IHeadingPair[].

**Zwraca:**
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Klonuje bieżący obiekt

**Zwraca:**
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

Klonuje bieżący obiekt

**Zwraca:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone