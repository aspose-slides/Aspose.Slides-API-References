---
title: SlideCollection
second_title: مرجع API الخاص بـ Aspose.Slides للـ Java
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

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | يحصل على عدد العناصر الموجودة فعليًا في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | يضيف نسخة من شريحة محددة إلى نهاية المجموعة. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | يضيف نسخة من شريحة محددة إلى نهاية القسم المحدد. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | يُدرج نسخة من شريحة محددة إلى الموقع المحدد في المجموعة. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | يضيف شريحة فارغة جديدة إلى نهاية المجموعة. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | يُدرج نسخة من شريحة محددة إلى الموقع المحدد في المجموعة. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | يضيف نسخة من شريحة محددة إلى نهاية المجموعة. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | يُدرج نسخة من شريحة محددة إلى الموقع المحدد في المجموعة. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | يضيف نسخة من شريحة مصدر محددة إلى نهاية المجموعة. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | يُدرج نسخة من شريحة مصدر محددة إلى الموقع المحدد في المجموعة. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | يزيل أول تكرار لكائن محدد من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر في الفهرس المحدد من المجموعة. |
| [iterator()](#iterator--) | يعيد عدادًا (enumerator) يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مُكرّر (iterator) جافا للمجموعة بالكامل. |
| [toArray()](#toArray--) | ينشئ ويعيد مصفوفة تحتوي على جميع الشرائح. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | ينشئ ويعيد مصفوفة تحتوي على جميع الشرائح من النطاق المحدد. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | ينقل شريحة من المجموعة إلى الموقع المحدد. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | ينقل الشرائح من المجموعة إلى الموقع المحدد. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | يعيد فهرس الشريحة المحددة في المجموعة. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة مع مراعاة خيارات استيراد PDF. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموقع المحدد. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموقع المحدد. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموقع المحدد. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموقع المحدد. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموقع المحدد. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموقع المحدد. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموقع المحدد. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموقع المحدد. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يعيد جذر التزامن. |

### size() {#size--}
```
public final int size()
```

يحصل على عدد العناصر الموجودة فعليًا في المجموعة. للقراءة فقط int.

**الإرجاع:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد. للقراءة فقط [Slide](../../com.aspose.slides/slide).

**المعلمات:**
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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة المراد استنساخها. |

--------------------

عند استنساخ شريحة بين عروض تقديمية مختلفة يمكن أيضًا استنساخ ماستر الشريحة. يتم استخدام سجل داخلي لتتبع ماسترات المستنسخة تلقائيًا لمنع إنشاء نسخ متعددة من نفس شريحة الماستر. لا يتم منع أو تسجيل الاستنساخ اليدوي لشرائح الماستر. إذا كنت بحاجة إلى مزيد من التحكم في عملية الاستنساخ استخدم \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) أو \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) لاستنساخ الشرائح، [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) أو [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) لاستنساخ التخطيطات و [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) لاستنساخ الماسترات. |

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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة المراد استنساخها. |
| section | [ISection](../../com.aspose.slides/isection) | القسم لشريحة جديدة. |

**الإرجاع:**  
[ISlide](../../com.aspose.slides/islide) - شريحة جديدة.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

يُدرج نسخة من شريحة محددة إلى الموقع المحدد في المجموعة.

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


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الشريحة الجديدة. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة المراد استنساخها. |

عند استنساخ شريحة بين عروض تقديمية مختلفة يمكن أيضًا استنساخ ماستر الشريحة. يتم استخدام سجل داخلي لتتبع الماسترات المستنسخة تلقائيًا لمنع إنشاء نسخ متعددة من نفس شريحة الماستر. لا يتم منع أو تسجيل الاستنساخ اليدوي لشرائح الماستر. إذا كنت بحاجة إلى مزيد من التحكم في عملية الاستنساخ استخدم \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) أو \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) لاستنساخ الشرائح و [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) لاستنساخ الماسترات. |

**الإرجاع:**  
[ISlide](../../com.aspose.slides/islide) - الشريحة المدخلة.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

يضيف شريحة فارغة جديدة إلى نهاية المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | تخطيط للشريحة. |

**الإرجاع:**  
[ISlide](../../com.aspose.slides/islide) - الشريحة المضافة.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

