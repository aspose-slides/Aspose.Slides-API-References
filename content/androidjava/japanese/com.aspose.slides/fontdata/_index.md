---
title: FontData
second_title: Aspose.Slides for Android via Java API リファレンス
description: フォント定義を表します。
type: docs
url: /ja/com.aspose.slides/fontdata/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

フォント定義を表します。変更不可です。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | 指定されたフォント名で新しい FontData オブジェクトを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFontName()](#getFontName--) | フォント名を返します。 |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | フォント名を返します。テーマ参照を実際に使用されるフォントに置き換えます。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 二つの FontData インスタンスが等しいかどうかを判定します。 |
| [hashCode()](#hashCode--) | 特定の型のハッシュ関数として機能し、ハッシュアルゴリズムやハッシュテーブルのようなデータ構造で使用できます。 |
| [toString()](#toString--) | 文字列表現を返します。 |

### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

指定されたフォント名で新しい FontData オブジェクトを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontName | java.lang.String | フォント名。 |

### getFontName() {#getFontName--}
```
public final String getFontName()
```

フォント名を返します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

フォント名を返します。テーマ参照を実際に使用されるフォントに置き換えます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | テーマからテーマフォント名を取得します。呼び出し側が正しい値を提供する必要があります。参照 [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**戻り値:**
java.lang.String - フォント名。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

二つの FontData インスタンスが等しいかどうかを判定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 現在の FontData と比較する FontData。 |

**戻り値:**
boolean - **true** の場合、指定された FontData が現在の FontData と等しいことを示します。そうでなければ **false**。

### hashCode() {#hashCode--}
```
public int hashCode()
```

特定の型のハッシュ関数として機能し、ハッシュアルゴリズムやハッシュテーブルのようなデータ構造で使用できます。

**戻り値:**
int - FontData のハッシュコード。

### toString() {#toString--}
```
public String toString()
```

文字列表現を返します。

**戻り値:**
java.lang.String - 文字列表現。