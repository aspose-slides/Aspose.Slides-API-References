---
title: SlideUtil
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: プレゼンテーション内のシェイプとテキストの検索を支援するメソッドを提供します。
type: docs
url: /ja/com.aspose.slides/slideutil/
---
**継承:**
java.lang.Object
```
public class SlideUtil
```

プレゼンテーション内のシェイプとテキストの検索を支援するメソッドを提供します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | PPTX プレゼンテーション内で代替テキストによりシェイプを検索します。 |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | PPTX プレゼンテーションのスライド上で代替テキストによりシェイプを検索します。 |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | 指定されたスライド上ですべてのシェイプを検索し、指定されたプレースホルダータイプに一致するものを返します。 |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | スライド上のすべてのシェイプの配置を変更します。 |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | スライド上の選択されたシェイプの配置を変更します。 |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | グループシェイプ内のすべてのシェイプの配置を変更します。 |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | グループシェイプ内の選択されたシェイプの配置を変更します。 |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | プレゼンテーション内のテキストを指定された書式で検索し置換します |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | プレゼンテーション内のテキストを指定された書式で検索し置換します |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | PPTX プレゼンテーションのスライド上のすべてのテキストフレームを返します。 |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | 指定されたテキストを含む、指定スライド上のすべてのテキストフレームを返します。 |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | PPTX プレゼンテーション内のすべてのテキストフレームを返します。 |
| [toSaveFormat(int format)](#toSaveFormat-int-) | ソースファイル形式を対応する [SaveFormat](../../com.aspose.slides/saveformat) に変換します。 |
### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```


### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```


PPTX プレゼンテーション内で代替テキストによりシェイプを検索します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | スキャンされたプレゼンテーション。 |
| altText | java.lang.String | シェイプの代替テキスト。 |

**戻り値:**
[IShape](../../com.aspose.slides/ishape) - Shape または null.
### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```


スライド上で代替テキストによりシェイプを検索します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | スキャンされたスライド。 |
| altText | java.lang.String | シェイプの代替テキスト。 |

**戻り値:**
[IShape](../../com.aspose.slides/ishape) - Shape または null.
### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```


指定されたスライド上ですべてのシェイプを検索し、指定されたプレースホルダータイプに一致するものを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | シェイプを検索するスライド。 |
| placeholderType | byte | シェイプをフィルタリングするプレースホルダーのタイプ。 |

**戻り値:**
com.aspose.slides.IShape[] - 指定されたプレースホルダータイプに一致する [IShape](../../com.aspose.slides/ishape) オブジェクトの配列。
### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```


スライド上のすべてのシェイプの配置を変更します。シェイプを余白またはスライドの端に合わせるか、相互に整列させます。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignBottom, true, pres.getSlides().get_Item(0));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| alignmentType | int | 適用される整列タイプを決定します。 |
| alignToSlide | boolean | true の場合、シェイプはスライドの端に対して整列されます。 |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 親スライド。 |

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```


スライド上の選択されたシェイプの配置を変更します。シェイプを余白またはスライドの端に合わせるか、相互に整列させます。

--------------------

> ```
> Example:
>   
>   Presentation pres = new Presentation("pres.pptx");
>   try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IShape shape1 = slide.getShapes().get_Item(0);
>      IShape shape2 = slide.getShapes().get_Item(1);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignBottom, false, pres.getSlides().get_Item(0), new int[]
>      {
>          slide.getShapes().indexOf(shape1),
>          slide.getShapes().indexOf(shape2)
>      });
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| alignmentType | int | 適用される整列タイプを決定します。 |
| alignToSlide | boolean | true の場合、シェイプはスライドの端に対して整列されます。 |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 親スライド。 |
| shapeIndexes | int[] | 整列させるシェイプのインデックス。 |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```


グループシェイプ内のすべてのシェイプの配置を変更します。シェイプを余白またはスライドの端に合わせるか、相互に整列させます。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape) slide.getShapes().get_Item(0));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| alignmentType | int | 適用される整列タイプを決定します。 |
| alignToSlide | boolean | true の場合、シェイプはスライドの端に対して整列されます。 |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | 親グループシェイプ。 |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```


グループシェイプ内の選択されたシェイプの配置を変更します。シェイプを余白またはスライドの端に合わせるか、相互に整列させます。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.getShapes().get_Item(0), new int[] { 0, 2 });
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| alignmentType | int | 適用される整列タイプを決定します。 |
| alignToSlide | boolean | true の場合、シェイプはスライドの端に対して整列されます。 |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | 親グループシェイプ。 |
| shapeIndexes | int[] | 整列させるシェイプのインデックス。 |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```


指定された書式でプレゼンテーション内のテキストを検索し置換します。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PortionFormat format = new PortionFormat();
>      format.setFontHeight(24f);
>      format.setFontItalic(NullableBool.True);
>      format.getFillFormat().setFillType(FillType.Solid);
>      format.getFillFormat().getSolidFillColor().setColor(Color.RED);
> 
>      SlideUtil.findAndReplaceText(pres, true, "[this block] ", "my text ", format);
>      pres.save("replaced.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | スキャンされたプレゼンテーション。 |
| withMasters | boolean | マスタースライドも検索するかどうかを決定します。 |
| find | java.lang.String | 検索する文字列。 |
| replace | java.lang.String | 置換する文字列。検索文字列の文字 |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```


指定された書式でプレゼンテーション内のテキストを検索し置換します。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PortionFormat format = new PortionFormat();
>      format.setFontHeight(24f);
>      format.setFontItalic(NullableBool.True);
>      format.getFillFormat().setFillType(FillType.Solid);
>      format.getFillFormat().getSolidFillColor().setColor(Color.RED);
> 
>      SlideUtil.findAndReplaceText(pres, true, "[this block] ", "my text ", format);
>      pres.save("replaced.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | スキャンされたプレゼンテーション。 |
| withMasters | boolean | マスタースライドも検索するかどうかを決定します。 |
| find | java.lang.String | 検索する文字列。 |
| replace | java.lang.String | 置換する文字列。 |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | テキスト部分を置換する際の書式。null の場合、検索文字列の最初の文字の書式が使用されます。 |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```


PPTX プレゼンテーションのスライド上のすべてのテキストフレームを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | スキャンされたスライド。 |

**戻り値:**
com.aspose.slides.ITextFrame[] - [TextFrame](../../com.aspose.slides/textframe) オブジェクトの配列。
### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```


指定されたテキストを含む、指定スライド上のすべてのテキストフレームを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 検索対象のスライド。 |
| text | java.lang.String | テキストフレーム内で検索するテキスト。 |
| checkPlaceholderText | boolean | 空のテキストフレームでも、プレースホルダーテキストに検索テキストが含まれる場合に含めるかを示します。 |

**戻り値:**
com.aspose.slides.ITextFrame[] - 指定されたテキストを含む [ITextFrame](../../com.aspose.slides/itextframe) オブジェクトの配列。
### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```


PPTX プレゼンテーション内のすべてのテキストフレームを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | スキャンされたプレゼンテーション。 |
| withMasters | boolean | マスタースライドも検索するかどうかを決定します。 |

**戻り値:**
com.aspose.slides.ITextFrame[] - [TextFrame](../../com.aspose.slides/textframe) オブジェクトの配列。
### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```


ソースファイル形式を対応する [SaveFormat](../../com.aspose.slides/saveformat) に変換します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| format | int | ソースファイル形式。 |

**戻り値:**
int - 対応する [SaveFormat](../../com.aspose.slides/saveformat) 値。