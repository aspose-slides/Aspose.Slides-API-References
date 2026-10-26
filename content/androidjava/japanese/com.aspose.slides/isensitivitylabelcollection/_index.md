---
title: ISensitivityLabelCollection
second_title: Java API リファレンスによる Android 向け Aspose.Slides
description: ドキュメントに適用された感度ラベルのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/isensitivitylabelcollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
```

ドキュメントに適用された感度ラベルのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | インデックスで感度ラベルを返します。 |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | コレクションの末尾に感度ラベルを追加します。 |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | SensitivityLabel をコレクションに追加します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスの感度ラベルを削除します。 |
| [clear()](#clear--) | コレクションからすべての要素を削除します。 |
| [getCount()](#getCount--) | コレクション内のすべての要素数を取得します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```

インデックスで感度ラベルを返します。読み取り専用 [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

コレクションの末尾に感度ラベルを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| id | java.lang.String | 感度ラベルの ID。 |
| siteId | java.util.UUID | Azure Active Directory (Azure AD) サイト識別子。 |
| isEnabled | boolean | 感度ラベルが有効かどうかを示すフラグ。 |
| methodType | int | 感度ラベルの割り当て方法。 |

**戻り値:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```

SensitivityLabel をコレクションに追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | コレクションの末尾に追加される SensitivityLabel オブジェクト。 |

**戻り値:**
int - SensitivityLabel が追加されたインデックス。
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

指定されたインデックスの感度ラベルを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除すべき感度ラベルのインデックス。 |
### clear() {#clear--}
```
public abstract void clear()
```

コレクションからすべての要素を削除します。

### getCount() {#getCount--}
```
public abstract int getCount()
```

コレクション内のすべての要素数を取得します。読み取り専用 int 。

**戻り値:**
int