---
title: ILicense
second_title: Aspose.Slides for Java API Reference
description: Provides methods to license the component.
type: docs
url: /ar/com.aspose.slides/ilicense/
---```
public interface ILicense
```

يوفر طرقًا لترخيص المكوّن.

--------------------

> ```
> في هذا المثال، سيُحاول العثور على ملف ترخيص اسمه MyLicense.lic
>  في المجلد الذي يحتوي على المكوّن، في المجلد الذي يحتوي على تجميع الاستدعاء،
>  في مجلد تجميع الإدخال ثم في الموارد المضمنة لتجميع الاستدعاء.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
```
## الطرق

| طريقة | وصف |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | يرخص المكوّن. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | يرخص المكوّن. |
| [resetLicense()](#resetLicense--) | إعادة تعيين الترخيص |
| [isLicensed()](#isLicensed--) | التحقق مما إذا كان الترخيص تم تطبيقه على المكوّن |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```


يرخص المكوّن.

--------------------

> ```
> في هذا المثال، سيُحاول العثور على ملف ترخيص اسمه MyLicense.lic
>  في المجلد الذي يحتوي على المكوّن، في المجلد الذي يحتوي على تجميع الاستدعاء،
>  في مجلد تجميع الإدخال ثم في الموارد المدمجة لتجميع الاستدعاء.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
```

**المعلمات:**
| معلمة | نوع | وصف |
| --- | --- | --- |
| licenseName | java.lang.String | يمكن أن يكون اسم ملف كامل أو قصير أو اسم مورد مضمّن. استخدم سلسلة فارغة للتبديل إلى وضع التقييم. |

--------------------

يحاول العثور على الترخيص في المواقع التالية:

1. مسار صريح.
2. مجلد تجميع المكوّن.
3. مجلد تجميع الاستدعاء للعميل.
4. مجلد تجميع الإدخال.
5. مورد مضمّن في تجميع الاستدعاء للعميل. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```


يرخص المكوّن.

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
```

**المعلمات:**
| معلمة | نوع | وصف |
| --- | --- | --- |
| stream | java.io.InputStream | دفق يحتوي على الترخيص. |

--------------------

استخدم هذه الطريقة لتحميل الترخيص من دفق. |

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


التحقق مما إذا كان الترخيص تم تطبيقه على المكوّن

**القيمة المرجعة:**
boolean - true إذا كان المكوّن مرخصًا، وإلا false