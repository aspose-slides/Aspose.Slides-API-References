---
title: IFontSources
second_title: Aspose.Slides for Java API Reference
description: Provides file and memory sources for external fonts.
type: docs
url: /ja/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

外部フォント用のファイルおよびメモリ ソースを提供します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | フォント ファイルが含まれるフォルダー。 |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | フォント ファイルが含まれるフォルダー。 |
| [getMemoryFonts()](#getMemoryFonts--) | バイト配列として表現されたフォントのコレクション。 |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | バイト配列として表現されたフォントのコレクション。 |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```


フォント ファイルが含まれるフォルダー。これらのフォルダーにあるすべてのフォント ファイルがコレクションに含まれます。再帰的に検索されるフォルダー。

**戻り値:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```


フォント ファイルが含まれるフォルダー。これらのフォルダーにあるすべてのフォント ファイルがコレクションに含まれます。再帰的に検索されるフォルダー。

**パラメーター:**
| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```


バイト配列として表現されたフォントのコレクション。

**戻り値:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```


バイト配列として表現されたフォントのコレクション。

**パラメーター:**
| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| value | byte[][] |  |