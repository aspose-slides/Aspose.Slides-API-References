---
title: SizeF
second_title: Java API リファレンスによる Android 向け Aspose.Slides
description: 任意の単位で浮動小数点値を使用して幅と高さの寸法を表すクラスです。
type: docs
url: /ja/com.aspose.slides.android/sizef/
---
**継承:**  
java.lang.Object  
```
public class SizeF
```

任意の単位で浮動小数点値を用いて幅と高さの寸法を表すクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SizeF(float width, float height)](#SizeF-float-float-) | 新しい SizeF インスタンスを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getWidth()](#getWidth--) | サイズの幅を取得します。 |
| [getHeight()](#getHeight--) | サイズの高さを取得します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | このサイズが他のサイズと等しいかどうかを確認します。 |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | サイズを "WxH" 形式の文字列として返します。 |

### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```

新しい SizeF インスタンスを作成します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| width | float | サイズの幅 |
| height | float | サイズの高さ |

### getWidth() {#getWidth--}
```
public float getWidth()
```

サイズの幅を取得します。

**戻り値:**
float - width

### getHeight() {#getHeight--}
```
public float getHeight()
```

サイズの高さを取得します。

**戻り値:**
float - height

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

このサイズが他のサイズと等しいかどうかを確認します。

2 つのサイズが等しいのは、幅と高さの両方が同じ場合に限ります。

この目的のために、幅/高さの float 値は、メソッド Float\#floatToIntBits(float).floatToIntBits(float) が各々に適用されたときに同一の int 値を返す場合に限り、同じとみなされます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**戻り値:**
boolean - オブジェクトが等しい場合は true、そうでない場合は false

### hashCode() {#hashCode--}
```
public int hashCode()
```

**戻り値:**
int

### toString() {#toString--}
```
public String toString()
```

サイズを "WxH" 形式の文字列として返します。

**戻り値:**
java.lang.String - サイズの文字列表現