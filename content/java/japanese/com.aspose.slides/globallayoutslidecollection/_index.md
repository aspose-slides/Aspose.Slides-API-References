---
title: GlobalLayoutSlideCollection
second_title: Aspose.Slides for Java API リファレンス
description: プレゼンテーション内のすべてのレイアウトスライドのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/globallayoutslidecollection/
---
**継承:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

プレゼンテーション内のすべてのレイアウトスライドのコレクションを表します。LayoutSlideCollection クラスを拡張し、個々のマスターレイアウトスライドコレクションを統合するコンテキストでレイアウトスライドの追加/クローン作成メソッドを提供します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | プレゼンテーションに指定されたレイアウトスライドのコピーを追加します。 |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | プレゼンテーションに指定されたレイアウトスライドのコピーを追加します。 |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | プレゼンテーションに新しいレイアウトスライドを追加します。 |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

プレゼンテーションに指定されたレイアウトスライドのコピーを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | クローン対象のスライド。 |

--------------------

異なるプレゼンテーション間でレイアウトをクローンする場合、元の書式設定を保持するためにレイアウトのマスターもクローンできる場合があります。内部レジストリは自動的にクローンされたマスターを追跡し、同一マスタースライドの複数クローン作成を防止します。マスタースライドの手動クローンは防止も登録もされません。 |

**戻り値:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 追加されたスライド。
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

プレゼンテーションに指定されたレイアウトスライドのコピーを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | クローン対象のスライド。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新しいレイアウト用のマスタースライド。 |

--------------------

1) 新しいレイアウトは宛先プレゼンテーションで定義されたマスターにリンクされます。これは PowerPoint の「宛先のテーマを使用」オプションを伴うコピー/貼り付けと同等です。2) このメソッドに相当するのは [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) メソッドで、([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) プロパティでアクセスします。 |

**戻り値:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 追加されたスライド。
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

プレゼンテーションに新しいレイアウトスライドを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新しいレイアウト用のマスタースライド。 |
| layoutType | byte | 新しいレイアウトのレイアウトタイプ。サポートされているレイアウトタイプ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. 現在サポートされていないレイアウトタイプ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | 新しいレイアウトの名前。指定した名前がすでに使用中の場合は ArgumentException がスローされます。null が渡された場合、レイアウトタイプに応じて自動的に名前が生成されます（例: 「Title Slide」や「1\_Title Slide」、 「2\_..」など）。 |

--------------------

1) layoutType に SlideLayoutType.Custom を指定した場合、プレースホルダーもシェイプも含まれないレイアウトが追加されます。2) このメソッドに相当するのは [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) メソッドで、([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) プロパティでアクセスします。 |

**戻り値:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 追加されたスライド。