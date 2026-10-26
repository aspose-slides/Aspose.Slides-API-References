---
title: SensitivityLabelCollection
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: ドキュメントに適用された感度ラベルのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/sensitivitylabelcollection/
---
**継承:**
java.lang.Object, com.aspose.slides.DomObject

**すべての実装インターフェイス:**
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

ドキュメントに適用された感度ラベルのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | インデックスで感度ラベルを返します。 |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | コレクションの末尾に感度ラベルを追加します。 |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | 感度ラベルをコレクションに追加します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスの感度ラベルを削除します。 |
| [clear()](#clear--) | コレクションからすべての要素を削除します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [getCount()](#getCount--) | コレクション内の要素数を返します。 |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | コレクションのすべての要素を指定された配列にコピーします。 |
### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```

インデックスで感度ラベルを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

コレクションの末尾に感度ラベルを追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| id | java.lang.String | 感度ラベルの ID。 |
| siteId | java.util.UUID | Azure Active Directory (Azure AD) サイト識別子。 |
| isEnabled | boolean | 感度ラベルが有効かどうかを示すフラグ。 |
| methodType | int | 感度ラベルの割り当て方法。 |

**戻り値:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```

コレクションに SensitivityLabel を追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | コレクションの末尾に追加される SensitivityLabel オブジェクト。 |

**戻り値:**
int - SensitivityLabel が追加されたインデックス。
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

指定されたインデックスの感度ラベルを削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除すべき感度ラベルのインデックス。 |
### clear() {#clear--}
```
public final void clear()
```

コレクションからすべての要素を削除します。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - コレクションを反復処理するために使用できる System.Collections.Generic.IEnumerator1  
### getCount() {#getCount--}
```
public final int getCount()
```

コレクション内の要素数を返します。読み取り専用  int 。

**戻り値:**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```

コレクションのすべての要素を指定された配列にコピーします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | ターゲット配列。 |
| index | int | 対象配列の開始インデックス。 |