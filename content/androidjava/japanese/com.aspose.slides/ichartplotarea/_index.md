---
title: IChartPlotArea
second_title: Aspose.Slides for Android の Java API リファレンス
description: チャートタイトルのプロパティを表します。
type: docs
url: /ja/com.aspose.slides/ichartplotarea/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

チャートタイトルのプロパティを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFormat()](#getFormat--) | プロット領域のフォーマットを返します。 |
| [getLayoutTargetType()](#getLayoutTargetType--) | プロット領域のレイアウトが手動で定義されている場合、このプロパティは領域を内部（軸と軸ラベルを含まない）にレイアウトするか、外部（軸と軸ラベルを含む）にレイアウトするかを指定します。 |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | プロット領域のレイアウトが手動で定義されている場合、このプロパティは領域を内部（軸と軸ラベルを含まない）にレイアウトするか、外部（軸と軸ラベルを含む）にレイアウトするかを指定します。 |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


プロット領域のフォーマットを返します。読み取り専用 [IFormat](../../com.aspose.slides/iformat)。

**戻り値:**
[IFormat](../../com.aspose.slides/iformat)
### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```


プロット領域のレイアウトが手動で定義されている場合、このプロパティは領域を内部（軸と軸ラベルを含まない）にレイアウトするか、外部（軸と軸ラベルを含む）にレイアウトするかを指定します。読み書き可能 [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```

**戻り値:**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public abstract void setLayoutTargetType(int value)
```


プロット領域のレイアウトが手動で定義されている場合、このプロパティは領域を内部（軸と軸ラベルを含まない）にレイアウトするか、外部（軸と軸ラベルを含む）にレイアウトするかを指定します。読み書き可能 [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |