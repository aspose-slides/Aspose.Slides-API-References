---
title: SlideCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش یک مجموعه از اسلایدها.
type: docs
url: /fa/com.aspose.slides/slidecollection/
---
**ارث‌برداری:**  
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)  
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

نمایش یک مجموعه از اسلایدها.

## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد عناصری که واقعاً در مجموعه موجود هستند را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | عنصر مورد نظر را در ایندکس مشخص‌شده برمی‌گرداند. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | یک نسخه از اسلاید مشخص‌شده را به انتهای مجموعه اضافه می‌کند. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | یک نسخه از اسلاید مشخص‌شده را به انتهای بخش مشخص‌شده اضافه می‌کند. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | یک نسخه از اسلاید مشخص‌شده را در موقعیت مشخص‌شده‌ی مجموعه وارد می‌کند. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | یک اسلاید خالی جدید به انتهای مجموعه اضافه می‌کند. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | یک نسخه از اسلاید مشخص‌شده را در موقعیت مشخص‌شده‌ی مجموعه وارد می‌کند. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | یک نسخه از اسلاید مشخص‌شده را به انتهای مجموعه اضافه می‌کند. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | یک نسخه از اسلاید مشخص‌شده را در موقعیت مشخص‌شده‌ی مجموعه وارد می‌کند. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | یک نسخه از اسلاید منبع مشخص‌شده را به انتهای مجموعه اضافه می‌کند. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | یک نسخه از اسلاید منبع مشخص‌شده را در موقعیت مشخص‌شده‌ی مجموعه وارد می‌کند. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصر در ایندکس مشخص‌شده‌ی مجموعه را حذف می‌کند. |
| [iterator()](#iterator--) | یک enumerator برمی‌گرداند که از طریق مجموعه پیمایش می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |
| [toArray()](#toArray--) | یک آرایه شامل تمام اسلایدها ایجاد و برمی‌گرداند. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | یک آرایه شامل تمام اسلایدهای بازهٔ مشخص‌شده ایجاد و برمی‌گرداند. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | اسلاید را از مجموعه به موقعیت مشخص‌شده انتقال می‌دهد. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | اسلایدها را از مجموعه به موقعیت مشخص‌شده انتقال می‌دهد. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | ایندکس اسلاید مشخص‌شده را در مجموعه برمی‌گرداند. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند، به‌همین‌که گزینه‌های واردات PDF را در نظر می‌گیرد. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایهٔ مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقدار نشان‌دهنده این‌که دسترسی به مجموعه همزمانی (Thread-Safe) است را برمی‌گرداند. |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همزمانی را برمی‌گرداند. |

### size() {#size--}
```
public final int size()
```

تعداد عناصری که واقعاً در مجموعه موجود هستند را برمی‌گرداند. فقط‌خواندنی int.

**بازگرداندن:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

عنصر مورد نظر را در ایندکس مشخص‌شده برمی‌گرداند. فقط‌خواندنی [Slide](../../com.aspose.slides/slide).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگرداندن:**  
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```

یک نسخه از اسلاید مشخص‌شده را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلاید برای تکثیر. |

--------------------

هنگام کلون کردن یک اسلاید بین ارائه‌های مختلف، مستر اسلاید نیز می‌تواند کلون شود. سامانهٔ داخلی برای ردیابی مسترهای کلون‌شده به‌صورت خودکار استفاده می‌شود تا از ایجاد چندین کلون از همان مستر اسلاید جلوگیری شود. کلون کردن دستی مستر اسلایدها نه جلوگیری می‌شود و نه ثبت می‌شود. اگر به کنترل بیشتری بر فرآیند کلون کردن نیاز دارید از `#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide)` یا `#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean)` برای کلون اسلایدها، [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) یا [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) برای کلون لایه‌ها و [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) برای کلون مسترها استفاده کنید.

**بازگرداندن:**  
[ISlide](../../com.aspose.slides/islide) - اسلاید جدید.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
```

یک نسخه از اسلاید مشخص‌شده را به انتهای بخش مشخص‌شده اضافه می‌کند.

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
>      // اکنون بخش دوم شامل یک کپی از اسلاید اول است.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلاید برای تکثیر. |
| section | [ISection](../../com.aspose.slides/isection) | بخش برای اسلاید جدید. |

**بازگرداندن:**  
[ISlide](../../com.aspose.slides/islide) - اسلاید جدید.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

یک نسخه از اسلاید مشخص‌شده را در موقعیت مشخص‌شده‌ی مجموعه وارد می‌کند.

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // ایجاد یک شی از کلاس Presentation که یک فایل ارائه را نشان می‌دهد
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // کپی اسلاید مورد نظر به انتهای مجموعه اسلایدها در همان ارائه
>      ISlideCollection slds = pres.getSlides();
>      // کپی اسلاید مورد نظر به ایندکس مشخص‌شده در همان ارائه
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // نوشتن ارائه‌ی اصلاح‌شده به دیسک
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // ایجاد یک شی از کلاس Presentation برای بارگذاری فایل ارائه منبع
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // ایجاد یک شی از کلاس Presentation برای فایل PPTX مقصد (جایی که اسلاید باید کپی شود)
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // نوشتن ارائه مقصد به دیسک
>          destPres.save("Aspose2_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس اسلاید جدید. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلاید برای تکثیر. |

--------------------

هنگام کلون کردن یک اسلاید بین ارائه‌های مختلف، مستر اسلاید نیز می‌تواند کلون شود. سامانهٔ داخلی برای ردیابی مسترهای کلون‌شده به‌صورت خودکار استفاده می‌شود تا از ایجاد چندین کلون از همان مستر اسلاید جلوگیری شود. کلون کردن دستی مستر اسلایدها نه جلوگیری می‌شود و نه ثبت می‌شود. اگر به کنترل بیشتری بر فرآیند کلون کردن نیاز دارید از `#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide)` یا `#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean)` برای کلون اسلایدها و [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) برای کلون مسترها استفاده کنید.

**بازگرداندن:**  
[ISlide](../../com.aspose.slides/islide) - اسلاید وارد‌شده.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

یک اسلاید خالی جدید به انتهای مجموعه اضافه می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | لایه برای اسلاید. |

**بازگرداندن:**  
[ISlide](../../com.aspose.slides/islide) - اسلاید اضافه‌شده.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

یک نسخه از اسلاید مشخص‌شده را در موقعیت مشخص‌شده‌ی مجموعه وارد می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس اسلاید جدید. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | لایه برای اسلاید. |

**بازگرداندن:**  
[ISlide](../../com.aspose.slides/islide) - اسلاید وارد‌شده.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

یک نسخه از اسلاید مشخص‌شده را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلاید برای تکثیر. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | لایه اسلاید برای اسلاید جدید. |

**بازگرداندن:**  
[ISlide](../../com.aspose.slides/islide) - اسلاید جدید.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

یک نسخه از اسلاید مشخص‌شده را در موقعیت مشخص‌شده‌ی مجموعه وارد می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس اسلاید جدید. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلاید برای تکثیر. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | لایه اسلاید برای اسلاید جدید. |

**بازگرداندن:**  
[ISlide](../../com.aspose.slides/islide) - اسلاید وارد‌شده.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

یک نسخه از اسلاید منبع مشخص‌شده را به انتهای مجموعه اضافه می‌کند. لایهٔ مناسب به‌صورت خودکار از مستر مشخص‌شده انتخاب می‌شود (لایهٔ مناسب همان لایه‌ای است که همان Type یا Name لایهٔ اسلاید منبع را دارد). اگر لایهٔ مناسب وجود نداشته باشد، لایهٔ اسلاید منبع کلون می‌شود (اگر allowCloneMissingLayout برابر true باشد) یا یک PptxEditException پرتاب می‌شود (اگر برابر false باشد).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلاید برای تکثیر. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | مستر اسلاید برای اسلاید جدید. |
| allowCloneMissingLayout | boolean | اگر در مستر مشخص‌شده لایهٔ مناسبی وجود نداشته باشد، لایهٔ اسلاید منبع کلون می‌شود (اگر true باشد) یا یک PptxEditException پرتاب می‌شود (اگر false باشد). |

**بازگرداندن:**  
[ISlide](../../com.aspose.slides/islide) - اسلاید جدید.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

یک نسخه از اسلاید منبع مشخص‌شده را در موقعیت مشخص‌شده‌ی مجموعه وارد می‌کند. لایهٔ مناسب به‌صورت خودکار از مستر مشخص‌شده انتخاب می‌شود (لایهٔ مناسب همان لایه‌ای است که همان Type یا Name لایهٔ اسلاید منبع را دارد). اگر لایهٔ مناسب وجود نداشته باشد، لایهٔ اسلاید منبع کلون می‌شود (اگر allowCloneMissingLayout برابر true باشد) یا یک PptxEditException پرتاب می‌شود (اگر برابر false باشد).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس اسلاید جدید. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلاید برای تکثیر. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | مستر اسلاید برای اسلاید جدید. |
| allowCloneMissingLayout | boolean | اگر در مستر مشخص‌شده لایهٔ مناسبی وجود نداشته باشد، لایهٔ اسلاید منبع کلون می‌شود (اگر true باشد) یا یک PptxEditException پرتاب می‌شود (اگر false باشد). |

**بازگرداندن:**  
[ISlide](../../com.aspose.slides/islide) - اسلاید وارد‌شده.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | اسلایدی که باید از مجموعه حذف شود. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

عنصر در ایندکس مشخص‌شده‌ی مجموعه را حذف می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفرپهلو عنصر مورد حذف. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

یک enumerator برمی‌گرداند که از طریق مجموعه پیمایش می‌کند.

**بازگرداندن:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - یک IGenericEnumerator که برای پیمایش مجموعه می‌توان از آن استفاده کرد.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**بازگرداندن:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - یک java.util.Iterator برای کل مجموعه.

### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

یک آرایه شامل تمام اسلایدها ایجاد و برمی‌گرداند.

**بازگرداندن:**  
com.aspose.slides.ISlide[] - آرایه‌ای از [Slide](../../com.aspose.slides/slide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

یک آرایه شامل تمام اسلایدهای بازهٔ مشخص‌شده ایجاد و برمی‌گرداند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | int | ایندکس اولین اسلاید برای اضافه کردن. |
| count | int | تعداد اسلایدهایی که باید اضافه شوند. |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - آرایه‌ای از [Slide](../../com.aspose.slides/slide)

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

اسلاید را از مجموعه به موقعیت مشخص‌شده انتقال می‌دهد.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس هدف. |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلایدی که باید منتقل شود. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

اسلایدها را از مجموعه به موقعیت مشخص‌شده انتقال می‌دهد. اسلایدها از ایندکس هدف به ترتیب ظاهر شدن در لیست قرار می‌گیرند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس هدف. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | اسلایدهایی که باید منتقل شوند. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```

ایندکس اسلاید مشخص‌شده را در مجموعه برمی‌گرداند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلایدی که باید جستجو شود. |

**بازگرداندن:**  
int - ایندکس اسلاید یا -1 اگر اسلاید از این مجموعه نباشد.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```

اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند.

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

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | java.lang.String | مسیر به سند PDF |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند، به‌همین‌که گزینه‌های واردات PDF را در نظر می‌گیرد.

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

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | java.lang.String | مسیر به سند PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | گزینه‌های واردات PDF |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```

اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند.

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

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pdfStream | java.io.InputStream | جریان ورودی که به‌عنوان منبع سند PDF استفاده می‌شود. |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند.

--------------------

> ```
> مثال:
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

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pdfStream | java.io.InputStream | جریان ورودی که به‌عنوان منبع سند PDF استفاده می‌شود. |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | گزینه‌های واردات PDF |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| htmlText | java.lang.String | HTML برای اضافه کردن. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | شیء callback برای دریافت اشیاء خارجی. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | java.lang.String | URI مربوط به HTML مشخص‌شده. برای حل لینک‌های نسبی استفاده می‌شود. |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| htmlText | java.lang.String | HTML برای اضافه کردن. |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| htmlStream | java.io.InputStream | شیء Stream که به‌عنوان منبع فایل HTML استفاده می‌شود. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | شیء callback برای دریافت اشیاء خارجی. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | java.lang.String | URI مربوط به HTML مشخص‌شده. برای حل لینک‌های نسبی استفاده می‌شود. |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند.

--------------------

> ```
> // یک نمونه از کلاس Presentation ایجاد کنید.
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("file.html");
>          // متد AddFromHtml را صدا بزنید و فایل HTML را پاس کنید.
>          pres.getSlides().addFromHtml(fos);
>          // از متد Save برای ذخیرهٔ فایل به‌عنوان سند PowerPoint استفاده کنید.
>          pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| htmlStream | java.io.InputStream | شیء Stream که به‌عنوان منبع فایل HTML استفاده می‌شود. |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیتی که باید وارد شود. |
| htmlText | java.lang.String | HTML برای اضافه کردن. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | شیء callback برای دریافت اشیاء خارجی. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | java.lang.String | URI مربوط به HTML مشخص‌شده. برای حل لینک‌های نسبی استفاده می‌شود. |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده.

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیتی که باید وارد شود. |
| htmlText | java.lang.String | HTML برای اضافه کردن. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | شیء callback برای دریافت اشیاء خارجی. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | java.lang.String | URI مربوط به HTML مشخص‌شده. برای حل لینک‌های نسبی استفاده می‌شود. |
| useSlideWithIndexAsStart | boolean | این پرچم تعیین می‌کند که درج از اسلاید جدید شروع شود یا از اسلاید با ایندکس مشخص‌شده. اگر **true** باشد، درج داده‌ها از فضای خالی در اسلاید با ایندکس مشخص‌شده شروع می‌شود؛ اگر **false** باشد، داده‌ها به اسلایدهای ساخته‌شده اضافه می‌شوند. |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیتی که باید وارد شود. |
| htmlText | java.lang.String | HTML برای اضافه کردن. |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده.

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیتی که باید وارد شود. |
| htmlText | java.lang.String | HTML برای اضافه کردن. |
| useSlideWithIndexAsStart | boolean | این پرچم تعیین می‌کند که درج از اسلاید جدید شروع شود یا از اسلاید با ایندکس مشخص‌شده. اگر **true** باشد، درج داده‌ها از فضای خالی در اسلاید با ایندکس مشخص‌شده شروع می‌شود؛ اگر **false** باشد، داده‌ها به اسلایدهای ساخته‌شده اضافه می‌شوند. |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده.

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیتی که باید وارد شود. |
| htmlStream | java.io.InputStream | شیء Stream که به‌عنوان منبع فایل HTML استفاده می‌شود. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | شیء callback برای دریافت اشیاء خارجی. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | java.lang.String | URI مربوط به HTML مشخص‌شده. برای حل لینک‌های نسبی استفاده می‌شود. |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده.

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیتی که باید وارد شود. |
| htmlStream | java.io.InputStream | شیء Stream که به‌عنوان منبع فایل HTML استفاده می‌شود. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | شیء callback برای دریافت اشیاء خارجی. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | java.lang.String | URI مربوط به HTML مشخص‌شده. برای حل لینک‌های نسبی استفاده می‌شود. |
| useSlideWithIndexAsStart | boolean | این پرچم تعیین می‌کند که درج از اسلاید جدید شروع شود یا از اسلاید با ایندکس مشخص‌شده. اگر **true** باشد، درج داده‌ها از فضای خالی در اسلاید با ایندکس مشخص‌شده شروع می‌شود؛ اگر **false** باشد، داده‌ها به اسلایدهای ساخته‌شده اضافه می‌شوند. |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیتی که باید وارد شود. |
| htmlStream | java.io.InputStream | شیء Stream که به‌عنوان منبع فایل HTML استفاده می‌شود. |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه وارد می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیتی که باید وارد شود. |
| htmlStream | java.io.InputStream | شیء Stream که به‌عنوان منبع فایل HTML استفاده می‌شود. |
| useSlideWithIndexAsStart | boolean | این پرچم تعیین می‌کند که درج از اسلاید جدید شروع شود یا از اسلاید با ایندکس مشخص‌شده. اگر **true** باشد، درج داده‌ها از فضای خالی در اسلاید با ایندکس مشخص‌شده شروع می‌شود؛ اگر **false** باشد، داده‌ها به اسلایدهای ساخته‌شده اضافه می‌شوند. |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر را از مجموعه به آرایهٔ مشخص‌شده کپی می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف. |
| index | int | ایندکس شروع در آرایه هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همزمانی (Thread-Safe) است یا نه. فقط‌خواندنی boolean.

**بازگرداندن:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشهٔ همزمانی را برمی‌گرداند. فقط‌خواندنی Object.

**بازگرداندن:**  
java.lang.Object