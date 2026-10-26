---
title: TagCollection
second_title: Aspose.Slides for Java API リファレンス
description: ユーザー定義の文字列ペアからなるタグコレクションを表します
type: docs
url: /ja/com.aspose.slides/tagcollection/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ITagCollection](../../com.aspose.slides/itagcollection)
```
public final class TagCollection implements ITagCollection
```

タグのコレクション（ユーザー定義の文字列ペア）を表します

--------------------

> ```
> The following example shows how to add a tag to a PowerPoint Presentation.
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
| [indexOfName(String name)](#indexOfName-java.lang.String-) | コレクション内の指定されたキーの0ベースインデックスを返します。 |
| [contains(String name)](#contains-java.lang.String-) | コレクションに特定の名前が含まれているかどうかを判断します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスのタグを削除します。 |
| [clear()](#clear--) | コレクションからすべてのタグを削除します。 |
| [getValueByIndex(int index)](#getValueByIndex-int-) | 指定されたインデックスのタグの値を返します。 |
| [getNameByIndex(int index)](#getNameByIndex-int-) | 指定されたインデックスのタグのキーを返します。 |
| [getNamesOfTags()](#getNamesOfTags--) | タグの名前を返します。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | タグのキーと値のペアを取得または設定します。 |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | タグのキーと値のペアを取得または設定します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションのすべての要素を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化（スレッドセーフ）されているかどうかを示す値を返します。 |
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

コレクション内の指定されたキーの0ベースインデックスを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | コレクション内で検索する名前。 |

**戻り値:**
int - キーが見つかった場合は0ベースインデックス、見つからない場合は -1。
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```

コレクションに特定の名前が含まれているかどうかを判断します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 検索するキー。 |

**戻り値:**
boolean - 指定されたキーのタグがコレクションに含まれる場合は true、それ以外は false。
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

指定されたインデックスのタグを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除するタグの0ベースインデックス。 |
### clear() {#clear--}
```
public final void clear()
```

コレクションからすべてのタグを削除します。

### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```

指定されたインデックスのタグの値を返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 取得するタグのインデックス。 |

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
| index | int | 取得するタグのインデックス。 |

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

コレクションのすべての要素を指定された配列にコピーします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 填充する配列。 |
| index | int | ターゲット配列の開始位置。 |
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
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - java.util.Iterator。