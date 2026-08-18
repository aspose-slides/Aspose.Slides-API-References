---
title: VbaModuleCollection
second_title: Aspose.Slides for Java API リファレンス
description: VBA プロジェクトのモジュールのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/vbamodulecollection/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)  
```
public final class VbaModuleCollection implements IVbaModuleCollection
```

VBA プロジェクトのモジュールのコレクションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [size()](#size--) | コレクションに実際に含まれている要素の数を取得します。 |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | コレクションから特定のオブジェクトの最初の出現を削除します。 |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | VBA プロジェクトに新しい空のモジュールを追加します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [iterator()](#iterator--) | コレクションを反復する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションからすべての要素を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期化のルートを返します。 |
### size() {#size--}
```
public final int size()
```

コレクションに実際に含まれている要素の数を取得します。Read-only int.

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

コレクションを反復する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - コレクションを反復するために使用できる IGenericEnumerator。
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

コレクションからすべての要素を指定された配列にコピーします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 対象配列。 |
| index | int | 対象配列の開始インデックス。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を返します。Read-only boolean.

**戻り値:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

同期化のルートを返します。Read-only Object.

**戻り値:**
java.lang.Object