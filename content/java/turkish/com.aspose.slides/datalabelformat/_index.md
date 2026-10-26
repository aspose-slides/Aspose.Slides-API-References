---
title: DataLabelFormat
second_title: Aspose.Slides for Java API Referansı
description: DataLabel için biçimlendirme seçeneklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/datalabelformat/
---
**Kalıtım:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Uygulanan Tüm Arayüzler:**  
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)  
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

DataLabel için biçimlendirme seçeneklerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Okunur/Yazılır boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Okunur/Yazılır boolean. |
| [getNumberFormat()](#getNumberFormat--) | DataLabels nesnesi için biçim dizesini temsil eder. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | DataLabels nesnesi için biçim dizesini temsil eder. |
| [getFormat()](#getFormat--) | Veri etiketinin biçimini temsil eder. |
| [getPosition()](#getPosition--) | Veri etiketi konumunu temsil eder. |
| [setPosition(int value)](#setPosition-int-) | Veri etiketi konumunu temsil eder. |
| [getShowLegendKey()](#getShowLegendKey--) | Belirtilen bir grafiğin veri etiketi lejand anahtarının görüntülenme davranışını temsil eder. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Belirtilen bir grafiğin veri etiketi lejand anahtarının görüntülenme davranışını temsil eder. |
| [getShowValue()](#getShowValue--) | Belirtilen bir grafiğin veri etiketi yüzde değerinin görüntülenme davranışını temsil eder. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Belirtilen bir grafiğin veri etiketi yüzde değerinin görüntülenme davranışını temsil eder. |
| [getShowCategoryName()](#getShowCategoryName--) | Belirtilen bir grafiğin veri etiketi kategori adının görüntülenme davranışını temsil eder. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Belirtilen bir grafiğin veri etiketi kategori adının görüntülenme davranışını temsil eder. |
| [getShowSeriesName()](#getShowSeriesName--) | Bir grafikteki veri etiketleri için seri adının görüntülenme davranışını belirten Boolean değeri döndürür veya ayarlar. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Bir grafikteki veri etiketleri için seri adının görüntülenme davranışını belirten Boolean değeri döndürür veya ayarlar. |
| [getShowPercentage()](#getShowPercentage--) | Belirtilen bir grafiğin veri etiketi yüzde değerinin görüntülenme davranışını temsil eder. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Belirtilen bir grafiğin veri etiketi yüzde değerinin görüntülenme davranışını temsil eder. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Belirtilen bir grafiğin veri etiketi balon boyutu değerinin görüntülenme davranışını temsil eder. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Belirtilen bir grafiğin veri etiketi balon boyutu değerinin görüntülenme davranışını temsil eder. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Belirtilen bir grafiğin veri etiketi yönlendirme çizgilerinin görüntülenme davranışını temsil eder. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Belirtilen bir grafiğin veri etiketi yönlendirme çizgilerinin görüntülenme davranışını temsil eder. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Belirtilen bir grafiğin veri etiketi hücre değerinin görüntülenme davranışını temsil eder. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Belirtilen bir grafiğin veri etiketi hücre değerinin görüntülenme davranışını temsil eder. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Belirtilen bir grafiğin veri etiketinin veri açıklaması olarak mı yoksa veri etiketi olarak mı gösterileceğini belirler. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Belirtilen bir grafiğin veri etiketinin veri açıklaması olarak mı yoksa veri etiketi olarak mı gösterileceğini belirler. |
| [getSeparator()](#getSeparator--) | Bir grafikteki veri etiketleri için kullanılan ayıracı temsil eden Variant değerini ayarlar veya döndürür. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Bir grafikteki veri etiketleri için kullanılan ayıracı temsil eden Variant değerini ayarlar veya döndürür. |
| [getTextFormat()](#getTextFormat--) | Grafik metin biçimini döndürür. |
| [getChart()](#getChart--) | Grafiği döndürür. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Sürüm. Salt okunur long.

**Döndürür:**  
long
### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Okunur/Yazılır boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik DataLabelCollection koleksiyonundaki yeni veri etiketleri için IsNumberFormatLinkedToSource özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketlerinin IsNumberFormatLinkedToSource özelliğine de atar (ör. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" tüm DataLabels.get_Item(i).isNumberFormatLinkedToSource() değerinin val olmasına neden olur).

**Döndürür:**  
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Okunur/Yazılır boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik DataLabelCollection koleksiyonundaki yeni veri etiketleri için IsNumberFormatLinkedToSource özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketlerinin IsNumberFormatLinkedToSource özelliğine de atar (ör. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" tüm DataLabels.get_Item(i).isNumberFormatLinkedToSource() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

DataLabels nesnesi için biçim dizesini temsil eder. Okunur/Yazılır String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik DataLabelCollection koleksiyonundaki yeni veri etiketleri için NumberFormat özelliğinin varsayılan değerini alır veya ayarlar. Bu özellik bir değerle ayarlandığında, aynı değer NumberFormat özelliği tüm veri etiketleri için de ayarlanır (ör. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" tüm DataLabels.get_Item(i).getNumberFormat() değerinin val olmasına neden olur).

**Döndürür:**  
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

DataLabels nesnesi için biçim dizesini temsil eder. Okunur/Yazılır String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik DataLabelCollection koleksiyonundaki yeni veri etiketleri için NumberFormat özelliğinin varsayılan değerini alır veya ayarlar. Bu özellik bir değerle ayarlandığında, aynı değer NumberFormat özelliği tüm veri etiketleri için de ayarlanır (ör. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" tüm DataLabels.get_Item(i).getNumberFormat() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Veri etiketinin biçimini temsil eder. Salt okunur [IFormat](../../com.aspose.slides/iformat).

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik DataLabelCollection koleksiyonundaki yeni veri etiketleri için varsayılan biçimi temsil eder.

**Döndürür:**  
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Veri etiketinin konumunu temsil eder. Okunur/Yazılır [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik DataLabelCollection koleksiyonundaki yeni veri etiketleri için Position özelliğinin varsayılan değerini alır veya ayarlar. Veri etiketi nesneleri için konumu temsil eder. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri Position özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" tüm DataLabels.get_Item(i).getPosition() değerinin val olmasına neden olur).

**Döndürür:**  
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Veri etiketinin konumunu temsil eder. Okunur/Yazılır [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik DataLabelCollection koleksiyonundaki yeni veri etiketleri için Position özelliğinin varsayılan değerini alır veya ayarlar. Veri etiketi nesneleri için konumu temsil eder. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri Position özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" tüm DataLabels.get_Item(i).getPosition() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

Belirtilen bir grafiğin veri etiketi lejand anahtarının görüntülenme davranışını temsil eder. Veri etiketi lejand anahtarı görünürse True. Okunur/Yazılır boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik DataLabelCollection koleksiyonundaki yeni veri etiketleri için ShowLegendKey özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowLegendKey özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" tüm DataLabels.get_Item(i).getShowLegendKey() değerinin val olmasına neden olur).

**Döndürür:**  
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

Belirtilen bir grafiğin veri etiketi lejand anahtarının görüntülenme davranışını temsil eder. Veri etiketi lejand anahtarı görünürse True. Okunur/Yazılır boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik DataLabelCollection koleksiyonundaki yeni veri etiketleri için ShowLegendKey özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowLegendKey özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" tüm DataLabels.get_Item(i).getShowLegendKey() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

Belirtilen bir grafiğin veri etiketi yüzde değerinin görüntülenme davranışını temsil eder. True ise yüzde değerini gösterir. False ise gizler. Okunur/Yazılır boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik DataLabelCollection koleksiyonundaki yeni veri etiketleri için ShowValue özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowValue özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" tüm DataLabels.get_Item(i).getShowValue() değerinin val olmasına neden olur).

**Döndürür:**  
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

Belirtilen bir grafiğin veri etiketi yüzde değerinin görüntülenme davranışını temsil eder. True ise yüzde değerini gösterir. False ise gizler. Okunur/Yazılır boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik DataLabelCollection koleksiyonundaki yeni veri etiketleri için ShowValue özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowValue özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" tüm DataLabels.get_Item(i).getShowValue() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

Belirtilen bir grafiğin veri etiketi kategori adının görüntülenme davranışını temsil eder. True ise bir grafikteki veri etiketleri için kategori adını gösterir. False ise gizler. Okunur/Yazılır boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik DataLabelCollection koleksiyonundaki yeni veri etiketleri için ShowCategoryName özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowCategoryName özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" tüm DataLabels.get_Item(i).getShowCategoryName() değerinin val olmasına neden olur).

**Döndürür:**  
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

Belirtilen bir grafiğin veri etiketi kategori adının görüntülenme davranışını temsil eder. True ise bir grafikteki veri etiketleri için kategori adını gösterir. False ise gizler. Okunur/Yazılır boolean.

--------------------
If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowCategoryName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowCategoryName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" cause to all DataLabels.get_Item(i).getShowCategoryName() is equal to val).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

Veri etiketlerinin bir çizelgede serinin adını gösterme davranışını belirten bir Boolean döndürür veya ayarlar. Serinin adı gösterilsin ise true, gizlensin ise false. Okunabilir/Yazılabilir boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get_Item(i).getShowSeriesName() is equal to val).

**Döndürür:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

Veri etiketlerinin bir çizelgede serinin adını gösterme davranışını belirten bir Boolean döndürür veya ayarlar. Serinin adı gösterilsin ise true, gizlensin ise false. Okunabilir/Yazılabilir boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get_Item(i).getShowSeriesName() is equal to val).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

Belirli bir çizelgede veri etiketi yüzde değerinin gösterim davranışını temsil eder. Yüzde değeri gösterilsin ise true, gizlensin ise false. Okunabilir/Yazılabilir boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowPercentage property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowPercentage property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get_Item(i).getShowPercentage() is equal to val).

**Döndürür:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

Belirli bir çizelgede veri etiketi yüzde değerinin gösterim davranışını temsil eder. Yüzde değeri gösterilsin ise true, gizlensin ise false. Okunabilir/Yazılabilir boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowPercentage property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowPercentage property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get_Item(i).getShowPercentage() is equal to val).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

Belirli bir çizelgede veri etiketi balon boyutu değerinin gösterim davranışını temsil eder. Balon boyutu değeri gösterilsin ise true, gizlensin ise false. Okunabilir/Yazılabilir boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowBubbleSize property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowBubbleSize property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get_Item(i).getShowBubbleSize() is equal to val).

**Döndürür:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

Belirli bir çizelgede veri etiketi balon boyutu değerinin gösterim davranışını temsil eder. Balon boyutu değeri gösterilsin ise true, gizlensin ise false. Okunabilir/Yazılabilir boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowBubbleSize property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowBubbleSize property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get_Item(i).getShowBubbleSize() is equal to val).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

Belirli bir çizelgede veri etiketi lider hatlarının gösterim davranışını temsil eder. Lider hatları gösterilsin ise true, gizlensin ise false. Okunabilir/Yazılabilir boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLeaderLines property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLeaderLines property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get_Item(i).getShowLeaderLines() is equal to val).

**Döndürür:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

Belirli bir çizelgede veri etiketi lider hatlarının gösterim davranışını temsil eder. Lider hatları gösterilsin ise true, gizlensin ise false. Okunabilir/Yazılabilir boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLeaderLines property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLeaderLines property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get_Item(i).getShowLeaderLines() is equal to val).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

Belirli bir çizelgede veri etiketi hücre değerinin gösterim davranışını temsil eder. Hücre değeri gösterilsin ise true, gizlensin ise false. Okunabilir/Yazılabilir boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelValueFromCell property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelValueFromCell property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get_Item(i).getShowLabelValueFromCell() is equal to val).

**Döndürür:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

Belirli bir çizelgede veri etiketi hücre değerinin gösterim davranışını temsil eder. Hücre değeri gösterilsin ise true, gizlensin ise false. Okunabilir/Yazılabilir boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelValueFromCell property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelValueFromCell property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get_Item(i).getShowLabelValueFromCell() is equal to val).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

Belirli bir çizelgede veri etiketinin veri çağrısı olarak mı yoksa veri etiketi olarak mı gösterileceğini belirler.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelAsDataCallout property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelAsDataCallout property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get_Item(i).getShowLabelAsDataCallout() is equal to val).

**Döndürür:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

Belirli bir çizelgede veri etiketinin veri çağrısı olarak mı yoksa veri etiketi olarak mı gösterileceğini belirler.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelAsDataCallout property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelAsDataCallout property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get_Item(i).getShowLabelAsDataCallout() is equal to val).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

Bir çizelgede veri etiketleri için kullanılan ayırıcıyı temsil eden bir Variant döndürür veya ayarlar. Okunabilir/Yazılabilir String.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Separator property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the Separator property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get_Item(i).getSeparator() is equal to val).

**Döndürür:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

Bir çizelgede veri etiketleri için kullanılan ayırıcıyı temsil eden bir Variant döndürür veya ayarlar. Okunabilir/Yazılabilir String.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Separator property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the Separator property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get_Item(i).getSeparator() is equal to val).
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