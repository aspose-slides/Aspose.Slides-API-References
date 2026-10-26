---
title: FontsLoader
second_title: Aspose.Slides für Java API-Referenz
description: Klasse zum Laden benutzerdefinierter Schriftarten, die vom Benutzer definiert wurden.
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

Klasse zum Laden von benutzerdefinierten Schriftarten. Sollte vor dem Erstellen von Präsentationsobjekten verwendet werden.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | Fügt zusätzliche Ordner zum Suchen von Schriftarten hinzu. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | Fügt die Schriftart aus den Binärdaten hinzu. |
| [getFontFolders()](#getFontFolders--) | Ermittelt Schriftordner. |
| [clearCache()](#clearCache--) | Gibt alle vom Benutzer definierten benutzerdefinierten Schriftarten frei. |
### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```


Fügt zusätzliche Ordner zum Suchen von Schriftarten hinzu.

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // Ordner zum Suchen von Schriften
>  String[] folders = new String[] { dataDir };
>  // Lade das benutzerdefinierte Schriftartenverzeichnis
>  FontsLoader.loadExternalFonts(folders);
>  // Führe einige Arbeiten aus und rendere die Präsentation/Folien
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // Font-Cache leeren
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| directories | java.lang.String[] | Verzeichnisse zum Lesen zusätzlicher Schriftarten. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```


Fügt die Schriftart aus den Binärdaten hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | byte[] | Daten der Schriftart |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```


Ermittelt Schriftordner. Gibt Ordner zurück, die mit der Methode LoadExternalFonts hinzugefügt wurden, sowie Systemschriftordner.

**Rückgabewert:**
java.lang.String[] - Array, das Ordnernamen enthält
### clearCache() {#clearCache--}
```
public static void clearCache()
```


Gibt alle vom Benutzer definierten benutzerdefinierten Schriftarten frei.

--------------------

Diese Methode muss den Cache mit den vom Benutzer definierten benutzerdefinierten Schriftarten leeren.