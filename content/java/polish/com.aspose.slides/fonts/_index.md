---
title: Fonts
second_title: Referencja API Aspose.Slides dla Java
description: Zbiór czcionek.
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

Zbiór czcionek.
## Metody

| Metoda | Opis |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | Zwraca słownik wszystkich definicji czcionek skryptów w prezentacji. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Pobiera nazwę czcionki powiązaną z określonym tagiem skryptu z tematu prezentacji. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Przypisuje nazwę czcionki do określonego tagu skryptu, co definiuje sposób renderowania tekstu tego skryptu w prezentacji. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Usuwa ustawienie czcionki powiązane z określonym tagiem skryptu ze zbioru czcionek tematu. |
| [getLatinFont()](#getLatinFont--) | Zwraca lub ustawia czcionkę łacińską. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Zwraca lub ustawia czcionkę łacińską. |
| [getEastAsianFont()](#getEastAsianFont--) | Zwraca lub ustawia czcionkę wschodnioazjatycką. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Zwraca lub ustawia czcionkę wschodnioazjatycką. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Zwraca lub ustawia czcionkę skryptu złożonego. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Zwraca lub ustawia czcionkę skryptu złożonego. |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

Zwraca słownik wszystkich definicji czcionek skryptów w prezentacji.

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

Pobiera nazwę czcionki powiązaną z określonym tagiem skryptu z tematu prezentacji.

--------------------

> ```
> Ten przykład pokazuje, jak pobrać czcionkę przypisaną do skryptu cyrylicy w temacie prezentacji.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| script | java.lang.String | Kod skryptu BCP-47 (np. "Latn", "Cyrl", "Jpan") używany do identyfikacji systemu pisma. |

**Zwraca:**
java.lang.String - Nazwa czcionki używanej dla określonego skryptu, lub  null  jeśli skrypt nie jest zdefiniowany.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```

Przypisuje nazwę czcionki do określonego tagu skryptu, co definiuje sposób renderowania tekstu tego skryptu w prezentacji.

--------------------

> ```
> Ten przykład pokazuje, jak ustawić czcionkę dla skryptu arabskiego na "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| script | java.lang.String | Kod skryptu BCP-47 (np. "Arab", "Hebr", "Hans") identyfikujący system pisma. |
| fontName | java.lang.String | Nazwa czcionki, którą należy przypisać do określonego skryptu. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```

Usuwa ustawienie czcionki powiązane z określonym tagiem skryptu ze zbioru czcionek tematu.

--------------------

> ```
> Ten przykład pokazuje, jak usunąć mapowanie czcionki dla skryptu hebrajskiego:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| script | java.lang.String | Kod skryptu BCP-47, dla którego ustawienie czcionki powinno zostać usunięte. |

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

Zwraca lub ustawia czcionkę skryptu złożonego. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Zwraca lub ustawia czcionkę skryptu złożonego. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |