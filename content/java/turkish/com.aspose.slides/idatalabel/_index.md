---
title: IDataLabel
second_title: Aspose.Slides Java API Referansı
description: Bir seri etiketini temsil eder.
type: docs
url: /tr/com.aspose.slides/idatalabel/
---
**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Bir seri etiketini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isVisible()](#isVisible--) | False, veri etiketinin görünür olmadığı anlamına gelir (ve bu nedenle tüm Show*-flags (ShowValue, ...) false olur). |
| [hide()](#hide--) | Tüm Show*-flags (ShowValue, ...) false durumuna ayarlayarak veri etiketini gizleyin. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Veri etiketinin biçimini döndürür. |
| [getValueFromCell()](#getValueFromCell--) | Çalışma kitabı veri hücresini alır veya ayarlar. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Çalışma kitabı veri hücresini alır veya ayarlar. |
| [getActualLabelText()](#getActualLabelText--) | DataLabelFormat ayarlarına veya TextFrameForOverriding.Text değerine göre gerçek etiket metnini döndürür. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False, veri etiketinin görünür olmadığı anlamına gelir (ve bu nedenle tüm Show*-flags (ShowValue, ...) false olur). Salt-okunur boolean.

--------------------

Veri etiketi görünürse, Hide() yöntemiyle onu gizleyebilirsiniz. Ancak veri etiketi görünür değilse (IsVisible false ise) Show*-flags (ShowValue, ...) değerlerini true durumuna ayarlayarak veri etiketini görünür yapabilirsiniz.

**Döndürür:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Tüm Show*-flags (ShowValue, ...) false durumuna ayarlayarak veri etiketini gizleyin. Bu işlemden sonra IsVisible false olur.

--------------------

Veri etiketi görünür değilse (IsVisible false ise) Show*-flags (ShowValue, ...) değerlerini true durumuna ayarlayarak veri etiketini görünür yapabilirsiniz.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Veri etiketinin biçimini döndürür. Salt-okunur [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Döndürür:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Çalışma kitabı veri hücresini alır veya ayarlar. IDataLabelFormat.ShowLabelValueFromCell özelliği true olduğunda uygulanır.

**Döndürür:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Çalışma kitabı veri hücresini alır veya ayarlar. IDataLabelFormat.ShowLabelValueFromCell özelliği true olduğunda uygulanır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

DataLabelFormat ayarlarına veya TextFrameForOverriding.Text değerine göre gerçek etiket metnini döndürür.

**Döndürür:**
java.lang.String - Gerçek etiket metni String