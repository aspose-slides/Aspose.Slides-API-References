---
title: ICaptionsCollection
second_title: Android 用 Aspose.Slides Java API リファレンス
description: 閉じたキャプションのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/icaptionscollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

閉じたキャプションのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの閉じたキャプションを返します。 |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | コレクションの末尾に WebVTT の閉じたキャプションを追加します。 |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | ストリームからコレクションの末尾に WebVTT の閉じたキャプションを追加します。 |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | コレクションから指定された閉じたキャプションを削除します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスの閉じたキャプションを削除します。 |
| [clear()](#clear--) | コレクションからすべての閉じたキャプションを削除します。 |
| [getCount()](#getCount--) | コレクション内の要素数を返します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
```


指定されたインデックスの閉じたキャプションを返します。読み取り専用 [ICaptions](../../com.aspose.slides/icaptions)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public abstract ICaptions add(String label, String filePath)
```


コレクションの末尾に WebVTT の閉じたキャプションを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| label | java.lang.String | 閉じたキャプションのラベル。 |
| filePath | java.lang.String | WebVTT ファイルへのパス。 |

**戻り値:**
[ICaptions](../../com.aspose.slides/icaptions) - 追加された [ICaptions](../../com.aspose.slides/icaptions) インスタンス。
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public abstract ICaptions add(String label, InputStream stream)
```


ストリームからコレクションの末尾に WebVTT の閉じたキャプションを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| label | java.lang.String | 閉じたキャプションのラベル。 |
| stream | java.io.InputStream | WebVTT 形式のデータを含む入力ストリーム。 |

**戻り値:**
[ICaptions](../../com.aspose.slides/icaptions) - 追加された [ICaptions](../../com.aspose.slides/icaptions) インスタンス。
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```


コレクションから指定された閉じたキャプションを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | 削除する閉じたキャプション。 |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


指定されたインデックスの閉じたキャプションを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除する閉じたキャプションのインデックス。 |
### clear() {#clear--}
```
public abstract void clear()
```


コレクションからすべての閉じたキャプションを削除します。

### getCount() {#getCount--}
```
public abstract int getCount()
```


コレクション内の要素数を返します。読み取り専用  int .

**戻り値:**
int