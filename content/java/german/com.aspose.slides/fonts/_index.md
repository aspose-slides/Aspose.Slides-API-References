---
title: Fonts
second_title: Aspose.Slides für Java API Referenz
description: Schriftartensammlung.
type: docs
url: /de/com.aspose.slides/fonts/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

Schriftartensammlung.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | Gibt ein Wörterbuch aller Skript-Schriftartdefinitionen in der Präsentation zurück. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Gibt den Schriftartnamen zurück, der mit einem bestimmten Skript-Tag aus dem Präsentationsthema verknüpft ist. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Ordnet einem bestimmten Skript-Tag einen Schriftartnamen zu, der definiert, wie Text dieses Skripts in der Präsentation gerendert wird. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Entfernt die Schriftarteinstellung, die mit einem bestimmten Skript-Tag aus der Schriftartsammlung des Themas verknüpft ist. |
| [getLatinFont()](#getLatinFont--) | Gibt die Lateinische Schriftart zurück oder legt sie fest. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Gibt die Lateinische Schriftart zurück oder legt sie fest. |
| [getEastAsianFont()](#getEastAsianFont--) | Gibt die Ostasiatische Schriftart zurück oder legt sie fest. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Gibt die Ostasiatische Schriftart zurück oder legt sie fest. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Gibt die komplexe Skript-Schriftart zurück oder legt sie fest. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Gibt die komplexe Skript-Schriftart zurück oder legt sie fest. |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
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
public final String getScriptFont(String script)
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
| script | java.lang.String | Der BCP-47 Skriptcode (z. B. "Latn", "Cyrl", "Jpan"), der ein Schriftsystem identifiziert. |

**Rückgabe:**
java.lang.String - Der Name der für das angegebene Skript verwendeten Schriftart, oder  null  wenn das Skript nicht definiert ist.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```

Ordnet einem bestimmten Skript-Tag einen Schriftartnamen zu, der definiert, wie Text dieses Skripts in der Präsentation gerendert wird.

--------------------

> ```
> Dieses Beispiel zeigt, wie man die Schriftart für das Arabische Skript auf "Segoe UI" setzt:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| script | java.lang.String | Der BCP-47 Skriptcode (z. B. "Arab", "Hebr", "Hans"), der das Schriftsystem identifiziert. |
| fontName | java.lang.String | Der Name der Schriftart, die dem angegebenen Skript zugewiesen werden soll. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```

Entfernt die Schriftarteinstellung, die mit einem bestimmten Skript-Tag aus der Schriftartsammlung des Themas verknüpft ist.

--------------------

> ```
> Dieses Beispiel demonstriert, wie man die Schriftzuordnung für das Hebräische Skript entfernt:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| script | java.lang.String | Der BCP-47 Skriptcode, dessen Schriftarteinstellung entfernt werden soll. |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Gibt die Lateinische Schriftart zurück oder legt sie fest. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Gibt die Lateinische Schriftart zurück oder legt sie fest. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Gibt die Ostasiatische Schriftart zurück oder legt sie fest. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Gibt die Ostasiatische Schriftart zurück oder legt sie fest. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Gibt die komplexe Skript-Schriftart zurück oder legt sie fest. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Rückgabe:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Gibt die komplexe Skript-Schriftart zurück oder legt sie fest. Lesen/Schreiben [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |