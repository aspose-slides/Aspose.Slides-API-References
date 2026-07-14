---
title: SwfOptions
second_title: Aspose.Slides لـ Android عبر مرجع API للجافا
description: يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بصيغة Swf.
type: docs
url: /ar/com.aspose.slides/swfoptions/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**جميع الواجهات المنفذة:**
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بصيغة Swf format.

--------------------

> ```
> المثال التالي يوضح كيفية تحويل PowerPoint إلى SWF Flash.
>  
>  // إنشاء كائن Presentation يمثل ملف عرض تقديمي
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      swfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // حفظ العرض التقديمي وصفحات الملاحظات
>      pres.save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
>      swfOptions.setViewerIncluded(true);
>      pres.save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [SwfOptions()](#SwfOptions--) | منشئ افتراضي. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | يحدد ما إذا كان المستند المُنشأ يجب أن يتضمن شرائح مخفية أم لا. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | يحدد ما إذا كان المستند المُنشأ يجب أن يتضمن شرائح مخفية أم لا. |
| [getCompressed()](#getCompressed--) | يحدد ما إذا كان المستند SWF المُنشأ يجب أن يتم ضغطه أم لا. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | يحدد ما إذا كان المستند SWF المُنشأ يجب أن يتم ضغطه أم لا. |
| [getViewerIncluded()](#getViewerIncluded--) | يحدد ما إذا كان المستند SWF المُنشأ يجب أن يتضمن عارض المستند المتكامل أم لا. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | يحدد ما إذا كان المستند SWF المُنشأ يجب أن يتضمن عارض المستند المتكامل أم لا. |
| [getShowPageBorder()](#getShowPageBorder--) | يحدد ما إذا كان يجب إظهار الحد حول الصفحات. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | يحدد ما إذا كان يجب إظهار الحد حول الصفحات. |
| [getShowFullScreen()](#getShowFullScreen--) | إظهار/إخفاء زر الشاشة الكاملة. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | إظهار/إخفاء زر الشاشة الكاملة. |
| [getShowPageStepper()](#getShowPageStepper--) | إظهار/إخفاء مؤشر الصفحة. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | إظهار/إخفاء مؤشر الصفحة. |
| [getShowSearch()](#getShowSearch--) | إظهار/إخفاء قسم البحث. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | إظهار/إخفاء قسم البحث. |
| [getShowTopPane()](#getShowTopPane--) | إظهار/إخفاء اللوحة العليا بالكامل. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | إظهار/إخفاء اللوحة العليا بالكامل. |
| [getShowBottomPane()](#getShowBottomPane--) | إظهار/إخفاء اللوحة السفلية. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | إظهار/إخفاء اللوحة السفلية. |
| [getShowLeftPane()](#getShowLeftPane--) | إظهار/إخفاء اللوحة اليسرى. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | إظهار/إخفاء اللوحة اليسرى. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | ابدأ باللوحة اليسرى المفتوحة. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | ابدأ باللوحة اليسرى المفتوحة. |
| [getEnableContextMenu()](#getEnableContextMenu--) | تمكين/تعطيل قائمة السياق. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | تمكين/تعطيل قائمة السياق. |
| [getLogoImageBytes()](#getLogoImageBytes--) | الصورة التي ستُعرض كشعار في الزاوية العليا اليمنى للعارض. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | الصورة التي ستُعرض كش شعار في الزاوية العليا اليمنى للعارض. |
| [getLogoLink()](#getLogoLink--) | يحصل على أو يضع عنوان الارتباط الكامل للشعار. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | يحصل على أو يضع عنوان الارتباط الكامل للشعار. |
| [getJpegQuality()](#getJpegQuality--) | يحدد جودة صور JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | يحدد جودة صور JPEG. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | يحصل على أو يضع الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | يحصل على أو يضع الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```


منشئ افتراضي.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


