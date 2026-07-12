---
title: MasterSlideCollection
second_title: Aspose.Slides for Android の Java API リファレンス
description: マスタースライドのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/masterslidecollection/
---
**継承:**
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

マスタースライドのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [size()](#size--) | コレクションに実際に含まれる要素数を取得します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | コレクションから特定のオブジェクトの最初の出現を削除します。 |
| [removeAt(int index)](#removeAt-int-) | コレクションの指定されたインデックスにある要素を削除します。 |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | 未使用のマスタースライドを削除します。 |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | 指定されたマスタースライドのコピーをコレクションの末尾に追加します。 |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | 指定されたマスタースライドのコピーをコレクションの指定位置に挿入します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションのすべての要素を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期化のルートを返します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の Java イテレータを返します。 |
### size() {#size--}
```
public final int size()
```

コレクションに実際に含まれる要素数を取得します。 読み取り専用 int.

**戻り値:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```

指定されたインデックスの要素を取得します。 読み取り専用 [MasterSlide](../../com.aspose.slides/masterslide).

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```

コレクションから特定のオブジェクトの最初の出現を削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | コレクションから削除するマスタースライド。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

コレクションの指定されたインデックスにある要素を削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除する要素のゼロベースインデックス。

--------------------

PptxEditException のスローを防ぐために、事前にマスターの HasDependingSlides プロパティを確認してください。 |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```

未使用のマスタースライドを削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ignorePreserveField | boolean | このメソッドが、[MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) プロパティが true に設定されている場合でも未使用のマスターを削除すべきかどうかを決定します。 |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```

指定されたマスタースライドのコピーをコレクションの末尾に追加します。リンクされたレイアウトスライドもコピーされます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | クローン対象のスライド。 |

**戻り値:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 追加されたスライド。
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

指定されたマスタースライドのコピーをコレクションの指定位置に挿入します。リンクされたレイアウトスライドもコピーされます。

--------------------

> ```
> 以下の例は、別の PowerPoint プレゼンテーションでマスタースライドをクローンする方法を示しています。
>  
>  // ソース プレゼンテーション ファイルを読み込むために Presentation クラスのインスタンスを作成します
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // スライドをクローンする先のプレゼンテーション用に Presentation クラスのインスタンスを作成します（スライドをクローンする先）
>      Presentation destPres = new Presentation();
>      try {
>          // ソース プレゼンテーションのスライドコレクションから ISlide をインスタンス化し、
>          // マスタースライド
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // 宛先プレゼンテーションのマスタースライドを取得します
>          IMasterSlideCollection masters = destPres.getMasters();
>          // ソース プレゼンテーションから目的のマスタースライドをコピーし、 
>          // 宛先プレゼンテーション
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // 宛先プレゼンテーションのスライドコレクション
>          ISlideCollection slds = destPres.getSlides();
>          // ソース スライドを宛先のスライドコレクションにクローンします。
>          slds.addClone(SourceSlide, iSlide, true);
>          // 宛先プレゼンテーションをディスクに保存します
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しいスライドのインデックス。 |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | クローン対象のスライド。 |

**戻り値:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 挿入されたマスタースライド。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

コレクションのすべての要素を指定された配列にコピーします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目的の配列。 |
| index | int | 目的の配列内の開始インデックス。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を返します。 読み取り専用 boolean.

**戻り値:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

同期化のルートを返します。 読み取り専用 Object.

**戻り値:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - コレクションを反復処理できる IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```

コレクション全体の Java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - コレクション全体の java.util.Iterator。