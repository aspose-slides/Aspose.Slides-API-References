---
title: Fonts
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: フォントのコレクション。
type: docs
url: /ja/com.aspose.slides/fonts/
---
**継承:**
java.lang.Object

**すべての実装インターフェイス:**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

フォントコレクション。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | プレゼンテーション内のすべてのスクリプトフォント定義の辞書を返します。 |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | プレゼンテーションテーマから特定のスクリプトタグに関連付けられたフォント名を取得します。 |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | 特定のスクリプトタグにフォント名を割り当て、プレゼンテーションでそのスクリプトのテキストがどのように描画されるかを定義します。 |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | テーマのフォントコレクションから特定のスクリプトタグに関連付けられたフォント設定を削除します。 |
| [getLatinFont()](#getLatinFont--) | Latin フォントを取得または設定します。 |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Latin フォントを取得または設定します。 |
| [getEastAsianFont()](#getEastAsianFont--) | East Asian フォントを取得または設定します。 |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | East Asian フォントを取得または設定します。 |
| [getComplexScriptFont()](#getComplexScriptFont--) | 複合スクリプト フォントを取得または設定します。 |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | 複合スクリプト フォントを取得または設定します。 |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

プレゼンテーション内のすべてのスクリプトフォント定義の辞書を返します。

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
public final String getScriptFont(String script)
```

プレゼンテーションテーマから特定のスクリプトタグに関連付けられたフォント名を取得します。

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
| script | java.lang.String | 文字体系を識別するために使用される BCP-47 スクリプトコード（例: "Latn", "Cyrl", "Jpan"）です。 |

**戻り値:**
java.lang.String - 指定されたスクリプトに使用されるフォント名。スクリプトが定義されていない場合は null。

### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```

特定のスクリプトタグにフォント名を割り当て、プレゼンテーションでそのスクリプトのテキストがどのように描画されるかを定義します。

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| script | java.lang.String | 文字体系を識別する BCP-47 スクリプトコード（例: "Arab", "Hebr", "Hans"）。 |
| fontName | java.lang.String | 指定されたスクリプトに割り当てるフォント名。 |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```

テーマのフォントコレクションから特定のスクリプトタグに関連付けられたフォント設定を削除します。

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| script | java.lang.String | フォント設定を削除すべきスクリプトコードです。 |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Latin フォントを取得または設定します。読み取り/書き込み [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Latin フォントを取得または設定します。読み取り/書き込み [IFontData](../../com.aspose.slides/ifontdata)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

East Asian フォントを取得または設定します。読み取り/書き込み [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

East Asian フォントを取得または設定します。読み取り/書き込み [IFontData](../../com.aspose.slides/ifontdata)。

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