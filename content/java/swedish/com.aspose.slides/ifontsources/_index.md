---
title: IFontSources
second_title: Aspose.Slides for Java API Reference
description: Tillhandahåller fil- och minneskällor för externa typsnitt.
type: docs
url: /sv/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

Tillhandahåller fil- och minneskällor för externa typsnitt.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Mappar som innehåller typsnittsfiler. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Mappar som innehåller typsnittsfiler. |
| [getMemoryFonts()](#getMemoryFonts--) | En samling av typsnitt som representeras som byte-arrayer. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | En samling av typsnitt som representeras som byte-arrayer. |

### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```

Mappar som innehåller typsnittsfiler. Alla typsnittsfiler som finns i dessa mappar inkluderas i samlingen. Mappar som söks igenom rekursivt.

**Returnerar:**
java.lang.String[]

### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```

Mappar som innehåller typsnittsfiler. Alla typsnittsfiler som finns i dessa mappar inkluderas i samlingen. Mappar som söks igenom rekursivt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```

En samling av typsnitt som representeras som byte-arrayer.

**Returnerar:**
byte[][]

### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```

En samling av typsnitt som representeras som byte-arrayer.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte[][] |  |