---
title: IDataLabel
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Bir serinin etiketlerini temsil eder.
type: docs
url: /tr/com.aspose.slides/idatalabel/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Bir seri etiketlerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isVisible()](#isVisible--) | False, veri etiketinin görünür olmadığı anlamına gelir (ve bu yüzden tüm Show*-bayrakları (ShowValue, ...) false olur). |
| [hide()](#hide--) | Tüm Show*-bayrakları (ShowValue, ...) false duruma ayarlayarak veri etiketini gizleyin. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Veri etiketinin biçimini döndürür. |
| [getValueFromCell()](#getValueFromCell--) | Çalışma kitabı veri hücresini alır veya ayarlar. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Çalışma kitabı veri hücresini alır veya ayarlar. |
| [getActualLabelText()](#getActualLabelText--) | DataLabelFormat ayarlarına veya TextFrameForOverriding.Text değerine göre gerçek etiket metnini döndürür. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


False, veri etiketinin görünür olmadığı anlamına gelir (ve bu yüzden tüm Show*-bayrakları (ShowValue, ...) false olur). Salt okunur boolean.

--------------------

Veri etiketi görünürse, Hide() yöntemiyle gizleyebilirsiniz. Ancak veri etiketi görünür değilse (IsVisible false ise) Show*-bayraklarını (ShowValue, ...) true durumuna ayarlayarak veri etiketini görünür yapabilirsiniz.

**Döndürür:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


Tüm Show*-bayrakları (ShowValue, ...) false durumuna ayarlayarak veri etiketini gizleyin. Bu işlemden sonra IsVisible false olacaktır.

--------------------

Veri etiketi görünür değilse (IsVisible false ise) Show*-bayraklarını (ShowValue, ...) true durumuna ayarlayarak veri etiketini görünür yapabilirsiniz.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```


Veri etiketinin biçimini döndürür. Salt okunur [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Döndürür:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```


Çalışma kitabı veri hücresini alır veya ayarlar. IDataLabelFormat.ShowLabelValueFromCell özelliği true ise uygulanır.

**Döndürür:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```


Çalışma kitabı veri hücresini alır veya ayarlar. IDataLabelFormat.ShowLabelValueFromCell özelliği true ise uygulanır.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```


DataLabelFormat ayarlarına veya TextFrameForOverriding.Text değerine göre gerçek etiket metnini döndürür.

**Döndürür:**
java.lang.String - Gerçek etiket metni String