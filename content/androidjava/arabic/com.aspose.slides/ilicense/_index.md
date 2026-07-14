---
title: ILicense
second_title: Aspose.Slides for Android via Java API Reference
description: يوفر طرقًا لترخيص المكوّن.
type: docs
url: /ar/com.aspose.slides/ilicense/
---```
public interface ILicense
```

يوفر طرقًا لترخيص المكوّن.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | يقوم بترخيص المكوّن. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | يقوم بترخيص المكوّن. |
| [resetLicense()](#resetLicense--) | إعادة تعيين الترخيص |
| [isLicensed()](#isLicensed--) | التحقق مما إذا تم تطبيق الترخيص على المكوّن |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```


يقوم بترخيص المكوّن.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| licenseName | java.lang.String | يمكن أن يكون اسم ملف كامل أو قصير أو اسم مورد مضمن. استخدم سلسلة فارغة للتبديل إلى وضع التقييم. |

--------------------

يحاول العثور على الترخيص في المواقع التالية:

1. مسار صريح.
2. مجلد تجميع المكوّن.
3. مجلد تجميع الاستدعاء للعميل.
4. مجلد تجميع الإدخال.
5. مورد مضمن في تجميع الاستدعاء للعميل. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```


يقوم بترخيص المكوّن.

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | تدفق يحتوي على الترخيص. |

--------------------

استخدم هذه الطريقة لتحميل الترخيص من تدفق. |

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```


إعادة تعيين الترخيص

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

--------------------

استخدم هذه الطريقة لإعادة تعيين الترخيص في المكوّن

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```


التحقق مما إذا تم تطبيق الترخيص على المكوّن

**الإرجاع:**
boolean - true إذا كان المكوّن مرخصًا، وإلا false