---
title: IFonts
second_title: Aspose.Slides for Java API Reference
description: Stellt eine Sammlung von Schriftarten dar.
type: docs
url: /de/com.aspose.slides/ifonts/
---```
public interface IFonts
```

Stellt eine Sammlung von Schriftarten dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | Gibt die Lateinische Schrift zurück oder legt sie fest. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Gibt die Lateinische Schrift zurück oder legt sie fest. |
| [getEastAsianFont()](#getEastAsianFont--) | Gibt die ostasiatische Schrift zurück oder legt sie fest. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Gibt die ostasiatische Schrift zurück oder legt sie fest. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Gibt die komplexe Skript-Schrift zurück oder legt sie fest. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Gibt die komplexe Skript-Schrift zurück oder legt sie fest. |
| [getScriptFontMap()](#getScriptFontMap--) | Gibt ein Wörterbuch aller Skript-Schriftdefinitionen in der Präsentation zurück. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Ruft den Schriftartnamen ab, der einem bestimmten Skript-Tag im Präsentationsthema zugeordnet ist. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Weist einem bestimmten Skript-Tag einen Schriftartnamen zu, der bestimmt, wie Text dieses Skripts in der Präsentation gerendert wird. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Entfernt die Schriftarteinstellung, die einem bestimmten Skript-Tag zugeordnet ist, aus der Schriftartsammlung des Themas. |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Gibt die Lateinische Schrift zurück oder legt sie fest. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Gibt die Lateinische Schrift zurück oder legt sie fest. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Gibt die ostasiatische Schrift zurück oder legt sie fest. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Gibt die ostasiatische Schrift zurück oder legt sie fest. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Gibt die komplexe Skript-Schrift zurück oder legt sie fest. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Gibt die komplexe Skript-Schrift zurück oder legt sie fest. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

Gibt ein Wörterbuch aller Skript-Schriftdefinitionen in der Präsentation zurück.

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
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - Ein Wörterbuch, das Skriptcodes Schriftartnamen zuordnet.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```

Ruft den Schriftartnamen ab, der einem bestimmten Skript-Tag im Präsentationsthema zugeordnet ist.

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
| script | java.lang.String | Der BCP-47 Skriptcode (z.B. "Latn", "Cyrl", "Jpan") zur Identifizierung eines Schriftsystems. |

**Rückgabe:**
java.lang.String - Der Name der für das angegebene Skript verwendeten Schriftart, oder null, falls das Skript nicht definiert ist.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```

Weist einem bestimmten Skript-Tag einen Schriftartnamen zu, der bestimmt, wie Text dieses Skripts in der Präsentation gerendert wird.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| script | java.lang.String | Der BCP-47 Skriptcode (z.B. "Arab", "Hebr", "Hans") zur Identifizierung des Schriftsystems. |
| fontName | java.lang.String | Der Name der Schriftart, die dem angegebenen Skript zugeordnet werden soll. |
### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```

Entfernt die Schriftarteinstellung, die einem bestimmten Skript-Tag zugeordnet ist, aus der Schriftartsammlung des Themas.

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| script | java.lang.String | Der BCP-47 Skriptcode, dessen Schriftarteinstellung entfernt werden soll. |