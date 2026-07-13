---
title: Fonts
second_title: Aspose.Slides dla Androida poprzez odwołanie do interfejsu API Java
description: Kolekcja czcionek.
type: docs
url: /pl/com.aspose.slides/fonts/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

Kolekcja czcionek.
## Metody

| Metoda | Opis |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | Zwraca słownik wszystkich definicji czcionek skryptowych w prezentacji. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Pobiera nazwę czcionki powiązaną ze specyficznym tagiem skryptu z motywu prezentacji. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Przypisuje nazwę czcionki do określonego tagu skryptu, co definiuje sposób renderowania tekstu tego skryptu w prezentacji. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Usuwa ustawienie czcionki powiązane z określonym tagiem skryptu z kolekcji czcionek motywu. |
| [getLatinFont()](#getLatinFont--) | Zwraca lub ustawia czcionkę łacińską. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Zwraca lub ustawia czcionkę łacińską. |
| [getEastAsianFont()](#getEastAsianFont--) | Zwraca lub ustawia czcionkę wschodnioazjatycką. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Zwraca lub ustawia czcionkę wschodnioazjatycką. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Zwraca lub ustawia czcionkę skryptów złożonych. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Zwraca lub ustawia czcionkę skryptów złożonych. |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```


Zwraca słownik wszystkich definicji czcionek skryptowych w prezentacji.

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```


**Zwraca:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - Słownik mapujący kody skryptów na nazwy czcionek.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public final String getScriptFont(String script)
```


Pobiera nazwę czcionki powiązaną ze specyficznym tagiem skryptu z motywu prezentacji.

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| script | java.lang.String | Kod skryptu BCP-47 (np. "Latn", "Cyrl", "Jpan") używany do identyfikacji systemu pisma. |

**Zwraca:**
java.lang.String - Nazwa czcionki używanej dla określonego skryptu lub  null  jeśli skrypt nie jest zdefiniowany.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```


Przypisuje nazwę czcionki do określonego tagu skryptu, co definiuje sposób renderowania tekstu tego skryptu w prezentacji.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| script | java.lang.String | Kod skryptu BCP-47 (np. "Arab", "Hebr", "Hans") identyfikujący system pisma. |
| fontName | java.lang.String | Nazwa czcionki do przypisania określonemu skryptowi. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```


Usuwa ustawienie czcionki powiązane z określonym tagiem skryptu z kolekcji czcionek motywu.

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| script | java.lang.String | Kod skryptu BCP-47, którego ustawienie czcionki ma zostać usunięte. |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```


Zwraca lub ustawia czcionkę łacińską. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```


Zwraca lub ustawia czcionkę łacińską. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```


Zwraca lub ustawia czcionkę wschodnioazjatycką. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```


Zwraca lub ustawia czcionkę wschodnioazjatycką. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```


Zwraca lub ustawia czcionkę skryptów złożonych. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```


Zwraca lub ustawia czcionkę skryptów złożonych. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |