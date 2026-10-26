---
title: IFonts
second_title: Aspose.Slides for Android via Java API Reference
description: Reprezentuje kolekcję czcionek.
type: docs
url: /pl/com.aspose.slides/ifonts/
---```
public interface IFonts
```

Reprezentuje kolekcję czcionek.

## Metody

| Metoda | Opis |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | Zwraca lub ustawia czcionkę łacińską. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Zwraca lub ustawia czcionkę łacińską. |
| [getEastAsianFont()](#getEastAsianFont--) | Zwraca lub ustawia czcionkę wschodnioazjatycką. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Zwraca lub ustawia czcionkę wschodnioazjatycką. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Zwraca lub ustawia czcionkę skryptu złożonego. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Zwraca lub ustawia czcionkę skryptu złożonego. |
| [getScriptFontMap()](#getScriptFontMap--) | Zwraca słownik wszystkich definicji czcionek skryptowych w prezentacji. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Pobiera nazwę czcionki powiązaną z określonym tagiem skryptu z motywu prezentacji. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Przypisuje nazwę czcionki do określonego tagu skryptu, co definiuje sposób renderowania tekstu tego skryptu w prezentacji. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Usuwa ustawienie czcionki powiązane z określonym tagiem skryptu z kolekcji czcionek motywu. |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Zwraca lub ustawia czcionkę łacińską. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Zwraca lub ustawia czcionkę łacińską. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Zwraca lub ustawia czcionkę wschodnioazjatycką. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Zwraca lub ustawia czcionkę wschodnioazjatycką. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Zwraca lub ustawia czcionkę skryptu złożonego. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Zwraca lub ustawia czcionkę skryptu złożonego. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
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
public abstract String getScriptFont(String script)
```

Pobiera nazwę czcionki powiązaną z określonym tagiem skryptu z motywu prezentacji.

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
java.lang.String - Nazwa czcionki używana dla określonego skryptu lub null, jeśli skrypt nie jest zdefiniowany.

### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
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
| fontName | java.lang.String | Nazwa czcionki do przypisania do określonego skryptu. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
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
| script | java.lang.String | Kod skryptu BCP-47, którego ustawienie czcionki powinno zostać usunięte. |