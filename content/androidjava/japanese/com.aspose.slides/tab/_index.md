---
title: Tab
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: テキストのタブ設定を表します。
type: docs
url: /ja/com.aspose.slides/tab/
---
**継承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されたすべてのインターフェース:**
[com.aspose.slides.ITab](../../com.aspose.slides/itab)
```
public final class Tab extends PVIObject implements ITab
```

テキストのタブ設定を表します。
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | 新しい Tab を作成します |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | タブの位置を取得または設定します。 |
| [setPosition(double value)](#setPosition-double-) | タブの位置を取得または設定します。 |
| [getAlignment()](#getAlignment--) | タブの整列スタイルを取得または設定します。 |
| [setAlignment(int value)](#setAlignment-int-) | タブの整列スタイルを取得または設定します。 |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | 現在のインスタンスを同じ型の別のオブジェクトと比較します。 |
### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```


新しい Tab を作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| position | double | タブの位置。 |
| align | int | 整列。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```


バージョン。読み取り専用の long。

**戻り値:**
long
### getPosition() {#getPosition--}
```
public final double getPosition()
```


タブの位置を取得または設定します。このプロパティを設定すると、コレクション内のタブのインデックスが変更され、Enumerator が無効になる可能性があります。読み取り/書き込み可能な double。

**戻り値:**
double
### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```


タブの位置を取得または設定します。このプロパティを設定すると、コレクション内のタブのインデックスが変更され、Enumerator が無効になる可能性があります。読み取り/書き込み可能な double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


タブの整列スタイルを取得または設定します。読み取り/書き込み可能な [TabAlignment](../../com.aspose.slides/tabalignment)。

**戻り値:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


タブの整列スタイルを取得または設定します。読み取り/書き込み可能な [TabAlignment](../../com.aspose.slides/tabalignment)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


現在のインスタンスを同じ型の別のオブジェクトと比較します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較するオブジェクト。 |

**戻り値:**
int - 比較対象の相対的な順序を示す 32 ビット整数です。戻り値の意味は次のとおりです：

 *  < 0 - このインスタンスは obj より小さいです。
 *  = 0 - このインスタンスは obj と等しいです。
 *  > 0 - このインスタンスは obj より大きいです。