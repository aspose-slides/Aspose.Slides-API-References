---
title: ISwfOptions
second_title: مرجع API لـ Aspose.Slides for Java
description: يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بتنسيق SWF.
type: docs
url: /ar/com.aspose.slides/iswfoptions/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISwfOptions extends ISaveOptions
```

يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بتنسيق SWF.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCompressed()](#getCompressed--) | تحدد ما إذا كان مستند SWF المتولد يجب أن يكون مضغوطًا أم لا. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | تحدد ما إذا كان مستند SWF المتولد يجب أن يكون مضغوطًا أم لا. |
| [getViewerIncluded()](#getViewerIncluded--) | تحدد ما إذا كان مستند SWF المتولد يجب أن يتضمن عارض المستند المتكامل أم لا. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | تحدد ما إذا كان مستند SWF المتولد يجب أن يتضمن عارض المستند المتكامل أم لا. |
| [getShowPageBorder()](#getShowPageBorder--) | تحدد ما إذا كان يجب إظهار الحدود حول الصفحات. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | تحدد ما إذا كان يجب إظهار الحدود حول الصفحات. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | تحدد ما إذا كان المستند المتولد يجب أن يتضمن الشرائح المخفية أم لا. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | تحدد ما إذا كان المستند المتولد يجب أن يتضمن الشرائح المخفية أم لا. |
| [getShowFullScreen()](#getShowFullScreen--) | إظهار/إخفاء زر ملء الشاشة. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | إظهار/إخفاء زر ملء الشاشة. |
| [getShowPageStepper()](#getShowPageStepper--) | إظهار/إخفاء متحكم الصفحات. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | إظهار/إخفاء متحكم الصفحات. |
| [getShowSearch()](#getShowSearch--) | إظهار/إخفاء قسم البحث. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | إظهار/إخفاء قسم البحث. |
| [getShowTopPane()](#getShowTopPane--) | إظهار/إخفاء الجزء العلوي بالكامل. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | إظهار/إخفاء الجزء العلوي بالكامل. |
| [getShowBottomPane()](#getShowBottomPane--) | إظهار/إخفاء الجزء السفلي. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | إظهار/إخفاء الجزء السفلي. |
| [getShowLeftPane()](#getShowLeftPane--) | إظهار/إخفاء الجزء الأيسر. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | إظهار/إخفاء الجزء الأيسر. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | ابدأ بالجزء الأيسر المفتوح. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | ابدأ بالجزء الأيسر المفتوح. |
| [getEnableContextMenu()](#getEnableContextMenu--) | تمكين/تعطيل قائمة السياق. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | تمكين/تعطيل قائمة السياق. |
| [getLogoImageBytes()](#getLogoImageBytes--) | الصورة التي ستُعرض كشعار في الزاوية العليا اليمنى للعارض. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | الصورة التي ستُعرض كشعار في الزاوية العليا اليمنى للعارض. |
| [getLogoLink()](#getLogoLink--) | يحصل أو يحدد عنوان الارتباط الكامل للشعار. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | يحصل أو يحدد عنوان الارتباط الكامل للشعار. |
| [getJpegQuality()](#getJpegQuality--) | تحدد جودة صور JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | تحدد جودة صور JPEG. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | يحصل أو يحدد الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | يحصل أو يحدد الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |

### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```

تحدد ما إذا كان مستند SWF المتولد يجب أن يكون مضغوطًا أم لا. القيمة الافتراضية هي true.

**القيمة المرجعة:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```

تحدد ما إذا كان مستند SWF المتولد يجب أن يكون مضغوطًا أم لا. القيمة الافتراضية هي true.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```

تحدد ما إذا كان مستند SWF المتولد يجب أن يتضمن عارض المستند المتكامل أم لا. القيمة الافتراضية هي true.

**القيمة المرجعة:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```

تحدد ما إذا كان مستند SWF المتولد يجب أن يتضمن عارض المستند المتكامل أم لا. القيمة الافتراضية هي true.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```

تحدد ما إذا كان يجب إظهار الحدود حول الصفحات. القيمة الافتراضية هي true.

**القيمة المرجعة:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```

تحدد ما إذا كان يجب إظهار الحدود حول الصفحات. القيمة الافتراضية هي true.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

تحدد ما إذا كان المستند المتولد يجب أن يتضمن الشرائح المخفية أم لا. القيمة الافتراضية هي false.

**القيمة المرجعة:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

تحدد ما إذا كان المستند المتولد يجب أن يتضمن الشرائح المخيفة أم لا. القيمة الافتراضية هي false.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```

إظهار/إخفاء زر ملء الشاشة. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true.

**القيمة المرجعة:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```

إظهار/إخفاء زر ملء الشاشة. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```

إظهار/إخفاء متحكم الصفحات. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true.

**القيمة المرجعة:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```

إظهار/إخفاء متحكم الصفحات. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```

إظهار/إخفاء قسم البحث. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true.

**القيمة المرجعة:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```

إظهار/إخفاء قسم البحث. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```

إظهار/إخفاء الجزء العلوي بالكامل. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true.

**القيمة المرجعة:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```

إظهار/إخفاء الجزء العلوي بالكامل. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```

إظهار/إخفاء الجزء السفلي. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true.

**القيمة المرجعة:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```

إظهار/إخفاء الجزء السفلي. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```

إظهار/إخفاء الجزء الأيسر. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true.

**القيمة المرجعة:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```

إظهار/إخفاء الجزء الأيسر. يمكن تجاوزها في flashvars. القيمة الافتراضية هي true.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```

ابدأ بالجزء الأيسر المفتوح. يمكن تجاوزها في flashvars. القيمة الافتراضية هي false.

**القيمة المرجعة:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```

ابدأ بالجزء الأيسر المفتوح. يمكن تجاوزها في flashvars. القيمة الافتراضية هي false.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```

تمكين/تعطيل قائمة السياق. القيمة الافتراضية هي true.

**القيمة المرجعة:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```

تمكين/تعطيل قائمة السياق. القيمة الافتراضية هي true.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```

الصورة التي ستُعرض كشعار في الزاوية العليا اليمنى للعارض. يجب أن تكون الصورة PNG بحجم 32x64 بكسل، وإلا قد يُعرض الشعار بصورة غير صحيحة.

**القيمة المرجعة:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```

الصورة التي ستُعرض كشعار في الزاوية العليا اليمنى للعارض. يجب أن تكون الصورة PNG بحجم 32x64 بكسل، وإلا قد يُعرض الشعار بصورة غير صحيحة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```

يحصل أو يحدد عنوان الارتباط الكامل للشعار. له تأثير فقط إذا تم تحديد (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])). 

**القيمة المرجعة:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```

يحصل أو يحدد عنوان الارتباط الكامل للشعار. له تأثير فقط إذا تم تحديد (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])). 

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

تحدد جودة صور JPEG. القيمة الافتراضية هي 95.

**القيمة المرجعة:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

تحدد جودة صور JPEG. القيمة الافتراضية هي 95.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

يحصل أو يحدد الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). هذه الخاصية لا تدعم تعيين كائنات من النوع [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

يحصل أو يحدد الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). هذه الخاصية لا تدعم تعيين كائنات من النوع [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

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