---
title: ISlideCollection
second_title: Aspose.Slides for Java API リファレンス
description: スライドのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/islidecollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.slides.IGenericCollection
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

スライドのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | 指定されたスライドのコピーをコレクションの末尾に追加します。 |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | 指定されたスライドのコピーを指定されたセクションの末尾に追加します。 |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | 指定されたスライドのコピーをコレクションの指定位置に挿入します。 |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | 新しい空のスライドをコレクションの末尾に追加します。 |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | 指定されたスライドのコピーをコレクションの指定位置に挿入します。 |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | 指定されたスライドのコピーをコレクションの末尾に追加します。 |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | 指定されたスライドのコピーをコレクションの指定位置に挿入します。 |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | 指定された元スライドのコピーをコレクションの末尾に追加します。 |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | 指定された元スライドのコピーをコレクションの指定位置に挿入します。 |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | コレクションから特定のオブジェクトの最初の出現を削除します。 |
| [removeAt(int index)](#removeAt-int-) | コレクションの指定されたインデックスの要素を削除します。 |
| [toArray()](#toArray--) | すべてのスライドを含む配列を作成して返します。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 指定された範囲のすべてのスライドを含む配列を作成して返します。 |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | コレクションからスライドを指定された位置に移動します。 |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | コレクションからスライドを指定された位置に移動します。 |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | コレクション内の指定されたスライドのインデックスを返します。 |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | PDFドキュメントからスライドを作成し、コレクションの末尾に追加します。 |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | PDFインポートオプションを考慮して、PDFドキュメントからスライドを作成し、コレクションの末尾に追加します。 |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | PDFドキュメントからスライドを作成し、コレクションの末尾に追加します。 |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | PDFドキュメントからスライドを作成し、コレクションの末尾に追加します。 |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTMLテキストからスライドを作成し、コレクションの末尾に追加します。 |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | HTMLテキストからスライドを作成し、コレクションの末尾に追加します。 |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTMLテキストからスライドを作成し、コレクションの末尾に追加します。 |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | HTMLテキストからスライドを作成し、コレクションの末尾に追加します。 |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTMLテキストからスライドを作成し、コレクションの指定位置に挿入します。 |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | HTMLテキストからスライドを作成し、コレクションの指定位置に挿入します。 |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTMLテキストからスライドを作成し、コレクションの指定位置に挿入します。 |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | HTMLテキストからスライドを作成し、コレクションの指定位置に挿入します。 |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | HTMLテキストからスライドを作成し、コレクションの指定位置に挿入します。 |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | HTMLテキストからスライドを作成し、コレクションの指定位置に挿入します。 |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | HTMLテキストからスライドを作成し、コレクションの指定位置に挿入します。 |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | HTMLテキストからスライドを作成し、コレクションの指定位置に挿入します。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISlide get_Item(int index)
```

指定されたインデックスの要素を取得します。読み取り専用 [ISlide](../../com.aspose.slides/islide)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public abstract ISlide addClone(ISlide sourceSlide)
```

指定されたスライドのコピーをコレクションの末尾に追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | クローン対象のスライド。 |

--------------------

異なるプレゼンテーション間でスライドをクローンする場合、スライドのマスターもクローンされることがあります。内部レジストリは自動的にクローンされたマスターを追跡し、同一マスタースライドの複数のクローン作成を防止します。マスタースライドの手動クローンは防止も登録もされません。クローン処理をより細かく制御したい場合は \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) または \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) をスライドのクローンに使用し、[IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) または [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) をレイアウトのクローンに、[IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) をマスターのクローンに使用してください。

**戻り値:**
[ISlide](../../com.aspose.slides/islide) - 新しいスライド。

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public abstract ISlide addClone(ISlide sourceSlide, ISection section)
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
>      // Now the second section contains a copy of the first slide.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | クローン対象のスライド。 |
| section | [ISection](../../com.aspose.slides/isection) | 新しいスライドのセクション。 |

