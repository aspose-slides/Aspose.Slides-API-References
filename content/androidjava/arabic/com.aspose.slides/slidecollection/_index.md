---
title: SlideCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل مجموعة من الشرائح.
type: docs
url: /ar/com.aspose.slides/slidecollection/
---
**الوراثة:**  
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**  
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)  
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

يمثل مجموعة من الشرائح.

## الطرق

| الدالة | الوصف |
| --- | --- |
| [size()](#size--) | يحصل على عدد العناصر الموجودة فعليًا في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر عند الفهرس المحدد. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | يضيف نسخة من شريحة محددة إلى نهاية المجموعة. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | يضيف نسخة من شريحة محددة إلى نهاية القسم المحدد. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | يدرج نسخة من شريحة محددة إلى الموضع المحدد في المجموعة. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | يضيف شريحة فارغة جديدة إلى نهاية المجموعة. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | يدرج نسخة من شريحة محددة إلى الموضع المحدد في المجموعة. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | يضيف نسخة من شريحة محددة إلى نهاية المجموعة. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | يدرج نسخة من شريحة محددة إلى الموضع المحدد في المجموعة. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | يضيف نسخة من شريحة مصدر محددة إلى نهاية المجموعة. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | يدرج نسخة من شريحة مصدر محددة إلى الموضع المحدد في المجموعة. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | يزيل الظهور الأول لكائن محدد من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر عند الفهرس المحدد في المجموعة. |
| [iterator()](#iterator--) | يرجع عدّادًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع مكرِّر جافا للمجموعة بأكملها. |
| [toArray()](#toArray--) | ينشئ ويعيد مصفوفة تحتوي على جميع الشرائح. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | ينشئ ويعيد مصفوفة تحتوي على جميع الشرائح من النطاق المحدد. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | ينقل شريحة من المجموعة إلى الموضع المحدد. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | ينقل الشرائح من المجموعة إلى الموضع المحدد. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | يرجع فهرس الشريحة المحددة في المجموعة. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة مع مراعاة خيارات استيراد PDF. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن من الخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يرجع جذر المزامنة. |

### size() {#size--}
```
public final int size()
```

يحصل على عدد العناصر الموجودة فعليًا في المجموعة. قراءة فقط int.

**الإرجاع:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

يحصل على العنصر عند الفهرس المحدد. قراءة فقط [Slide](../../com.aspose.slides/slide).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**  
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```

يضيف نسخة من شريحة محددة إلى نهاية المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة التي سيتم نسخها. |

--------------------

عند نسخ شريحة بين عروض تقديمية مختلفة يمكن أيضًا نسخ ماستر الشريحة. يتم استخدام سجل داخلي لتتبع ماسترات النسخ تلقائيًا لمنع إنشاء نسخ متعددة من ماستر الشريحة نفسه. لن يتم منع أو تسجيل النسخ اليدوي للماسترات. إذا كنت بحاجة إلى مزيد من التحكم في عملية النسخ استخدم \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) أو \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) لنسخ الشرائح، [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) أو [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) لنسخ التخطيطات و[IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) لنسخ الماسترات. 

**الإرجاع:**  
[ISlide](../../com.aspose.slides/islide) - شريحة جديدة.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
```

يضيف نسخة من شريحة محددة إلى نهاية القسم المحدد.

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة التي سيتم نسخها. |
| section | [ISection](../../com.aspose.slides/isection) | القسم للشريحة الجديدة. |

**الإرجاع:**  
[ISlide](../../com.aspose.slides/islide) - شريحة جديدة.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

يدرج نسخة من شريحة محددة إلى الموضع المحدد في المجموعة.

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // إنشاء فئة Presentation التي تمثل ملف عرض تقديمي
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // استنساخ الشريحة المطلوبة إلى نهاية مجموعة الشرائح في نفس العرض التقديمي
>      ISlideCollection slds = pres.getSlides();
>      // استنساخ الشريحة المطلوبة إلى الفهرس المحدد في نفس العرض التقديمي
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // كتابة العرض التقديمي المعدل إلى القرص
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // إنشاء فئة Presentation لتحميل ملف العرض التقديمي المصدر
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // إنشاء فئة Presentation للملف PPTX الوجهة (حيث سيتم استنساخ الشريحة)
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // كتابة العرض التقديمي الوجهة إلى القرص
>          destPres.save("Aspose2_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الشريحة الجديدة. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة التي سيتم نسخها. |

--------------------

عند نسخ شريحة بين عروض تقديمية مختلفة يمكن أيضًا نسخ ماستر الشريحة. يتم استخدام سجل داخلي لتتبع ماسترات النسخ تلقائيًا لمنع إنشاء نسخ متعددة من ماستر الشريحة نفسه. لن يتم منع أو تسجيل النسخ اليدوي للماسترات. إذا كنت بحاجة إلى مزيد من التحكم في عملية النسخ استخدم \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) أو \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) لنسخ الشرائح و[IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) لنسخ الماسترات. 

**الإرجاع:**  
[ISlide](../../com.aspose.slides/islide) - الشريحة التي تم إدراجها.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

يضيف شريحة فارغة جديدة إلى نهاية المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | التخطيط للشريحة. |

**الإرجاع:**  
[ISlide](../../com.aspose.slides/islide) - الشريحة المضافة.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

يدرج نسخة من شريحة محددة إلى الموضع المحدد في المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الشريحة الجديدة. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | التخطيط للشريحة. |

**الإرجاع:**  
[ISlide](../../com.aspose.slides/islide) - الشريحة التي تم إدراجها.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

يضيف نسخة من شريحة محددة إلى نهاية المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة التي سيتم نسخها. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | تخطيط الشريحة للشريحة الجديدة. |

**الإرجاع:**  
[ISlide](../../com.aspose.slides/islide) - شريحة جديدة.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

يدرج نسخة من شريحة محددة إلى الموضع المحدد في المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الشريحة الجديدة. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة التي سيتم نسخها. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | تخطيط الشريحة للشريحة الجديدة. |

**الإرجاع:**  
[ISlide](../../com.aspose.slides/islide) - الشريحة التي تم إدراجها.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

يضيف نسخة من شريحة مصدر محددة إلى نهاية المجموعة. سيتم اختيار التخطيط المناسب تلقائيًا من الماستر المحدد (التخطيط المناسب هو التخطيط الذي يحمل نفس Type أو Name لتخطيط الشريحة المصدر). إذا لم يكن هناك تخطيط مناسب فسيتم نسخ تخطيط الشريحة المصدر (إذا كان allowCloneMissingLayout true) أو سيتم إلقاء استثناء PptxEditException (إذا كان allowCloneMissingLayout false).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة التي سيتم نسخها. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | ماستر الشريحة للشرائح الجديدة. |
| allowCloneMissingLayout | boolean | إذا لم يكن هناك تخطيط مناسب في الماستر المحدد فسيتم نسخ تخطيط الشريحة المصدر (إذا كان allowCloneMissingLayout true) أو سيتم إلقاء استثناء PptxEditException (إذا كان allowCloneMissingLayout false). |

**الإرجاع:**  
[ISlide](../../com.aspose.slides/islide) - شريحة جديدة.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

يدرج نسخة من شريحة مصدر محددة إلى الموضع المحدد في المجموعة. سيتم اختيار التخطيط المناسب تلقائيًا من الماستر المحدد (التخطيط المناسب هو التخطيط الذي يحمل نفس Type أو Name لتخطيط الشريحة المصدر). إذا لم يكن هناك تخطيط مناسب فسيتم نسخ تخطيط الشريحة المصدر (إذا كان allowCloneMissingLayout true) أو سيتم إلقاء استثناء PptxEditException (إذا كان allowCloneMissingLayout false).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الشريحة الجديدة. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة التي سيتم نسخها. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | ماستر الشريحة للشرائح الجديدة. |
| allowCloneMissingLayout | boolean | إذا لم يكن هناك تخطيط مناسب في الماستر المحدد فسيتم نسخ تخطيط الشريحة المصدر (إذا كان allowCloneMissingLayout true) أو سيتم إلقاء استثناء PptxEditException (إذا كان allowCloneMissingLayout false). |

**الإرجاع:**  
[ISlide](../../com.aspose.slides/islide) - الشريحة التي تم إدراجها.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

يزيل الظهور الأول لكائن محدد من المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | الشريحة التي سيتم إزالتها من المجموعة. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل العنصر عند الفهرس المحدد في المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر المراد إزالته. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

يرجع عدّادًا يتنقل عبر المجموعة.

**الإرجاع:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

يرجع مكرِّر جافا للمجموعة بأكملها.

**الإرجاع:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - java.util.Iterator للمجموعة بأكملها.

### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

ينشئ ويعيد مصفوفة تحتوي على جميع الشرائح.

**الإرجاع:**  
com.aspose.slides.ISlide[] - مصفوفة من [Slide](../../com.aspose.slides/slide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

ينشئ ويعيد مصفوفة تحتوي على جميع الشرائح من النطاق المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| startIndex | int | فهرس أول شريحة لإضافتها. |
| count | int | عدد الشرائح المراد إضافتها. |

**الإرجاع:**  
com.aspose.slides.ISlide[] - مصفوفة من [Slide](../../com.aspose.slides/slide)

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

ينقل شريحة من المجموعة إلى الموضع المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الهدف. |
| slide | [ISlide](../../com.aspose.slides/islide) | الشريحة التي سيتم نقلها. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

ينقل الشرائح من المجموعة إلى الموضع المحدد. سيتم وضع الشرائح بدءًا من الفهرس وترتيب ظهورها في القائمة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الهدف. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | الشرائح التي سيتم نقلها. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```

يرجع فهرس الشريحة المحددة في المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | الشريحة التي سيتم البحث عنها. |

**الإرجاع:**  
int - فهرس الشريحة أو -1 إذا لم تكن الشريحة من هذه المجموعة.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```

ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getSlides().addFromPdf("document.pdf");
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | java.lang.String | مسار مستند PDF |

**الإرجاع:**  
com.aspose.slides.ISlide[] - الشرائح المضافة

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة مع مراعاة خيارات استيراد PDF.

--------------------

> ```
> Example:
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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | java.lang.String | مسار مستند PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | خيارات استيراد PDF |

**الإرجاع:**  
com.aspose.slides.ISlide[] - الشرائح المضافة

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```

ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة.

--------------------

> ```
> Example:
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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pdfStream | java.io.InputStream | تدفق سيُستخدم كمصدر لمستند PDF |

**الإرجاع:**  
com.aspose.slides.ISlide[] - الشرائح المضافة

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pdfStream | java.io.InputStream | تدفق سيُستخدم كمصدر لمستند PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | خيارات استيراد PDF |

**الإرجاع:**  
com.aspose.slides.ISlide[] - الشرائح المضافة

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| htmlText | java.lang.String | HTML للإضافة. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null سيتم تجاهل جميع الكائنات الخارجية. |
| uri | java.lang.String | URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |

**الإرجاع:**  
com.aspose.slides.ISlide[] - الشرائح المضافة.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| htmlText | java.lang.String | HTML للإضافة. |

**الإرجاع:**  
com.aspose.slides.ISlide[] - الشرائح المضافة

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| htmlStream | java.io.InputStream | كائن تدفق سيُستخدم كمصدر لملف HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null سيتم تجاهل جميع الكائنات الخارجية. |
| uri | java.lang.String | URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |

**الإرجاع:**  
com.aspose.slides.ISlide[] - الشرائح المضافة.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة.

--------------------

> ```
> // إنشاء مثال من فئة Presentation.
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("file.html");
>          // استدعاء طريقة AddFromHtml وتمرير ملف HTML.
>          pres.getSlides().addFromHtml(fos);
>          // استخدام طريقة Save لحفظ الملف كوثيقة PowerPoint.
>          pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| htmlStream | java.io.InputStream | كائن تدفق سيُستخدم كمصدر لملف HTML. |

**الإرجاع:**  
com.aspose.slides.ISlide[] - الشرائح المضافة

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الموضع للإدراج. |
| htmlText | java.lang.String | HTML للإضافة. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null سيتم تجاهل جميع الكائنات الخارجية. |
| uri | java.lang.String | URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |

**الإرجاع:**  
com.aspose.slides.ISlide[] - الشرائح المضافة.

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الموضع للإدراج. |
| htmlText | java.lang.String | HTML للإضافة. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null سيتم تجاهل جميع الكائنات الخارجية. |
| uri | java.lang.String | URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |
| useSlideWithIndexAsStart | boolean | تحدد هذه العلامة طريقة بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد. إذا كان **true**، سيبدأ إدخال البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد. إذا كان **false**، ستُضاف البيانات إلى الشرائح المنشأة. |

**الإرجاع:**  
com.aspose.slides.ISSlide[] - الشرائح المضافة.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الموضع للإدراج. |
| htmlText | java.lang.String | HTML للإضافة. |

**الإرجاع:**  
com.aspose.slides.ISSlide[] - الشرائح المضافة

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الموضع للإدراج. |
| htmlText | java.lang.String | HTML للإضافة. |
| useSlideWithIndexAsStart | boolean | تحدد هذه العلامة طريقة بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد. إذا كان **true**، سيبدأ إدخال البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد. إذا كان **false**، ستُضاف البيانات إلى الشرائح المنشأة. |

**الإرجاع:**  
com.aspose.slides.ISSlide[] - الشرائح المضافة

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الموضع للإدراج. |
| htmlStream | java.io.InputStream | كائن تدفق سيُستخدم كمصدر لملف HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null سيتم تجاهل جميع الكائنات الخارجية. |
| uri | java.lang.String | URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |

**الإرجاع:**  
com.aspose.slides.ISSlide[] - الشرائح المضافة.

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الموضع للإدراج. |
| htmlStream | java.io.InputStream | كائن تدفق سيُستخدم كمصدر لملف HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null سيتم تجاهل جميع الكائنات الخارجية. |
| uri | java.lang.String | URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |
| useSlideWithIndexAsStart | boolean | تحدد هذه العلامة طريقة بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد. إذا كان **true**، سيبدأ إدخال البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد. إذا كان **false**، ستُضاف البيانات إلى الشرائح المنشأة. |

**الإرجاع:**  
com.aspose.slides.ISSlide[] - الشرائح المضافة.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الموضع للإدراج. |
| htmlStream | java.io.InputStream | كائن تدفق سيُستخدم كمصدر لملف HTML. |

**الإرجاع:**  
com.aspose.slides.ISSlide[] - الشرائح المضافة

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الموضع للإدراج. |
| htmlStream | java.io.InputStream | كائن تدفق سيُستخدم كمصدر لملف HTML. |
| useSlideWithIndexAsStart | boolean | تحدد هذه العلامة طريقة بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد. إذا كان **true**، سيبدأ إدخال البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد. إذا كان **false**، ستُضاف البيانات إلى الشرائح المنشأة. |

**الإرجاع:**  
com.aspose.slides.ISSlide[] - الشرائح المضافة

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف. |
| index | int | الفهرس الابتدائي في المصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن من الخيوط). قراءة فقط boolean.

**الإرجاع:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يرجع جذر المزامنة. قراءة فقط Object.

**الإرجاع:**  
java.lang.Object