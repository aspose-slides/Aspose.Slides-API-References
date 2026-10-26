---
title: IFontSources
second_title: Aspose.Slides for Android via Java API Reference
description: Provides file and memory sources for external fonts.
type: docs
url: /el/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

Παρέχει πηγές αρχείων και μνήμης για εξωτερικές γραμματοσειρές.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Φάκελοι που περιέχουν αρχεία γραμματοσειρών. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Φάκελοι που περιέχουν αρχεία γραμματοσειρών. |
| [getMemoryFonts()](#getMemoryFonts--) | Μια συλλογή γραμματοσειρών που αναπαρίστανται ως byte arrays. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Μια συλλογή γραμματοσειρών που αναπαρίστανται ως byte arrays. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```


Φάκελοι που περιέχουν αρχεία γραμματοσειρών. Όλα τα αρχεία γραμματοσειρών που βρίσκονται σε αυτούς τους φακέλους περιλαμβάνονται στη συλλογή. Φάκελοι που αναζητούνται αναδρομικά.

**Επιστρέφει:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```


Φάκελοι που περιέχουν αρχεία γραμματοσειρών. Όλα τα αρχεία γραμματοσειρών που βρίσκονται σε αυτούς τους φακέλους περιλαμβάνονται στη συλλογή. Φάκελοι που αναζητούνται αναδρομικά.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```


Μια συλλογή γραμματοσειρών που αναπαρίστανται ως byte arrays.

**Επιστρέφει:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```


Μια συλλογή γραμματοσειρών που αναπαρίστανται ως byte arrays.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte[][] |  |