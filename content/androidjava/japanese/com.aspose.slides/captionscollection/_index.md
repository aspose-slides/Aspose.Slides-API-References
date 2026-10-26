---
title: CaptionsCollection
second_title: Aspose.Slides for Android の Java API リファレンス
description: 閉じられたキャプションのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/captionscollection/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

クローズドキャプションのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスのクローズドキャプションを返します。 |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | WebVTT クローズドキャプションをコレクションの末尾に追加します。 |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | ストリームから WebVTT クローズドキャプションをコレクションの末尾に追加します。 |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | 指定されたクローズドキャプションをコレクションから削除します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスのクローズドキャプションを削除します。 |
| [clear()](#clear--) | コレクションからすべてのクローズドキャプションを削除します。 |
| [getCount()](#getCount--) | コレクション内の要素数を返します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```

指定されたインデックスのクローズドキャプションを返します。読み取り専用 [ICaptions](../../com.aspose.slides/icaptions)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public final ICaptions add(String label, String filePath)
```

WebVTT クローズドキャプションをコレクションの末尾に追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| label | java.lang.String | クローズドキャプションのラベル。 |
| filePath | java.lang.String | WebVTT ファイルへのパス。 |

**戻り値:**
[ICaptions](../../com.aspose.slides/icaptions) - 追加された [ICaptions](../../com.aspose.slides/icaptions) インスタンス。
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```

ストリームから WebVTT クローズドキャプションをコレクションの末尾に追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| label | java.lang.String | クローズドキャプションのラベル。 |
| stream | java.io.InputStream | WebVTT 形式のデータを含む入力ストリーム。 |

**戻り値:**
[ICaptions](../../com.aspose.slides/icaptions) - 追加された [ICaptions](../../com.aspose.slides/icaptions) インスタンス。
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```

指定されたクローズドキャプションをコレクションから削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | 削除するクローズドキャプション。 |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

指定されたインデックスのクローズドキャプションを削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除するクローズドキャプションのインデックス。 |
### clear() {#clear--}
```
public final void clear()
```

コレクションからすべてのクローズドキャプションを削除します。
### getCount() {#getCount--}
```
public final int getCount()
```

コレクション内の要素数を返します。読み取り専用 int 。

**戻り値:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - コレクションを反復処理するために使用できる System.Collections.Generic.IEnumerator1 。