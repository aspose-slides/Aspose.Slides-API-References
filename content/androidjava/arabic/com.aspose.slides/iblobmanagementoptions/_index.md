---
title: IBlobManagementOptions
second_title: Aspose.Slides for Android via Java API Reference
description: A Binary Large Object BLOB is a binary data stored as a single entity - i.e.
type: docs
url: /ar/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

كائن كبير ثنائي (BLOB) هو بيانات ثنائية مخزنة ككيان واحد - أي يمكن أن يكون BLOB صوتًا أو فيديو أو العرض التقديمي نفسه. يتم استخدام عدد من التقنيات لتحسين استهلاك الذاكرة أثناء العمل مع BLOBs - سواء كانت مخزنة بالفعل في العرض التقديمي أو تتم إضافتها لاحقًا برمجيًا. باستخدام [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) يمكنك تعديل جوانب سلوك مختلفة تتعلق بمعالجة BLOBs طوال مدة وجود كائن [IPresentation](../../com.aspose.slides/ipresentation).

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | هذه الخاصية تحدد ما إذا كان كائن من فئة Presentation يمكن أن يكون مالكًا للمصدر - ملف أو تدفق - طوال مدة وجود الكائن. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | هذه الخاصية تحدد ما إذا كان كائن من فئة Presentation يمكن أن يكون مالكًا للمصدر - ملف أو تدفق - طوال مدة وجود الكائن. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | هذه الخاصية تحدد ما إذا كان يمكن إنشاء ملفات مؤقتة أثناء العمل مع BLOBs، مما يقلل بشكل كبير من استهلاك الذاكرة ولكنه يتطلب أذونات لإنشاء الملفات. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | هذه الخاصية تحدد ما إذا كان يمكن إنشاء ملفات مؤقتة أثناء العمل مع BLOBs، مما يقلل بشكل كبير من استهلاك الذاكرة ولكنه يتطلب أذونات لإنشاء الملفات. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | مسار الجذر حيث سيتم إنشاء الملفات المؤقتة. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | مسار الجذر حيث سيتم إنشاء الملفات المؤقتة. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | يعرف الحد الأقصى للإجمالي الكلي للحجم (بالبايت) الذي قد تشغله جميع BLOBs في الذاكرة. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | يعرف الحد الأقصى للإجمالي الكلي للحجم (بالبايت) الذي قد تشغله جميع BLOBs في الذاكرة. |

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

هذه الخاصية تحدد ما إذا كان كائن من فئة Presentation يمكن أن يكون مالكًا للمصدر - ملف أو تدفق - طوال مدة وجود الكائن. إذا كان الكائن مالكًا، فإنه يقفل المصدر. هذا يساعد على تحسين استهلاك الذاكرة والأداء أثناء العمل مع BLOBs، لكن لا يمكن تغيير المصدر (التدفق أو الملف) خلال مدة وجود كائن Presentation. هذا مثال:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // سيتم إلقاء استثناء IOException لأن pres.pptx مقفل طوال عمر Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // بعد التخلص من كائن Presentation، يتم إلغاء قفل الملف ويمكن حذفه
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
```

**القيمة المرجعة:**  
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

هذه الخاصية تحدد ما إذا كان كائن من فئة Presentation يمكن أن يكون مالكًا للمصدر - ملف أو تدفق - طوال مدة وجود الكائن. إذا كان الكائن مالكًا، فإنه يقفل المصدر. هذا يساعد على تحسين استهلاك الذاكرة والأداء أثناء العمل مع BLOBs، لكن لا يمكن تغيير المصدر (التدفق أو الملف) خلال مدة وجود كائن Presentation. هذا مثال:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // سيتم إلقاء استثناء IOException لأن pres.pptx مقفل طوال عمر Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // بعد التخلص من كائن Presentation، يتم إلغاء قفل الملف ويمكن حذفه
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

هذه الخاصية تحدد ما إذا كان يمكن إنشاء ملفات مؤقتة أثناء العمل مع BLOBs، مما يقلل بشكل كبير من استهلاك الذاكرة ولكنه يتطلب أذونات لإنشاء الملفات.

--------------------

سيتم حذف جميع الملفات بعد انتهاء العمل مع العرض التقديمي.

**القيمة المرجعة:**  
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

هذه الخاصية تحدد ما إذا كان يمكن إنشاء ملفات مؤقتة أثناء العمل مع BLOBs، مما يقلل بشكل كبير من استهلاك الذاكرة ولكنه يتطلب أذونات لإنشاء الملفات.

--------------------

سيتم حذف جميع الملفات بعد انتهاء العمل مع العرض التقديمي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

مسار الجذر حيث سيتم إنشاء الملفات المؤقتة. سيتم استخدام دليل النظام المؤقت افتراضيًا. يجب أن يكون للعملية المضيفة أذونات لإنشاء الملفات والمجلدات هناك.

**القيمة المرجعة:**  
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

مسار الجذر حيث سيتم إنشاء الملفات المؤقتة. سيتم استخدام دليل النظام المؤقت افتراضيًا. يجب أن يكون للعملية المضيفة أذونات لإنشاء الملفات والمجلدات هناك.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

يعرف الحد الأقصى للإجمالي الكلي للحجم (بالبايت) الذي قد تشغله جميع BLOBs في الذاكرة. بشكل افتراضي، يتم تحميل جميع BLOBs إلى الذاكرة؛ وعندما يُصل إلى هذا الحد فقط تُستخدم آليات بديلة (مثل الملفات المؤقتة). إبقاء BLOBs في الذاكرة يعزز الأداء ولكنه قد يؤدي إلى استهلاك عالي للذاكرة. استخدم هذه الخاصية لتكييف السلوك مع بيئتك أو متطلباتك.

--------------------

هذه الخاصية تُهمل إذا تم تعيين #isTemporaryFilesAllowed.isTemporaryFilesAllowed/#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) إلى false، لأن الذاكرة ستكون حينئذٍ هي موقع التخزين الوحيد المتاح وضبط استخدام BLOB في الذاكرة ليس له أي تأثير.

--------------------

القيمة الافتراضية هي 629,145,600 بايت (600 ميغابايت).

--------------------

يمكنك ضبط هذه الخاصية إلى الصفر، لكن سيتم الاحتفاظ بكمية صغيرة من الذاكرة كحد أدنى.

**القيمة المرجعة:**  
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

يعرف الحد الأقصى للإجمالي الكلي للحجم (بالبايت) الذي قد تشغله جميع BLOBs في الذاكرة. بشكل افتراضي، يتم تحميل جميع BLOBs إلى الذاكرة؛ وعندما يُصل إلى هذا الحد فقط تُستخدم آليات بديلة (مثل الملفات المؤقتة). إبقاء BLOBs في الذاكرة يعزز الأداء ولكنه قد يؤدي إلى استهلاك عالي للذاكرة. استخدم هذه الخاصية لتكييف السلوك مع بيئتك أو متطلباتك.

--------------------

هذه الخاصية تُهمل إذا تم تعيين #isTemporaryFilesAllowed.isTemporaryFilesAllowed/#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) إلى false، لأن الذاكرة ستكون حينئذٍ هي موقع التخزين الوحيد المتاح وضبط استخدام BLOB في الذاكرة ليس له أي تأثير.

--------------------

القيمة الافتراضية هي 629,145,600 بايت (600 ميغابايت).

--------------------

يمكنك ضبط هذه الخاصية إلى الصفر، لكن سيتم الاحتفاظ بكمية صغيرة من الذاكرة كحد أدنى.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |