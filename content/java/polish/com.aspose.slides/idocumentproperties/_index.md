---
title: IDocumentProperties
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje właściwości prezentacji.
type: docs
url: /pl/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

Reprezentuje właściwości prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Zwraca wersję aplikacji. |
| [getNameOfApplication()](#getNameOfApplication--) | Zwraca lub ustawia nazwę aplikacji. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Zwraca lub ustawia nazwę aplikacji. |
| [getCompany()](#getCompany--) | Zwraca lub ustawia właściwość firmy. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Zwraca lub ustawia właściwość firmy. |
| [getManager()](#getManager--) | Zwraca lub ustawia właściwość menedżera. |
| [setManager(String value)](#setManager-java.lang.String-) | Zwraca lub ustawia właściwość menedżera. |
| [getPresentationFormat()](#getPresentationFormat--) | Zwraca lub ustawia zamierzony format prezentacji. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Zwraca lub ustawia zamierzony format prezentacji. |
| [getSharedDoc()](#getSharedDoc--) | Określa, czy prezentacja jest współdzielona przez wielu użytkowników. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Określa, czy prezentacja jest współdzielona przez wielu użytkowników. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Zwraca lub ustawia szablon aplikacji. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Zwraca lub ustawia szablon aplikacji. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Całkowity czas edycji prezentacji. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Całkowity czas edycji prezentacji. |
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
| [getLastSavedBy()](#getLastSavedBy--) | Zwraca lub ustawia imię i nazwisko ostatniej osoby modyfikującej prezentację. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Zwraca lub ustawia imię i nazwisko ostatniej osoby modyfikującej prezentację. |
| [getRevisionNumber()](#getRevisionNumber--) | Zwraca lub ustawia numer wersji prezentacji. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Zwraca lub ustawia numer wersji prezentacji. |
| [getContentStatus()](#getContentStatus--) | Zwraca lub ustawia status treści prezentacji. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Zwraca lub ustawia status treści prezentacji. |
| [getContentType()](#getContentType--) | Zwraca lub ustawia typ treści prezentacji. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Zwraca lub ustawia typ treści prezentacji. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Zwraca lub ustawia właściwość dokumentu HyperlinkBase. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Zwraca lub ustawia właściwość dokumentu HyperlinkBase. |
| [getScaleCrop()](#getScaleCrop--) | Wskazuje tryb wyświetlania miniatury dokumentu. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Wskazuje tryb wyświetlania miniatury dokumentu. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Wskazuje, czy hiperłącza w dokumencie są aktualne. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Wskazuje, czy hiperłącza w dokumencie są aktualne. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Określa, że jedno lub więcej hiperłączy w tej części zostało zaktualizowanych wyłącznie w tej części przez producenta. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Określa, że jedno lub więcej hiperłączy w tej części zostało zaktualizowanych wyłącznie w tej części przez producenta. |
| [getSlides()](#getSlides--) | Określa całkowitą liczbę slajdów w dokumencie prezentacji. |
| [getHiddenSlides()](#getHiddenSlides--) | Określa liczbę ukrytych slajdów w dokumencie prezentacji. |
| [getNotes()](#getNotes--) | Określa liczbę slajdów w prezentacji zawierających notatki. |
| [getParagraphs()](#getParagraphs--) | Określa łączną liczbę akapitów w dokumencie, jeśli dotyczy. |
| [getWords()](#getWords--) | Określa łączną liczbę słów w dokumencie. |
| [getMultimediaClips()](#getMultimediaClips--) | Określa łączną liczbę klipów dźwiękowych lub wideo w dokumencie. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Określa tytuł każdej części dokumentu. |
| [getHeadingPairs()](#getHeadingPairs--) | Wskazuje grupowanie części dokumentu i liczbę części w każdej grupie. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Zwraca liczbę niestandardowych właściwości faktycznie zawartych w kolekcji. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Zwraca nazwę niestandardowej właściwości pod określonym indeksem. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Usuwa niestandardową właściwość powiązaną z określoną nazwą. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Sprawdza obecność niestandardowej właściwości o określonej nazwie. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Zwraca lub ustawia niestandardową właściwość powiązaną z określoną nazwą. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Zwraca lub ustawia niestandardową właściwość powiązaną z określoną nazwą. |
| [clearCustomProperties()](#clearCustomProperties--) | Usuwa wszystkie niestandardowe właściwości. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Czyści i ustawia wartości domyślne dla wszystkich wbudowanych właściwości. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Pobiera nazwany wartość logiczną z niestandardowych właściwości. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Pobiera nazwany wartość całkowitą z niestandardowych właściwości. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Pobiera nazwany wartość DateTime z niestandardowych właściwości. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Pobiera nazwany wartość tekstową z niestandardowych właściwości. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Pobiera nazwany wartość zmiennoprzecinkową (float) z niestandardowych właściwości. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Pobiera nazwany wartość zmiennoprzecinkową (double) z niestandardowych właściwości. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Ustawia nazwany boolean jako niestandardową właściwość. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Ustawia nazwany integer jako niestandardową właściwość. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Ustawia nazwany DateTime jako niestandardową właściwość. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Ustawia nazwany string jako niestandardową właściwość. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Ustawia nazwany float jako niestandardową właściwość. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Ustawia nazwany double jako niestandardową właściwość. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Pobiera tablicę etykiet wrażliwości z niestandardowych właściwości dokumentu (Microsoft Information Protection SDK Metadata). |

### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

Zwraca wersję aplikacji. Tylko do odczytu String.

--------------------

Zawartość tego elementu musi mieć postać XX.YYYY, gdzie X i Y reprezentują wartości liczbowe; w przeciwnym razie dokument będzie uznany za niezgodny. Aspose.Slides reprezentuje swoją wersję w formacie XX.YY.ZZ, gdzie: XX – wersja główna YY – wersja podrzędna ZZ – wersja poprawki. Na przykład wartość 23.0105 oznacza wersję Aspose.Slides 23.1.5.

**Zwraca:**
java.lang.String

### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

Zwraca lub ustawia nazwę aplikacji. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```

Zwraca lub ustawia nazwę aplikacji. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public abstract String getCompany()
```

Zwraca lub ustawia właściwość firmy. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

Zwraca lub ustawia właściwość firmy. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public abstract String getManager()
```

Zwraca lub ustawia właściwość menedżera. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

Zwraca lub ustawia właściwość menedżera. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

Zwraca lub ustawia zamierzony format prezentacji. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

Zwraca lub ustawia zamierzony format prezentacji. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

Określa, czy prezentacja jest współdzielona przez wielu użytkowników. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

Określa, czy prezentacja jest współdzielona przez wielu użytkowników. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

Zwraca lub ustawia szablon aplikacji. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```

Zwraca lub ustawia szablon aplikacji. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```

Całkowity czas edycji prezentacji. Odczyt/zapis double.

**Zwraca:**
double

### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

Całkowity czas edycji prezentacji. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

Zwraca lub ustawia tytuł prezentacji. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

Zwraca lub ustawia tytuł prezentacji. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public abstract String getSubject()
```

Zwraca lub ustawia temat prezentacji. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```

Zwraca lub ustawia temat prezentacji. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```

Zwraca lub ustawia autora prezentacji. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```

Zwraca lub ustawia autora prezentacji. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```

Zwraca lub ustawia słowa kluczowe prezentacji. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

Zwraca lub ustawia słowa kluczowe prezentacji. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract String getComments()
```

Zwraca lub ustawia komentarze prezentacji. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

Zwraca lub ustawia komentarze prezentacji. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public abstract String getCategory()
```

Zwraca lub ustawia kategorię prezentacji. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```

Zwraca lub ustawia kategorię prezentacji. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |

| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```


Zwraca datę utworzenia prezentacji. Wartości są w formacie UTC. Odczyt/zapis java.util.Date.

**Zwraca:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```


Zwraca datę utworzenia prezentacji. Wartości są w formacie UTC. Odczyt/zapis java.util.Date.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```


Zwraca datę ostatniej modyfikacji prezentacji. Wartości są w formacie UTC. P Tylko do odczytu w przypadku Presentation.DocumentProperties (ponieważ będzie aktualizowane wewnętrznie podczas procesu zapisu obiektu IPresentation). Można zmienić za pośrednictwem instancji DocumentProperties zwracanej metodą [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Zobacz przykład w podsumowaniu metody [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Zwraca:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```


Zwraca datę ostatniej modyfikacji prezentacji. Wartości są w formacie UTC. P Tylko do odczytu w przypadku Presentation.DocumentProperties (ponieważ będzie aktualizowane wewnętrznie podczas procesu zapisu obiektu IPresentation). Można zmienić za pośrednictwem instancji DocumentProperties zwracanej metodą [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Zobacz przykład w podsumowaniu metody [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```


Zwraca datę, kiedy prezentacja została ostatnio wydrukowana. Odczyt/zapis java.util.Date.

**Zwraca:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```


Zwraca datę, kiedy prezentacja została ostatnio wydrukowana. Odczyt/zapis java.util.Date.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```


Zwraca lub ustawia nazwisko ostatniej osoby, która modyfikowała prezentację. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```


Zwraca lub ustawia nazwisko ostatniej osoby, która modyfikowała prezentację. Odczyt/zapis String.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```


Zwraca lub ustawia numer wersji prezentacji. Odczyt/zapis int.

**Zwraca:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```


Zwraca lub ustawia numer wersji prezentacji. Odczyt/zapis int.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```


Zwraca lub ustawia status zawartości prezentacji. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```


Zwraca lub ustawia status zawartości prezentacji. Odczyt/zapis String.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Zwraca lub ustawia typ zawartości prezentacji. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```


Zwraca lub ustawia typ zawartości prezentacji. Odczyt/zapis String.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```


Zwraca lub ustawia właściwość dokumentu HyperlinkBase. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```


Zwraca lub ustawia właściwość dokumentu HyperlinkBase. Odczyt/zapis String.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```


Wskazuje tryb wyświetlania miniatury dokumentu. Ustaw ten element na **true**, aby włączyć skalowanie miniatury dokumentu do wyświetlacza. Ustaw ten element na **false**, aby włączyć przycinanie miniatury dokumentu tak, aby wyświetlał tylko sekcje pasujące do wyświetlacza. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```


Wskazuje tryb wyświetlania miniatury dokumentu. Ustaw ten element na **true**, aby włączyć skalowanie miniatury dokumentu do wyświetlacza. Ustaw ten element na **false**, aby włączyć przycinanie miniatury dokumentu tak, aby wyświetlał tylko sekcje pasujące do wyświetlacza. Odczyt/zapis boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```


Wskazuje, czy hiperłącza w dokumencie są aktualne. Ustaw ten element na **true**, aby zaznaczyć, że hiperłącza są zaktualizowane. Ustaw ten element na **false**, aby zaznaczyć, że hiperłącza są nieaktualne. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```


Wskazuje, czy hiperłącza w dokumencie są aktualne. Ustaw ten element na **true**, aby zaznaczyć, że hiperłącza są zaktualizowane. Ustaw ten element na **false**, aby zaznaczyć, że hiperłącza są nieaktualne. Odczyt/zapis boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```


Określa, że jedno lub więcej hiperłączy w tej części zostało zaktualizowanych wyłącznie w tej części przez producenta. Następny producent otwierający dokument powinien zaktualizować relacje hiperłączy przy użyciu nowych hiperłączy określonych w tej części. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```


Określa, że jedno lub więcej hiperłączy w tej części zostało zaktualizowanych wyłącznie w tej części przez producenta. Następny producent otwierający dokument powinien zaktualizować relacje hiperłączy przy użyciu nowych hiperłączy określonych w tej części. Odczyt/zapis boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```


Określa całkowitą liczbę slajdów w dokumencie prezentacji. Tylko do odczytu int.

**Zwraca:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```


Określa liczbę ukrytych slajdów w dokumencie prezentacji. Tylko do odczytu int.

**Zwraca:**
int
### getNotes() {#getNotes--}
```
public abstract int getNotes()
```


Określa liczbę slajdów w prezentacji zawierających notatki. Tylko do odczytu int.

**Zwraca:**
int
### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```


Określa całkowitą liczbę akapitów znalezionych w dokumencie, jeśli dotyczy. Tylko do odczytu int.

**Zwraca:**
int
### getWords() {#getWords--}
```
public abstract int getWords()
```


Określa całkowitą liczbę słów zawartych w dokumencie. Tylko do odczytu int.

**Zwraca:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```


Określa całkowitą liczbę klipów dźwiękowych lub wideo, które są obecne w dokumencie. Tylko do odczytu int.

**Zwraca:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```


Określa tytuł każdej części dokumentu. Te części nie są fizycznymi częściami dokumentu, lecz koncepcyjnymi reprezentacjami sekcji dokumentu. Tylko do odczytu String[].

**Zwraca:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```


Wskazuje grupowanie części dokumentu i liczbę części w każdej grupie. Tylko do odczytu IHeadingPair[].

**Zwraca:**
com.aspose.slides.IHeadingPair[]
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```


Zwraca liczbę własnych właściwości faktycznie zawartych w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```


Zwraca nazwę własnej właściwości w podanym indeksie.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Zero-based indeks własnej właściwości do pobrania. |

**Zwraca:**
java.lang.String - Nazwa własnej właściwości w podanym indeksie.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```


Usuwa własną właściwość powiązaną z określoną nazwą.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nazwa własnej właściwości do usunięcia. |

**Zwraca:**
boolean - Zwraca true, jeśli właściwość została usunięta, w przeciwnym razie false.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```


Sprawdza obecność własnej właściwości o określonej nazwie.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nazwa własnej właściwości do sprawdzenia. |

**Zwraca:**
boolean - Zwraca true, jeśli właściwość istnieje, false w przeciwnym razie.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```


Zwraca lub ustawia własną właściwość powiązaną z określoną nazwą. Odczyt/zapis Object.

--------------------

Wartość może być **int**, **float**, **double**, **String**, **boolean** lub **Date**.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Zwraca:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```


Zwraca lub ustawia własną właściwość powiązaną z określoną nazwą. Odczyt/zapis Object.

--------------------

Wartość może być **int**, **float**, **double**, **String**, **boolean** lub **Date**.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### clearCustomProperties() {#clearCustomProperties--}
```
public abstract void clearCustomProperties()
```


Usuwa wszystkie własne właściwości.

### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract void clearBuiltInProperties()
```


Czyści i ustawia domyślne wartości dla wszystkich wbudowanych właściwości.

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```


Pobiera nazwany wartość typu boolean z własnych właściwości.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nazwa własnej właściwości do pobrania |
| value | boolean[] | Wartość własnej właściwości |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```


Pobiera nazwany wartość typu int z własnych właściwości.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nazwa własnej właściwości do pobrania |
| value | int[] | Wartość własnej właściwości |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```


Pobiera nazwany wartość typu Date z własnych właściwości.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nazwa własnej właściwości do pobrania |
| value | java.util.Date[] | Wartość własnej właściwości |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```


Pobiera nazwany wartość typu String z własnych właściwości.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nazwa własnej właściwości do pobrania |
| value | java.lang.String[] | Wartość własnej właściwości |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```


Pobiera nazwany wartość typu float z własnych właściwości.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nazwa własnej właściwości do pobrania |
| value | float[] | Wartość własnej właściwości |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```


Pobiera nazwany wartość typu double z własnych właściwości.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nazwa własnej właściwości do pobrania |
| value | double[] | Wartość własnej właściwości |
| nazwa | java.lang.String | Nazwa własności niestandardowej do pobrania. |
| wartość | double[] | Wartość własności niestandardowej |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

Ustawia nazwane własność typu boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa własności niestandardowej do ustawienia |
| value | boolean | Wartość własności niestandardowej |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

Ustawia nazwane własność typu całkowitą.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa własności niestandardowej do ustawienia |
| value | int | Wartość własności niestandardowej |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

Ustawia nazwane własność typu DateTime.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa własności niestandardowej do ustawienia |
| value | java.util.Date | Wartość własności niestandardowej |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

Ustawia nazwane własność typu string.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa własności niestandardowej do ustawienia |
| value | java.lang.String | Wartość własności niestandardowej |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

Ustawia nazwane własność typu float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa własności niestandardowej do ustawienia |
| value | float | Wartość własności niestandardowej |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

Ustawia nazwane własność typu double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa własności niestandardowej do ustawienia |
| value | double | Wartość własności niestandardowej |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

Pobiera tablicę etykiet wrażliwości z niestandardowych własności dokumentu (Microsoft Information Protection SDK Metadata).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Pobierz etykiety wrażliwości z własności dokumentu
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