---
title: Metered
second_title: Aspose.Slides لـ Java مرجع API
description: يوفر طرقًا لتعيين المفتاح المقيس.
type: docs
url: /ar/com.aspose.slides/metered/
---
**الوراثة:**
java.lang.Object
```
public class Metered
```

يوفر طرقًا لتعيين المفتاح المقيس.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Metered()](#Metered--) | يقوم بإنشاء مثيل جديد لهذه الفئة. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | يحدد المفتاح العام والخاص المقيس. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | يحصل على حجم ملف الاستهلاك |
| [getConsumptionCredit()](#getConsumptionCredit--) | يحصل على رصيد الاستهلاك |
| [isMeteredLicensed()](#isMeteredLicensed--) | يتحقق ما إذا كان المقيس مرخصًا |
### Metered() {#Metered--}
```
public Metered()
```

يقوم بإنشاء مثيل جديد لهذه الفئة.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```

يحدد المفتاح العام والخاص المقيس. إذا قمت بشراء ترخيص مقيس، عند بدء التطبيق، يجب استدعاء هذا API، عادةً، هذا يكفي. ومع ذلك، إذا فشل دائمًا تحميل بيانات الاستهلاك وتجاوز 24 ساعة، سيتم ضبط الترخيص إلى حالة تقييم، لتجنب هذه الحالة، يجب عليك فحص حالة الترخيص بانتظام، إذا كانت حالة تقييم، استدعِ هذا API مرة أخرى.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| publicKey | java.lang.String | المفتاح العام |
| privateKey | java.lang.String | المفتاح الخاص |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```

يحصل على حجم ملف الاستهلاك

**القيم المرتجعة:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```

يحصل على رصيد الاستهلاك

**القيم المرتجعة:**
double - كمية الاستهلاك
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```

يتحقق ما إذا كان المقيس مرخصًا

**القيم المرتجعة:**
boolean - صحيح أو خطأ