---
title: ImageTransformOCollectionEffectiveData
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 有効な画像変換エフェクトの読み取り専用コレクションを表す不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/imagetransformocollectioneffectivedata/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
com.aspose.slides.IEffectiveData, [com.aspose.slides.IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)
```
public class ImageTransformOCollectionEffectiveData implements IEffectiveData, IImageTransformOCollectionEffectiveData
```

有効な画像変換エフェクトの読み取り専用コレクションを表す不変オブジェクトです。

--------------------

Name IImageTransformOperationCollectionEffectiveData truncuted to IImageTransformOCollectionEffectiveData because of COM names length cannot be more then 39.
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [ImageTransformOCollectionEffectiveData()](#ImageTransformOCollectionEffectiveData--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [size()](#size--) | コレクション内の画像エフェクトの数を返します。 |
| [get_Item(int index)](#get-Item-int-) | インデックスで要素を返します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定されたオブジェクトが現在のオブジェクトと等しいかどうかを判定します。 |
| [hashCode()](#hashCode--) | 特定の型のハッシュ関数として機能し、ハッシュテーブルなどのハッシュアルゴリズムやデータ構造での使用に適しています。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションのすべての要素を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化（スレッドセーフ）されているかどうかを示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期化ルートを返します。 |
### ImageTransformOCollectionEffectiveData() {#ImageTransformOCollectionEffectiveData--}
```
public ImageTransformOCollectionEffectiveData()
```


### size() {#size--}
```
public final int size()
```


コレクション内の画像エフェクトの数を返します。読み取り専用 int。

**戻り値:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IEffectEffectiveData get_Item(int index)
```


インデックスで要素を返します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 要素のインデックス。 |

**戻り値:**
[IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) - この [IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) オブジェクト。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定されたオブジェクトが現在のオブジェクトと等しいかどうかを判定します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 現在のオブジェクトと比較するオブジェクト。 |

**戻り値:**
boolean - 指定されたオブジェクトが現在のオブジェクトと等しい場合は true、そうでない場合は false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


特定の型のハッシュ関数として機能し、ハッシュテーブルなどのハッシュアルゴリズムやデータ構造での使用に適しています。

**戻り値:**
int - 現在のオブジェクトのハッシュコード。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iterator()
```


コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - コレクションを反復処理するために使用できる IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iteratorJava()
```


コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - コレクション全体の java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


コレクションのすべての要素を指定された配列にコピーします。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 格納先の配列。 |
| index | int | 対象配列の開始位置。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


コレクションへのアクセスが同期化（スレッドセーフ）されているかどうかを示す値を返します。読み取り専用 boolean。

**戻り値:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


同期化ルートを返します。読み取り専用 Object。

**戻り値:**
java.lang.Object