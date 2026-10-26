---
title: ISensitivityLabelCollection
second_title: Aspose.Slides dla Androida - odniesienie Java API
description: Reprezentuje kolekcję etykiet wrażliwości zastosowanych do dokumentu.
type: docs
url: /pl/com.aspose.slides/isensitivitylabelcollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
```

Reprezentuje kolekcję etykiet wrażliwości zastosowanych do dokumentu.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca etykietę wrażliwości według indeksu. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Dodaje etykietę wrażliwości na końcu kolekcji. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Dodaje SensitivityLabel do kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa etykietę wrażliwości pod wskazanym indeksem. |
| [clear()](#clear--) | Usuwa wszystkie elementy z kolekcji. |
| [getCount()](#getCount--) | Pobiera liczbę wszystkich elementów w kolekcji. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```


Zwraca etykietę wrażliwości według indeksu. Tylko do odczytu [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
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
public abstract int add(ISensitivityLabel label)
```


Dodaje SensitivityLabel do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | Obiekt SensitivityLabel, który ma zostać dodany na końcu kolekcji. |

**Zwraca:**
int - Indeks, pod którym dodano SensitivityLabel.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Usuwa etykietę wrażliwości pod wskazanym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks etykiety wrażliwości, którą należy usunąć. |

### clear() {#clear--}
```
public abstract void clear()
```


Usuwa wszystkie elementy z kolekcji.

### getCount() {#getCount--}
```
public abstract int getCount()
```


Pobiera liczbę wszystkich elementów w kolekcji. Tylko do odczytu int .

**Zwraca:**
int