**戻り値:**
[ISlide](../../com.aspose.slides/islide) - 新しいスライド。

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

指定されたスライドのコピーをコレクションの指定位置に挿入します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しいスライドのインデックス。 |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | クローン対象のスライド。 |

--------------------

異なるプレゼンテーション間でスライドをクローンする場合、スライドのマスターもクローンされることがあります。内部レジストリは自動的にクローンされたマスターを追跡し、同一マスタースライドの複数のクローン作成を防止します。マスタースライドの手動クローンは防止も登録もされません。クローン処理をより細かく制御したい場合は \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) または \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) をスライドのクローンに使用し、[IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) をマスターのクローンに使用してください。

**戻り値:**
[ISlide](../../com.aspose.slides/islide) - 挿入されたスライド。

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addEmptySlide(ILayoutSlide layout)
```

新しい空のスライドをコレクションの末尾に追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | スライドのレイアウト。 |

**戻り値:**
[ISlide](../../com.aspose.slides/islide) - 追加されたスライド。

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

空のスライドをコレクションの指定位置に挿入します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しいスライドのインデックス。 |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | スライドのレイアウト。 |

**戻り値:**
[ISlide](../../com.aspose.slides/islide) - 挿入されたスライド。

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

指定されたスライドのコピーをコレクションの末尾に追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | クローン対象のスライド。 |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 新しいスライドのレイアウトスライド。 |

**戻り値:**
[ISlide](../../com.aspose.slides/islide) - 新しいスライド。

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

指定されたスライドのコピーをコレクションの指定位置に挿入します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しいスライドのインデックス。 |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | クローン対象のスライド。 |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 新しいスライドのレイアウトスライド。 |

**戻り値:**
[ISlide](../../com.aspose.slides/islide) - 挿入されたスライド。

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

指定された元スライドのコピーをコレクションの末尾に追加します。適切なレイアウトは指定されたマスターから自動的に選択されます（適切なレイアウトとは、元スライドのレイアウトと同じ Type または Name を持つレイアウトです）。適切なレイアウトが存在しない場合、元スライドのレイアウトはクローンされます（allowCloneMissingLayout が true の場合）。allowCloneMissingLayout が false の場合は PptxEditException がスローされます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | クローン対象のスライド。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新しいスライドのマスタースライド。 |
| allowCloneMissingLayout | boolean | 指定されたマスターに適切なレイアウトがない場合、allowCloneMissingLayout が true であれば元スライドのレイアウトをクローンし、false であれば PptxEditException をスローします。 |

**戻り値:**
[ISlide](../../com.aspose.slides/islide) - 新しいスライド。

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

指定された元スライドのコピーをコレクションの指定位置に挿入します。適切なレイアウトは指定されたマスターから自動的に選択されます（適切なレイアウトとは、元スライドのレイアウトと同じ Type または Name を持つレイアウトです）。適切なレイアウトが存在しない場合、元スライドのレイアウトはクローンされます（allowCloneMissingLayout が true の場合）。allowCloneMissingLayout が false の場合は PptxEditException がスローされます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しいスライドのインデックス。 |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | クローン対象のスライド。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新しいスライドのマスタースライド。 |
| allowCloneMissingLayout | boolean | 指定されたマスターに適切なレイアウトがない場合、allowCloneMissingLayout が true であれば元スライドのレイアウトをクローンし、false であれば PptxEditException をスローします。 |

**戻り値:**
[ISlide](../../com.aspose.slides/islide) - 挿入されたスライド。

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

コレクションから特定のオブジェクトの最初の出現を削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | コレクションから削除するスライド。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

コレクションの指定されたインデックスの要素を削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除する要素のゼロベースインデックス。 |

### toArray() {#toArray--}
```
public abstract ISlide[] toArray()
```

すべてのスライドを含む配列を作成して返します。

**戻り値:**
com.aspose.slides.ISlide[] - [ISlide](../../com.aspose.slides/islide) の配列

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract ISlide[] toArray(int startIndex, int count)
```

