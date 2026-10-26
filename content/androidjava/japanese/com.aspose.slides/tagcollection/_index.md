---
title: TagCollection
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: ユーザー定義の文字列ペアであるタグのコレクションを表します
type: docs
url: /ja/com.aspose.slides/tagcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ITagCollection](../../com.aspose.slides/itagcollection)
```
public final class TagCollection implements ITagCollection
```

ユーザー定義の文字列ペアであるタグのコレクションを表します。

--------------------

> ```
> 以下の例は、PowerPoint プレゼンテーションにタグを追加する方法を示しています。
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ITagCollection tags = pres.getCustomData().getTags();
>      pres.getCustomData().getTags().add("MyTag", "My Tag Value");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [size()](#size--) | コレクション内のタグ数を返します。 |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | 新しいタグをコレクションに追加します。 |
| [remove(String name)](#remove-java.lang.String-) | 指定された名前のタグをコレクションから削除します。 |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | コレクション内の指定されたキーのゼロベースインデックスを返します。 |
| [contains(String name)](#contains-java.lang.String-) | コレクションが特定の名前を含むかどうかを判定します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスのタグを削除します。 |
| [clear()](#clear--) | コレクション内のすべてのタグを削除します。 |
| [getValueByIndex(int index)](#getValueByIndex-int-) | 指定されたインデックスのタグの値を返します。 |
| [getNameByIndex(int index)](#getNameByIndex-int-) | 指定されたインデックスのタグのキーを返します。 |
| [getNamesOfTags()](#getNamesOfTags--) | タグの名前を返します。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | タグのキーと値のペアを取得または設定します。 |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | タグのキーと値のペアを取得または設定します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクション内のすべての要素を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化されているかどうかを示す値を返します（スレッドセーフ）。 |
| [getSyncRoot()](#getSyncRoot--) | 同期化ルートを返します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
### size() {#size--}
```
public final int size()
```

コレクション内のタグ数を返します。読み取り専用 int。

**戻り値:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```

新しいタグをコレクションに追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | タグの名前。 |
| value | java.lang.String | タグの値。 |

**戻り値:**
int - 追加されたタグのインデックス。
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

指定された名前のタグをコレクションから削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 削除するタグの名前。 |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```

コレクション内の指定されたキーのゼロベースインデックスを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | コレクション内で検索する名前。 |

**戻り値:**
int - キーが見つかった場合のゼロベースインデックス。見つからない場合は -1。
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```

コレクションが特定の名前を含むかどうかを判定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 検索するキー。 |

**戻り値:**
boolean - 指定されたキーのタグがコレクションに含まれている場合は true、そうでない場合は false。
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

指定されたインデックスのタグを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除するタグのゼロベースインデックス。 |
### clear() {#clear--}
```
public final void clear()
```

コレクション内のすべてのタグを削除します。

### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```

指定されたインデックスのタグの値を返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 返すタグのインデックス。 |

**戻り値:**
java.lang.String - タグの値。
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```

指定されたインデックスのタグのキーを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 返すタグのインデックス。 |

**戻り値:**
java.lang.String - タグのキー。
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```

タグの名前を返します。

**戻り値:**
java.lang.String[] - タグの名前。
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

タグのキーと値のペアを取得または設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | タグのキー。 |

**戻り値:**
java.lang.String - タグの値。
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

タグのキーと値のペアを取得または設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | タグのキー。 |
| value | java.lang.String |  |
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

コレクション内のすべての要素を指定された配列にコピーします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 填充する配列。 |
| index | int | 対象配列の開始位置。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

コレクションへのアクセスが同期化されているかどうかを示す値を返します（スレッドセーフ）。読み取り専用 boolean。

**戻り値:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

同期化ルートを返します。読み取り専用 Object。

**戻り値:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - コレクションを反復処理できる IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - java.util.Iterator for the entire collection.