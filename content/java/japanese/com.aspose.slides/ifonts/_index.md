---
title: IFonts
second_title: Aspose.Slides for Java API Reference
description: Represents fonts collection.
type: docs
url: /ja/com.aspose.slides/ifonts/
---```
public interface IFonts
```

フォントコレクションを表します。
## メソッド

| Method | Description |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | Latin フォントを取得または設定します。 |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Latin フォントを取得または設定します。 |
| [getEastAsianFont()](#getEastAsianFont--) | East Asian フォントを取得または設定します。 |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | East Asian フォントを取得または設定します。 |
| [getComplexScriptFont()](#getComplexScriptFont--) | complex script フォントを取得または設定します。 |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | complex script フォントを取得または設定します。 |
| [getScriptFontMap()](#getScriptFontMap--) | プレゼンテーション内のすべてのスクリプト フォント定義の辞書を返します。 |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | プレゼンテーションテーマから特定のスクリプト タグに関連付けられたフォント名を取得します。 |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | プレゼンテーションでそのスクリプトのテキストがどのように表示されるかを定義する、特定のスクリプト タグにフォント名を割り当てます。 |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | テーマのフォントコレクションから特定のスクリプト タグに関連付けられたフォント設定を削除します。 |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Latin フォントを取得または設定します。読み書き [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Latin フォントを取得または設定します。読み書き [IFontData](../../com.aspose.slides/ifontdata)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

East Asian フォントを取得または設定します。読み書き [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

East Asian フォントを取得または設定します。読み書き [IFontData](../../com.aspose.slides/ifontdata)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

complex script フォントを取得または設定します。読み書き [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

complex script フォントを取得または設定します。読み書き [IFontData](../../com.aspose.slides/ifontdata)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

プレゼンテーション内のすべてのスクリプト フォント定義の辞書を返します。

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```

**戻り値:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - スクリプト コードをフォント名にマッピングする辞書。
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```

プレゼンテーションテーマから特定のスクリプト タグに関連付けられたフォント名を取得します。

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| script | java.lang.String | 書記体系を識別するために使用される BCP-47 スクリプトコード (例: "Latn", "Cyrl", "Jpan")。 |

**戻り値:**
java.lang.String - 指定されたスクリプトで使用されるフォント名、またはスクリプトが定義されていない場合は null。
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```

特定のスクリプト タグにフォント名を割り当てます。これにより、そのスクリプトのテキストがプレゼンテーションでどのようにレンダリングされるかが定義されます。

--------------------

> ```
> この例は、アラビア文字スクリプトのフォントを "Segoe UI" に設定する方法を示しています:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| script | java.lang.String | 書記体系を識別する BCP-47 スクリプトコード (例: "Arab", "Hebr", "Hans")。 |
| fontName | java.lang.String | 指定されたスクリプトに割り当てるフォント名。 |
### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```

テーマのフォントコレクションから特定のスクリプト タグに関連付けられたフォント設定を削除します。

--------------------

> ```
> この例は、ヘブライ文字スクリプトのフォントマッピングを削除する方法を示しています:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| script | java.lang.String | フォント設定を削除すべき BCP-47 スクリプトコード。 |