يُدرج نسخة من شريحة محددة إلى الموقع المحدد في المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الشريحة الجديدة. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | تخطيط للشريحة. |

**الإرجاع:**  
[ISlide](../../com.aspose.slides/islide) - الشريحة المدخلة.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

يضيف نسخة من شريحة محددة إلى نهاية المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة المراد استنساخها. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | تخطيط الشريحة لشريحة جديدة. |

**الإرجاع:**  
[ISlide](../../com.aspose.slides/islide) - شريحة جديدة.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

يُدرج نسخة من شريحة محددة إلى الموقع المحدد في المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الشريحة الجديدة. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة المراد استنساخها. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | تخطيط الشريحة لشريحة جديدة. |

**الإرجاع:**  
[ISlide](../../com.aspose.slides/islide) - الشريحة المدخلة.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

يضيف نسخة من شريحة مصدر محددة إلى نهاية المجموعة. سيتم اختيار التخطيط المناسب تلقائيًا من الماستر المحدد (التخطيط المناسب هو التخطيط الذي يحمل نفس النوع أو الاسم لتخطيط الشريحة المصدر). إذا لم يكن هناك تخطيط مناسب فسيتم استنساخ تخطيط الشريحة المصدر (إذا كان allowCloneMissingLayout صحيحًا) أو سيتم طرح استثناء PptxEditException (إذا كان allowCloneMissingLayout خاطئًا).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة المراد استنساخها. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | ماستر الشريحة لشريحة جديدة. |
| allowCloneMissingLayout | boolean | إذا لم يكن هناك تخطيط مناسب في الماستر المحدد فسيتم استنساخ تخطيط الشريحة المصدر (إذا كان allowCloneMissingLayout صحيحًا) أو سيتم طرح استثناء PptxEditException (إذا كان allowCloneMissingLayout خاطئًا). |

**الإرجاع:**  
[ISlide](../../com.aspose.slides/islide) - شريحة جديدة.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

يُدرج نسخة من شريحة مصدر محددة إلى الموقع المحدد في المجموعة. سيتم اختيار التخطيط المناسب تلقائيًا من الماستر المحدد (التخطيط المناسب هو التخطيط الذي يحمل نفس النوع أو الاسم لتخطيط الشريحة المصدر). إذا لم يكن هناك تخطيط مناسب فسيتم استنساخ تخطيط الشريحة المصدر (إذا كان allowCloneMissingLayout صحيحًا) أو سيتم طرح استثناء PptxEditException (إذا كان allowCloneMissingLayout خاطئًا).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الشريحة الجديدة. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة المراد استنساخها. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | ماستر الشريحة لشريحة جديدة. |
| allowCloneMissingLayout | boolean | إذا لم يكن هناك تخطيط مناسب في الماستر المحدد فسيتم استنساخ تخطيط الشريحة المصدر (إذا كان allowCloneMissingLayout صحيحًا) أو سيتم طرح استثناء PptxEditException (إذا كان allowCloneMissingLayout خاطئًا). |

**الإرجاع:**  
[ISlide](../../com.aspose.slides/islide) - الشريحة المدخلة.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

يزيل أول تكرار لكائن محدد من المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | الشريحة التي سيتم إزالتها من المجموعة. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل العنصر في الفهرس المحدد من المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر المراد إزالته. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

يعيد عدادًا (enumerator) يتنقل عبر المجموعة.

**الإرجاع:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - يمكن استخدامه للتنقل عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

يعيد مُكرّر جافا للمجموعة بالكامل.

**الإرجاع:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - java.util.Iterator لتصفح المجموعة بالكامل.

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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| startIndex | int | فهرس أول شريحة للإضافة. |
| count | int | عدد الشرائح للإضافة. |

**الإرجاع:**  
com.aspose.slides.ISlide[] - مصفوفة من [Slide](../../com.aspose.slides/slide)
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

ينقل الشريحة من التجميع إلى الموضع المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الهدف. |
| slide | [ISlide](../../com.aspose.slides/islide) | الشريحة التي سيتم نقلها. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

