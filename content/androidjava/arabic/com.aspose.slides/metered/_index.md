---
title: Metered
second_title: Aspose.Slides لأجهزة Android عبر مرجع API Java
description: يوفر طرقًا لتعيين مفتاح القياس.
type: docs
url: /ar/com.aspose.slides/metered/
---
**الوراثة:**  
java.lang.Object  
```
public class Metered
```

يوفر طرقًا لتعيين مفتاح القياس.

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Metered()](#Metered--) | ينشئ مثيلًا جديدًا لهذه الفئة. |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | يضبط مفتاح القياس العام والخاص. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | يحصل على حجم ملف الاستهلاك |
| [getConsumptionCredit()](#getConsumptionCredit--) | يحصل على رصيد الاستهلاك |
| [isMeteredLicensed()](#isMeteredLicensed--) | التحقق مما إذا كان القياس مرخصًا |

### Metered() {#Metered--}
```
public Metered()
```

ينشئ مثيلًا جديدًا لهذه الفئة.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```

يضبط مفتاح القياس العام والخاص. إذا قمت بشراء ترخيص مدفوع بالمقياس، عند بدء التطبيق يجب استدعاء هذه الواجهة البرمجية، عادةً هذا يكفي. ومع ذلك، إذا فشل دائمًا تحميل بيانات الاستهلاك وتجاوز 24 ساعة، سيتم ضبط الترخيص إلى حالة التقييم؛ لتجنب ذلك، يجب عليك فحص حالة الترخيص بانتظام، إذا كانت في حالة التقييم، استدعِ هذه الواجهة البرمجية مرة أخرى.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| publicKey | java.lang.String | المفتاح العام |
| privateKey | java.lang.String | المفتاح الخاص |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```

يحصل على حجم ملف الاستهلاك

**الإرجاع:**
double

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```

يحصل على رصيد الاستهلاك

**الإرجاع:**
double - كمية الاستهلاك

### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```

التحقق مما إذا كان القياس مرخصًا

**الإرجاع:**
boolean - صحيح أو خطأ