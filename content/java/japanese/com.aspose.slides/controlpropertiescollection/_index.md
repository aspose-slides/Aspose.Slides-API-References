---
title: ControlPropertiesCollection
second_title: Aspose.Slides for Java API リファレンス
description: AcitveX プロパティのコレクションです。
type: docs
url: /ja/com.aspose.slides/controlpropertiescollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

ActiveX プロパティのコレクションです。

## Methods

| Method | Description |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | コレクションにプロパティを追加します。 |
| [remove(String name)](#remove-java.lang.String-) | 指定された名前のプロパティを削除します。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | プロパティを取得または設定します。 |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | プロパティを取得または設定します。 |
| [getNamesOfProperties()](#getNamesOfProperties--) | プロパティ名のコレクションを返します。 |
| [clear()](#clear--) | すべてのプロパティを削除します。 |
| [getCount()](#getCount--) | コレクション内のプロパティ数を返します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |

### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```

コレクションにプロパティを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | プロパティの名前。 |
| value | java.lang.String | プロパティの値。 |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

指定された名前のプロパティを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 削除するプロパティの名前。 |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

プロパティを取得または設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | プロパティの名前。 |

**戻り値:**
java.lang.String - プロパティ。

### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

プロパティを取得または設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | プロパティの名前。 |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

プロパティ名のコレクションを返します。 読み取り専用 [IGenericCollection](../../com.aspose.slides/igenericcollection)。

**戻り値:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)

### clear() {#clear--}
```
public final void clear()
```

すべてのプロパティを削除します。

### getCount() {#getCount--}
```
public final int getCount()
```

コレクション内のプロパティ数を返します。 読み取り専用 int。

**戻り値:**
int

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - コレクションを反復処理するために使用できる IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - コレクション全体の java.util.Iterator。