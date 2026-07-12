---
title: IControlPropertiesCollection
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: ActiveX コントロールのコレクションです。
type: docs
url: /ja/com.aspose.slides/icontrolpropertiescollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

ActiveX コントロールのコレクションです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCount()](#getCount--) | コレクション内のプロパティ数を返します。 |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | コレクションにプロパティを追加します。 |
| [remove(String name)](#remove-java.lang.String-) | 指定された名前のプロパティを削除します。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | プロパティを取得または設定します。 |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | プロパティを取得または設定します。 |
| [getNamesOfProperties()](#getNamesOfProperties--) | コレクション内のプロパティ数を返します。 |
| [clear()](#clear--) | すべてのプロパティを削除します。 |
### getCount() {#getCount--}
```
public abstract int getCount()
```


コレクション内のプロパティ数を返します。 読み取り専用 int。

**戻り値:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```


コレクションにプロパティを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | プロパティの名前。 |
| value | java.lang.String | プロパティの値。 |

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```


指定された名前のプロパティを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 削除するプロパティの名前。 |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
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
public abstract void set_Item(String name, String value)
```


プロパティを取得または設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | プロパティの名前。 |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```


コレクション内のプロパティ数を返します。 読み取り専用 [IGenericCollection](../../com.aspose.slides/igenericcollection)。

**戻り値:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```


すべてのプロパティを削除します。