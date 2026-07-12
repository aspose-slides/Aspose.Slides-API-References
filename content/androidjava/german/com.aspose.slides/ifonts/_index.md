---
title: IFonts
second_title: Aspose.Slides for Android via Java API Reference
description: Represents fonts collection.
type: docs
url: /de/com.aspose.slides/ifonts/
---```
public interface IFonts
```

Stellt die Schriftartensammlung dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | Gibt die Latin-Schriftart zurück oder setzt sie. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Gibt die Latin-Schriftart zurück oder setzt sie. |
| [getEastAsianFont()](#getEastAsianFont--) | Gibt die East Asian-Schriftart zurück oder setzt sie. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Gibt die East Asian-Schriftart zurück oder setzt sie. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Gibt die complex script-Schriftart zurück oder setzt sie. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Gibt die complex script-Schriftart zurück oder setzt sie. |
| [getScriptFontMap()](#getScriptFontMap--) | Gibt ein Wörterbuch aller Skript-Schriftartdefinitionen in der Präsentation zurück. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Gibt den Schriftartnamen zurück, der mit einem bestimmten Skript-Tag aus dem Präsentationsthema verknüpft ist. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Weist einem bestimmten Skript-Tag einen Schriftartnamen zu, der definiert, wie Text dieses Skripts in der Präsentation gerendert wird. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Entfernt die Schriftarteinstellung, die mit einem bestimmten Skript-Tag aus der Schriftartsammlung des Themas verknüpft ist. |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Gibt die Latin-Schriftart zurück oder setzt sie. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Gibt die Latin-Schriftart zurück oder setzt sie. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Gibt die East Asian-Schriftart zurück oder setzt sie. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Gibt die East Asian-Schriftart zurück oder setzt sie. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Gibt die complex script-Schriftart zurück oder setzt sie. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Gibt die complex script-Schriftart zurück oder setzt sie. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

Gibt ein Wörterbuch aller Skript-Schriftartdefinitionen in der Präsentation zurück.

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```


**Rückgabe:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - A dictionary mapping script codes to font names.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```

Gibt den Schriftartnamen zurück, der mit einem bestimmten Skript-Tag aus dem Präsentationsthema verknüpft ist.

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| script | java.lang.String | Der BCP-47-Skriptcode (z. B. "Latn", "Cyrl", "Jpan"), der ein Schriftsystem identifiziert. |

**Rückgabe:**
java.lang.String - Der Name der für das angegebene Skript verwendeten Schriftart, oder  null  falls das Skript nicht definiert ist.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```

Weist einem bestimmten Skript-Tag einen Schriftartnamen zu, der definiert, wie Text dieses Skripts in der Präsentation gerendert wird.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| script | java.lang.String | Der BCP-47-Skriptcode (z. B. "Arab", "Hebr", "Hans"), der das Schriftsystem identifiziert. |
| fontName | java.lang.String | Der Name der Schriftart, die dem angegebenen Skript zugewiesen werden soll. |
### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```

Entfernt die Schriftarteinstellung, die mit einem bestimmten Skript-Tag aus der Schriftartsammlung des Themas verknüpft ist.

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| script | java.lang.String | Der BCP-47-Skriptcode, dessen Schriftarteinstellung entfernt werden soll. |