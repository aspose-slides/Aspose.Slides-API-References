---
title: PointCollection
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: アニメーションポイントのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/pointcollection/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IPointCollection](../../com.aspose.slides/ipointcollection)
```
public class PointCollection implements IPointCollection
```

アニメーションポイントのコレクションを表します。
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCount()](#getCount--) | コレクション内のポイント数を返します。 |
| [get_Item(int index)](#get-Item-int-) | 指定したインデックスのポイントを返します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の Java イテレータを返します。 |
### PointCollection() {#PointCollection--}
```
public PointCollection()
```


### getCount() {#getCount--}
```
public final int getCount()
```


コレクション内のポイント数を返します。 読み取り専用 int.

**戻り値:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```


指定したインデックスのポイントを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 要素のインデックス。 |

**戻り値:**
[IPoint](../../com.aspose.slides/ipoint) - [IPoint](../../com.aspose.slides/ipoint) オブジェクト。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```


コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - コレクションを反復処理できる IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```


コレクション全体の Java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - コレクション全体の java.util.Iterator。