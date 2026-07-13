---
title: IFontSources
second_title: Aspose.Slides for Android via Java API Reference
description: Provides file and memory sources for external fonts.
type: docs
url: /nl/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

Biedt bestands- en geheugenbronnen voor externe lettertypen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Mappen die lettertypebestanden bevatten. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Mappen die lettertypebestanden bevatten. |
| [getMemoryFonts()](#getMemoryFonts--) | Een collectie lettertypen weergegeven als byte-arrays. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Een collectie lettertypen weergegeven als byte-arrays. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```


Mappen die lettertypebestanden bevatten. Alle lettertypebestanden die zich in deze mappen bevinden, zijn opgenomen in de collectie. Mappen die recursief worden doorzocht.

**Retour:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```


Mappen die lettertypebestanden bevatten. Alle lettertypebestanden die zich in deze mappen bevinden, zijn opgenomen in de collectie. Mappen die recursief worden doorzocht.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |
### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```


Een collectie lettertypen weergegeven als byte-arrays.

**Retour:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```


Een collectie lettertypen weergegeven als byte-arrays.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[][] |  |