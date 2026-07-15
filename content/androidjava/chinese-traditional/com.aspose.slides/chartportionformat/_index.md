---
title: ChartPortionFormat
second_title: Aspose.Slides for Android 的 Java API 參考
description: 此類別包含圖表中使用的圖表部份格式屬性。
type: docs
url: /zh-hant/com.aspose.slides/chartportionformat/
---
**繼承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**所有實作的介面：**
[com.aspose.slides.IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
```
public final class ChartPortionFormat extends BasePortionFormat implements IChartPortionFormat
```

此類別包含圖表中使用的圖表部份格式屬性。與 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) 不同，此類別的所有屬性皆可寫入。

--------------------

此類別用於返回和操作針對特定部份定義的文字部份格式屬性。這表示在取得值時不會套用繼承，因此在大多數情況下您會取得「未定義」的值。

若要取得包括繼承在內的有效格式參數值，您需要使用 [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective) 方法，該方法會返回一個 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) 實例。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
### getVersion() {#getVersion--}
```
public long getVersion()
```


版本。唯讀 long.

**返回值：**
long