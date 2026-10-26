---
title: FontData
second_title: Aspose.Slides dla Androida poprzez odwołanie do interfejsu API Java
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

Reprezentuje definicję czcionki. Nieodwracalny.
## Konstruktorzy

| Konstruktor | Opis |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | Creates a new FontData object with the specified font name. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getFontName()](#getFontName--) | Returns the font name. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Returns the font name, replacing theme referrence with an actual font used. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether two FontData instances are equal. |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table. |
| [toString()](#toString--) | Returns string representation. |
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

Zwraca nazwę czcionki. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

Zwraca nazwę czcionki, zastępując odwołanie do motywu rzeczywistą używaną czcionką.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Motyw, z którego należy pobrać nazwę czcionki tematycznej. To zależy od wywołującego, aby dostarczył prawidłową wartość. Zobacz [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

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
| obj | java.lang.Object | FontData, z którym porównywana jest bieżąca FontData. |

**Zwraca:**
boolean - **true** jeśli określona FontData jest równa bieżącej FontData; w przeciwnym razie **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Służy jako funkcja mieszająca dla danego typu, odpowiednia do użycia w algorytmach haszujących i strukturach danych takich jak tablica mieszająca.

**Zwraca:**
int - Kod hash obiektu FontData.
### toString() {#toString--}
```
public String toString()
```

Zwraca reprezentację łańcucha znaków.

**Zwraca:**
java.lang.String - Reprezentacja łańcucha znaków.