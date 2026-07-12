---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: エフェクトの動作に対するタイミングプロパティを表します。
type: docs
url: /ja/com.aspose.slides/ibehaviorpropertycollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

エフェクトの動作に対するタイミングプロパティを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | コレクションに新しいプロパティを追加します。 |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | List 内でプロパティ値により特定の項目のインデックスを決定します。 |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | 指定されたインデックスに新しいプロパティ（指定されたプロパティ値）をコレクションに挿入します。 |
| [remove(String propertyValue)](#remove-java.lang.String-) | コレクションから指定されたプロパティを削除します。 |
| [contains(String propertyValue)](#contains-java.lang.String-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) に特定の値が含まれているかどうかを判断します。 |
### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```

コレクションに新しいプロパティを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| propertyValue | java.lang.String | 追加するプロパティの値。 |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```

List 内でプロパティ値により特定の項目のインデックスを決定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| propertyValue | java.lang.String | プロパティの値 |

**戻り値:**
int - 指定された値を持つプロパティのインデックス

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```

指定されたインデックスに新しいプロパティ（指定されたプロパティ値）をコレクションに挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しいプロパティを挿入すべきインデックス。 |
| propertyValue | java.lang.String | 追加するプロパティの値。 |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```

コレクションから指定されたプロパティを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| propertyValue | java.lang.String | 削除するプロパティの値。 |

**戻り値:**
boolean - プロパティが正常に削除された場合は true

### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) に特定の値が含まれているかどうかを判断します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| propertyValue | java.lang.String | [IGenericCollection](../../com.aspose.slides/igenericcollection) 内で検索するプロパティの値。 |

**戻り値:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection) に propertyValue が見つかった場合は true、それ以外の場合は false。