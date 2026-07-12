---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides for Android の Java API リファレンス
description: プレゼンテーション内のすべてのレイアウトスライドのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/igloballayoutslidecollection/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

プレゼンテーション内のすべてのレイアウトスライドのコレクションを表します。ILayoutSlideCollection インターフェイスを拡張し、マスターのレイアウトスライドの個々のコレクションを統合するコンテキストでレイアウトスライドを追加/クローンするためのメソッドを提供します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | 指定されたレイアウトスライドのコピーをプレゼンテーションに追加します。 |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | 指定されたレイアウトスライドのコピーをプレゼンテーションに追加します。 |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | 新しいレイアウトスライドをプレゼンテーションに追加します。 |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

指定されたレイアウトスライドのコピーをプレゼンテーションに追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | クローンするスライド。 |

--------------------

異なるプレゼンテーション間でレイアウトをクローンする場合、元の書式を保持するためにレイアウトのマスターもクローンできます。内部レジストリが自動的にクローンされたマスターを追跡し、同じマスタースライドのクローンが複数作成されるのを防止します。マスター スライドの手動クローンは防止も登録もされません。

**戻り値:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 追加されたスライド。

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

指定されたレイアウトスライドのコピーをプレゼンテーションに追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | クローンするスライド。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新しいレイアウト用のマスタースライド。 |

--------------------

新しいレイアウトは、宛先プレゼンテーションで定義されたマスターにリンクされます。これは PowerPoint の「宛先のテーマを使用」オプションでのコピー/貼り付けと同等です。

**戻り値:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 追加されたスライド。

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

新しいレイアウトスライドをプレゼンテーションに追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新しいレイアウト用のマスタースライド。 |
| layoutType | byte | 新しいレイアウトのレイアウトタイプ。サポートされているレイアウトタイプ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. 現在サポートされていないレイアウトタイプ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | 新しいレイアウトの名前。すでに使用中の名前が渡された場合は ArgumentException がスローされます。null が渡された場合、渡されたレイアウトタイプに応じて自動的に名前が生成されます（例: "Title Slide"、"1_Title Slide"、"2_…" など）。 |

--------------------

1) layoutType に SlideLayoutType.Custom の値を指定した場合、プレースホルダーもシェイプも含まれないレイアウトが追加されます。2) このメソッドのアナログは、[IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) メソッドで ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) プロパティを使用してアクセスできます。

**戻り値:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 追加されたスライド。