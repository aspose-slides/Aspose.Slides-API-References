---
title: ISwfOptions
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بصيغة SWF.
type: docs
url: /ar/com.aspose.slides/iswfoptions/
---
**جميع الواجهات المُنفّذة:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISwfOptions extends ISaveOptions
```

يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بصيغة SWF.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCompressed()](#getCompressed--) | يحدد ما إذا كان يجب ضغط المستند SWF المُولَّد أم لا. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | يحدد ما إذا كان يجب ضغط المستند SWF المُولَّد أم لا. |
| [getViewerIncluded()](#getViewerIncluded--) | يحدد ما إذا كان ينبغي أن يتضمن المستند SWF المُولَّد عارض المستند المتكامل أم لا. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | يحدد ما إذا كان ينبغي أن يتضمن المستند SWF المُولَّد عارض المستند المتكامل أم لا. |
| [getShowPageBorder()](#getShowPageBorder--) | يحدد ما إذا كان يجب إظهار الحد حول الصفحات. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | يحدد ما إذا كان يجب إظهار الحد حول الصفحات. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | يحدد ما إذا كان يجب أن يتضمن المستند المُولَّد الشرائح المخفية أم لا. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | يحدد ما إذا كان يجب أن يتضمن المستند المُولَّد الشرائح المخفية أم لا. |
| [getShowFullScreen()](#getShowFullScreen--) | إظهار/إخفاء زر ملء الشاشة. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | إظهار/إخفاء زر ملء الشاشة. |
| [getShowPageStepper()](#getShowPageStepper--) | إظهار/إخفاء متحكم الصفحات. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | إظهار/إخفاء متحكم الصفحات. |
| [getShowSearch()](#getShowSearch--) | إظهار/إخفاء قسم البحث. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | إظهار/إخفاء قسم البحث. |
| [getShowTopPane()](#getShowTopPane--) | إظهار/إخفاء اللوحة العلوية بالكامل. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | إظهار/إخفاء اللوحة العلوية بالكامل. |
| [getShowBottomPane()](#getShowBottomPane--) | إظهار/إخفاء اللوحة السفلية. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | إظهار/إخفاء اللوحة السفلية. |
| [getShowLeftPane()](#getShowLeftPane--) | إظهار/إخفاء اللوحة اليسرى. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | إظهار/إخفاء اللوحة اليسرى. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | ابدأ مع اللوحة اليسرى المفتوحة. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | ابدأ مع اللوحة اليسرى المفتوحة. |
| [getEnableContextMenu()](#getEnableContextMenu--) | تمكين/تعطيل قائمة السياق. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | تمكين/تعطيل قائمة السياق. |
| [getLogoImageBytes()](#getLogoImageBytes--) | الصورة التي سيتم عرضها كشعار في الزاوية العلوية اليمنى للعارض. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | الصورة التي سيتم عرضها كشعار في الزاوية العلوية اليمنى للعارض. |
| [getLogoLink()](#getLogoLink--) | يحصل على أو يضبط عنوان الرابط الكامل لشعار. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | يحصل على أو يضبط عنوان الرابط الكامل لشعار. |
| [getJpegQuality()](#getJpegQuality--) | يحدد جودة صور JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | يحدد جودة صور JPEG. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | يحصل على أو يضبط الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | يحصل على أو يضبط الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |

### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```

يحدد ما إذا كان يجب ضغط المستند SWF المُولَّد أم لا. القيمة الافتراضية true.

**الإرجاع:**
boolean

### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```

يحدد ما إذا كان يجب ضغط المستند SWF المُولَّد أم لا. القيمة الافتراضية true.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```

يحدد ما إذا كان ينبغي أن يتضمن المستند SWF المُولَّد عارض المستند المتكامل أم لا. القيمة الافتراضية true.

**الإرجاع:**
boolean

### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```

يحدد ما إذا كان ينبغي أن يتضمن المستند SWF المُولَّد عارض المستند المتكامل أم لا. القيمة الافتراضية true.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```

يحدد ما إذا كان يجب إظهار الحد حول الصفحات. القيمة الافتراضية true.

**الإرجاع:**
boolean

### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```

