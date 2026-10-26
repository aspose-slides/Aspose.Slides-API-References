---
title: FontSources
second_title: Aspose.Slides for Android の Java API リファレンス
description: 外部フォント用のファイルとメモリ ソースを提供します。
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

外部フォントのファイルとメモリ ソースを提供します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FontSources()](#FontSources--) | 新しいデフォルトのフォントオプションを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | フォントファイルが含まれるフォルダー。 |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | フォントファイルが含まれるフォルダー。 |
| [getMemoryFonts()](#getMemoryFonts--) | バイト配列として表現されたフォントのコレクション。 |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | バイト配列として表現されたフォントのコレクション。 |
### FontSources() {#FontSources--}
```
public FontSources()
```

新しいデフォルトのフォントオプションを作成します。

### getFontFolders() {#getFontFolders--}
```
public final String[] getFontFolders()
```

フォントファイルが含まれるフォルダー。このフォルダー内にあるすべてのフォントファイルがコレクションに含まれます。再帰的に検索されるフォルダーです。

**戻り値:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public final void setFontFolders(String[] value)
```

フォントファイルが含まれるフォルダー。このフォルダー内にあるすべてのフォントファイルがコレクションに含まれます。再帰的に検索されるフォルダーです。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String[] |  |
### getMemoryFonts() {#getMemoryFonts--}
```
public final byte[][] getMemoryFonts()
```

バイト配列として表現されたフォントのコレクション。

**戻り値:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public final void setMemoryFonts(byte[][] value)
```

バイト配列として表現されたフォントのコレクション。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte[][] |  |