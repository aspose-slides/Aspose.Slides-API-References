---
title: IDataLabelFormat
second_title: Aspose.Slides for Android için Java API Referansı
description: DataLabel için biçimlendirme seçeneklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/idatalabelformat/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

DataLabel için biçimlendirme seçeneklerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Okunur/yazılabilir boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Okunur/yazılabilir boolean. |
| [getNumberFormat()](#getNumberFormat--) | DataLabels nesnesi için biçim dizesini temsil eder. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | DataLabels nesnesi için biçim dizesini temsil eder. |
| [getFormat()](#getFormat--) | Veri etiketinin biçimini temsil eder. |
| [getPosition()](#getPosition--) | Veri etiketinin konumunu temsil eder. |
| [setPosition(int value)](#setPosition-int-) | Veri etiketinin konumunu temsil eder. |
| [getShowLegendKey()](#getShowLegendKey--) | Belirtilen grafik için veri etiketi açıklama anahtarı görüntüleme davranışını temsil eder. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Belirtilen grafik için veri etiketi açıklama anahtarı görüntüleme davranışını temsil eder. |
| [getShowValue()](#getShowValue--) | Belirtilen grafik için veri etiketi yüzde değeri görüntüleme davranışını temsil eder. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Belirtilen grafik için veri etiketi yüzde değeri görüntüleme davranışını temsil eder. |
| [getShowCategoryName()](#getShowCategoryName--) | Belirtilen grafik için veri etiketi kategori adı görüntüleme davranışını temsil eder. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Belirtilen grafik için veri etiketi kategori adı görüntüleme davranışını temsil eder. |
| [getShowSeriesName()](#getShowSeriesName--) | Bir Boolean değerini alır veya ayarlar; bir grafikteki veri etiketleri için seri adı görüntüleme davranışını belirler. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Bir Boolean değerini alır veya ayarlar; bir grafikteki veri etiketleri için seri adı görüntüleme davranışını belirler. |
| [getShowPercentage()](#getShowPercentage--) | Belirtilen grafik için veri etiketi yüzde değeri görüntüleme davranışını temsil eder. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Belirtilen grafik için veri etiketi yüzde değeri görüntüleme davranışını temsil eder. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Belirtilen grafik için veri etiketi balon boyutu değeri görüntüleme davranışını temsil eder. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Belirtilen grafik için veri etiketi balon boyutu değeri görüntüleme davranışını temsil eder. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Belirtilen grafik için veri etiketi lider çizgileri görüntüleme davranışını temsil eder. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Belirtilen grafik için veri etiketi lider çizgileri görüntüleme davranışını temsil eder. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Belirtilen grafiğin veri etiketinin veri çağrısı mı yoksa veri etiketi mi olarak görüntüleneceğini belirler. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Belirtilen grafiğin veri etiketinin veri çağrısı mı yoksa veri etiketi mi olarak görüntüleneceğini belirler. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Belirtilen grafik için veri etiketi hücre değeri görüntüleme davranışını temsil eder. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Belirtilen grafik için veri etiketi hücre değeri görüntüleme davranışını temsil eder. |
| [getSeparator()](#getSeparator--) | Bir grafikteki veri etiketleri için kullanılan ayırıcıyı temsil eden Variant değerini ayarlar veya döndürür. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Bir grafikteki veri etiketleri için kullanılan ayırıcıyı temsil eden Variant değerini ayarlar veya döndürür. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Okunur/yazılabilir boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için IsNumberFormatLinkedToSource özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketleri için IsNumberFormatLinkedToSource özelliğine de atar (ör. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" tüm DataLabels.get_Item(i).isNumberFormatLinkedToSource() değerinin val olmasına neden olur).

**Dönüş:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Okunur/yazılabilir boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için IsNumberFormatLinkedToSource özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketleri için IsNumberFormatLinkedToSource özelliğine de atar (ör. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" tüm DataLabels.get_Item(i).isNumberFormatLinkedToSource() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

DataLabels nesnesi için biçim dizesini temsil eder. Okunur/yazılabilir String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için NumberFormat özelliğinin varsayılan değerini alır veya ayarlar. Bu özellik bir değerle ayarlandığında, aynı değer NumberFormat özelliği tüm veri etiketleri için de ayarlanır (ör. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" tüm DataLabels.get_Item(i).getNumberFormat() değerinin val olmasına neden olur).

**Dönüş:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

DataLabels nesnesi için biçim dizesini temsil eder. Okunur/yazılabilir String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için NumberFormat özelliğinin varsayılan değerini alır veya ayarlar. Bu özellik bir değerle ayarlandığında, aynı değer NumberFormat özelliği tüm veri etiketleri için de ayarlanır (ör. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" tüm DataLabels.get_Item(i).getNumberFormat() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Veri etiketinin biçimini temsil eder. Salt okunur [IFormat](../../com.aspose.slides/iformat).

--------------------

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için varsayılan biçimi temsil eder.

**Dönüş:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Veri etiketinin konumunu temsil eder. Okunur/yazılabilir [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için Position özelliğinin varsayılan değerini alır veya ayarlar. DataLabel nesneleri için konumu temsil eder. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri Position özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" tüm DataLabels.get_Item(i).getPosition() değerinin val olmasına neden olur).

**Dönüş:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Veri etiketinin konumunu temsil eder. Okunur/yazılabilir [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için Position özelliğinin varsayılan değerini alır veya ayarlar. DataLabel nesneleri için konumu temsil eder. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri Position özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" tüm DataLabels.get_Item(i).getPosition() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

Belirtilen grafik için veri etiketi açıklama anahtarı görüntüleme davranışını temsil eder. Anahtar görünürse true. Okunur/yazılabilir boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için ShowLegendKey özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowLegendKey özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" tüm DataLabels.get_Item(i).getShowLegendKey() değerinin val olmasına neden olur).

**Dönüş:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

Belirtilen grafik için veri etiketi açıklama anahtarı görüntüleme davranışını temsil eder. Anahtar görünürse true. Okunur/yazılabilir boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için ShowLegendKey özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowLegendKey özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" tüm DataLabels.get_Item(i).getShowLegendKey() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

Belirtilen grafik için veri etiketi yüzde değeri görüntüleme davranışını temsil eder. Değer görünürse true, gizlemek için false. Okunur/yazılabilir boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için ShowValue özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowValue özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" tüm DataLabels.get_Item(i).getShowValue() değerinin val olmasına neden olur).

**Dönüş:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

Belirtilen grafik için veri etiketi yüzde değeri görüntüleme davranışını temsil eder. Değer görünürse true, gizlemek için false. Okunur/yazılabilir boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için ShowValue özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowValue özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" tüm DataLabels.get_Item(i).getShowValue() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

Belirtilen grafik için veri etiketi kategori adı görüntüleme davranışını temsil eder. Kategori adı görünürse true, gizlemek için false. Okunur/yazılabilir boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için ShowCategoryName özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowCategoryName özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" tüm DataLabels.get_Item(i).getShowCategoryName() değerinin val olmasına neden olur).

**Dönüş:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

Belirtilen grafik için veri etiketi kategori adı görüntüleme davranışını temsil eder. Kategori adı görünürse true, gizlemek için false. Okunur/yazılabilir boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için ShowCategoryName özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowCategoryName özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" tüm DataLabels.get_Item(i).getShowCategoryName() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

Seri adının bir grafikteki veri etiketlerinde gösterilip gösterilmeyeceğini belirten Boolean değerini alır veya ayarlar. Gösterim için true, gizleme için false. Okunur/yazılabilir boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için ShowSeriesName özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowSeriesName özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" tüm DataLabels.get_Item(i).getShowSeriesName() değerinin val olmasına neden olur).

**Dönüş:**
boolean

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

Seri adının bir grafikteki veri etiketlerinde gösterilip gösterilmeyeceğini belirten Boolean değerini alır veya ayarlar. Gösterim için true, gizleme için false. Okunur/yazılabilir boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için ShowSeriesName özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowSeriesName özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" tüm DataLabels.get_Item(i).getShowSeriesName() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

Belirtilen grafik için veri etiketi yüzde değeri görüntüleme davranışını temsil eder. Değer görünürse true, gizlemek için false. Okunur/yazılabilir boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için ShowPercentage özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowPercentage özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" tüm DataLabels.get_Item(i).getShowPercentage() değerinin val olmasına neden olur).

**Dönüş:**
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

Belirtilen grafik için veri etiketi yüzde değeri görüntüleme davranışını temsil eder. Değer görünürse true, gizlemek için false. Okunur/yazılabilir boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için ShowPercentage özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowPercentage özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" tüm DataLabels.get_Item(i).getShowPercentage() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

Belirtilen grafik için veri etiketi balon boyutu değeri görüntüleme davranışını temsil eder. Değer görünürse true, gizlemek için false. Okunur/yazılabilir boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için ShowBubbleSize özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowBubbleSize özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" tüm DataLabels.get_Item(i).getShowBubbleSize() değerinin val olmasına neden olur).

**Dönüş:**
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

Belirtilen grafik için veri etiketi balon boyutu değeri görüntüleme davranışını temsil eder. Değer görünürse true, gizlemek için false. Okunur/yazılabilir boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için ShowBubbleSize özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowBubbleSize özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" tüm DataLabels.get_Item(i).getShowBubbleSize() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

Belirtilen grafik için veri etiketi lider çizgileri görüntüleme davranışını temsil eder. Çizgiler görünürse true, gizlemek için false. Okunur/yazılabilir boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için ShowLeaderLines özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowLeaderLines özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" tüm DataLabels.get_Item(i).getShowLeaderLines() değerinin val olmasına neden olur).

**Dönüş:**
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

Belirtilen grafik için veri etiketi lider çizgileri görüntüleme davranışını temsil eder. Çizgiler görünürse true, gizlemek için false. Okunur/yazılabilir boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için ShowLeaderLines özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowLeaderLines özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" tüm DataLabels.get_Item(i).getShowLeaderLines() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

Belirtilen grafik için veri etiketinin veri çağrısı mı yoksa veri etiketi mi olarak görüntüleneceğini belirler.

--------------------

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için ShowLabelAsDataCallout özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowLabelAsDataCallout özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" tüm DataLabels.get_Item(i).getShowLabelAsDataCallout() değerinin val olmasına neden olur).

**Dönüş:**
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

Belirtilen grafik için veri etiketinin veri çağrısı mı yoksa veri etiketi mi olarak görüntüleneceğini belirler.

--------------------

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için ShowLabelAsDataCallout özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowLabelAsDataCallout özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" tüm DataLabels.get_Item(i).getShowLabelAsDataCallout() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

Belirtilen grafik için veri etiketi hücre değeri görüntüleme davranışını temsil eder. Hücre değeri görünürse true, gizlemek için false. Okunur/yazılabilir boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için ShowLabelValueFromCell özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowLabelValueFromCell özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" tüm DataLabels.get_Item(i).getShowLabelValueFromCell() değerinin val olmasına neden olur).

**Dönüş:**
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

Belirtilen grafik için veri etiketi hücre değeri görüntüleme davranışını temsil eder. Hücre değeri görünürse true, gizlemek için false. Okunur/yazılabilir boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için ShowLabelValueFromCell özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri ShowLabelValueFromCell özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" tüm DataLabels.get_Item(i).getShowLabelValueFromCell() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

Bir grafikteki veri etiketleri için kullanılan ayırıcıyı temsil eden Variant değerini ayarlar veya döndürür. Okunur/yazılabilir String.

--------------------

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için Separator özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri Separator özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" tüm DataLabels.get_Item(i).getSeparator() değerinin val olmasına neden olur).

**Dönüş:**
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

Bir grafikteki veri etiketleri için kullanılan ayırıcıyı temsil eden Variant değerini ayarlar veya döndürür. Okunur/yazılabilir String.

--------------------

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için Separator özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri Separator özelliği tüm veri etiketleri için de ayarlar (ör. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" tüm DataLabels.get_Item(i).getSeparator() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |