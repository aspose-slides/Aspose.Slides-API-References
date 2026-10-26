---
title: DataLabelFormat
second_title: Aspose.Slides for Android için Java API Referansı
description: DataLabel için biçimlendirme seçeneklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/datalabelformat/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

DataLabel için biçimlendirme seçeneklerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Okunur/yazılır boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Okunur/yazılır boolean. |
| [getNumberFormat()](#getNumberFormat--) | DataLabels nesnesi için biçim dizesini temsil eder. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | DataLabels nesnesi için biçim dizesini temsil eder. |
| [getFormat()](#getFormat--) | Veri etiketinin biçimini temsil eder. |
| [getPosition()](#getPosition--) | Veri etiketinin konumunu temsil eder. |
| [setPosition(int value)](#setPosition-int-) | Veri etiketinin konumunu temsil eder. |
| [getShowLegendKey()](#getShowLegendKey--) | Belirtilen bir grafiğin veri etiketi efsane anahtarı gösterim davranışını temsil eder. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Belirtilen bir grafiğin veri etiketi efsane anahtarı gösterim davranışını temsil eder. |
| [getShowValue()](#getShowValue--) | Belirtilen bir grafiğin veri etiketi yüzde değer gösterim davranışını temsil eder. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Belirtilen bir grafiğin veri etiketi yüzde değer gösterim davranışını temsil eder. |
| [getShowCategoryName()](#getShowCategoryName--) | Belirtilen bir grafiğin veri etiketi kategori adı gösterim davranışını temsil eder. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Belirtilen bir grafiğin veri etiketi kategori adı gösterim davranışını temsil eder. |
| [getShowSeriesName()](#getShowSeriesName--) | Bir grafikteki veri etiketlerinin seri adı gösterim davranışını belirtmek için Boolean döndürür veya ayarlar. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Bir grafikteki veri etiketlerinin seri adı gösterim davranışını belirtmek için Boolean döndürür veya ayarlar. |
| [getShowPercentage()](#getShowPercentage--) | Belirtilen bir grafiğin veri etiketi yüzde değer gösterim davranışını temsil eder. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Belirtilen bir grafiğin veri etiketi yüzde değer gösterim davranışını temsil eder. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Belirtilen bir grafiğin veri etiketi balon boyutu değer gösterim davranışını temsil eder. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Belirtilen bir grafiğin veri etiketi balon boyutu değer gösterim davranışını temsil eder. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Belirtilen bir grafiğin veri etiketi lider çizgi gösterim davranışını temsil eder. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Belirtilen bir grafiğin veri etiketi lider çizgi gösterim davranışını temsil eder. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Belirtilen bir grafiğin veri etiketi hücre değeri gösterim davranışını temsil eder. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Belirtilen bir grafiğin veri etiketi hücre değeri gösterim davranışını temsil eder. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Belirtilen bir grafiğin veri etiketinin veri çağrısı mı yoksa veri etiketi mi olarak gösterileceğini belirler. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Belirtilen bir grafiğin veri etiketinin veri çağrısı mı yoksa veri etiketi mi olarak gösterileceğini belirler. |
| [getSeparator()](#getSeparator--) | Bir grafikteki veri etiketleri için kullanılan ayırıcıyı temsil eden Variant'ı ayarlar veya döndürür. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Bir grafikteki veri etiketleri için kullanılan ayırıcıyı temsil eden Variant'ı ayarlar veya döndürür. |
| [getTextFormat()](#getTextFormat--) | Grafik metin biçimini döndürür. |
| [getChart()](#getChart--) | Grafiği döndürür. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Sürüm. Salt-okunur long.

**Döndürür:**
long
### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Okunur/yazılır boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki IsNumberFormatLinkedToSource özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketleri için IsNumberFormatLinkedToSource özelliğine de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" tüm DataLabels.get_Item(i).isNumberFormatLinkedToSource() değerinin val olmasına neden olur).

**Döndürür:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Okunur/yazılır boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki IsNumberFormatLinkedToSource özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketleri için IsNumberFormatLinkedToSource özelliğine de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" tüm DataLabels.get_Item(i).isNumberFormatLinkedToSource() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

DataLabels nesnesi için biçim dizesini temsil eder. Okunur/yazılır String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki NumberFormat özelliğinin varsayılan değerini alır veya ayarlar. Bu özellik bir değerle ayarlandığında, aynı değer DataLabelCollection koleksiyonundaki tüm veri etiketleri için NumberFormat özelliğine de uygulanır (ör. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" tüm DataLabels.get_Item(i).getNumberFormat() değerinin val olmasına neden olur).

**Döndürür:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

DataLabels nesnesi için biçim dizesini temsil eder. Okunur/yazılır String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki NumberFormat özelliğinin varsayılan değerini alır veya ayarlar. Bu özellik bir değerle ayarlandığında, aynı değer DataLabelCollection koleksiyonundaki tüm veri etiketleri için NumberFormat özelliğine de uygulanır (ör. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" tüm DataLabels.get_Item(i).getNumberFormat() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Veri etiketinin biçimini temsil eder. Salt-okunur [IFormat](../../com.aspose.slides/iformat).

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki varsayılan biçimi temsil eder.

**Döndürür:**
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Veri etiketinin konumunu temsil eder. Okunur/yazılır [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki Position özelliğinin varsayılan değerini alır veya ayarlar. VeriLabel nesneleri için konumu temsil eder. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri Position özelliğine tüm veri etiketleri için de uygular (ör. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" tüm DataLabels.get_Item(i).getPosition() değerinin val olmasına neden olur).

**Döndürür:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Veri etiketinin konumunu temsil eder. Okunur/yazılır [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki Position özelliğinin varsayılan değerini alır veya ayarlar. VeriLabel nesneleri için konumu temsil eder. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri Position özelliğine tüm veri etiketleri için de uygular (ör. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" tüm DataLabels.get_Item(i).getPosition() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

Belirtilen bir grafiğin veri etiketi efsane anahtarı gösterim davranışını temsil eder. Veri etiketi efsane anahtarı görünürse True. Okunur/yazılır boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowLegendKey özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowLegendKey özelliğine tüm veri etiketleri için de uygular (ör. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" tüm DataLabels.get_Item(i).getShowLegendKey() değerinin val olmasına neden olur).

**Döndürür:**
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

Belirtilen bir grafiğin veri etiketi efsane anahtarı gösterim davranışını temsil eder. Veri etiketi efsane anahtarı görünürse True. Okunur/yazılır boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowLegendKey özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowLegendKey özelliğine tüm veri etiketleri için de uygular (ör. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" tüm DataLabels.get_Item(i).getShowLegendKey() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

Belirtilen bir grafiğin veri etiketi yüzde değer gösterim davranışını temsil eder. True yüzde değerini gösterir. False gizler. Okunur/yazılır boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowValue özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowValue özelliğine tüm veri etiketleri için de uygular (ör. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" tüm DataLabels.get_Item(i).getShowValue() değerinin val olmasına neden olur).

**Döndürür:**
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

Belirtilen bir grafiğin veri etiketi yüzde değer gösterim davranışını temsil eder. True yüzde değerini gösterir. False gizler. Okunur/yazılır boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowValue özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowValue özelliğine tüm veri etiketleri için de uygular (ör. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" tüm DataLabels.get_Item(i).getShowValue() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

Belirtilen bir grafiğin veri etiketi kategori adı gösterim davranışını temsil eder. True kategori adını gösterir. False gizler. Okunur/yazılır boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowCategoryName özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowCategoryName özelliğine tüm veri etiketleri için de uygular (ör. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" tüm DataLabels.get_Item(i).getShowCategoryName() değerinin val olmasına neden olur).

**Döndürür:**
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

Belirtilen bir grafiğin veri etiketi kategori adı gösterim davranışını temsil eder. True kategori adını gösterir. False gizler. Okunur/yazılır boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowCategoryName özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowCategoryName özelliğine tüm veri etiketleri için de uygular (ör. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" tüm DataLabels.get_Item(i).getShowCategoryName() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

Bir grafikteki veri etiketlerinin seri adı gösterim davranışını belirtmek için Boolean döndürür veya ayarlar. True seri adını gösterir. False gizler. Okunur/yazılır boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowSeriesName özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowSeriesName özelliğine tüm veri etiketleri için de uygular (ör. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" tüm DataLabels.get_Item(i).getShowSeriesName() değerinin val olmasına neden olur).

**Döndürür:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

Bir grafikteki veri etiketlerinin seri adı gösterim davranışını belirtmek için Boolean döndürür veya ayarlar. True seri adını gösterir. False gizler. Okunur/yazılır boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowSeriesName özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowSeriesName özelliğine tüm veri etiketleri için de uygular (ör. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" tüm DataLabels.get_Item(i).getShowSeriesName() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

Belirtilen bir grafiğin veri etiketi yüzde değer gösterim davranışını temsil eder. True yüzde değerini gösterir. False gizler. Okunur/yazılır boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowPercentage özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowPercentage özelliğine tüm veri etiketleri için de uygular (ör. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" tüm DataLabels.get_Item(i).getShowPercentage() değerinin val olmasına neden olur).

**Döndürür:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

Belirtilen bir grafiğin veri etiketi yüzde değer gösterim davranışını temsil eder. True yüzde değerini gösterir. False gizler. Okunur/yazılır boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowPercentage özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowPercentage özelliğine tüm veri etiketleri için de uygular (ör. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" tüm DataLabels.get_Item(i).getShowPercentage() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

Belirtilen bir grafiğin veri etiketi balon boyutu değer gösterim davranışını temsil eder. True balon boyutu değerini gösterir. False gizler. Okunur/yazılır boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowBubbleSize özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowBubbleSize özelliğine tüm veri etiketleri için de uygular (ör. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" tüm DataLabels.get_Item(i).getShowBubbleSize() değerinin val olmasına neden olur).

**Döndürür:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

Belirtilen bir grafiğin veri etiketi balon boyutu değer gösterim davranışını temsil eder. True balon boyutu değerini gösterir. False gizler. Okunur/yazılır boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowBubbleSize özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowBubbleSize özelliğine tüm veri etiketleri için de uygular (ör. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" tüm DataLabels.get_Item(i).getShowBubbleSize() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

Belirtilen bir grafiğin veri etiketi lider çizgi gösterim davranışını temsil eder. True lider çizgileri gösterir. False gizler. Okunur/yazılır boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowLeaderLines özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowLeaderLines özelliğine tüm veri etiketleri için de uygular (ör. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" tüm DataLabels.get_Item(i).getShowLeaderLines() değerinin val olmasına neden olur).

**Döndürür:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

Belirtilen bir grafiğin veri etiketi lider çizgi gösterim davranışını temsil eder. True lider çizgileri gösterir. False gizler. Okunur/yazılır boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowLeaderLines özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowLeaderLines özelliğine tüm veri etiketleri için de uygular (ör. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" tüm DataLabels.get_Item(i).getShowLeaderLines() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

Belirtilen bir grafiğin veri etiketi hücre değeri gösterim davranışını temsil eder. True hücre değerini gösterir. False gizler. Okunur/yazılır boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowLabelValueFromCell özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowLabelValueFromCell özelliğine tüm veri etiketleri için de uygular (ör. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" tüm DataLabels.get_Item(i).getShowLabelValueFromCell() değerinin val olmasına neden olur).

**Döndürür:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

Belirtilen bir grafiğin veri etiketi hücre değeri gösterim davranışını temsil eder. True hücre değerini gösterir. False gizler. Okunur/yazılır boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowLabelValueFromCell özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowLabelValueFromCell özelliğine tüm veri etiketleri için de uygular (ör. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" tüm DataLabels.get_Item(i).getShowLabelValueFromCell() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

Belirtilen bir grafiğin veri etiketinin veri çağrısı mı yoksa veri etiketi mi olarak gösterileceğini belirler.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowLabelAsDataCallout özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowLabelAsDataCallout özelliğine tüm veri etiketleri için de uygular (ör. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" tüm DataLabels.get_Item(i).getShowLabelAsDataCallout() değerinin val olmasına neden olur).

**Döndürür:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

Belirtilen bir grafiğin veri etiketinin veri çağrısı mı yoksa veri etiketi mi olarak gösterileceğini belirler.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowLabelAsDataCallout özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowLabelAsDataCallout özelliğine tüm veri etiketleri için de uygular (ör. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" tüm DataLabels.get_Item(i).getShowLabelAsDataCallout() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

Bir grafikteki veri etiketleri için kullanılan ayırıcıyı temsil eden Variant'ı ayarlar veya döndürür. Okunur/yazılır String.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki Separator özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri Separator özelliğine tüm veri etiketleri için de uygular (ör. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" tüm DataLabels.get_Item(i).getSeparator() değerinin val olmasına neden olur).

**Döndürür:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

Bir grafikteki veri etiketleri için kullanılan ayırıcıyı temsil eden Variant'ı ayarlar veya döndürür. Okunur/yazılır String.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki Separator özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri Separator özelliğine tüm veri etiketleri için de uygular (ör. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" tüm DataLabels.get_Item(i).getSeparator() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Grafik metin biçimini döndürür. Salt-okunur [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Döndürür:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```

Grafiği döndürür. Salt-okunur [IChart](../../com.aspose.slides/ichart).

**Döndürür:**
[IChart](../../com.aspose.slides/ichart)