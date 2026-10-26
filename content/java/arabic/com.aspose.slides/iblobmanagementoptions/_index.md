---
title: IBlobManagementOptions
second_title: Aspose.Slides for Java API Reference
description: A Binary Large Object BLOB is a binary data stored as a single entity - i.e.
type: docs
url: /ar/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

كائن ثنائي كبير (BLOB) هو بيانات ثنائية مخزنة ككيان واحد - أي يمكن أن يكون BLOB صوتًا أو فيديو أو العرض التقديمي نفسه. يتم استخدام عدد من التقنيات لتحسين استهلاك الذاكرة أثناء التعامل مع BLOBs - سواء كان قد تم تخزينه بالفعل في العرض التقديمي أو سيُضاف لاحقًا برمجيًا. باستخدام [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) يمكنك تغيير جوانب سلوك مختلفة تتعلق بمعالجة BLOBs طوال عمر مثيل [IPresentation](../../com.aspose.slides/ipresentation).

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | تحدد هذه الخاصية ما إذا كان يمكن لكائن من فئة Presentation أن يكون مالكًا للمصدر - الملف أو التدفق طوال عمر الكائن. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | تحدد هذه الخصيّة ما إذا كان يمكن لكائن من فئة Presentation أن يكون مالكًا للمصدر - الملف أو التدفق طوال عمر الكائن. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | تحدد هذه الخاصية ما إذا كان يمكن إنشاء ملفات مؤقتة أثناء العمل مع BLOBs، مما يقلل بشكل كبير من استهلاك الذاكرة ولكنه يتطلب أذونات لإنشاء الملفات. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | تحدد هذه الخصيّة ما إذا كان يمكن إنشاء ملفات مؤقتة أثناء العمل مع BLOBs، مما يقلل بشكل كبير من استهلاك الذاكرة ولكنه يتطلب أذونات لإنشاء الملفات. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | مسار الجذر حيث سيتم إنشاء الملفات المؤقتة. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | مسار الجذر حيث سيتم إنشاء الملفات المؤقتة. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | يحدد الحد الأقصى للحجم الإجمالي (بالبايت) الذي قد تحتله جميع BLOBs في الذاكرة. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | يحدد الحد الأقصى للحجم الإجمالي (بالبايت) الذي قد تحتله جميع BLOBs في الذاكرة. |

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

تحدد هذه الخاصية ما إذا كان يمكن لكائن من فئة Presentation أن يكون مالكًا للمصدر - الملف أو التدفق طوال عمر الكائن. إذا كان الكائن مالكًا، فإنه يقفل المصدر. يساعد ذلك على تحسين استهلاك الذاكرة والأداء أثناء العمل مع BLOBs، لكن لا يمكن تغيير المصدر (التدفق أو الملف) خلال عمر مثيل Presentation. هذا مثال:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // سيتم رمي IOException لأن pres.pptx مقفلة طوال عمر الـ Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // بعد أن يتم التخلص من كائن Presentation، يتم إلغاء قفل الملف ويمكن حذفه
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```

**الإرجاع:**  
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

تحدد هذه الخاصية ما إذا كان يمكن لكائن من فئة Presentation أن يكون مالكًا للمصدر - الملف أو التدفق طوال عمر الكائن. إذا كان الكائن مالكًا، فإنه يقفل المصدر. يساعد ذلك على تحسين استهلاك الذاكرة والأداء أثناء العمل مع BLOBs، لكن لا يمكن تغيير المصدر (التدفق أو الملف) خلال عمر مثيل Presentation. هذا مثال:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // سيُرمى IOException لأن pres.pptx مقفلة طوال عمر الـ Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // بعد أن يتم التخلص من كائن Presentation، يتم إلغاء قفل الملف ويمكن حذفه
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

تحدد هذه الخاصية ما إذا كان يمكن إنشاء ملفات مؤقتة أثناء العمل مع BLOBs، مما يقلل بشكل كبير من استهلاك الذاكرة ولكنه يتطلب أذونات لإنشاء الملفات.

--------------------

سيتم حذف جميع الملفات بعد الانتهاء من العمل مع العرض التقديمي.

**الإرجاع:**  
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

تحدد هذه الخاصية ما إذا كان يمكن إنشاء ملفات مؤقتة أثناء العمل مع BLOBs، مما يقلل بشكل كبير من استهلاك الذاكرة ولكنه يتطلب أذونات لإنشاء الملفات.

--------------------

سيتم حذف جميع الملفات بعد الانتهاء من العمل مع العرض التقديمي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

مسار الجذر حيث سيتم إنشاء الملفات المؤقتة. سيُستخدم دليل النظام المؤقت بشكل افتراضي. يجب أن يكون لدى عملية الاستضافة أذونات لإنشاء الملفات والمجلدات هناك.

**الإرجاع:**  
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

مسار الجذر حيث سيتم إنشاء الملفات المؤقتة. سيُستخدم دليل النظام المؤقت بشكل افتراضي. يجب أن يكون لدى عملية الاستضافة أذونات لإنشاء الملفات والمجلدات هناك.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

يحدد الحد الأقصى للحجم الإجمالي (بالبايت) الذي قد تحتله جميع BLOBs في الذاكرة. بشكل افتراضي، تُحمَّل جميع BLOBs إلى الذاكرة؛ وعند وصول هذا الحد تُستَخدم آليات بديلة (مثل الملفات المؤقتة). الاحتفاظ بـ BLOBs في الذاكرة يعظم الأداء لكنه قد يؤدي إلى استهلاك عالي للذاكرة. استخدم هذه الخاصية لضبط السلوك وفقًا لبيئتك أو متطلباتك.

--------------------

يتم تجاهل هذه الخاصية إذا تم تعيين \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) إلى false، حيث تكون الذاكرة هي موقع التخزين الوحيد المتاح ولا يكون لتحديد استخدام BLOB في الذاكرة أي تأثير.

--------------------

القيمة الافتراضية هي 629,145,600 بايت (600 ميغابايت).

--------------------

يمكنك تعيين هذه الخاصية إلى صفر، ولكن سيظل يتم حجز كمية صغيرة من الذاكرة على الأقل.

**الإرجاع:**  
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

يحدد الحد الأقصى للحجم الإجمالي (بالبايت) الذي قد تحتله جميع BLOBs في الذاكرة. بشكل افتراضي، تُحمَّل جميع BLOBs إلى الذاكرة؛ وعند وصول هذا الحد تُستَخدم آليات بديلة (مثل الملفات المؤقتة). الاحتفاظ بـ BLOBs في الذاكرة يعظم الأداء لكنه قد يؤدي إلى استهلاك عالي للذاكرة. استخدم هذه الخاصية لضبط السلوك وفقًا لبيئتك أو متطلباتك.

--------------------

يتم تجاهل هذه الخاصية إذا تم تعيين \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) إلى false، حيث تكون الذاكرة هي موقع التخزين الوحيد المتاح ولا يكون لتحديد استخدام BLOB في الذاكرة أي تأثير.

--------------------

القيمة الافتراضية هي 629,145,600 بايت (600 ميغابايت).

--------------------

يمكنك تعيين هذه الخاصية إلى صفر، ولكن سيظل يتم حجز كمية صغيرة من الذاكرة على الأقل.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |