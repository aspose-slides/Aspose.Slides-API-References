---
title: CustomXmlPartCollection
second_title: Aspose.Slides for Android の Java API リファレンス
description: カスタム XML パーツのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/customxmlpartcollection/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject  
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

カスタム XML パーツのコレクションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を返します。 |
| [size()](#size--) | コレクション内のカスタム XML パーツの数を返します。 |
| [add(String xmlString)](#add-java.lang.String-) | 新しいカスタム XML パーツを追加します。 |
| [add(byte[] xmlData)](#add-byte---) | 新しいカスタム XML パーツを追加します。 |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | 新しいカスタム XML パーツを追加します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスのカスタム XML パーツを削除します。 |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | コレクションから特定のオブジェクトの最初の出現を削除します。 |
| [clear()](#clear--) | コレクションからすべての項目を削除します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化（スレッドセーフ）されているかどうかを示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期化ルートを返します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

指定されたインデックスの要素を返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 取得する要素のゼロベースインデックス。 |

**戻り値:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 指定されたインデックスの要素。

### size() {#size--}
```
public final int size()
```

コレクション内のカスタム XML パーツの数を返します。読み取り専用 int。

**戻り値:**
int

### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

新しいカスタム XML パーツを追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xmlString | java.lang.String | 追加する新しいパートの XML 文字列。 |

**戻り値:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 作成されたカスタム XML パーツ。

### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

新しいカスタム XML パーツを追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xmlData | byte[] | 追加する新しいパートの XML データ。 |

**戻り値:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 作成されたカスタム XML パーツ。

### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

新しいカスタム XML パーツを追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 追加する新しいパートの XML データを含む inputStream。 |

**戻り値:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 作成されたカスタム XML パーツ。

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

指定されたインデックスのカスタム XML パーツを削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除する要素のゼロベースインデックス。 |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

コレクションから特定のオブジェクトの最初の出現を削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | 削除するカスタム XML パーツ。 |

**戻り値:**
boolean - アイテムが正常に削除された場合は true、そうでない場合は false。

### clear() {#clear--}
```
public final void clear()
```

コレクションからすべての項目を削除します。

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

指定された配列にコピーします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | コピー先の配列。 |
| index | int | コピー開始インデックス。 |

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
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - コレクションを反復処理できる IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - コレクション全体の java.util.Iterator。

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject