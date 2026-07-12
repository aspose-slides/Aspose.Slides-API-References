---
title: IFontSources
second_title: Aspose.Slides for Android via Java API Reference
description: 外部フォント用のファイルおよびメモリ ソースを提供します。
type: docs
url: /ja/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

外部フォント用のファイルおよびメモリ ソースを提供します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | フォントファイルが含まれるフォルダー。 |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | フォントファイルが含まれるフォルダー。 |
| [getMemoryFonts()](#getMemoryFonts--) | バイト配列として表現されたフォントのコレクション。 |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | バイト配列として表現されたフォントのコレクション。 |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```

フォントファイルが含まれるフォルダー。これらのフォルダー内にあるすべてのフォントファイルがコレクションに含まれます。フォルダーは再帰的に検索されます。

**戻り値:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```

フォントファイルが含まれるフォルダー。これらのフォルダー内にあるすべてのフォントファイルがコレクションに含まれます。フォルダーは再帰的に検索されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte[][] |  |