---
title: IFonts
second_title: Aspose.Slides for Android via Java API リファレンス
description: フォント コレクションを表します。
type: docs
url: /ja/com.aspose.slides/ifonts/
---```
public interface IFonts
```

フォント コレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | Latin フォントを取得または設定します。 |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Latin フォントを取得または設定します。 |
| [getEastAsianFont()](#getEastAsianFont--) | 東アジア フォントを取得または設定します。 |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | 東アジア フォントを取得または設定します。 |
| [getComplexScriptFont()](#getComplexScriptFont--) | 複合スクリプト フォントを取得または設定します。 |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | 複合スクリプト フォントを取得または設定します。 |
| [getScriptFontMap()](#getScriptFontMap--) | プレゼンテーション内のすべてのスクリプト フォント定義の辞書を返します。 |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | プレゼンテーション テーマから特定のスクリプト タグに関連付けられたフォント名を取得します。 |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | プレゼンテーションでそのスクリプトのテキストがどのようにレンダリングされるかを定義する、特定のスクリプト タグにフォント名を割り当てます。 |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | テーマのフォント コレクションから特定のスクリプト タグに関連付けられたフォント設定を削除します。 |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Latin フォントを取得または設定します。読み取り/書き込み [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Latin フォントを取得または設定します。読み取り/書き込み [IFontData](../../com.aspose.slides/ifontdata)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

東アジア フォントを取得または設定します。読み取り/書き込み [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

東アジア フォントを取得または設定します。読み取り/書き込み [IFontData](../../com.aspose.slides/ifontdata)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

複合スクリプト フォントを取得または設定します。読み取り/書き込み [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

複合スクリプト フォントを取得または設定します。読み取り/書き込み [IFontData](../../com.aspose.slides/ifontdata)。

**パラメーター:**
| パラメーター | 型 | 説明 |
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
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - スクリプトコードをフォント名にマッピングする辞書。
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```

プレゼンテーション テーマから特定のスクリプト タグに関連付けられたフォント名を取得します。

--------------------

> ```
> この例は、プレゼンテーションのテーマでキリル文字スクリプトに割り当てられたフォントを取得する方法を示しています。
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| script | java.lang.String | BCP-47 スクリプト コード（例: "Latn", "Cyrl", "Jpan"）で、書記体系を識別するために使用されます。 |

**戻り値:**
java.lang.String - 指定されたスクリプトで使用されるフォント名、または定義されていない場合は  null です。
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```

指定されたスクリプト タグにフォント名を割り当てます。これにより、そのスクリプトのテキストがプレゼンテーションでどのようにレンダリングされるかが決定されます。

--------------------

> ```
> この例は、アラビア文字スクリプトのフォントを "Segoe UI" に設定する方法を示しています：
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| script | java.lang.String | BCP-47 スクリプト コード（例: "Arab", "Hebr", "Hans"）で、書記体系を識別します。 |
| fontName | java.lang.String | 指定されたスクリプトに割り当てるフォント名。 |
### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```

テーマのフォント コレクションから特定のスクリプト タグに関連付けられたフォント設定を削除します。

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| script | java.lang.String | フォント設定を削除すべき BCP-47 スクリプト コード。 |