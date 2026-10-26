---
title: ISummaryZoomSectionCollection
second_title: Aspose.Slides for Java API リファレンス
description: Summary Zoom Section オブジェクトのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/isummaryzoomsectioncollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.slides.IGenericCollection
```
public interface ISummaryZoomSectionCollection extends IGenericCollection<ISummaryZoomSection>
```

Summary Zoom Section オブジェクトのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | 新しい Summary Zoom Section オブジェクトを作成し、コレクションに追加します |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | 指定されたセクションの Summary Zoom Section 要素を返します。 |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | コレクションから Summary Zoom Section オブジェクトを削除します。 |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | 指定された SummaryZoomSection オブジェクトのインデックスを返します。 |
| [clear()](#clear--) | コレクションからすべての SummaryZoomSection オブジェクトを削除します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISummaryZoomSection get_Item(int index)
```

指定されたインデックスの要素を取得します。読み取り専用 [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)。

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection zoomSection = collection.get_Item(1);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
### addSummaryZoomSection(ISection section) {#addSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection addSummaryZoomSection(ISection section)
```

新しい Summary Zoom Section オブジェクトを作成し、コレクションに追加します

--------------------

> ```
> この例はインデックスによって Summary Zoom Section 要素を取得する方法を示しています:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection newZoomSection = collection.addSummaryZoomSection(pres.getSections().get_Item(3));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 新しい Summary Zoom Section 要素のセクション [ISection](../../com.aspose.slides/isection)

既にこのセクションの要素がコレクションに存在する場合、既存の要素が返されます。 |

**戻り値:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - 追加された [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) 要素
### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection getSummarySection(ISection section)
```

指定されたセクションの Summary Zoom Section 要素を返します。

--------------------

> ```
> この例はインデックスによって Summary Zoom Section 要素を取得する方法を示しています:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection selectedObject = collection.getSummarySection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 見つけるセクション [ISection](../../com.aspose.slides/isection) |

**戻り値:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) または、コレクションがセクションの要素を含まない場合は null。
### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract void removeSummaryZoomSection(ISection section)
```

コレクションから Summary Zoom Section オブジェクトを削除します。

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       collection.removeSummaryZoomSection(pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Summary Zoom Section 要素を削除するセクション [ISection](../../com.aspose.slides/isection)。 |

### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public abstract int indexOf(ISummaryZoomSection summaryZoomSection)
```

指定された SummaryZoomSection オブジェクトのインデックスを返します。

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection selectedObject = collection.getSummarySection(pres.getSections().get_Item(2));
>       int idx = collection.indexOf(selectedObject);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| summaryZoomSection | [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) | 見つける SummaryZoomSection オブジェクト [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)。 |

**戻り値:**
int - SummaryZoomSection オブジェクトのインデックス、またはこのコレクションに属さない場合は -1。
### clear() {#clear--}
```
public abstract void clear()
```

コレクションからすべての SummaryZoomSection オブジェクトを削除します。

--------------------

> ```
> この例はインデックスによって Summary Zoom Section 要素を取得する方法を示しています:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       collection.clear();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```