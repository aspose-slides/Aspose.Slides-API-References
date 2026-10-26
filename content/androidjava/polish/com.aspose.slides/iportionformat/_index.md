---
title: IPortionFormat
second_title: Aspose.Slides dla Androida – odwołanie API Java
description: Ta klasa zawiera właściwości formatowania fragmentu tekstu.
type: docs
url: /pl/com.aspose.slides/iportionformat/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

Ta klasa zawiera właściwości formatowania fragmentu tekstu. W przeciwieństwie do [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), wszystkie właściwości tej klasy są zapisywalne.

--------------------

Ta klasa służy do zwracania i manipulowania właściwościami formatowania fragmentu tekstu zdefiniowanymi dla konkretnego fragmentu. Oznacza to, że przy pobieraniu wartości nie jest stosowane dziedziczenie, więc w większości przypadków otrzymasz wartości oznaczające „niezdefiniowane”.

Aby uzyskać skuteczne wartości parametrów formatowania, w tym odziedziczone, należy użyć metody [getEffective](../../com.aspose.slides/iportionformat\#getEffective), która zwraca instancję [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## Metody

| Metoda | Opis |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Zwraca lub ustawia identyfikator zakładki. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Zwraca lub ustawia identyfikator zakładki. |
| [getSmartTagClean()](#getSmartTagClean--) | Określa, czy znacznik inteligentny powinien być wyczyszczony. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Określa, czy znacznik inteligentny powinien być wyczyszczony. |
| [getEffective()](#getEffective--) | Pobiera skuteczne dane formatowania fragmentu z zastosowanym dziedziczeniem. |

### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

Zwraca lub ustawia identyfikator zakładki. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```

Zwraca lub ustawia identyfikator zakładki. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

Określa, czy znacznik inteligentny powinien być wyczyszczony. Nie stosuje się dziedziczenia. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

Określa, czy znacznik inteligentny powinien być wyczyszczony. Nie stosuje się dziedziczenia. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

Pobiera skuteczne dane formatowania fragmentu z zastosowanym dziedziczeniem.

**Zwraca:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).