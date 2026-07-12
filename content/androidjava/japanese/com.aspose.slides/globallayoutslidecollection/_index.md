---
title: GlobalLayoutSlideCollection
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: プレゼンテーション内のすべてのレイアウト スライドのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/globallayoutslidecollection/
---
**継承:**  
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**実装されたすべてのインターフェイス:**  
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)  
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

プレゼンテーション内のすべてのレイアウト スライドのコレクションを表します。LayoutSlideCollection クラスを拡張し、マスターのレイアウト スライドの個々のコレクションを統合するコンテキストで、レイアウト スライドの追加/クローン作成メソッドを提供します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | 指定されたレイアウト スライドのコピーをプレゼンテーションに追加します。 |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | 指定されたレイアウト スライドのコピーをプレゼンテーションに追加します。 |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | プレゼンテーションに新しいレイアウト スライドを追加します。 |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

指定されたレイアウト スライドのコピーをプレゼンテーションに追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | クローン対象のスライド。 |

--------------------

異なるプレゼンテーション間でレイアウトをクローンする場合、元の書式を保持するためにレイアウトのマスターもクローンできます。内部レジストリは自動的にクローンされたマスターを追跡し、同じマスタースライドの複数のクローンが作成されるのを防止します。マスタースライドの手動クローンは防止も登録もされません。

**戻り値:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 追加されたスライド。

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

指定されたレイアウト スライドのコピーをプレゼンテーションに追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | クローン対象のスライド。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新しいレイアウトのマスタースライド。 |

--------------------

1) 新しいレイアウトは宛先プレゼンテーションで定義されたマスターにリンクされます。したがって、PowerPoint の「宛先のテーマを使用」オプションを使用したコピー/貼り付けと同等です。2) このメソッドの類似は、[IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) メソッドで、([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) プロパティでアクセスします。

**戻り値:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 追加されたスライド。

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

プレゼンテーションに新しいレイアウト スライドを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新しいレイアウトのマスタースライド。 |
| layoutType | byte | 新しいレイアウトのレイアウト タイプ。サポートされているレイアウト タイプ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. その他のレイアウト タイプは現在サポートされていません: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | 新しいレイアウトの名前。指定された名前が既に使用されている場合は ArgumentException がスローされます。null パラメータが渡された場合、渡されたレイアウト タイプに基づいて名前が自動的に生成されます（例: "Title Slide" や "1_Title Slide", "2_.." など）。 |

--------------------

1) layoutType が SlideLayoutType.Custom の場合、追加されたレイアウトにはプレースホルダーもシェイプも含まれません。2) このメソッドの類似は、[IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) メソッドで、([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) プロパティでアクセスします。

**戻り値:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 追加されたスライド。