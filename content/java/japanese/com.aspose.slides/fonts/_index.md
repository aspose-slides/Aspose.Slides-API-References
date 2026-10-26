---
title: Fonts
second_title: Aspose.Slides for Java API リファレンス
description: フォントコレクション。
type: docs
url: /ja/com.aspose.slides/fonts/
---
**継承:**  
java.lang.Object

**実装されたすべてのインターフェイス:**  
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)  
```
public class Fonts implements IFonts
```

フォントコレクション。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | プレゼンテーション内のすべてのスクリプト フォント定義の辞書を返します。 |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | プレゼンテーションのテーマから特定のスクリプト タグに関連付けられたフォント名を取得します。 |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | 特定のスクリプト タグにフォント名を割り当て、プレゼンテーションでそのスクリプトのテキストがどのように描画されるかを定義します。 |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | テーマのフォントコレクションから特定のスクリプト タグに関連付けられたフォント設定を削除します。 |
| [getLatinFont()](#getLatinFont--) | ラテン文字フォントを取得または設定します。 |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | ラテン文字フォントを取得または設定します。 |
| [getEastAsianFont()](#getEastAsianFont--) | 東アジア文字フォントを取得または設定します。 |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | 東アジア文字フォントを取得または設定します。 |
| [getComplexScriptFont()](#getComplexScriptFont--) | 複合スクリプト フォントを取得または設定します。 |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | 複合スクリプト フォントを取得または設定します。 |

### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
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
public final String getScriptFont(String script)
```

プレゼンテーションのテーマから特定のスクリプト タグに関連付けられたフォント名を取得します。

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
| script | java.lang.String | 書記体系を識別するために使用される BCP-47 スクリプト コード (例: "Latn", "Cyrl", "Jpan")。 |

**戻り値:**  
java.lang.String - 指定されたスクリプトに使用されるフォントの名前。スクリプトが定義されていない場合は null を返します。

### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```

特定のスクリプト タグにフォント名を割り当て、プレゼンテーションでそのスクリプトのテキストがどのように描画されるかを定義します。

--------------------

> ```
> この例は、アラビア文字のフォントを "Segoe UI" に設定する方法を示しています:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| script | java.lang.String | 書記体系を識別する BCP-47 スクリプト コード (例: "Arab", "Hebr", "Hans")。 |
| fontName | java.lang.String | 指定されたスクリプトに割り当てるフォント名。 |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```

テーマのフォントコレクションから特定のスクリプト タグに関連付けられたフォント設定を削除します。

--------------------

> ```
> この例は、ヘブライ文字のフォントマッピングを削除する方法を示しています:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| script | java.lang.String | フォント設定を削除すべき BCP-47 スクリプト コード。 |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

ラテン文字フォントを取得または設定します。読み取り/書き込み [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

ラテン文字フォントを取得または設定します。読み取り/書き込み [IFontData](../../com.aspose.slides/ifontdata)。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

東アジア文字フォントを取得または設定します。読み取り/書き込み [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

東アジア文字フォントを取得または設定します。読み取り/書き込み [IFontData](../../com.aspose.slides/ifontdata)。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

複合スクリプト フォントを取得または設定します。読み取り/書き込み [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

複合スクリプト フォントを取得または設定します。読み取り/書き込み [IFontData](../../com.aspose.slides/ifontdata)。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |