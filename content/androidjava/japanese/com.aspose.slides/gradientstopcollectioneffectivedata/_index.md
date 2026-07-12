---
title: GradientStopCollectionEffectiveData
second_title: Aspose.Slides for Android の Java API リファレンス
description: GradientStopData オブジェクトのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/gradientstopcollectioneffectivedata/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
com.aspose.slides.IEffectiveData, [com.aspose.slides.IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)
```
public class GradientStopCollectionEffectiveData implements IEffectiveData, IGradientStopCollectionEffectiveData
```

GradientStopData オブジェクトのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [size()](#size--) | コレクション内のグラデーションストップの数を返します。 |
| [get_Item(int index)](#get-Item-int-) | インデックスでグラデーションストップを返します。 |
| [iterator()](#iterator--) | コレクションを走査する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の Java イテレータを返します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションのすべての要素を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化されているか (スレッドセーフ) を示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期化ルートを返します。 |
### size() {#size--}
```
public final int size()
```


コレクション内のグラデーションストップの数を返します。読み取り専用 int.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStopEffectiveData get_Item(int index)
```


インデックスでグラデーションストップを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IGradientStopEffectiveData](../../com.aspose.slides/igradientstopeffectivedata)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iterator()
```


コレクションを走査する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iteratorJava()
```


コレクション全体の Java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


コレクションのすべての要素を指定された配列にコピーします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Target array. |
| index | int | Starting index in the target array. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


コレクションへのアクセスが同期化されているか (スレッドセーフ) を示す値を返します。読み取り専用 boolean.

**戻り値:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


同期化ルートを返します。読み取り専用 Object.

**戻り値:**
java.lang.Object