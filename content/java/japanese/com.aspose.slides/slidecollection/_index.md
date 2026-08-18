---
title: SlideCollection
second_title: Aspose.Slides for Java API リファレンス
description: スライドのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/slidecollection/
---
**継承:**
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

スライドのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [size()](#size--) | コレクションに実際に含まれる要素数を取得します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | 指定されたスライドのコピーをコレクションの末尾に追加します。 |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | 指定されたスライドのコピーを指定されたセクションの末尾に追加します。 |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | 指定されたスライドのコピーをコレクションの指定位置に挿入します。 |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | 新しい空白スライドをコレクションの末尾に追加します。 |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | 指定されたスライドのコピーをコレクションの指定位置に挿入します。 |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | 指定されたスライドのコピーをコレクションの末尾に追加します。 |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | 指定されたスライドのコピーをコレクションの指定位置に挿入します。 |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | 指定されたソーススライドのコピーをコレクションの末尾に追加します。 |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | 指定されたソーススライドのコピーをコレクションの指定位置に挿入します。 |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | コレクションから特定のオブジェクトの最初の出現を削除します。 |
| [removeAt(int index)](#removeAt-int-) | コレクションの指定インデックスにある要素を削除します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [toArray()](#toArray--) | すべてのスライドを含む配列を作成し返します。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 指定された範囲のすべてのスライドを含む配列を作成し返します。 |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | コレクション内のスライドを指定された位置に移動します。 |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | コレクション内のスライドを指定された位置に移動します。 |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | コレクション内の指定されたスライドのインデックスを返します。 |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | PDF ドキュメントからスライドを作成し、コレクションの末尾に追加します。 |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | PDF ドキュメントからスライドを作成し、PDF インポートオプションを考慮してコレクションの末尾に追加します。 |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | PDF ドキュメントからスライドを作成し、コレクションの末尾に追加します。 |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | PDF ドキュメントからスライドを作成し、コレクションの末尾に追加します。 |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML テキストからスライドを作成し、コレクションの末尾に追加します。 |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | HTML テキストからスライドを作成し、コレクションの末尾に追加します。 |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML テキストからスライドを作成し、コレクションの末尾に追加します。 |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | HTML テキストからスライドを作成し、コレクションの末尾に追加します。 |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML テキストからスライドを作成し、コレクションの指定位置に挿入します。 |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | HTML テキストからスライドを作成し、コレクションの指定位置に挿入します。 |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | HTML テキストからスライドを作成し、コレクションの指定位置に挿入します。 |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | HTML テキストからスライドを作成し、コレクションの指定位置に挿入します。 |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML テキストからスライドを作成し、コレクションの指定位置に挿入します。 |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | HTML テキストからスライドを作成し、コレクションの指定位置に挿入します。 |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | HTML テキストからスライドを作成し、コレクションの指定位置に挿入します。 |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | HTML テキストからスライドを作成し、コレクションの指定位置に挿入します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションのすべての要素を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化 (スレッドセーフ) されているかどうかを示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期ルートを返します。 |

### size() {#size--}
```
public final int size()
```

コレクションに実際に含まれる要素数を取得します。読み取り専用 int。

**戻り値:**
int

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

指定されたインデックスの要素を取得します。読み取り専用 [Slide](../../com.aspose.slides/slide)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```

指定されたスライドのコピーをコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | クローン対象のスライド。 |

--------------------

異なるプレゼンテーション間でスライドをクローンすると、スライドのマスターもクローンされる場合があります。内部レジストリは自動的にクローンされたマスターを追跡し、同じマスター スライドの複数のクローン作成を防止します。マスター スライドの手動クローンは防止も登録もされません。クローン処理をより細かく制御したい場合は、#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) または #addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) を使用してスライドをクローンし、[IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) または [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) でレイアウトをクローンし、[IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) でマスターをクローンしてください。

**戻り値:**
[ISlide](../../com.aspose.slides/islide) - 新しいスライド。

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
```

指定されたスライドのコピーを指定されたセクションの末尾に追加します。

--------------------

> ```
> IPresentation presentation = new Presentation();
>  try
>  {
>      presentation.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 50, 300, 100);
>      presentation.getSections().addSection("Section 1", presentation.getSlides().get_Item(0));
>      
>      ISection section2 = presentation.getSections().appendEmptySection("Section 2");
>      presentation.getSlides().addClone(presentation.getSlides().get_Item(0), section2);
>      
>      // 2番目のセクションには最初のスライドのコピーが含まれます。
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | クローン対象のスライド。 |
| section | [ISection](../../com.aspose.slides/isection) | 新しいスライドのセクション。 |

**戻り値:**
[ISlide](../../com.aspose.slides/islide) - 新しいスライド。

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

コレクションの指定位置に指定されたスライドのコピーを挿入します。

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // プレゼンテーションファイルを表す Presentation クラスのインスタンスを作成します
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // 同じプレゼンテーション内のスライドコレクションの末尾に目的のスライドをクローンします
>      ISlideCollection slds = pres.getSlides();
>      // 同じプレゼンテーション内の指定インデックスに目的のスライドをクローンします
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // 変更されたプレゼンテーションをディスクに保存します
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // ソースプレゼンテーションファイルを読み込むために Presentation クラスのインスタンスを作成します
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // スライドをクローンする先の PPTX 用に Presentation クラスのインスタンスを作成します
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // 宛先プレゼンテーションをディスクに保存します
>          destPres.save("Aspose2_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しいスライドのインデックス。 |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | クローン対象のスライド。 |

--------------------

異なるプレゼンテーション間でスライドをクローンすると、スライドのマスターもクローンされる場合があります。内部レジストリは自動的にクローンされたマスターを追跡し、同じマスター スライドの複数のクローン作成を防止します。マスター スライドの手動クローンは防止も登録もされません。クローン処理をより細かく制御したい場合は、#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) または #insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) を使用してスライドをクローンし、[IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) でマスターをクローンしてください。

**戻り値:**
[ISlide](../../com.aspose.slides/islide) - 挿入されたスライド。

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

新しい空白スライドをコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | スライドのレイアウト。 |

**戻り値:**
[ISlide](../../com.aspose.slides/islide) - 追加されたスライド。

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

コレクションの指定位置に指定されたスライドのコピーを挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しいスライドのインデックス。 |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | スライドのレイアウト。 |

**戻り値:**
[ISlide](../../com.aspose.slides/islide) - 挿入されたスライド。

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

指定されたスライドのコピーをコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | クローン対象のスライド。 |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 新しいスライドのレイアウト スライド。 |

**戻り値:**
[ISlide](../../com.aspose.slides/islide) - 新しいスライド。

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

コレクションの指定位置に指定されたスライドのコピーを挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しいスライドのインデックス。 |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | クローン対象のスライド。 |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 新しいスライドのレイアウト スライド。 |

**戻り値:**
[ISlide](../../com.aspose.slides/islide) - 挿入されたスライド。

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

指定されたソーススライドのコピーをコレクションの末尾に追加します。適切なレイアウトは、指定されたマスターから自動的に選択されます（適切なレイアウトとは、ソーススライドのレイアウトと同じ Type または Name を持つレイアウトです）。適切なレイアウトが存在しない場合、ソーススライドのレイアウトがクローンされます（allowCloneMissingLayout が true の場合）または PptxEditException がスローされます（allowCloneMissingLayout が false の場合）。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | クローン対象のスライド。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新しいスライドのマスター スライド。 |
| allowCloneMissingLayout | boolean | 指定されたマスターに適切なレイアウトがない場合、ソーススライドのレイアウトをクローンするか (true の場合) それとも PptxEditException をスローするか (false の場合) を示すブール値。 |

**戻り値:**
[ISlide](../../com.aspose.slides/islide) - 新しいスライド。

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

コレクションの指定位置に指定されたソーススライドのコピーを挿入します。適切なレイアウトは、指定されたマスターから自動的に選択されます（適切なレイアウトとは、ソーススライドのレイアウトと同じ Type または Name を持つレイアウトです）。適切なレイアウトが存在しない場合、ソーススライドのレイアウトがクローンされます（allowCloneMissingLayout が true の場合）または PptxEditException がスローされます（allowCloneMissingLayout が false の場合）。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しいスライドのインデックス。 |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | クローン対象のスライド。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新しいスライドのマスター スライド。 |
| allowCloneMissingLayout | boolean | 指定されたマスターに適切なレイアウトがない場合、ソーススライドのレイアウトをクローンするか (true の場合) それとも PptxEditException をスローするか (false の場合) を示すブール値。 |

**戻り値:**
[ISlide](../../com.aspose.slides/islide) - 挿入されたスライド。

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

コレクションから特定のオブジェクトの最初の出現を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | コレクションから削除するスライド。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

コレクションの指定インデックスにある要素を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除する要素のゼロベースインデックス。 |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - An java.util.Iterator for the entire collection.

### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

すべてのスライドを含む配列を作成し返します。

**戻り値:**
com.aspose.slides.ISlide[] - Array of [Slide](../../com.aspose.slides/slide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

指定された範囲のすべてのスライドを含む配列を作成し返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| startIndex | int | 追加する最初のスライドのインデックス。 |
| count | int | 追加するスライドの数。 |

**戻り値:**
com.aspose.slides.ISlide[] - Array of [Slide](../../com.aspose.slides/slide)
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

スライドをコレクションから指定された位置へ移動します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 対象インデックス。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 移動するスライド。 |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

スライドをコレクションから指定された位置へ移動します。スライドはインデックスから開始し、リストに現れる順序で配置されます。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 対象インデックス。 |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | 移動するスライド。 |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```

コレクション内の指定されたスライドのインデックスを返します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | 検索するスライド。 |

**戻り値:**
int - スライドのインデックス、またはコレクションに属さない場合は -1。

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```

PDF ドキュメントからスライドを作成し、コレクションの末尾に追加します。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getSlides().addFromPdf("document.pdf");
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | PDF ドキュメントへのパス |

**戻り値:**
com.aspose.slides.ISlide[] - 追加されたスライド

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

PDF ドキュメントからスライドを作成し、PDF インポート オプションを考慮してコレクションの末尾に追加します。

--------------------

> ```
> 例:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
>      pres.getSlides().addFromPdf("document.pdf", pdfImportOptions);
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | PDF ドキュメントへのパス |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF インポートのオプション |

**戻り値:**
com.aspose.slides.ISlide[] - 追加されたスライド

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```

PDF ドキュメントからスライドを作成し、コレクションの末尾に追加します。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream stream = new FileInputStream("document.pdf");
>      pres.getSlides().addFromPdf(stream);
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfStream | java.io.InputStream | PDF ドキュメントのソースとして使用されるストリーム |

**戻り値:**
com.aspose.slides.ISlide[] - 追加されたスライド

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

PDF ドキュメントからスライドを作成し、PDF インポート オプションを考慮してコレクションの末尾に追加します。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
> 
>      FileInputStream stream = new FileInputStream("document.pdf");
>      pres.getSlides().addFromPdf(stream, pdfImportOptions);
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfStream | java.io.InputStream | PDF ドキュメントのソースとして使用されるストリーム |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF インポートのオプション |

**戻り値:**
com.aspose.slides.ISlide[] - 追加されたスライド

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

HTML テキストからスライドを作成し、コレクションの末尾に追加します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | java.lang.String | 追加する HTML。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 外部オブジェクトを取得するコールバックオブジェクト。null の場合、すべての外部オブジェクトは無視されます。 |
| uri | java.lang.String | 指定された HTML の URI。相対リンクの解決に使用されます。 |

**戻り値:**
com.aspose.slides.ISlide[] - 追加されたスライド。

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

HTML テキストからスライドを作成し、コレクションの末尾に追加します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | java.lang.String | 追加する HTML。 |

**戻り値:**
com.aspose.slides.ISSlide[] - 追加されたスライド

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

HTML テキストからスライドを作成し、コレクションの末尾に追加します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | java.io.InputStream | HTML ファイルのソースとして使用される Stream オブジェクト。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 外部オブジェクトを取得するコールバックオブジェクト。null の場合、すべての外部オブジェクトは無視されます。 |
| uri | java.lang.String | 指定された HTML の URI。相対リンクの解決に使用されます。 |

**戻り値:**
com.aspose.slides.ISSlide[] - 追加されたスライド。

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

HTML テキストからスライドを作成し、コレクションの末尾に追加します。

--------------------

> ```
> // Presentation クラスのインスタンスを作成します。
>  Presentation pres = new Presentation();
>  try {
>      String html = new String(Files.readAllBytes(Paths.get("file.html")));
>      // AddFromHtml メソッドを呼び出し、HTML ファイルを渡します。
>      pres.getSlides().addFromHtml(html);
>      // Save メソッドでファイルを PowerPoint ドキュメントとして保存します。
>      pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | java.io.InputStream | HTML ファイルのソースとして使用される Stream オブジェクト。 |

**戻り値:**
com.aspose.slides.ISSlide[] - 追加されたスライド

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

HTML テキストからスライドを作成し、指定された位置に挿入します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 挿入位置。 |
| htmlText | java.lang.String | 追加する HTML。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 外部オブジェクトを取得するコールバックオブジェクト。null の場合、すべての外部オブジェクトは無視されます。 |
| uri | java.lang.String | 指定された HTML の URI。相対リンクの解決に使用されます。 |

**戻り値:**
com.aspose.slides.ISSlide[] - 追加されたスライド。

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

HTML テキストからスライドを作成し、指定された位置に挿入します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 挿入位置。 |
| htmlText | java.lang.String | 追加する HTML。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 外部オブジェクトを取得するコールバックオブジェクト。null の場合、すべての外部オブジェクトは無視されます。 |
| uri | java.lang.String | 指定された HTML の URI。相対リンクの解決に使用されます。 |
| useSlideWithIndexAsStart | boolean | このフラグは挿入開始方法を決定します。true の場合、指定インデックスのスライド上の空白から開始します。false の場合、作成されたスライドにデータが追加されます。 |

**戻り値:**
com.aspose.slides.ISSlide[] - 追加されたスライド。

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

HTML テキストからスライドを作成し、指定された位置に挿入します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 挿入位置。 |
| htmlText | java.lang.String | 追加する HTML。 |

**戻り値:**
com.aspose.slides.ISSlide[] - 追加されたスライド

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

HTML テキストからスライドを作成し、指定された位置に挿入します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 挿入位置。 |
| htmlText | java.lang.String | 追加する HTML。 |
| useSlideWithIndexAsStart | boolean | このフラグは挿入開始方法を決定します。true の場合、指定インデックスのスライド上の空白から開始します。false の場合、作成されたスライドにデータが追加されます。 |

**戻り値:**
com.aspose.slides.ISSlide[] - 追加されたスライド

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

HTML テキストからスライドを作成し、指定された位置に挿入します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 挿入位置。 |
| htmlStream | java.io.InputStream | HTML ファイルのソースとして使用される Stream オブジェクト。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 外部オブジェクトを取得するコールバックオブジェクト。null の場合、すべての外部オブジェクトは無視されます。 |
| uri | java.lang.String | 指定された HTML の URI。相対リンクの解決に使用されます。 |

**戻り値:**
com.aspose.slides.ISSlide[] - 追加されたスライド。

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

HTML テキストからスライドを作成し、指定された位置に挿入します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 挿入位置。 |
| htmlStream | java.io.InputStream | HTML ファイルのソースとして使用される Stream オブジェクト。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 外部オブジェクトを取得するコールバックオブジェクト。null の場合、すべての外部オブジェクトは無視されます。 |
| uri | java.lang.String | 指定された HTML の URI。相対リンクの解決に使用されます。 |
| useSlideWithIndexAsStart | boolean | このフラグは挿入開始方法を決定します。true の場合、指定インデックスのスライド上の空白から開始します。false の場合、作成されたスライドにデータが追加されます。 |

**戻り値:**
com.aspose.slides.ISSlide[] - 追加されたスライド。

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

HTML テキストからスライドを作成し、指定された位置に挿入します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 挿入位置。 |
| htmlStream | java.io.InputStream | HTML ファイルのソースとして使用される Stream オブジェクト。 |

**戻り値:**
com.aspose.slides.ISSlide[] - 追加されたスライド

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

HTML テキストからスライドを作成し、指定された位置に挿入します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 挿入位置。 |
| htmlStream | java.io.InputStream | HTML ファイルのソースとして使用される Stream オブジェクト。 |
| useSlideWithIndexAsStart | boolean | このフラグは挿入開始方法を決定します。true の場合、指定インデックスのスライド上の空白から開始します。false の場合、作成されたスライドにデータが追加されます。 |

**戻り値:**
com.aspose.slides.ISSlide[] - 追加されたスライド

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

コレクションのすべての要素を指定された配列にコピーします。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 対象配列。 |
| index | int | 対象配列の開始インデックス。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

コレクションへのアクセスが同期 (スレッドセーフ) であるかどうかを示す値を返します。読み取り専用 boolean。

**戻り値:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

同期ルートを返します。読み取り専用 Object。

**戻り値:**
java.lang.Object