指定された範囲のすべてのスライドを含む配列を作成して返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startIndex | int | 追加する最初のスライドのインデックス。 |
| count | int | 追加するスライドの数。 |

**戻り値:**
com.aspose.slides.ISlide[] - [ISlide](../../com.aspose.slides/islide) の配列

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public abstract void reorder(int index, ISlide slide)
```

コレクションからスライドを指定された位置に移動します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 対象インデックス。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 移動するスライド。 |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public abstract void reorder(int index, ISlide[] slides)
```

コレクションからスライドを指定された位置に移動します。スライドはインデックスから開始し、リストに現れる順序で配置されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 対象インデックス。 |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | 移動するスライド。 |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public abstract int indexOf(ISlide slide)
```

コレクション内の指定されたスライドのインデックスを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | 検索するスライド。 |

**戻り値:**
int - スライドのインデックス、またはコレクションに属さない場合は -1。

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public abstract ISlide[] addFromPdf(String path)
```

PDFドキュメントからスライドを作成し、コレクションの末尾に追加します。

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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | java.lang.String | PDF ドキュメントへのパス |

**戻り値:**  
com.aspose.slides.ISlide[] - Added slides
### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

PDF ドキュメントからスライドを作成し、pdf インポート オプションを考慮してコレクションの末尾に追加します。

--------------------

> ```
> Example:
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | java.lang.String | PDF ドキュメントへのパス |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | pdf インポートのオプション |

**戻り値:**  
com.aspose.slides.ISlide[] - Added slides
### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
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


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pdfStream | java.io.InputStream | PDF ドキュメントのソースとして使用されるストリーム |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | pdf インポートのオプション |

**戻り値:**  
com.aspose.slides.ISlide[] - Added slides
### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pdfStream | java.io.InputStream | PDF ドキュメントのソースとして使用されるストリーム |

**戻り値:**  
com.aspose.slides.ISlide[] - Added slides
### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

HTML テキストからスライドを作成し、コレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| htmlText | java.lang.String | 追加する HTML |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 外部オブジェクトを取得するために使用されるコールバック オブジェクト。このパラメータが null の場合、すべての外部オブジェクトは無視されます。 |
| uri | java.lang.String | 指定された HTML の URI。相対リンクの解決に使用されます。 |

**戻り値:**  
com.aspose.slides.ISlide[] - Added slides.
### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
```

HTML テキストからスライドを作成し、コレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| htmlText | java.lang.String | 追加する HTML |

**戻り値:**  
com.aspose.slides.ISlide[] - Added slides
### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

HTML テキストからスライドを作成し、コレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| htmlStream | java.io.InputStream | HTML ファイルのソースとして使用されるストリーム オブジェクト。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 外部オブジェクトを取得するために使用されるコールバック オブジェクト。このパラメータが null の場合、すべての外部オブジェクトは無視されます。 |
| uri | java.lang.String | 指定された HTML の URI。相対リンクの解決に使用されます。 |

**戻り値:**  
com.aspose.slides.ISlide[] - Added slides.
### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```

HTML テキストからスライドを作成し、コレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| htmlStream | java.io.InputStream | HTML ファイルのソースとして使用されるストリーム オブジェクト。 |

**戻り値:**  
com.aspose.slides.ISlide[] - Added slides
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

HTML テキストからスライドを作成し、指定された位置にコレクションに挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 挿入位置 |
| htmlText | java.lang.String | 追加する HTML |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 外部オブジェクトを取得するために使用されるコールバック オブジェクト。このパラメータが null の場合、すべての外部オブジェクトは無視されます。 |
| uri | java.lang.String | 指定された HTML の URI。相対リンクの解決に使用されます。 |

**戻り値:**  
com.aspose.slides.ISlide[] - Added slides.
### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```

