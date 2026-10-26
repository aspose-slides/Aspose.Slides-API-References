---
title: SlideCollection
second_title: Java API 経由の Android 用 Aspose.Slides リファレンス
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
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | 新しい空のスライドをコレクションの末尾に追加します。 |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | 指定されたスライドのコピーをコレクションの指定位置に挿入します。 |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | 指定されたスライドのコピーをコレクションの末尾に追加します。 |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | 指定されたスライドのコピーをコレクションの指定位置に挿入します。 |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | 指定されたソーススライドのコピーをコレクションの末尾に追加します。 |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | 指定されたソーススライドのコピーをコレクションの指定位置に挿入します。 |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | コレクションから特定のオブジェクトの最初の出現を削除します。 |
| [removeAt(int index)](#removeAt-int-) | コレクションの指定インデックスにある要素を削除します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の Java イテレータを返します。 |
| [toArray()](#toArray--) | すべてのスライドを含む配列を作成して返します。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 指定された範囲のすべてのスライドを含む配列を作成して返します。 |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | コレクションからスライドを指定された位置に移動します。 |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | コレクションからスライドを指定された位置に移動します。 |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | コレクション内の指定されたスライドのインデックスを返します。 |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | PDF ドキュメントからスライドを作成し、コレクションの末尾に追加します。 |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | PDF インポートオプションを考慮して、PDF ドキュメントからスライドを作成し、コレクションの末尾に追加します。 |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | PDF ドキュメントからスライドを作成し、コレクションの末尾に追加します。 |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | PDF ドキュメントからスライドを作成し、コレクションの末尾に追加します。 |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML テキストからスライドを作成し、コレクションの末尾に追加します。 |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | HTML テキストからスライドを作成し、コレクションの末尾に追加します。 |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML テキストからスライドを作成し、コレクションの末尾に追加します。 |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | HTML テキストからスライドを作成し、コレクションの末尾に追加します。 |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML テキストからスライドを作成し、指定された位置に挿入します。 |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | HTML テキストからスライドを作成し、指定された位置に挿入します。 |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | HTML テキストからスライドを作成し、指定された位置に挿入します。 |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | HTML テキストからスライドを作成し、指定された位置に挿入します。 |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML テキストからスライドを作成し、指定された位置に挿入します。 |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | HTML テキストからスライドを作成し、指定された位置に挿入します。 |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | HTML テキストからスライドを作成し、指定された位置に挿入します。 |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | HTML テキストからスライドを作成し、指定された位置に挿入します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションのすべての要素を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化されているかどうかを示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期ルートを返します。 |

### size() {#size--}
```
public final int size()
```

コレクションに実際に含まれる要素数を取得します。 読み取り専用 int.

**返り値:**
int

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

指定されたインデックスの要素を取得します。 読み取り専用 [Slide](../../com.aspose.slides/slide)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**返り値:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```

指定されたスライドのコピーをコレクションの末尾に追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | クローン対象のスライド。

--------------------

異なるプレゼンテーション間でスライドをクローンする場合、スライドのマスターもクローンされる可能性があります。内部レジストリは自動的にクローンされたマスターを追跡し、同一マスタースライドの複数クローン作成を防止します。マスタースライドの手動クローンは防止も登録もされません。クローン処理を詳細に制御したい場合は \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) または \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) を使用してください。スライドのクローンには [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) または [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-)、レイアウトのクローンには [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) を使用します。

**返り値:**
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
>      // 現在、第二セクションには最初のスライドのコピーが含まれています。
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | クローン対象のスライド。 |
| section | [ISection](../../com.aspose.slides/isection) | 新しいスライドのセクション。 |

**返り値:**
[ISlide](../../com.aspose.slides/islide) - 新しいスライド。

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

指定されたスライドのコピーをコレクションの指定位置に挿入します。

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // プレゼンテーションファイルを表す Presentation クラスのインスタンスを作成する
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // 同じプレゼンテーションのスライドコレクションの末尾に目的のスライドをクローンする
>      ISlideCollection slds = pres.getSlides();
>      // 同じプレゼンテーション内の指定インデックスに目的のスライドをクローンする
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // 変更したプレゼンテーションをディスクに保存する
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // ソースのプレゼンテーションファイルを読み込むために Presentation クラスのインスタンスを作成する
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // スライドをクローンする先の PPTX 用に Presentation クラスのインスタンスを作成する
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // 宛先プレゼンテーションをディスクに保存する
>          destPres.save("Aspose2_out.pptx", SaveFormat.Pptx);
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
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | クローン対象のスライド。

--------------------

異なるプレゼンテーション間でスライドをクローンする場合、スライドのマスターもクローンされる可能性があります。内部レジストリは自動的にクローンされたマスターを追跡し、同一マスタースライドの複数クローン作成を防止します。マスタースライドの手動クローンは防止も登録もされません。クローン処理を詳細に制御したい場合は \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) または \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) を使用してください。スライドのクローンには [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) を使用します。

**返り値:**
[ISlide](../../com.aspose.slides/islide) - 挿入されたスライド。

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

新しい空のスライドをコレクションの末尾に追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | スライドのレイアウト。

**返り値:**
[ISlide](../../com.aspose.slides/islide) - 追加されたスライド。

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

指定されたスライドのコピーをコレクションの指定位置に挿入します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しいスライドのインデックス。 |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | スライドのレイアウト。

**返り値:**
[ISlide](../../com.aspose.slides/islide) - 挿入されたスライド。

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

指定されたスライドのコピーをコレクションの末尾に追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | クローン対象のスライド。 |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 新しいスライドのレイアウトスライド。

**返り値:**
[ISlide](../../com.aspose.slides/islide) - 新しいスライド。

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

指定されたスライドのコピーをコレクションの指定位置に挿入します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しいスライドのインデックス。 |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | クローン対象のスライド。 |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 新しいスライドのレイアウトスライド。

**返り値:**
[ISlide](../../com.aspose.slides/islide) - 挿入されたスライド。

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

指定されたソーススライドのコピーをコレクションの末尾に追加します。適切なレイアウトは、指定されたマスターから自動的に選択されます（適切なレイアウトは、ソーススライドのレイアウトと同じ Type または Name を持つもの）。適切なレイアウトが存在しない場合、ソーススライドのレイアウトはクローンされます（allowCloneMissingLayout が true の場合）。false の場合は PptxEditException がスローされます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | クローン対象のスライド。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新しいスライドのマスタースライド。 |
| allowCloneMissingLayout | boolean | 指定されたマスターに適切なレイアウトがない場合、ソーススライドのレイアウトをクローンするかどうかを決定します。true の場合はクローンし、false の場合は PptxEditException がスローされます。 |

**返り値:**
[ISlide](../../com.aspose.slides/islide) - 新しいスライド。

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

指定されたソーススライドのコピーをコレクションの指定位置に挿入します。適切なレイアウトは、指定されたマスターから自動的に選択されます（適切なレイアウトは、ソーススライドのレイアウトと同じ Type または Name を持つもの）。適切なレイアウトが存在しない場合、ソーススライドのレイアウトはクローンされます（allowCloneMissingLayout が true の場合）。false の場合は PptxEditException がスローされます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しいスライドのインデックス。 |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | クローン対象のスライド。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新しいスライドのマスタースライド。 |
| allowCloneMissingLayout | boolean | 指定されたマスターに適切なレイアウトがない場合の挙動を決定します。true の場合はクローンし、false の場合は PptxEditException がスローされます。 |

**返り値:**
[ISlide](../../com.aspose.slides/islide) - 挿入されたスライド。

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

コレクションから特定のオブジェクトの最初の出現を削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | コレクションから削除するスライド。

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

コレクションの指定インデックスにある要素を削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除対象要素の 0 ベースインデックス。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

コレクションを反復処理する列挙子を返します。

**返り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - コレクションを反復処理できる IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

コレクション全体の Java イテレータを返します。

**返り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - 全体コレクション用の java.util.Iterator。

### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

すべてのスライドを含む配列を作成して返します。

**返り値:**
com.aspose.slides.ISlide[] - [Slide](../../com.aspose.slides/slide) の配列

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

指定された範囲のすべてのスライドを含む配列を作成して返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startIndex | int | 追加する最初のスライドのインデックス。 |
| count | int | 追加するスライドの数。

**返り値:**
com.aspose.slides.ISlide[] - [Slide](../../com.aspose.slides/slide) の配列

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

コレクションからスライドを指定された位置に移動します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 目的インデックス。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 移動対象スライド。

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

コレクションからスライドを指定された位置に移動します。スライドはインデックスから開始し、リスト内の順序で配置されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 目的インデックス。 |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | 移動するスライド。

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```

コレクション内の指定されたスライドのインデックスを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | 検索対象スライド。

**返り値:**
int - スライドのインデックス、存在しなければ -1。

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


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| path | java.lang.String | PDF ドキュメントへのパス。

**返り値:**
com.aspose.slides.ISlide[] - 追加されたスライド

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

PDF インポートオプションを考慮して、PDF ドキュメントからスライドを作成し、コレクションの末尾に追加します。

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


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| path | java.lang.String | PDF ドキュメントへのパス。 |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF インポート用オプション。

**返り値:**
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

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pdfStream | java.io.InputStream | PDF ドキュメントのソースとして使用されるストリーム。

**返り値:**
com.aspose.slides.ISlide[] - 追加されたスライド

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

PDF ドキュメントからスライドを作成し、コレクションの末尾に追加します。

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

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pdfStream | java.io.InputStream | PDF ドキュメントのソースとして使用されるストリーム。 |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF インポート用オプション。

**返り値:**
com.aspose.slides.ISlide[] - 追加されたスライド

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

HTML テキストからスライドを作成し、コレクションの末尾に追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| htmlText | java.lang.String | 追加する HTML。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 外部オブジェクトを取得するコールバックオブジェクト。null の場合、すべての外部オブジェクトは無視されます。 |
| uri | java.lang.String | 指定された HTML の URI。相対リンクの解決に使用されます。

**返り値:**
com.aspose.slides.ISlide[] - 追加されたスライド。

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

HTML テキストからスライドを作成し、コレクションの末尾に追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| htmlText | java.lang.String | 追加する HTML。

**返り値:**
com.aspose.slides.ISlide[] - 追加されたスライド

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

HTML テキストからスライドを作成し、コレクションの末尾に追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| htmlStream | java.io.InputStream | HTML ファイルのソースとして使用されるストリーム。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 外部オブジェクトを取得するコールバックオブジェクト。null の場合、すべての外部オブジェクトは無視されます。 |
| uri | java.lang.String | 指定された HTML の URI。相対リンクの解決に使用されます。

**返り値:**
com.aspose.slides.ISlide[] - 追加されたスライド。

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
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("file.html");
>          // AddFromHtml メソッドを呼び出し、HTML ファイルを渡します。
>          pres.getSlides().addFromHtml(fos);
>          // Save メソッドを使用してファイルを PowerPoint ドキュメントとして保存します。
>          pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| htmlStream | java.io.InputStream | HTML ファイルのソースとして使用されるストリーム。

**返り値:**
com.aspose.slides.ISlide[] - 追加されたスライド

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

HTML テキストからスライドを作成し、指定された位置に挿入します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 挿入位置。 |
| htmlText | java.lang.String | 追加する HTML。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 外部オブジェクトを取得するコールバックオブジェクト。null の場合、すべての外部オブジェクトは無視されます。 |
| uri | java.lang.String | 指定された HTML の URI。相対リンクの解決に使用されます。

**返り値:**
com.aspose.slides.ISlide[] - 追加されたスライド。

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

HTML テキストからスライドを作成し、指定された位置に挿入します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 挿入位置。 |
| htmlText | java.lang.String | 追加する HTML。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 外部オブジェクトを取得するコールバックオブジェクト。null の場合、すべての外部オブジェクトは無視されます。 |
| uri | java.lang.String | 指定された HTML の URI。相対リンクの解決に使用されます。 |
| useSlideWithIndexAsStart | boolean | このフラグは、挿入開始方法を決定します。true の場合、指定インデックスのスライドの空白領域から開始し、false の場合は新しく作成されたスライドにデータが追加されます。

**返り値:**
com.aspose.slides.ISlide[] - 追加されたスライド。

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

HTML テキストからスライドを作成し、指定された位置に挿入します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 挿入位置。 |
| htmlText | java.lang.String | 追加する HTML。

**返り値:**
com.aspose.slides.ISlide[] - 追加されたスライド

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

HTML テキストからスライドを作成し、指定された位置に挿入します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 挿入位置。 |
| htmlText | java.lang.String | 追加する HTML。 |
| useSlideWithIndexAsStart | boolean | このフラグは、挿入開始方法を決定します。true の場合、指定インデックスのスライドの空白領域から開始し、false の場合は新しく作成されたスライドにデータが追加されます。

**返り値:**
com.aspose.slides.ISlide[] - 追加されたスライド

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

HTML テキストからスライドを作成し、指定された位置に挿入します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 挿入位置。 |
| htmlStream | java.io.InputStream | HTML ファイルのソースとして使用されるストリーム。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 外部オブジェクトを取得するコールバックオブジェクト。null の場合、すべての外部オブジェクトは無視されます。 |
| uri | java.lang.String | 指定された HTML の URI。相対リンクの解決に使用されます。

**返り値:**
com.aspose.slides.ISlide[] - 追加されたスライド。

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

HTML テキストからスライドを作成し、指定された位置に挿入します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 挿入位置。 |
| htmlStream | java.io.InputStream | HTML ファイルのソースとして使用されるストリーム。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 外部オブジェクトを取得するコールバックオブジェクト。null の場合、すべての外部オブジェクトは無視されます。 |
| uri | java.lang.String | 指定された HTML の URI。相対リンクの解決に使用されます。 |
| useSlideWithIndexAsStart | boolean | このフラグは、挿入開始方法を決定します。true の場合、指定インデックスのスライドの空白領域から開始し、false の場合は新しく作成されたスライドにデータが追加されます。

**返り値:**
com.aspose.slides.ISlide[] - 追加されたスライド。

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

HTML テキストからスライドを作成し、指定された位置に挿入します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 挿入位置。 |
| htmlStream | java.io.InputStream | HTML ファイルのソースとして使用されるストリーム。

**返り値:**
com.aspose.slides.ISlide[] - 追加されたスライド

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

HTML テキストからスライドを作成し、指定された位置に挿入します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 挿入位置。 |
| htmlStream | java.io.InputStream | HTML ファイルのソースとして使用されるストリーム。 |
| useSlideWithIndexAsStart | boolean | このフラグは、挿入開始方法を決定します。true の場合、指定インデックスのスライドの空白領域から開始し、false の場合は新しく作成されたスライドにデータが追加されます。

**返り値:**
com.aspose.slides.ISlide[] - 追加されたスライド

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

コレクションのすべての要素を指定された配列にコピーします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目的配列。 |
| index | int | 目的配列の開始インデックス。

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

コレクションへのアクセスが同期化されているかどうかを示す値を返します。 読み取り専用 boolean。

**返り値:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

同期ルートを返します。 読み取り専用 Object。

**返り値:**
java.lang.Object