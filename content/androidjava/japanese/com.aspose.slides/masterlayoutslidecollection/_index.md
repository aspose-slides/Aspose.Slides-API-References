---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: 定義されたマスタースライドのすべてのレイアウトスライドのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/masterlayoutslidecollection/
---
**継承:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
```
public final class MasterLayoutSlideCollection extends LayoutSlideCollection implements IMasterLayoutSlideCollection
```

定義されたマスタースライドのすべてのレイアウトスライドのコレクションを表します。LayoutSlideCollection クラスを継承し、マスターのレイアウトスライドの個々のコレクションのコンテキストでレイアウトスライドを追加/挿入/削除/クローン作成/順序変更するためのメソッドを提供します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | 指定されたレイアウトスライドのコピーをコレクションの末尾に追加します。 |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | 指定されたレイアウトスライドのコピーをコレクションの指定位置に挿入します。 |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | 新しいレイアウトスライドをコレクションの末尾に追加します。 |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | 新しいレイアウトスライドをコレクションの指定位置に挿入します。 |
| [removeAt(int index)](#removeAt-int-) | コレクションの指定インデックスにある要素を削除します。 |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | コレクションからレイアウトスライドを指定位置へ移動します。 |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

指定されたレイアウトスライドのコピーをコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | クローンするスライド。 |

--------------------

1) このレイアウトスライドコレクションの親マスタースライドに新しいレイアウトがリンクされます。したがって、PowerPoint の「Use Destination Theme」オプションを使用したコピー/貼り付けに相当します。 2) このメソッドに相当するものは、[IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) メソッドで、([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) プロパティを介してアクセスします。

**戻り値:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 追加されたスライド。
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

指定されたレイアウトスライドのコピーをコレクションの指定位置に挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しいスライドのインデックス。 |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | クローンするスライド。 |

--------------------

このレイアウトスライドコレクションの親マスタースライドに新しいレイアウトがリンクされます。したがって、PowerPoint の「Use Destination Theme」オプションを使用したコピー/貼り付けに相当します。

**戻り値:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 挿入されたスライド。
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

新しいレイアウトスライドをコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| layoutType | byte | 新しいレイアウトのレイアウトタイプ。サポートされているレイアウトタイプ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. 現在サポートされていないレイアウトタイプ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | 新しいレイアウトの名前。指定された名前が既に使用されている場合は ArgumentException がスローされます。null が渡された場合、レイアウトタイプに応じて自動的に名前が生成されます（例: "Title Slide" や "1_Title Slide", "2_.." など）。 |

--------------------

1) layoutType が SlideLayoutType.Custom の場合、追加されるレイアウトにはプレースホルダーもシェイプも含まれません。 2) このメソッドに相当するものは、[IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) メソッドで、([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) プロパティを介してアクセスします。

**戻り値:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 追加されたスライド。
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

新しいレイアウトスライドをコレクションの指定位置に挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しいスライドのインデックス。 |
| layoutType | byte | 新しいレイアウトのレイアウトタイプ。サポートされているレイアウトタイプ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. 現在サポートされていないレイアウトタイプ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | 新しいレイアウトの名前。指定された名前が既に使用されている場合は ArgumentException がスローされます。null が渡された場合、レイアウトタイプに応じて自動的に名前が生成されます（例: "Title Slide" や "1_Title Slide", "2_.." など）。 |

--------------------

layoutType が SlideLayoutType.Custom の場合、挿入されたレイアウトにはプレースホルダーもシェイプも含まれません。

**戻り値:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 挿入されたスライド。
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

コレクションの指定インデックスにある要素を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除する要素のゼロベースインデックス。

--------------------

1) PptxEditException のスローを回避するために、事前に layout の HasDependingSlides プロパティを確認してください。 2) コードを簡素化するために [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) メソッドも使用できます。

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

レイアウトスライドをコレクションから指定位置へ移動します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 対象インデックス。 |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 移動するスライド。 |