HTML テキストからスライドを作成し、指定された位置にコレクションに挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 挿入位置 |
| htmlText | java.lang.String | 追加する HTML |

**戻り値:**  
com.aspose.slides.ISlide[] - Added slides
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

HTML テキストからスライドを作成し、指定された位置にコレクションに挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 挿入位置 |
| htmlStream | java.io.InputStream | HTML ファイルのソースとして使用されるストリーム オブジェクト。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 外部オブジェクトを取得するために使用されるコールバック オブジェクト。このパラメータが null の場合、すべての外部オブジェクトは無視されます。 |
| uri | java.lang.String | 指定された HTML の URI。相対リンクの解決に使用されます。 |

**戻り値:**  
com.aspose.slides.ISlide[] - Added slides.
### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

HTML テキストからスライドを作成し、指定された位置にコレクションに挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 挿入位置 |
| htmlStream | java.io.InputStream | HTML ファイルのソースとして使用されるストリーム オブジェクト。 |

**戻り値:**  
com.aspose.slides.ISlide[] - Added slides
### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

HTML テキストからスライドを作成し、指定された位置にコレクションに挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 挿入位置 |
| htmlText | java.lang.String | 追加する HTML |
| useSlideWithIndexAsStart | boolean | このフラグは、挿入の開始方法を決定します。新しいスライドから開始するか、指定されたインデックスのスライドから開始するかです。**true** の場合、データの挿入は指定されたインデックスのスライドの空白スペースから開始されます。**false** の場合、データは作成されたスライドに追加されます。 |

**戻り値:**  
com.aspose.slides.ISlide[] - Added slides
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

HTML テキストからスライドを作成し、指定された位置にコレクションに挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 挿入位置 |
| htmlText | java.lang.String | 追加する HTML |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 外部オブジェクトを取得するために使用されるコールバック オブジェクト。このパラメータが null の場合、すべての外部オブジェクトは無視されます。 |
| uri | java.lang.String | 指定された HTML の URI。相対リンクの解決に使用されます。 |
| useSlideWithIndexAsStart | boolean | このフラグは、挿入の開始方法を決定します。新しいスライドから開始するか、指定されたインデックスのスライドから開始するかです。**true** の場合、データの挿入は指定されたインデックスのスライドの空白スペースから開始されます。**false** の場合、データは作成されたスライドに追加されます。 |

**戻り値:**  
com.aspose.slides.ISlide[] - Added slides.
### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

HTML テキストからスライドを作成し、指定された位置にコレクションに挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 挿入位置 |
| htmlStream | java.io.InputStream | HTML ファイルのソースとして使用されるストリーム オブジェクト。 |
| useSlideWithIndexAsStart | boolean | このフラグは、挿入の開始方法を決定します。新しいスライドから開始するか、指定されたインデックスのスライドから開始するかです。**true** の場合、データの挿入は指定されたインデックスのスライドの空白スペースから開始されます。**false** の場合、データは作成されたスライドに追加されます。 |

**戻り値:**  
com.aspose.slides.ISlide[] - Added slides
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

HTML テキストからスライドを作成し、指定された位置にコレクションに挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 挿入位置 |
| htmlStream | java.io.InputStream | HTML ファイルのソースとして使用されるストリーム オブジェクト。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | 外部オブジェクトを取得するために使用されるコールバック オブジェクト。このパラメータが null の場合、すべての外部オブジェクトは無視されます。 |
| uri | java.lang.String | 指定された HTML の URI。相対リンクの解決に使用されます。 |
| useSlideWithIndexAsStart | boolean | このフラグは、挿入の開始方法を決定します。新しいスライドから開始するか、指定されたインデックスのスライドから開始するかです。**true** の場合、データの挿入は指定されたインデックスのスライドの空白スペースから開始されます。**false** の場合、データは作成されたスライドに追加されます。 |

**戻り値:**  
com.aspose.slides.ISlide[] - Added slides.