يحدد ما إذا كان يجب إظهار الحد حول الصفحات. القيمة الافتراضية true.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

يحدد ما إذا كان يجب أن يتضمن المستند المُولَّد الشرائح المخفية أم لا. القيمة الافتراضية false.

**الإرجاع:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

يحدد ما إذا كان يجب أن يتضمن المستند المُولَّد الشرائح المخفية أم لا. القيمة الافتراضية false.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```

إظهار/إخفاء زر ملء الشاشة. يمكن تجاوزها في flashvars. القيمة الافتراضية true.

**الإرجاع:**
boolean

### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```

إظهار/إخفاء زر ملء الشاشة. يمكن تجاوزها في flashvars. القيمة الافتراضية true.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```

إظهار/إخفاء متحكم الصفحات. يمكن تجاوزها في flashvars. القيمة الافتراضية true.

**الإرجاع:**
boolean

### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```

إظهار/إخفاء متحكم الصفحات. يمكن تجاوزها في flashvars. القيمة الافتراضية true.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```

إظهار/إخفاء قسم البحث. يمكن تجاوزها في flashvars. القيمة الافتراضية true.

**الإرجاع:**
boolean

### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```

إظهار/إخفاء قسم البحث. يمكن تجاوزها في flashvars. القيمة الافتراضية true.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```

إظهار/إخفاء اللوحة العلوية بالكامل. يمكن تجاوزها في flashvars. القيمة الافتراضية true.

**الإرجاع:**
boolean

### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```

إظهار/إخفاء اللوحة العلوية بالكامل. يمكن تجاوزها في flashvars. القيمة الافتراضية true.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```

إظهار/إخفاء اللوحة السفلية. يمكن تجاوزها في flashvars. القيمة الافتراضية true.

**الإرجاع:**
boolean

### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```

إظهار/إخفاء اللوحة السفلية. يمكن تجاوزها في flashvars. القيمة الافتراضية true.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```

إظهار/إخفاء اللوحة اليسرى. يمكن تجاوزها في flashvars. القيمة الافتراضية true.

**الإرجاع:**
boolean

### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```

إظهار/إخفاء اللوحة اليسرى. يمكن تجاوزها في flashvars. القيمة الافتراضية true.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```

ابدأ مع اللوحة اليسرى المفتوحة. يمكن تجاوزها في flashvars. القيمة الافتراضية false.

**الإرجاع:**
boolean

### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```

ابدأ مع اللوحة اليسرى المفتوحة. يمكن تجاوزها في flashvars. القيمة الافتراضية false.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```

تمكين/تعطيل قائمة السياق. القيمة الافتراضية true.

**الإرجاع:**
boolean

### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```

تمكين/تعطيل قائمة السياق. القيمة الافتراضية true.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```

الصورة التي سيتم عرضها كشعار في الزاوية العلوية اليمنى للعارض. يجب أن تكون الصورة PNG بدقة 32x64 بكسل، وإلا قد يتم عرض الشعار بشكل غير صحيح.

**الإرجاع:**
byte[]

### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```

الصورة التي سيتم عرضها كشعار في الزاوية العلوية اليمنى للعارض. يجب أن تكون الصورة PNG بدقة 32x64 بكسل، وإلا قد يتم عرض الشعار بشكل غير صحيح.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```

يحصل على أو يضبط عنوان الرابط الكامل لشعار. له تأثير فقط إذا تم تحديد (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**الإرجاع:**
java.lang.String

### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```

يحصل على أو يضبط عنوان الرابط الكامل لشعار. له تأثير فقط إذا تم تحديد (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

يحدد جودة صور JPEG. القيمة الافتراضية 95.

**الإرجاع:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

يحدد جودة صور JPEG. القيمة الافتراضية 95.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

يحصل على أو يضبط الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). هذه الخاصية لا تدعم إعطاء كائنات من النوع [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

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

**الإرجاع:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

يحصل على أو يضبط الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). هذه الخاصية لا تدعم إعطاء كائنات من النوع [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |