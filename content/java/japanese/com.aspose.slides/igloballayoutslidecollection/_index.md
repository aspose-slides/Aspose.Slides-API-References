---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides for Java API リファレンス
description: プレゼンテーション内のすべてのレイアウト スライドのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/igloballayoutslidecollection/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

プレゼンテーション内のすべてのレイアウト スライドのコレクションを表します。ILayoutSlideCollection インターフェイスを拡張し、個々のマスター レイアウト スライドのコレクションを統合するコンテキストでレイアウト スライドを追加/クローンするメソッドを提供します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | 指定されたレイアウト スライドのコピーをプレゼンテーションに追加します。 |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | 指定されたレイアウト スライドのコピーをプレゼンテーションに追加します。 |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | 新しいレイアウト スライドをプレゼンテーションに追加します。 |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

指定されたレイアウト スライドのコピーをプレゼンテーションに追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | クローン対象のスライド。 |

--------------------

異なるプレゼンテーション間でレイアウトをクローンする場合、元の書式を保持するためにレイアウトのマスターもクローンできます。内部レジストリは自動的にクローンされたマスターを追跡し、同じマスター スライドの複数のクローン作成を防止します。マスター スライドの手動クローンは防止も登録もされません。

**戻り値:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 追加されたスライド。

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

指定されたレイアウト スライドのコピーをプレゼンテーションに追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | クローン対象のスライド。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新しいレイアウト用のマスター スライド。 |

--------------------

新しいレイアウトは、宛先プレゼンテーションで定義されたマスターにリンクされます。これは PowerPoint の「目的地のテーマを使用」オプションを伴うコピー/貼り付けと同等です。

**戻り値:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 追加されたスライド。

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

新しいレイアウト スライドをプレゼンテーションに追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新しいレイアウト用のマスター スライド。 |
| layoutType | byte | 新しいレイアウトのレイアウト タイプ。サポートされているレイアウト タイプ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom。現在サポートされていないレイアウト タイプ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| layoutName | java.lang.String | 新しいレイアウトの名前。指定した名前が既に使用中の場合は ArgumentException がスローされます。null が渡された場合、レイアウト タイプに応じて自動的に名前が生成されます（例: "Title Slide"、"1_Title Slide"、"2_…" など）。 |

--------------------

1) layoutType に SlideLayoutType.Custom を指定した場合、プレースホルダーもシェイプも含まないレイアウトが追加されます。2) このメソッドに相当するものは、[IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) プロパティ ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) でアクセスできるメソッドです。

**戻り値:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 追加されたスライド。