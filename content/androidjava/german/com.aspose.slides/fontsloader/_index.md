---
title: FontsLoader
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Klasse zum Laden benutzerdefinierter Schriften, die vom Benutzer definiert wurden.
type: docs
url: /de/com.aspose.slides/fontsloader/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

Klasse zum Laden benutzerdefinierter Schriften, die vom Benutzer definiert wurden. Sollte verwendet werden, bevor Präsentationsobjekte erstellt werden.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | Fügt zusätzliche Ordner zum Suchen von Schriften hinzu. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | Fügt Schrift aus den Binärdaten hinzu |
| [getFontFolders()](#getFontFolders--) | Ermittelt Schriftordner. |
| [clearCache()](#clearCache--) | Löscht alle vom Benutzer definierten benutzerdefinierten Schriften. |
### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```


Fügt zusätzliche Ordner zum Suchen von Schriften hinzu.

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // Ordner zum Suchen von Schriften
>  String[] folders = new String[] { dataDir };
>  // Lade das benutzerdefinierte Schriftverzeichnis
>  FontsLoader.loadExternalFonts(folders);
>  // Führe einige Arbeiten aus und rendere Präsentation/Folien
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // Schrift-Cache leeren
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| directories | java.lang.String[] | Verzeichnisse zum Lesen zusätzlicher Schriften. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```


Fügt Schrift aus den Binärdaten hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | byte[] | Daten der Schrift |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```


Ruft Schriftordner ab. Gibt Ordner zurück, die mit der LoadExternalFonts-Methode hinzugefügt wurden, sowie Systemschriftordner.

**Rückgabe:**
java.lang.String[] - array containing folder names
### clearCache() {#clearCache--}
```
public static void clearCache()
```


Löscht alle vom Benutzer definierten benutzerdefinierten Schriften.

--------------------

Diese Methode muss den Cache mit benutzerdefinierten Schriften leeren, die vom Benutzer definiert wurden.