ينقل الشرائح من التجميع إلى الموضع المحدد. ستوضع الشرائح بدءًا من الفهرس وفقًا للترتيب الذي تظهر به في القائمة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الهدف. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | الشرائح التي سيتم نقلها. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```

يعيد فهرس الشريحة المحددة في التجميع.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | الشريحة المراد العثور عليها. |

**القيمة المرجعة:**  
int - فهرس الشريحة أو -1 إذا لم تكن الشريحة من هذا التجميع.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```

ينشئ شرائح من مستند PDF ويضيفها إلى نهاية التجميع.

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


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | java.lang.String | مسار إلى مستند PDF |

**القيمة المرجعة:**  
com.aspose.slides.ISlide[] - الشرائح المضافة

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

ينشئ شرائح من مستند PDF ويضيفها إلى نهاية التجميع مع مراعاة خيارات استيراد PDF.

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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | java.lang.String | مسار إلى مستند PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | خيارات استيراد PDF |

**القيمة المرجعة:**  
com.aspose.slides.ISlide[] - الشرائح المضافة

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```

ينشئ شرائح من مستند PDF ويضيفها إلى نهاية التجميع.

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


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pdfStream | java.io.InputStream | تدفق سيُستخدم كمصدر لمستند PDF |

**القيمة المرجعة:**  
com.aspose.slides.ISlide[] - الشرائح المضافة

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

ينشئ شرائح من مستند PDF ويضيفها إلى نهاية التجميع.

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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pdfStream | java.io.InputStream | تدفق سيُستخدم كمصدر لمستند PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | خيارات استيراد PDF |

**القيمة المرجعة:**  
com.aspose.slides.ISlide[] - الشرائح المضافة

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

ينشئ شرائح من نص HTML ويضيفها إلى نهاية التجميع.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| htmlText | java.lang.String | HTML للإضافة. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | كائن استدعاء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل فارغًا (null) سيتم تجاهل جميع الكائنات الخارجية. |
| uri | java.lang.String | عنوان URI للـHTML المحدد. يُستخدم لحل الروابط النسبية. |

**القيمة المرجعة:**  
com.aspose.slides.ISlide[] - الشرائح المضافة.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

ينشئ شرائح من نص HTML ويضيفها إلى نهاية التجميع.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| htmlText | java.lang.String | HTML للإضافة. |

**القيمة المرجعة:**  
com.aspose.slides.ISlide[] - الشرائح المضافة

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

ينشئ شرائح من نص HTML ويضيفها إلى نهاية التجميع.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| htmlStream | java.io.InputStream | كائن تدفق يُستخدم كمصدر لملف HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | كائن استدعاء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل فارغًا (null) سيتم تجاهل جميع الكائنات الخارجية. |
| uri | java.lang.String | عنوان URI للـHTML المحدد. يُستخدم لحل الروابط النسبية. |

**القيمة المرجعة:**  
com.aspose.slides.ISlide[] - الشرائح المضافة.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

ينشئ شرائح من نص HTML ويضيفها إلى نهاية التجميع.

--------------------

> ```
> // إنشاء كائن من فئة Presentation.
>  Presentation pres = new Presentation();
>  try {
>      String html = new String(Files.readAllBytes(Paths.get("file.html")));
>      // استدعاء طريقة AddFromHtml وتمرير ملف HTML.
>      pres.getSlides().addFromHtml(html);
>      // استخدام طريقة Save لحفظ الملف كوثيقة PowerPoint.
>      pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| htmlStream | java.io.InputStream | كائن تدفق يُستخدم كمصدر لملف HTML. |

**القيمة المرجعة:**  
com.aspose.slides.ISlide[] - الشرائح المضافة

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

ينشئ شرائح من نص HTML ويُدخلها إلى التجميع في الموضع المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الموضع للإدراج. |
| htmlText | java.lang.String | HTML للإضافة. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | كائن استدعاء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل فارغًا (null) سيتم تجاهل جميع الكائنات الخارجية. |
| uri | java.lang.String | عنوان URI للـHTML المحدد. يُستخدم لحل الروابط النسبية. |

**القيمة المرجعة:**  
com.aspose.slides.ISlide[] - الشرائح المضافة.

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

ينشئ شرائح من نص HTML ويُدخلها إلى التجميع في الموضع المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الموضع للإدراج. |
| htmlText | java.lang.String | HTML للإضافة. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | كائن استدعاء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل فارغًا (null) سيتم تجاهل جميع الكائنات الخارجية. |
| uri | java.lang.String | عنوان URI للـHTML المحدد. يُستخدم لحل الروابط النسبية. |
| useSlideWithIndexAsStart | boolean | هذا العلم يحدد كيفية بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد. إذا كان **true**، فسيبدأ إدراج البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد. إذا كان **false**، فسيتم إضافة البيانات إلى الشرائح المُنشأة. |

**القيمة المرجعة:**  
com.aspose.slides.ISlide[] - الشرائح المضافة.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

ينشئ شرائح من نص HTML ويُدخلها إلى التجميع في الموضع المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الموضع للإدراج. |
| htmlText | java.lang.String | HTML للإضافة. |

**القيمة المرجعة:**  
com.aspose.slides.ISlide[] - الشرائح المضافة

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

ينشئ شرائح من نص HTML ويُدخلها إلى التجميع في الموضع المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الموضع للإدراج. |
| htmlText | java.lang.String | HTML للإضافة. |
| useSlideWithIndexAsStart | boolean | هذا العلم يحدد كيفية بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد. إذا كان **true**، فسيبدأ إدراج البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد. إذا كان **false**، فسيتم إضافة البيانات إلى الشرائح المُنشأة. |

**القيمة المرجعة:**  
com.aspose.slides.ISlide[] - الشرائح المضافة.

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

ينشئ شرائح من نص HTML ويُدخلها إلى التجميع في الموضع المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الموضع للإدراج. |
| htmlStream | java.io.InputStream | كائن تدفق يُستخدم كمصدر لملف HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | كائن استدعاء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل فارغًا (null) سيتم تجاهل جميع الكائنات الخارجية. |
| uri | java.lang.String | عنوان URI للـHTML المحدد. يُستخدم لحل الروابط النسبية. |

**القيمة المرجعة:**  
com.aspose.slides.ISlide[] - الشرائح المضافة.

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

ينشئ شرائح من نص HTML ويُدخلها إلى التجميع في الموضع المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الموضع للإدراج. |
| htmlStream | java.io.InputStream | كائن تدفق يُستخدم كمصدر لملف HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | كائن استدعاء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل فارغًا (null) سيتم تجاهل جميع الكائنات الخارجية. |
| uri | java.lang.String | عنوان URI للـHTML المحدد. يُستخدم لحل الروابط النسبية. |
| useSlideWithIndexAsStart | boolean | هذا العلم يحدد كيفية بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد. إذا كان **true**، فسيبدأ إدراج البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد. إذا كان **false**، فسيتم إضافة البيانات إلى الشرائح المُنشأة. |

**القيمة المرجعة:**  
com.aspose.slides.ISlide[] - الشرائح المضافة.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

ينشئ شرائح من نص HTML ويُدخلها إلى التجميع في الموضع المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الموضع للإدراج. |
| htmlStream | java.io.InputStream | كائن تدفق يُستخدم كمصدر لملف HTML. |

**القيمة المرجعة:**  
com.aspose.slides.ISlide[] - الشرائح المضافة

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

ينشئ شرائح من نص HTML ويُدخلها إلى التجميع في الموضع المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الموضع للإدراج. |
| htmlStream | java.io.InputStream | كائن تدفق يُستخدم كمصدر لملف HTML. |
| useSlideWithIndexAsStart | boolean | هذا العلم يحدد كيفية بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد. إذا كان **true**، فسيبدأ إدراج البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد. إذا كان **false**، فسيتم إضافة البيانات إلى الشرائح المُنشأة. |

**القيمة المرجعة:**  
com.aspose.slides.ISlide[] - الشرائح المضافة.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من التجميع إلى المصفوفة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف. |
| index | int | الفهرس الابتدائي في المصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يعيد قيمة تشير إلى ما إذا كان الوصول إلى التجميع متزامنًا (آمن للقراءة المتعددة). قيمة منطقية للقراءة فقط.

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يعيد جذر المزامنة. كائن للقراءة فقط.