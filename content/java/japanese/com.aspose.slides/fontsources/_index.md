---
title: FontSources
second_title: Aspose.Slides for Java API リファレンス
description: 外部フォント用のファイルとメモリソースを提供します。
type: docs
url: /ja/com.aspose.slides/fontsources/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IFontSources](../../com.aspose.slides/ifontsources)
```
public class FontSources implements IFontSources
```

外部フォント用のファイルとメモリソースを提供します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FontSources()](#FontSources--) | 新しいデフォルトフォントオプションを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | フォントファイルを含むフォルダー。 |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | フォントファイルを含むフォルダー。 |
| [getMemoryFonts()](#getMemoryFonts--) | バイト配列で表されるフォントのコレクション。 |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | バイト配列で表されるフォントのコレクション。 |
### FontSources() {#FontSources--}
```
public FontSources()
```


新しいデフォルトフォントオプションを作成します。

### getFontFolders() {#getFontFolders--}
```
public final String[] getFontFolders()
```


フォントファイルが含まれるフォルダー。このフォルダー内のすべてのフォントファイルがコレクションに含まれます。再帰的に検索されるフォルダー。

**戻り値:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public final void setFontFolders(String[] value)
```


フォントファイルが含まれるフォルダー。このフォルダー内のすべてのフォントファイルがコレクションに含まれます。再帰的に検索されるフォルダー。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public final byte[][] getMemoryFonts()
```


バイト配列で表されるフォントのコレクション。

**戻り値:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public final void setMemoryFonts(byte[][] value)
```


バイト配列で表されるフォントのコレクション。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte[][] |  |