---
title: VbaModuleCollection
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: VBA プロジェクトのモジュールのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/vbamodulecollection/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
```
public final class VbaModuleCollection implements IVbaModuleCollection
```

VBA プロジェクトのモジュールのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [size()](#size--) | コレクションに実際に含まれる要素数を取得します。 |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | コレクションから特定のオブジェクトの最初の出現を削除します。 |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | VBA プロジェクトに新しい空のモジュールを追加します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションのすべての要素を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化されているか（スレッドセーフ）を示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期化ルートを返します。 |
### size() {#size--}
```
public final int size()
```

コレクションに実際に含まれる要素数を取得します。読み取り専用 int。

**戻り値:**
int
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public final void remove(IVbaModule value)
```

コレクションから特定のオブジェクトの最初の出現を削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | コレクションから削除するモジュール。 |
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public final IVbaModule addEmptyModule(String name)
```

VBA プロジェクトに新しい空のモジュールを追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | モジュールの名前 |

**戻り値:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - 追加されたモジュール。
### get_Item(int index) {#get-Item-int-}
```
public final IVbaModule get_Item(int index)
```

指定されたインデックスの要素を取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - コレクションを反復処理するために使用できる IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - コレクション全体の java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

コレクションのすべての要素を指定された配列にコピーします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 対象配列。 |
| index | int | 対象配列の開始インデックス。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

コレクションへのアクセスが同期化されているか（スレッドセーフ）を示す値を返します。読み取り専用 boolean。

**戻り値:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

同期化ルートを返します。読み取り専用 Object。

**戻り値:**
java.lang.Object