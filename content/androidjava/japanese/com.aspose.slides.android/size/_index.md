---
title: Size
second_title: Java API リファレンスを介した Android 用 Aspose.Slides
description: 任意の単位で幅と高さの寸法を記述するクラスです。
type: docs
url: /ja/com.aspose.slides.android/size/
---
**継承:**
java.lang.Object
```
public class Size
```

任意の単位で幅と高さの寸法を記述するクラスです。
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [Size(int width, int height)](#Size-int-int-) | 新しい Size インスタンスを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getWidth()](#getWidth--) | サイズの幅を取得します。 |
| [getHeight()](#getHeight--) | サイズの高さを取得します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | このサイズが別のサイズと等しいかどうかを確認します。 |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | サイズを "WxH" 形式の文字列として返します。 |
### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


新しい Size インスタンスを作成します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| width | int | サイズの幅 |
| height | int | サイズの高さ |

### getWidth() {#getWidth--}
```
public int getWidth()
```


サイズの幅を取得します。

**戻り値:**
int - width
### getHeight() {#getHeight--}
```
public int getHeight()
```


サイズの高さを取得します。

**戻り値:**
int - height
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このサイズが別のサイズと等しいかどうかを確認します。

2 つのサイズは、幅と高さの両方が等しい場合に限り等しいとみなされます。

Size オブジェクトは他の型のオブジェクトとは決して等しくありません。

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