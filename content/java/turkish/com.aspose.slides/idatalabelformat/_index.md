---
title: IDataLabelFormat
second_title: Aspose.Slides for Java API Referansı
description: DataLabel için biçimlendirme seçeneklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/idatalabelformat/
---
**Tüm Uygulanan Arayüzler:**
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
| [getNumberFormat()](#getNumberFormat--) | DataLabels nesnesinin biçim dizesini temsil eder. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | DataLabels nesnesinin biçim dizesini temsil eder. |
| [getFormat()](#getFormat--) | Veri etiketinin biçimini temsil eder. |
| [getPosition()](#getPosition--) | Veri etiketinin konumunu temsil eder. |
| [setPosition(int value)](#setPosition-int-) | Veri etiketinin konumunu temsil eder. |
| [getShowLegendKey()](#getShowLegendKey--) | Belirtilen bir grafiğin veri etiketi lejand anahtarı gösterim davranışını temsil eder. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Belirtilen bir grafiğin veri etiketi lejand anahtarı gösterim davranışını temsil eder. |
| [getShowValue()](#getShowValue--) | Belirtilen bir grafiğin veri etiketi yüzde değer gösterim davranışını temsil eder. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Belirtilen bir grafiğin veri etiketi yüzde değer gösterim davranışını temsil eder. |
| [getShowCategoryName()](#getShowCategoryName--) | Belirtilen bir grafiğin veri etiketi kategori adı gösterim davranışını temsil eder. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Belirtilen bir grafiğin veri etiketi kategori adı gösterim davranışını temsil eder. |
| [getShowSeriesName()](#getShowSeriesName--) | Bir Boolean döndürür veya ayarlar; bir grafikteki veri etiketlerinin seri adı gösterim davranışını belirtir. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Bir Boolean döndürür veya ayarlar; bir grafikteki veri etiketlerinin seri adı gösterim davranışını belirtir. |
| [getShowPercentage()](#getShowPercentage--) | Belirtilen bir grafiğin veri etiketi yüzde değer gösterim davranışını temsil eder. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Belirtilen bir grafiğin veri etiketi yüzde değer gösterim davranışını temsil eder. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Belirtilen bir grafiğin veri etiketi baloncuk boyutu değer gösterim davranışını temsil eder. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Belirtilen bir grafiğin veri etiketi baloncuk boyutu değer gösterim davranışını temsil eder. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Belirtilen bir grafiğin veri etiketi lider çizgileri gösterim davranışını temsil eder. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Belirtilen bir grafiğin veri etiketi lider çizgileri gösterim davranışını temsil eder. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Belirtilen bir grafiğin veri etiketinin veri çağrısı olarak mı yoksa veri etiketi olarak mı görüntüleneceğini belirler. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Belirtilen bir grafiğin veri etiketinin veri çağrısı olarak mı yoksa veri etiketi olarak mı görüntüleneceğini belirler. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Belirtilen bir grafiğin veri etiketi hücre değeri gösterim davranışını temsil eder. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Belirtilen bir grafiğin veri etiketi hücre değeri gösterim davranışını temsil eder. |
| [getSeparator()](#getSeparator--) | Bir grafikteki veri etiketleri için kullanılan ayırıcıyı temsil eden Variant'ı ayarlar veya döndürür. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Bir grafikteki veri etiketleri için kullanılan ayırıcıyı temsil eden Variant'ı ayarlar veya döndürür. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Okunur/yazılabilir boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki IsNumberFormatLinkedToSource özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlarsanız, aynı değer DataLabelCollection koleksiyonundaki tüm veri etiketleri için IsNumberFormatLinkedToSource özelliğine de uygulanır (örnek: "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" tüm DataLabels.get_Item(i).isNumberFormatLinkedToSource() değerinin val olmasına neden olur).

**Döndürür:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Okunur/yazılabilir boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki IsNumberFormatLinkedToSource özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlarsanız, aynı değer DataLabelCollection koleksiyonundaki tüm veri etiketleri için IsNumberFormatLinkedToSource özelliğine de uygulanır (örnek: "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" tüm DataLabels.get_Item(i).isNumberFormatLinkedToSource() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tip | Açıklama |
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
```

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki NumberFormat özelliğinin varsayılan değerini alır veya ayarlar. Bu özellik bir değerle ayarlanırsa, aynı değer DataLabelCollection koleksiyonundaki tüm veri etiketleri için NumberFormat özelliğine de uygulanır (örnek: "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" tüm DataLabels.get_Item(i).getNumberFormat() değerinin val olmasına neden olur).

**Döndürür:**
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
```

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki NumberFormat özelliğinin varsayılan değerini alır veya ayarlar. Bu özellik bir değerle ayarlanırsa, aynı değer DataLabelCollection koleksiyonundaki tüm veri etiketleri için NumberFormat özelliğine de uygulanır (örnek: "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" tüm DataLabels.get_Item(i).getNumberFormat() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Veri etiketinin biçimini temsil eder. Yalnızca okunabilir [IFormat](../../com.aspose.slides/iformat).

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki varsayılan biçimi temsil eder.

**Döndürür:**
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Veri etiketinin konumunu temsil eder. Okunur/yazılabilir [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki Position özelliğinin varsayılan değerini alır veya ayarlar. Position, DataLabel nesnelerinin konumunu temsil eder. Bu özelliği bir değerle ayarlarsanız, aynı değer DataLabelCollection koleksiyonundaki tüm veri etiketleri için Position özelliğine de uygulanır (örnek: "DataLabels.getDefaultDataLabelFormat().setPosition(val)" tüm DataLabels.get_Item(i).getPosition() değerinin val olmasına neden olur).

**Döndürür:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Veri etiketinin konumunu temsil eder. Okunur/yazılabilir [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki Position özelliğinin varsayılan değerini alır veya ayarlar. Position, DataLabel nesnelerinin konumunu temsil eder. Bu özelliği bir değerle ayarlarsanız, aynı değer DataLabelCollection koleksiyonundaki tüm veri etiketleri için Position özelliğine de uygulanır (örnek: "DataLabels.getDefaultDataLabelFormat().setPosition(val)" tüm DataLabels.get_Item(i).getPosition() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

Belirtilen bir grafiğin veri etiketi lejand anahtarı gösterim davranışını temsil eder. Veri etiketi lejand anahtarı görünüyorsa True. Okunur/yazılabilir boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowLegendKey özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlarsanız, aynı değer DataLabelCollection koleksiyonundaki tüm veri etiketleri için ShowLegendKey özelliğine de uygulanır (örnek: "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" tüm DataLabels.get_Item(i).getShowLegendKey() değerinin val olmasına neden olur).

**Döndürür:**
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

Belirtilen bir grafiğin veri etiketi lejand anahtarı gösterim davranışını temsil eder. Veri etiketi lejand anahtarı görünüyorsa True. Okunur/yazılabilir boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowLegendKey özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlarsanız, aynı değer DataLabelCollection koleksiyonundaki tüm veri etiketleri için ShowLegendKey özelliğine de uygulanır (örnek: "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" tüm DataLabels.get_Item(i).getShowLegendKey() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

Belirtilen bir grafiğin veri etiketi yüzde değer gösterim davranışını temsil eder. True yüzde değerini gösterir. False gizlemek için. Okunur/yazılabilir boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowValue özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlarsanız, aynı değer DataLabelCollection koleksiyonundaki tüm veri etiketleri için ShowValue özelliğine de uygulanır (örnek: "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" tüm DataLabels.get_Item(i).getShowValue() değerinin val olmasına neden olur).

**Döndürür:**
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

Belirtilen bir grafiğin veri etiketi yüzde değer gösterim davranışını temsil eder. True yüzde değerini gösterir. False gizlemek için. Okunur/yazılabilir boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowValue özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlarsanız, aynı değer DataLabelCollection koleksiyonundaki tüm veri etiketleri için ShowValue özelliğine de uygulanır (örnek: "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" tüm DataLabels.get_Item(i).getShowValue() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

Belirtilen bir grafiğin veri etiketi kategori adı gösterim davranışını temsil eder. True grafik üzerindeki veri etiketleri için kategori adını gösterir. False gizlemek için. Okunur/yazılabilir boolean.

--------------------

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowCategoryName özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlarsanız, aynı değer DataLabelCollection koleksiyonundaki tüm veri etiketleri için ShowCategoryName özelliğine de uygulanır (örnek: "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" tüm DataLabels.get_Item(i).getShowCategoryName() değerinin val olmasına neden olur).

**Döndürür:**
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

Belirtilen bir grafiğin veri etiketi kategori adı gösterim davranışını temsil eder. True grafik üzerindeki veri etiketleri için kategori adını gösterir. False gizlemek için. Okunur/yazılabilir boolean.

--------------------
Bu DataLabelFormat nesnesinin üst öğesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowCategoryName özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketlerinin ShowCategoryName özelliğine de atar (örn. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" tüm DataLabels.get_Item(i).getShowCategoryName() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

Belirtilen bir grafiğin veri etiketlerinde seri adının görüntülenme davranışını belirten Boolean değerini alır veya ayarlar. True seri adını gösterir. False gizler. Okuma/yazma boolean.

--------------------

Bu DataLabelFormat nesnesinin üst öğesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowSeriesName özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketlerinin ShowSeriesName özelliğine de atar (örn. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" tüm DataLabels.get_Item(i).getShowSeriesName() değerinin val olmasına neden olur).

**Döndürür:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

Belirtilen bir grafiğin veri etiketlerinde seri adının görüntülenme davranışını belirten Boolean değerini alır veya ayarlar. True seri adını gösterir. False gizler. Okuma/yazma boolean.

--------------------

Bu DataLabelFormat nesnesinin üst öğesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowSeriesName özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketlerinin ShowSeriesName özelliğine de atar (örn. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" tüm DataLabels.get_Item(i).getShowSeriesName() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

Belirtilen bir grafiğin veri etiketi yüzde değerinin görüntülenme davranışını temsil eder. True yüzde değerini gösterir. False gizler. Okuma/yazma boolean.

--------------------

Bu DataLabelFormat nesnesinin üst öğesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowPercentage özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketlerinin ShowPercentage özelliğine de atar (örn. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" tüm DataLabels.get_Item(i).getShowPercentage() değerinin val olmasına neden olur).

**Döndürür:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

Belirtilen bir grafiğin veri etiketi yüzde değerinin görüntülenme davranışını temsil eder. True yüzde değerini gösterir. False gizler. Okuma/yazma boolean.

--------------------

Bu DataLabelFormat nesnesinin üst öğesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowPercentage özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketlerinin ShowPercentage özelliğine de atar (örn. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" tüm DataLabels.get_Item(i).getShowPercentage() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

Belirtilen bir grafiğin veri etiketi balon boyutu değerinin görüntülenme davranışını temsil eder. True balon boyutu değerini gösterir. False gizler. Okuma/yazma boolean.

--------------------

Bu DataLabelFormat nesnesinin üst öğesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowBubbleSize özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketlerinin ShowBubbleSize özelliğine de atar (örn. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" tüm DataLabels.get_Item(i).getShowBubbleSize() değerinin val olmasına neden olur).

**Döndürür:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

Belirtilen bir grafiğin veri etiketi balon boyutu değerinin görüntülenme davranışını temsil eder. True balon boyutu değerini gösterir. False gizler. Okuma/yazma boolean.

--------------------

Bu DataLabelFormat nesnesinin üst öğesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowBubbleSize özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketlerinin ShowBubbleSize özelliğine de atar (örn. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" tüm DataLabels.get_Item(i).getShowBubbleSize() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

Belirtilen bir grafiğin veri etiketi kılavuz çizgilerinin görüntülenme davranışını temsil eder. True kılavuz çizgilerini gösterir. False gizler. Okuma/yazma boolean.

--------------------

Bu DataLabelFormat nesnesinin üst öğesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowLeaderLines özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketlerinin ShowLeaderLines özelliğine de atar (örn. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" tüm DataLabels.get_Item(i).getShowLeaderLines() değerinin val olmasına neden olur).

**Döndürür:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

Belirtilen bir grafiğin veri etiketi kılavuz çizgilerinin görüntülenme davranışını temsil eder. True kılavuz çizgilerini gösterir. False gizler. Okuma/yazma boolean.

--------------------

Bu DataLabelFormat nesnesinin üst öğesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowLeaderLines özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketlerinin ShowLeaderLines özelliğine de atar (örn. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" tüm DataLabels.get_Item(i).getShowLeaderLines() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

Belirtilen bir grafiğin veri etiketinin veri çağrısı olarak mı yoksa veri etiketi olarak mı görüntüleneceğini belirler.

--------------------

Bu DataLabelFormat nesnesinin üst öğesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowLabelAsDataCallout özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketlerinin ShowLabelAsDataCallout özelliğine de atar (örn. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" tüm DataLabels.get_Item(i).getShowLabelAsDataCallout() değerinin val olmasına neden olur).

**Döndürür:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

Belirtilen bir grafiğin veri etiketinin veri çağrısı olarak mı yoksa veri etiketi olarak mı görüntüleneceğini belirler.

--------------------

Bu DataLabelFormat nesnesinin üst öğesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowLabelAsDataCallout özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketlerinin ShowLabelAsDataCallout özelliğine de atar (örn. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" tüm DataLabels.get_Item(i).getShowLabelAsDataCallout() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

Belirtilen bir grafiğin veri etiketi hücre değerinin görüntülenme davranışını temsil eder. True hücre değerini gösterir. False gizler. Okuma/yazma boolean.

--------------------

Bu DataLabelFormat nesnesinin üst öğesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowLabelValueFromCell özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketlerinin ShowLabelValueFromCell özelliğine de atar (örn. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" tüm DataLabels.get_Item(i).getShowLabelValueFromCell() değerinin val olmasına neden olur).

**Döndürür:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

Belirtilen bir grafiğin veri etiketi hücre değerinin görüntülenme davranışını temsil eder. True hücre değerini gösterir. False gizler. Okuma/yazma boolean.

--------------------

Bu DataLabelFormat nesnesinin üst öğesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowLabelValueFromCell özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketlerinin ShowLabelValueFromCell özelliğine de atar (örn. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" tüm DataLabels.get_Item(i).getShowLabelValueFromCell() değerinin val olmasına neden olur).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

Bir grafikteki veri etiketleri için kullanılan ayırıcıyı temsil eden bir Variant döndürür veya ayarlar. Okuma/yazma String.

--------------------

Bu DataLabelFormat nesnesinin üst öğesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki Separator özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketlerinin Separator özelliğine de atar (örn. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" tüm DataLabels.get_Item(i).getSeparator() değerinin val olmasına neden olur).

**Döndürür:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

Bir grafikteki veri etiketleri için kullanılan ayırıcıyı temsil eden bir Variant döndürür veya ayarlar. Okuma/yazma String.

--------------------

Bu DataLabelFormat nesnesinin üst öğesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki Separator özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketlerinin Separator özelliğine de atar (örn. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" tüm DataLabels.get_Item(i).getSeparator() değerinin val olmasına neden olur).
**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |