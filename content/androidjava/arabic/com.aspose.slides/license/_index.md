---
title: License
second_title: مرجع API Aspose.Slides لنظام Android عبر Java
description: يوفر طرقًا لترخيص المكوّن.
type: docs
url: /ar/com.aspose.slides/license/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُنفذة:**
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
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [License()](#License--) | يُهيئ مثالًا جديدًا من هذه الفئة. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | يرخص المكوّن. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | يرخص المكوّن. |
| [getVersion()](#getVersion--) | يرجع إصدار Aspose.Slides لنظام Android عبر Java. |
| [resetLicense()](#resetLicense--) | إعادة تعيين الترخيص. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```


يُهيئ مثالًا جديدًا من هذه الفئة.

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


يرخص المكوّن.

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
| stream | java.io.InputStream | تيار يحتوي على الترخيص. استخدم null للتبديل إلى وضع التقييم. |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```


يرخص المكوّن.

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
| namePath | java.lang.String | يمكن أن يكون اسم ملف كامل أو قصير أو اسم مورد مضمّن. استخدم سلسلة فارغة للتبديل إلى وضع التقييم. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```


يرجع إصدار Aspose.Slides لنظام Android عبر Java.

**الإرجاع:**
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```


إعادة تعيين الترخيص. استخدم هذه الطريقة لإعادة تعيين الترخيص في المكوّن.

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```


تحقق مما إذا كان الترخيص مُطبقًا على المكوّن

**الإرجاع:**
boolean