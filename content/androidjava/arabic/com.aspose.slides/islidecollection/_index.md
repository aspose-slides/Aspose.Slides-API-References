---
title: ISlideCollection
second_title: Aspose.Slides لأندرويد عبر مرجع API لجافا
description: يمثل مجموعة من الشرائح.
type: docs
url: /ar/com.aspose.slides/islidecollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCollection
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

يمثل مجموعة من الشرائح.
## الطرق

| طريقة | وصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | يضيف نسخة من الشريحة المحددة إلى نهاية المجموعة. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | يضيف نسخة من الشريحة المحددة إلى نهاية القسم المحدد. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | يدرج نسخة من الشريحة المحددة إلى الموضع المحدد في المجموعة. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | يضيف شريحة فارغة جديدة إلى نهاية المجموعة. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | يدرج نسخة من الشريحة المحددة إلى الموضع المحدد في المجموعة. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | يضيف نسخة من الشريحة المحددة إلى نهاية المجموعة. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | يدرج نسخة من الشريحة المحددة إلى الموضع المحدد في المجموعة. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | يضيف نسخة من شريحة المصدر المحددة إلى نهاية المجموعة. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | يدرج نسخة من شريحة المصدر المحددة إلى الموضع المحدد في المجموعة. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | يزيل الظهور الأول لكائن معين من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر في الفهرس المحدد من المجموعة. |
| [toArray()](#toArray--) | ينشئ ويرجع مصفوفة تحتوي على جميع الشرائح. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | ينشئ ويرجع مصفوفة تحتوي على جميع الشرائح من النطاق المحدد. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | ينقل الشريحة من المجموعة إلى الموضع المحدد. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | ينقل الشرائح من المجموعة إلى الموضع المحدد. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | يرجع فهرس الشريحة المحددة في المجموعة. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة مع مراعاة خيارات استيراد PDF. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموضع المحدد. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموضع المحدد. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموضع المحدد. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموضع المحدد. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموضع المحدد. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموضع المحدد. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموضع المحدد. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموضع المحدد. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISlide get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد. للقراءة فقط [ISlide](../../com.aspose.slides/islide).

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[ISlide](../../com.aspose.slides/islide)
### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public abstract ISlide addClone(ISlide sourceSlide)
```

يضيف نسخة من الشريحة المحددة إلى نهاية المجموعة.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة التي سيتم استنساخها.

--------------------

عند استنساخ شريحة بين عروض تقديمية مختلفة يمكن استنساخ رئيس الشريحة أيضًا. يتم استخدام سجل داخلي لتتبع الرؤساء المستنسخين تلقائيًا لمنع إنشاء نسخ متعددة من نفس شريحة الرئيس. لن يتم حظر أو تسجيل الاستنساخ اليدوي لرؤوس الشرائح. إذا كنت تحتاج إلى مزيد من التحكم في عملية الاستنساخ استخدم \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) أو \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) لاستنساخ الشرائح، [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) أو [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) لاستنساخ التخطيطات و[IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) لاستنساخ الرؤوس. |

**الإرجاع:**
[ISlide](../../com.aspose.slides/islide) - شريحة جديدة.
### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public abstract ISlide addClone(ISlide sourceSlide, ISection section)
```

يضيف نسخة من الشريحة المحددة إلى نهاية القسم المحدد.

--------------------

> ```
> IPresentation presentation = new Presentation();
>  try
>  {
>      presentation.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 50, 300, 100);
>      presentation.getSections().addSection("Section 1", presentation.getSlides().get_Item(0));
>      
>      ISection section2 = presentation.getSections().appendEmptySection("Section 2");
>      presentation.getSlides().addClone(presentation.getSlides().get_Item(0), section2);
>      
>      // الآن يحتوي القسم الثاني على نسخة من الشريحة الأولى.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة التي سيتم استنساخها. |
| section | [ISection](../../com.aspose.slides/isection) | القسم للشريحة الجديدة. |

**الإرجاع:**
[ISlide](../../com.aspose.slides/islide) - شريحة جديدة.
### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

يدرج نسخة من الشريحة المحددة إلى الموضع المحدد في المجموعة.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الشريحة الجديدة. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة التي سيتم استنساخها.

--------------------

عند استنساخ شريحة بين عروض تقديمية مختلفة يمكن استنساخ رئيس الشريحة أيضًا. يتم استخدام سجل داخلي لتتبع الرؤساء المستنسخين تلقائيًا لمنع إنشاء نسخ متعددة من نفس شريحة الرئيس. لن يتم حظر أو تسجيل الاستنساخ اليدوي لرؤوس الشرائح. إذا كنت تحتاج إلى مزيد من التحكم في عملية الاستنساخ استخدم \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) أو \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) لاستنساخ الشرائح و[IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) لاستنساخ الرؤوس. |

**الإرجاع:**
[ISlide](../../com.aspose.slides/islide) - الشريحة المدخلة.
### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addEmptySlide(ILayoutSlide layout)
```

يضيف شريحة فارغة جديدة إلى نهاية المجموعة.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | التخطيط للشريحة. |

**الإرجاع:**
[ISlide](../../com.aspose.slides/islide) - الشريحة المضافة.
### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

يدرج نسخة من الشريحة المحددة إلى الموضع المحدد في المجموعة.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الشريحة الجديدة. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | التخطيط للشريحة. |

**الإرجاع:**
[ISlide](../../com.aspose.slides/islide) - الشريحة المدخلة.
### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

يضيف نسخة من الشريحة المحددة إلى نهاية المجموعة.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة التي سيتم استنساخها. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | تخطيط الشريحة للشريحة الجديدة. |

**الإرجاع:**
[ISlide](../../com.aspose.slides/islide) - شريحة جديدة.
### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

يدرج نسخة من الشريحة المحددة إلى الموضع المحدد في المجموعة.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الشريحة الجديدة. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة التي سيتم استنساخها. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | تخطيط الشريحة للشريحة الجديدة. |

**الإرجاع:**
[ISlide](../../com.aspose.slides/islide) - الشريحة المدخلة.
### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

يضيف نسخة من شريحة المصدر المحددة إلى نهاية المجموعة. سيتم اختيار التخطيط المناسب تلقائيًا من الرئيس المحدد (التخطيط المناسب هو التخطيط الذي يحمل نفس النوع أو الاسم كتخطيط شريحة المصدر). إذا لم يكن هناك تخطيط مناسب فسيتم استنساخ تخطيط شريحة المصدر (إذا كان allowCloneMissingLayout صحيحًا) أو سيتم طرح استثناء PptxEditException (إذا كان allowCloneMissingLayout خاطئًا).

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة التي سيتم استنساخها. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | شريحة الرئيس للشريحة الجديدة. |
| allowCloneMissingLayout | boolean | إذا لم يكن هناك تخطيط مناسب في الرئيس المحدد فسيتم استنساخ تخطيط شريحة المصدر (إذا كان allowCloneMissingLayout صحيحًا) أو سيتم طرح استثناء PptxEditException (إذا كان allowCloneMissingLayout خاطئًا). |

**الإرجاع:**
[ISlide](../../com.aspose.slides/islide) - شريحة جديدة.
### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

يدرج نسخة من شريحة المصدر المحددة إلى الموضع المحدد في المجموعة. سيتم اختيار التخطيط المناسب تلقائيًا من الرئيس المحدد (التخطيط المناسب هو التخطيط الذي يحمل نفس النوع أو الاسم كتخطيط شريحة المصدر). إذا لم يكن هناك تخطيط مناسب فسيتم استنساخ تخطيط شريحة المصدر (إذا كان allowCloneMissingLayout صحيحًا) أو سيتم طرح استثناء PptxEditException (إذا كان allowCloneMissingLayout خاطئًا).

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الشريحة الجديدة. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة التي سيتم استنساخها. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | شريحة الرئيس للشريحة الجديدة. |
| allowCloneMissingLayout | boolean | إذا لم يكن هناك تخطيط مناسب في الرئيس المحدد فسيتم استنساخ تخطيط شريحة المصدر (إذا كان allowCloneMissingLayout صحيحًا) أو سيتم طرح استثناء PptxEditException (إذا كان allowCloneMissingLayout خاطئًا). |

**الإرجاع:**
[ISlide](../../com.aspose.slides/islide) - الشريحة المدخلة.
### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

يزيل الظهور الأول لكائن معين من المجموعة.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | الشريحة التي سيتم إزالتها من المجموعة. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل العنصر في الفهرس المحدد من المجموعة.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر الذي سيتم إزالته. |

### toArray() {#toArray--}
```
public abstract ISlide[] toArray()
```

ينشئ ويرجع مصفوفة تحتوي على جميع الشرائح.

**الإرجاع:**
com.aspose.slides.ISlide[] - مجموعة من [ISlide](../../com.aspose.slides/islide)
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract ISlide[] toArray(int startIndex, int count)
```

ينشئ ويرجع مصفوفة تحتوي على جميع الشرائح من النطاق المحدد.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| startIndex | int | فهرس الشريحة الأولى لإضافتها. |
| count | int | عدد الشرائح التي سيتم إضافتها. |

**الإرجاع:**
com.aspose.slides.ISlide[] - مجموعة من [ISlide](../../com.aspose.slides/islide)
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public abstract void reorder(int index, ISlide slide)
```

ينقل الشريحة من المجموعة إلى الموضع المحدد.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الهدف. |
| slide | [ISlide](../../com.aspose.slides/islide) | الشريحة التي سيتم نقلها. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public abstract void reorder(int index, ISlide[] slides)
```

ينقل الشرائح من المجموعة إلى الموضع المحدد. سيتم وضع الشرائح بدءًا من الفهرس بالترتيب الذي تظهر به في القائمة.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الهدف. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | الشرائح التي سيتم نقلها. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public abstract int indexOf(ISlide slide)
```

يرجع فهرس الشريحة المحددة في المجموعة.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | الشريحة التي سيتم البحث عنها. |

**الإرجاع:**
int - فهرس الشريحة أو -1 إذا لم تكن الشريحة من هذه المجموعة.
### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public abstract ISlide[] addFromPdf(String path)
```

ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة.

--------------------

> ```
> مثال:
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getSlides().addFromPdf("document.pdf");
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | java.lang.String | مسار مستند PDF |

**الإرجاع:**
com.aspose.slides.ISlide[] - الشرائح المضافة
### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة مع مراعاة خيارات استيراد PDF.

--------------------

> ```
> مثال:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
>      pres.getSlides().addFromPdf("document.pdf", pdfImportOptions);
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | java.lang.String | مسار مستند PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | خيارات استيراد PDF |

**الإرجاع:**
com.aspose.slides.ISlide[] - الشرائح المضافة
### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
> 
>      FileInputStream stream = new FileInputStream("document.pdf");
>      pres.getSlides().addFromPdf(stream, pdfImportOptions);
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pdfStream | java.io.InputStream | تدفق سيُستخدم كمصدر لمستند PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | خيارات استيراد PDF |

**الإرجاع:**
com.aspose.slides.ISlide[] - الشرائح المضافة
### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
```

ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة.

--------------------

> ```
> مثال:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream stream = new FileInputStream("document.pdf");
>      pres.getSlides().addFromPdf(stream);
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pdfStream | java.io.InputStream | تدفق سيُستخدم كمصدر لمستند PDF |

**الإرجاع:**
com.aspose.slides.ISlide[] - الشرائح المضافة
### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| htmlText | java.lang.String | HTML للإضافة. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null فستُهمل جميع الكائنات الخارجية. |
| uri | java.lang.String | URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |

**الإرجاع:**
com.aspose.slides.ISlide[] - الشرائح المضافة.
### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
```

ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| htmlText | java.lang.String | HTML للإضافة. |

**الإرجاع:**
com.aspose.slides.ISlide[] - الشرائح المضافة
### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| htmlStream | java.io.InputStream | كائن تدفق سيُستخدم كمصدر لملف HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null فستُهمل جميع الكائنات الخارجية. |
| uri | java.lang.String | URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |

**الإرجاع:**
com.aspose.slides.ISlide[] - الشرائح المضافة.
### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```

ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| htmlStream | java.io.InputStream | كائن تدفق سيُستخدم كمصدر لملف HTML. |

**الإرجاع:**
com.aspose.slides.ISlide[] - الشرائح المضافة
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموضع المحدد.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | الموضع للإدراج. |
| htmlText | java.lang.String | HTML للإضافة. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null فستُهمل جميع الكائنات الخارجية. |
| uri | java.lang.String | URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |

**الإرجاع:**
com.aspose.slides.ISlide[] - الشرائح المضافة.
### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```

ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموضع المحدد.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | الموضع للإدراج. |
| htmlText | java.lang.String | HTML للإضافة. |

**الإرجاع:**
com.aspose.slides.ISlide[] - الشرائح المضافة
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموضع المحدد.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | الموضع للإدراج. |
| htmlStream | java.io.InputStream | كائن تدفق سيُستخدم كمصدر لملف HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null فستُهمل جميع الكائنات الخارجية. |
| uri | java.lang.String | URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |

**الإرجاع:**
com.aspose.slides.ISlide[] - الشرائح المضافة.
### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموضع المحدد.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | الموضع للإدراج. |
| htmlStream | java.io.InputStream | كائن تدفق سيُستخدم كمصدر لملف HTML. |

**الإرجاع:**
com.aspose.slides.ISlide[] - الشرائح المضافة
### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموضع المحدد.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | الموضع للإدراج. |
| htmlText | java.lang.String | HTML للإضافة. |
| useSlideWithIndexAsStart | boolean | تحدد هذه الإشارة كيفية بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد. إذا كان **true**، سيبدأ إدخال البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد. إذا كان **false**، ستُضاف البيانات إلى الشرائح التي تم إنشاؤها. |

**الإرجاع:**
com.aspose.slides.ISlide[] - الشرائح المضافة
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموضع المحدد.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | الموضع للإدراج. |
| htmlText | java.lang.String | HTML للإضافة. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null فستُهمل جميع الكائنات الخارجية. |
| uri | java.lang.String | URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |
| useSlideWithIndexAsStart | boolean | تحدد هذه الإشارة كيفية بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد. إذا كان **true**، سيبدأ إدخال البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد. إذا كان **false**، ستُضاف البيانات إلى الشرائح التي تم إنشاؤها. |

**الإرجاع:**
com.aspose.slides.ISlide[] - الشرائح المضافة.
### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموضع المحدد.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | الموضع للإدراج. |
| htmlStream | java.io.InputStream | كائن تدفق سيُستخدم كمصدر لملف HTML. |
| useSlideWithIndexAsStart | boolean | تحدد هذه الإشارة كيفية بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد. إذا كان **true**، سيبدأ إدخال البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد. إذا كان **false**، ستُضاف البيانات إلى الشرائح التي تم إنشاؤها. |

**الإرجاع:**
com.aspose.slides.ISlide[] - الشرائح المضافة
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموضع المحدد.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | الموضع للإدراج. |
| htmlStream | java.io.InputStream | كائن تدفق سيُستخدم كمصدر لملف HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null فستُهمل جميع الكائنات الخارجية. |
| uri | java.lang.String | URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |
| useSlideWithIndexAsStart | boolean | تحدد هذه الإشارة كيفية بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد. إذا كان **true**، سيبدأ إدخال البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد. إذا كان **false**، ستُضاف البيانات إلى الشرائح التي تم إنشاؤها. |

**الإرجاع:**
com.aspose.slides.ISlide[] - الشرائح المضافة.