يحدد ما إذا كان المستند المُنشأ يجب أن يتضمن شرائح مخفية أم لا. القيمة الافتراضية هي false.

**القيمة المرجعة:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


يحدد ما إذا كان المستند المُنشأ يجب أن يتضمن شرائح مخفية أم لا. القيمة الافتراضية هي false.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```


يحدد ما إذا كان المستند SWF المُنشأ يجب أن يتم ضغطه أم لا. القيمة الافتراضية هي true.

**القيمة المرجعة:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```


يحدد ما إذا كان المستند SWF المُنشأ يجب أن يتم ضغطه أم لا. القيمة الافتراضية هي true.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```


يحدد ما إذا كان المستند SWF المُنشأ يجب أن يتضمن عارض المستند المتكامل أم لا. القيمة الافتراضية هي true.

**القيمة المرجعة:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```


يحدد ما إذا كان المستند SWF المُنشأ يجب أن يتضمن عارض المستند المتكامل أم لا. القيمة الافتراضية هي true.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```


يحدد ما إذا كان يجب إظهار الحد حول الصفحات. القيمة الافتراضية هي true.

**القيمة المرجعة:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```


يحدد ما إذا كان يجب إظهار الحد حول الصفحات. القيمة الافتراضية هي true.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```


إظهار/إخفاء زر الشاشة الكاملة. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true.

**القيمة المرجعة:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```


إظهار/إخفاء زر الشاشة الكاملة. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```


إظهار/إخفاء مؤشر الصفحة. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true.

**القيمة المرجعة:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```


إظهار/إخفاء مؤشر الصفحة. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```


إظهار/إخفاء قسم البحث. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true.

**القيمة المرجعة:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```


إظهار/إخفاء قسم البحث. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```


إظهار/إخفاء اللوحة العليا بالكامل. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true.

**القيمة المرجعة:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```


إظهار/إخفاء اللوحة العليا بالكامل. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```


إظهار/إخفاء اللوحة السفلية. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true.

**القيمة المرجعة:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```


إظهار/إخفاء اللوحة السفلية. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```


إظهار/إخفاء اللوحة اليسرى. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true.

**القيمة المرجعة:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```


إظهار/إخفاء اللوحة اليسرى. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```


ابدأ باللوحة اليسرى المفتوحة. يمكن تجاوزها في flashvars. القيمة الافتراضية هي false.

**القيمة المرجعة:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```


ابدأ باللوحة اليسرى المفتوحة. يمكن تجاوزها في flashvars. القيمة الافتراضية هي false.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```


تمكين/تعطيل قائمة السياق. القيمة الافتراضية هي true.

**القيمة المرجعة:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```


تمكين/تعطيل قائمة السياق. القيمة الافتراضية هي true.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```


الصورة التي ستُعرض كش شعار في الزاوية العليا اليمنى للعارض. يجب أن تكون الصورة PNG بدقة 32x64 بكسل، وإلا قد يُعرض الشعار بصورة غير صحيحة.

**القيمة المرجعة:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```


الصورة التي ستُعرض كش شعار في الزاوية العليا اليمنى للعارض. يجب أن تكون الصورة PNG بدقة 32x64 بكسل، وإلا قد يُعرض الشعار بصورة غير صحيحة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```


يحصل على أو يضع عنوان الارتباط الكامل للشعار. يؤثر فقط إذا تم تحديد (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])). 

**القيمة المرجعة:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```


يحصل على أو يضع عنوان الارتباط الكامل للشعار. يؤثر فقط إذا تم تحديد (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])). 

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```


يحدد جودة صور JPEG. القيمة الافتراضية هي 95.

**القيمة المرجعة:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```


يحدد جودة صور JPEG. القيمة الافتراضية هي 95.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


يحصل على أو يضع الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). هذه الخاصية لا تدعم تعيين كائنات من النوع [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المرجعة:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


يحصل على أو يضع الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). هذه الخاصية لا تدعم تعيين كائنات من النوع [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |