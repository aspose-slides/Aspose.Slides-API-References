---
title: BlobManagementOptions
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل الخيارات التي يمكن استخدامها لإدارة قواعد معالجة BLOB وإعدادات BLOB الأخرى.
type: docs
url: /ar/com.aspose.slides/blobmanagementoptions/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
```
public class BlobManagementOptions implements IBlobManagementOptions
```

يمثل الخيارات التي يمكن استخدامها لإدارة قواعد معالجة BLOB وإعدادات BLOB الأخرى.
## المنشئ

| المنشئ | الوصف |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | ينشئ خيارات إدارة BLOB افتراضية جديدة. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | هذه الخاصية تحدد ما إذا كان كائن من فئة Presentation يمكن أن يكون مالكًا للمصدر - الملف أو الدفق طوال عمر الكائن. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | هذه الخاصية تحدد ما إذا كان كائن من فئة Presentation يمكن أن يكون مالكًا للمصدر - الملف أو الدفق طوال عمر الكائن. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | هذه الخاصية تحدد ما إذا كان يمكن إنشاء ملفات مؤقتة أثناء العمل مع BLOBs، مما يقلل بشكل كبير من استهلاك الذاكرة ولكن يتطلب أذونات لإنشاء الملفات. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | هذه الخاصية تحدد ما إذا كان يمكن إنشاء ملفات مؤقتة أثناء العمل مع BLOBs، مما يقلل بشكل كبير من استهلاك الذاكرة ولكن يتطلب أذونات لإنشاء الملفات. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | مسار الجذر حيث سيتم إنشاء الملفات المؤقتة. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | مسار الجذر حيث سيتم إنشاء الملفات المؤقتة. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | يحدد الحد الأقصى الإجمالي لحجم BLOBs (بالبايت) الذي يمكن أن تحتله في الذاكرة. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | يحدد الحد الأقصى الإجمالي لحجم BLOBs (بالبايت) الذي يمكن أن تحتله في الذاكرة. |
### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

ينشئ خيارات إدارة BLOB افتراضية جديدة.

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

هذه الخاصية تحدد ما إذا كان كائن من فئة Presentation يمكن أن يكون مالكًا للمصدر - الملف أو الدفق طوال عمر الكائن. إذا كان الكائن مالكًا، فإنه يقفل المصدر. يساعد ذلك على تحسين استهلاك الذاكرة والأداء أثناء العمل مع BLOBs، لكن لا يمكن تغيير المصدر (الدفق أو الملف) طوال عمر كائن Presentation.

**الإرجاع:**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

هذه الخاصية تحدد ما إذا كان كائن من فئة Presentation يمكن أن يكون مالكًا للمصدر - الملف أو الدفق طوال عمر الكائن. إذا كان الكائن مالكًا، فإنه يقفل المصدر. يساعد ذلك على تحسين استهلاك الذاكرة والأداء أثناء العمل مع BLOBs، لكن لا يمكن تغيير المصدر (الدفق أو الملف) طوال عمر كائن Presentation.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```

هذه الخاصية تحدد ما إذا كان يمكن إنشاء ملفات مؤقتة أثناء العمل مع BLOBs، مما يقلل بشكل كبير من استهلاك الذاكرة ولكن يتطلب أذونات لإنشاء الملفات.

--------------------

جميع الملفات سيتم حذفها بعد الانتهاء من العمل مع العرض التقديمي.

**الإرجاع:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```

هذه الخاصية تحدد ما إذا كان يمكن إنشاء ملفات مؤقتة أثناء العمل مع BLOBs، مما يقلل بشكل كبير من استهلاك الذاكرة ولكن يتطلب أذونات لإنشاء الملفات.

--------------------

جميع الملفات سيتم حذفها بعد الانتهاء من العمل مع العرض التقديمي.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```

مسار الجذر حيث سيتم إنشاء الملفات المؤقتة. سيتم استخدام دليل النظام المؤقت بشكل افتراضي. يجب أن يكون للعميلة المستضيفة أذونات لإنشاء الملفات والمجلدات هناك.

**الإرجاع:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

مسار الجذر حيث سيتم إنشاء الملفات المؤقتة. سيتم استخدام دليل النظام المؤقت بشكل افتراضي. يجب أن يكون للعميلة المستضيفة أذونات لإنشاء الملفات والمجلدات هناك.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

يحدد الحد الأقصى الإجمالي لحجم BLOBs (بالبايت) الذي يمكن أن تحتله في الذاكرة. بشكل افتراضي، يتم تحميل جميع BLOBs في الذاكرة؛ فقط عندما يتم الوصول إلى هذا الحد يتم استخدام آليات بديلة (مثل الملفات المؤقتة). إبقاء BLOBs في الذاكرة يزيد الأداء لكن قد يؤدي إلى استهلاك عالي للذاكرة. استخدم هذه الخاصية لتكييف السلوك مع بيئتك أو متطلباتك.

--------------------

يتم تجاهل هذه الخاصية إذا تم تعيين \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) إلى false، لأن الذاكرة ستكون الموقع الوحيد المتاح للتخزين ولا يؤثر تحديد استخدام BLOB في الذاكرة.

--------------------

القيمة الافتراضية هي 629,145,600 بايت (600 ميغابايت).

--------------------

يمكنك تعيين هذه الخاصية إلى الصفر، لكن سيظل جزء صغير من الذاكرة محجوزًا.

**الإرجاع:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

يحدد الحد الأقصى الإجمالي لحجم BLOBs (بالبايت) الذي يمكن أن تحتله في الذاكرة. بشكل افتراضي، يتم تحميل جميع BLOBs في الذاكرة؛ فقط عندما يتم الوصول إلى هذا الحد يتم استخدام آليات بديلة (مثل الملفات المؤقتة). إبقاء BLOBs في الذاكرة يزيد الأداء لكن قد يؤدي إلى استهلاك عالي للذاكرة. استخدم هذه الخاصية لتكييف السلوك مع بيئتك أو متطلباتك.

--------------------

يتم تجاهل هذه الخاصية إذا تم تعيين \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) إلى false، لأن الذاكرة ستكون الموقع الوحيد المتاح للتخزين ولا يؤثر تحديد استخدام BLOB في الذاكرة.

--------------------

القيمة الافتراضية هي 629,145,600 بايت (600 ميغابايت).

--------------------

يمكنك تعيين هذه الخاصية إلى الصفر، لكن سيظل جزء صغير من الذاكرة محجوزًا.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |