---
title: ITagCollection
second_title: Aspose.Slides for Java API リファレンス
description: タグのコレクション（ユーザーが定義した文字列のペア）を表します
type: docs
url: /ja/com.aspose.slides/itagcollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

タグのコレクション（ユーザー定義の文字列ペア）を表します
## メソッド

| メソッド | 説明 |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | コレクションに新しいタグを追加します。 |
| [remove(String name)](#remove-java.lang.String-) | コレクションから指定された名前のタグを削除します。 |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | コレクション内の指定されたキーのゼロベースインデックスを返します。 |
| [contains(String name)](#contains-java.lang.String-) | コレクションが特定の名前を含んでいるかどうかを判定します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスのタグを削除します。 |
| [clear()](#clear--) | コレクションからすべてのタグを削除します。 |
| [getValueByIndex(int index)](#getValueByIndex-int-) | 指定されたインデックスのタグの値を返します。 |
| [getNameByIndex(int index)](#getNameByIndex-int-) | 指定されたインデックスのタグのキーを返します。 |
| [getNamesOfTags()](#getNamesOfTags--) | タグの名前を返します。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | タグのキーと値のペアを取得または設定します。 |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | タグのキーと値のペアを取得または設定します。 |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```

コレクションに新しいタグを追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | タグの名前。 |
| value | java.lang.String | タグの値。 |

**戻り値:**
int - 追加されたタグのインデックス。
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

コレクションから指定された名前のタグを削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 削除するタグの名前。 |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```

コレクション内の指定されたキーのゼロベースインデックスを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | コレクション内で検索する名前。 |

**戻り値:**
int - キーがコレクションに見つかった場合のゼロベースインデックス。見つからない場合は -1。
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```

コレクションが特定の名前を含んでいるかどうかを判定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 検索するキー。 |

**戻り値:**
boolean - 指定されたキーを持つタグがコレクションに存在する場合は true、そうでない場合は false。
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

指定されたインデックスのタグを削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除するタグのゼロベースインデックス。 |
### clear() {#clear--}
```
public abstract void clear()
```

コレクションからすべてのタグを削除します。

### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```

指定されたインデックスのタグの値を返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 返却するタグのインデックス。 |

**戻り値:**
java.lang.String - タグの値。
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```

指定されたインデックスのタグのキーを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 返却するタグのインデックス。 |

**戻り値:**
java.lang.String - タグのキー。
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```

タグの名前を返します。

**戻り値:**
java.lang.String[] - タグの名前。
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

タグのキーと値のペアを取得または設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | タグのキー。 |

**戻り値:**
java.lang.String - タグの値。
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

タグのキーと値のペアを取得または設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | タグのキー。 |
| value | java.lang.String |  |