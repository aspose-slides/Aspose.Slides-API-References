---
title: IErrorBarsCustomValues
second_title: Aspose.Slides for Java API Reference
description: يحدد قيم أشرطة الأخطاء.
type: docs
url: /ar/com.aspose.slides/ierrorbarscustomvalues/
---```
public interface IErrorBarsCustomValues
```

يحدد قيم أشرطة الأخطاء. يجب أن يُستخدم فقط عندما يكون نوع قيمة أشرطة الأخطاء هو Custom.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getXMinus()](#getXMinus--) | يحدد قيمة شريط الخطأ في الاتجاه السلبي. |
| [getYMinus()](#getYMinus--) | يحدد قيمة شريط الخطأ في الاتجاه السلبي. |
| [getXPlus()](#getXPlus--) | يحدد قيمة شريط الخطأ في الاتجاه الإيجابي. |
| [getYPlus()](#getYPlus--) | يحدد قيمة شريط الخطأ في الاتجاه الإيجابي. |
### getXMinus() {#getXMinus--}
```
public abstract IDoubleChartValue getXMinus()
```


يحدد قيمة شريط الخطأ في الاتجاه السلبي. متاح إذا كان نوع قيمة أشرطة الأخطاء هو Custom وكان ErrorBarsXFormat مسموحًا. في أي حالة أخرى تُعيد هذه الخاصية null. للقراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**القيمة المرجعة:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public abstract IDoubleChartValue getYMinus()
```


يحدد قيمة شريط الخطأ في الاتجاه السلبي. متاح إذا كان نوع قيمة أشرطة الأخطاء هو Custom وكان ErrorBarsYFormat مسموحًا. في أي حالة أخرى تُعيد هذه الخاصية null. للقراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**القيمة المرجعة:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public abstract IDoubleChartValue getXPlus()
```


يحدد قيمة شريط الخطأ في الاتجاه الإيجابي. متاح إذا كان نوع قيمة أشرطة الأخطاء هو Custom وكان ErrorBarsXFormat مسموحًا. في أي حالة أخرى تُعيد هذه الخاصية null. للقراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**القيمة المرجعة:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public abstract IDoubleChartValue getYPlus()
```


يحدد قيمة شريط الخطأ في الاتجاه الإيجابي. متاح إذا كان نوع قيمة أشرطة الأخطاء هو Custom وكان ErrorBarsYFormat مسموحًا. في أي حالة أخرى تُعيد هذه الخاصية null. للقراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**القيمة المرجعة:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)