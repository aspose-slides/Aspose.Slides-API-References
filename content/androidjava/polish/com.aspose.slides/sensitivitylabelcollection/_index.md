---
title: SensitivityLabelCollection
second_title: Aspose.Slides dla Androida przez interfejs API Java
description: Reprezentuje kolekcję etykiet wrażliwości zastosowanych w dokumencie.
type: docs
url: /pl/com.aspose.slides/sensitivitylabelcollection/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

Reprezentuje kolekcję etykiet wrażliwości zastosowanych w dokumencie.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca etykietę wrażliwości według indeksu. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Dodaje etykietę wrażliwości na końcu kolekcji. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Dodaje SensitivityLabel do kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa etykietę wrażliwości o podanym indeksie. |
| [clear()](#clear--) | Usuwa wszystkie elementy z kolekcji. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [getCount()](#getCount--) | Zwraca liczbę elementów w kolekcji. |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | Kopiuje wszystkie elementy z kolekcji do określonej tablicy. |
### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```


Zwraca etykietę wrażliwości według indeksu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```


Dodaje etykietę wrażliwości na końcu kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| id | java.lang.String | Identyfikator etykiety wrażliwości. |
| siteId | java.util.UUID | Identyfikator witryny Azure Active Directory (Azure AD). |
| isEnabled | boolean | Flaga wskazująca, czy etykieta wrażliwości jest włączona. |
| methodType | int | Metoda przypisania etykiety wrażliwości. |

**Zwraca:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```


Dodaje SensitivityLabel do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | Obiekt SensitivityLabel, który ma zostać dodany na końcu kolekcji. |

**Zwraca:**
int - Indeks, pod którym został dodany SensitivityLabel.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Usuwa etykietę wrażliwości o podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks etykiety wrażliwości, która ma zostać usunięta. |

### clear() {#clear--}
```
public final void clear()
```


Usuwa wszystkie elementy z kolekcji.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```


Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - A System.Collections.Generic.IEnumerator1, który może być użyty do iteracji po kolekcji.
### getCount() {#getCount--}
```
public final int getCount()
```


Zwraca liczbę elementów w kolekcji. Tylko do odczytu  int .

**Zwraca:**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```


Kopiuje wszystkie elementy z kolekcji do określonej tablicy.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | Docelowa tablica. |
| index | int | Początkowy indeks w docelowej tablicy. |