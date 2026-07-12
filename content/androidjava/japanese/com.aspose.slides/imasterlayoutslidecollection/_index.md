---
title: IMasterLayoutSlideCollection
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 定義されたマスタースライドのすべてのレイアウトスライドのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/imasterlayoutslidecollection/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

定義されたマスタースライドのすべてのレイアウトスライドのコレクションを表します。 ILayoutSlideCollection インターフェイスを拡張し、マスターのレイアウトスライドの個々のコレクションのコンテキストでレイアウトスライドを追加/挿入/削除/クローンするためのメソッドを提供します。
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
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

指定されたレイアウトスライドのコピーをコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | クローンするスライド。 |

--------------------

1) このレイアウトは、親マスタースライドにリンクされます。このレイアウトスライドコレクションのためです。したがって、PowerPoint の「宛先のテーマを使用」オプションを使用したコピー/貼り付けと同等です。 2) このメソッドに相当するものは、[IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) メソッドで、[IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides) プロパティでアクセスできます。

**戻り値:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 追加されたスライド。
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

指定されたレイアウトスライドのコピーをコレクションの指定位置に挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しいスライドのインデックス。 |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | クローンするスライド。 |

--------------------

このレイアウトは、親マスタースライドにリンクされます。このレイアウトスライドコレクションのためです。したがって、PowerPoint の「宛先のテーマを使用」オプションを使用したコピー/貼り付けと同等です。

**戻り値:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 挿入されたスライド。
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```

新しいレイアウトスライドをコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| layoutType | byte | 新しいレイアウトのレイアウトタイプ。サポートされているレイアウトタイプ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. 現在サポートされていないレイアウトタイプ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | 新しいレイアウトの名前。指定された名前が既に使用されている場合は ArgumentException がスローされます。null パラメータが渡された場合、レイアウトタイプに応じて自動的に名前が生成されます（例: "Title Slide" や "1_Title Slide", "2_.." など）。 |

--------------------

1) layoutType に SlideLayoutType.Custom の値を指定した場合、追加されるレイアウトにはプレースホルダーもシェイプも含まれません。 2) このメソッドに相当するものは、[IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) メソッドで、[IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides) プロパティでアクセスできます。

**戻り値:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 追加されたスライド。
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

新しいレイアウトスライドをコレクションの指定位置に挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しいスライドのインデックス。 |
| layoutType | byte | 新しいレイアウトのレイアウトタイプ。サポートされているレイアウトタイプ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. 現在サポートされていないレイアウトタイプ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | 新しいレイアウトの名前。指定された名前が既に使用されている場合は ArgumentException がスローされます。null パラメータが渡された場合、レイアウトタイプに応じて自動的に名前が生成されます（例: "Title Slide" や "1_Title Slide", "2_.." など）。 |

--------------------

layoutType に SlideLayoutType.Custom の値を指定した場合、挿入されるレイアウトにはプレースホルダーもシェイプも含まれません。

**戻り値:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 挿入されたスライド。
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

コレクションの指定インデックスにある要素を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除する要素のゼロベースインデックス。 |

--------------------

1) PptxEditException がスローされるのを防ぐために、事前にレイアウトの HasDependingSlides プロパティを確認してください。 2) また、[ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) メソッドを使用してコードを簡素化することもできます。
### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```

コレクションからレイアウトスライドを指定位置へ移動します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | ターゲットインデックス。 |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 移動するスライド。 |