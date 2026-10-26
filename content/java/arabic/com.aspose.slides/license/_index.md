---
title: License
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides for Java
description: يوفر طرقًا لترخيص المكوّن.
type: docs
url: /ar/com.aspose.slides/license/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)  
```
public final class License implements ILicense
```

يوفر طرقًا لترخيص المكوّن.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## Constructors

| المنشئ | الوصف |
| --- | --- |
| [License()](#License--) | ينشئ مثالًا جديدًا لهذه الفئة. |
## Methods

| الطريقة | الوصف |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | ترخص المكوّن. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | ترخص المكوّن. |
| [getVersion()](#getVersion--) | يعيد إصدار Aspose.Slides لـ Java. |
| [resetLicense()](#resetLicense--) | إعادة ضبط الترخيص. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```


ينشئ مثالًا جديدًا لهذه الفئة.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```


### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```


ترخص المكوّن.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | تدفق يحتوي على الترخيص. استخدم null للانتقال إلى وضع التقييم. |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```


ترخص المكوّن.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| namePath | java.lang.String | يمكن أن يكون اسم ملف كامل أو مختصر أو اسم مورد مضمّن. استخدم سلسلة فارغة للانتقال إلى وضع التقييم. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```


يعيد إصدار Aspose.Slides لـ Java.

**الإرجاع:**  
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```


إعادة ضبط الترخيص. استخدم هذه الطريقة لإعادة ضبط الترخيص في المكوّن.

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```


تحقق مما إذا كان الترخيص مُطبّقًا على المكوّن

**الإرجاع:**  
boolean