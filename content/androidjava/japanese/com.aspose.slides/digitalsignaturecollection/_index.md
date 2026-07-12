---
title: DigitalSignatureCollection
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: ドキュメントに添付されたデジタル署名のコレクションを表します。
type: docs
url: /ja/com.aspose.slides/digitalsignaturecollection/
---
**継承:**
java.lang.Object, com.aspose.slides.DomObject

**実装されたインターフェイス:**
[com.aspose.slides.IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
```
public class DigitalSignatureCollection extends DomObject<Presentation> implements IDigitalSignatureCollection
```

ドキュメントに添付されたデジタル署名のコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | インデックスで署名を返します。 |
| [add(IDigitalSignature signature)](#add-com.aspose.slides.IDigitalSignature-) | コレクションの末尾に署名を追加します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスの署名を削除します。 |
| [clear()](#clear--) | コレクションからすべての署名を削除します。 |
| [iterator()](#iterator--) | コレクションを反復する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [size()](#size--) | コレクション内の要素数を返します。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化されているか（スレッドセーフ）を示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期ルートを返します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションから指定された配列へすべての要素をコピーします。 |
### get_Item(int index) {#get-Item-int-}
```
public final IDigitalSignature get_Item(int index)
```

インデックスで署名を返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature signature) {#add-com.aspose.slides.IDigitalSignature-}
```
public final void add(IDigitalSignature signature)
```

コレクションの末尾に署名を追加します。

---

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      signature.setComments("Aspose.Slides digital signing test.");
>      pres.getDigitalSignatures().add(signature);
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| signature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | 追加する署名。 |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

指定されたインデックスの署名を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除する署名のインデックス。 |
### clear() {#clear--}
```
public final void clear()
```

コレクションからすべての署名を削除します。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iterator()
```

コレクションを反復する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - コレクションを反復するために使用できる IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - コレクション全体の java.util.Iterator。
### size() {#size--}
```
public final int size()
```

コレクション内の要素数を返します。読み取り専用 int。

**戻り値:**
int
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

コレクションへのアクセスが同期化されているか（スレッドセーフ）を示す値を返します。読み取り専用 boolean。

**戻り値:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

同期ルートを返します。読み取り専用 Object。

**戻り値:**
java.lang.Object
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

コレクションから指定された配列へすべての要素をコピーします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 対象配列。 |
| index | int | 対象配列の開始インデックス。 |