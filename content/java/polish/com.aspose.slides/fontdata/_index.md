---
title: FontData
second_title: Aspose.Slides dla Java API Reference
description: Reprezentuje definicję czcionki.
type: docs
url: /pl/com.aspose.slides/fontdata/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

Reprezentuje definicję czcionki. Niezmienny.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | Tworzy nowy obiekt FontData z określoną nazwą czcionki. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getFontName()](#getFontName--) | Zwraca nazwę czcionki. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Zwraca nazwę czcionki, zastępując odniesienie do motywu rzeczywistą używaną czcionką. |
| [equals(Object obj)](#equals-java.lang.Object-) | Określa, czy dwie instancje FontData są równe. |
| [hashCode()](#hashCode--) | Służy jako funkcja mieszająca dla określonego typu, odpowiednia do użycia w algorytmach mieszających i strukturach danych, takich jak tablica mieszająca. |
| [toString()](#toString--) | Zwraca reprezentację jako łańcuch znaków. |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

Tworzy nowy obiekt FontData z określoną nazwą czcionki.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fontName | java.lang.String | Nazwa czcionki. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```

Zwraca nazwę czcionki. Odczyt/Zapis String.

**Zwraca:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

Zwraca nazwę czcionki, zastępując odniesienie do motywu rzeczywistą używaną czcionką.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Motyw, z którego powinna być pobrana nazwa czcionki tematycznej. To po stronie wywołującego, aby dostarczyć prawidłową wartość. Zobacz [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**Zwraca:**
java.lang.String - Nazwa czcionki.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Określa, czy dwie instancje FontData są równe.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | Obiekt FontData, z którym porównywana jest bieżąca FontData. |

**Zwraca:**
boolean - **true**, jeśli podany FontData jest równy bieżącej FontData; w przeciwnym razie **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Służy jako funkcja mieszająca dla określonego typu, odpowiednia do użycia w algorytmach mieszających i strukturach danych, takich jak tablica mieszająca.

**Zwraca:**
int - Kod hash obiektu FontData.
### toString() {#toString--}
```
public String toString()
```

Zwraca reprezentację jako łańcuch znaków.

**Zwraca:**
java.lang.String - Reprezentacja jako łańcuch znaków.