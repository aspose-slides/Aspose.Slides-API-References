---
title: ICustomXmlPartCollection
second_title: Aspose.Slides for Android の Java API リファレンス
description: カスタム XML パーツのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/icustomxmlpartcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

カスタム XML パーツのコレクションを表します。

## メソッド

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を返します。 |
| [add(byte[] xmlData)](#add-byte---) | 新しいカスタム XML パーツを追加します。 |
| [add(String xmlString)](#add-java.lang.String-) | 新しいカスタム XML パーツを追加します。 |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | 新しいカスタム XML パーツを追加します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスのカスタム XML パーツを削除します。 |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | コレクションから特定のオブジェクトの最初の出現を削除します。 |
| [clear()](#clear--) | コレクションからすべての項目を削除します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```


指定されたインデックスの要素を返します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 取得する要素のゼロベースインデックス。 |

**Returns:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 指定されたインデックスの要素。

### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```


新しいカスタム XML パーツを追加します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlData | byte[] | 追加する新しいパーツの XML データ。 |

**Returns:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 作成されたカスタム XML パーツ。

### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```


新しいカスタム XML パーツを追加します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlString | java.lang.String | 追加する新しいパーツの XML 文字列。 |

**Returns:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 作成されたカスタム XML パーツ。

### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```


新しいカスタム XML パーツを追加します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | 追加する新しいパーツの XML データを含む InputStream。 |

**Returns:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 作成されたカスタム XML パーツ。

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


指定されたインデックスのカスタム XML パーツを削除します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 削除する要素のゼロベースインデックス。 |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```


コレクションから特定のオブジェクトの最初の出現を削除します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | 削除するカスタム XML パーツ。 |

**Returns:**
boolean - アイテムが正常に削除された場合は true、そうでない場合は false。

### clear() {#clear--}
```
public abstract void clear()
```


コレクションからすべての項目を削除します。