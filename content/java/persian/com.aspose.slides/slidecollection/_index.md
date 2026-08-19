---
title: SlideCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر مجموعه‌ای از اسلایدها است.
type: docs
url: /fa/com.aspose.slides/slidecollection/
---
**ارث‌بری:**  
java.lang.Object, com.aspose.slides.DomObject

**تمام اینترفیس‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)  
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

نمایندهٔ مجموعه‌ای از اسلایدها است.

## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد عناصری را که واقعاً در مجموعه موجود هستند برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | عنصر موجود در ایندکس مشخص را برمی‌گرداند. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | یک کپی از اسلاید مشخص را به انتهای مجموعه اضافه می‌کند. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | یک کپی از اسلاید مشخص را به انتهای بخش مشخص شده اضافه می‌کند. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | یک کپی از اسلاید مشخص را در موقعیت مشخص شده از مجموعه وارد می‌کند. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | یک اسلاید خالی جدید را به انتهای مجموعه اضافه می‌کند. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | یک کپی از اسلاید مشخص را در موقعیت مشخص شده از مجموعه وارد می‌کند. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | یک کپی از اسلاید مشخص را به انتهای مجموعه اضافه می‌کند. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | یک کپی از اسلاید مشخص را در موقعیت مشخص شده از مجموعه وارد می‌کند. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | یک کپی از اسلاید منبع مشخص را به انتهای مجموعه اضافه می‌کند. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | یک کپی از اسلاید منبع مشخص را در موقعیت مشخص شده از مجموعه وارد می‌کند. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصر موجود در ایندکس مشخص شده را از مجموعه حذف می‌کند. |
| [iterator()](#iterator--) | یک enumerator که از مجموعه عبور می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |
| [toArray()](#toArray--) | یک آرایه شامل تمام اسلایدها ایجاد و برمی‌گرداند. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | یک آرایه شامل تمام اسلایدهای بازهٔ مشخص‌شده ایجاد و برمی‌گرداند. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | اسلاید را از مجموعه به موقعیت مشخص انتقال می‌دهد. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | اسلایدها را از مجموعه به موقعیت مشخص انتقال می‌دهد. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | ایندکس اسلاید مشخص شده در مجموعه را برمی‌گرداند. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | اسلایدها را از سند PDF ایجاد کرده و با در نظر گرفتن گزینه‌های واردات PDF به انتهای مجموعه اضافه می‌کند. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص شده به مجموعه وارد می‌کند. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص شده به مجموعه وارد می‌کند. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص شده به مجموعه وارد می‌کند. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص شده به مجموعه وارد می‌کند. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص شده به مجموعه وارد می‌کند. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص شده به مجموعه وارد می‌کند. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص شده به مجموعه وارد می‌کند. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص شده به مجموعه وارد می‌کند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایهٔ مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقدار نشان‌دهنده این که دسترسی به مجموعه همزمان (thread-safe) است یا خیر را برمی‌گرداند. |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همزمانی را برمی‌گرداند. |

### size() {#size--}
```
public final int size()
```

تعداد عناصری را که واقعاً در مجموعه موجود هستند برمی‌گرداند. فقط-خواندنی int.

**بازگشت:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

عنصر موجود در ایندکس مشخص را برمی‌گرداند. فقط-خواندنی [Slide](../../com.aspose.slides/slide).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**  
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```

یک کپی از اسلاید مشخص را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلایدی که باید کلون شود. |

--------------------

هنگام کلون کردن اسلاید بین ارائه‌های مختلف، master اسلاید نیز می‌تواند کلون شود. یک رجیستری داخلی برای ردیابی خودکار master‌های کلون‌شده استفاده می‌شود تا از ایجاد چندین کلون از همان master جلوگیری شود. کلون دستی master‌ها نه منع می‌شود و نه ثبت می‌شود. اگر به کنترل بیشتری بر فرآیند کلون نیاز دارید از \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) یا \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) برای کلون اسلایدها، [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) یا [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) برای کلون لایه‌ها و [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) برای کلون master‌ها استفاده کنید. |

**بازگشت:**  
[ISlide](../../com.aspose.slides/islide) - اسلاید جدید.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
```

یک کپی از اسلاید مشخص را به انتهای بخش مشخص شده اضافه می‌کند.

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
>      // اکنون بخش دوم شامل یک نسخه از اسلاید اول است.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلایدی که باید کلون شود. |
| section | [ISection](../../com.aspose.slides/isection) | بخش برای اسلاید جدید. |

**بازگشت:**  
[ISlide](../../com.aspose.slides/islide) - اسلاید جدید.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

یک کپی از اسلاید مشخص را در موقعیت مشخص شده از مجموعه وارد می‌کند.

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // نمونه سازی کلاس Presentation که نمایانگر یک فایل ارائه است
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // کپی اسلاید مورد نظر به انتهای مجموعه اسلایدها در همان ارائه
>      ISlideCollection slds = pres.getSlides();
>      // کپی اسلاید مورد نظر به اندیس مشخص شده در همان ارائه
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // نوشتن ارائهٔ اصلاح‌شده به دیسک
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // نمونه سازی کلاس Presentation برای بارگذاری فایل ارائه منبع
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // نمونه سازی کلاس Presentation برای فایل PPTX مقصد (جایی که اسلاید باید کپی شود)
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
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلایدی که باید کلون شود. |

--------------------

هنگام کلون کردن اسلاید بین ارائه‌های مختلف، master اسلاید نیز می‌تواند کلون شود. یک رجیستری داخلی برای ردیابی خودکار master‌های کلون‌شده استفاده می‌شود تا از ایجاد چندین کلون از همان master جلوگیری شود. کلون دستی master‌ها نه منع می‌شود و نه ثبت می‌شود. اگر به کنترل بیشتری بر فرآیند کلون نیاز دارید از \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) یا \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) برای کلون اسلایدها و [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) برای کلون master‌ها استفاده کنید. |

**بازگشت:**  
[ISlide](../../com.aspose.slides/islide) - اسلاید وارد‌شده.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

یک اسلاید خالی جدید را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | لایه برای اسلاید. |

**بازگشت:**  
[ISlide](../../com.aspose.slides/islide) - اسلاید اضافه‌شده.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

یک کپی از اسلاید مشخص را در موقعیت مشخص شده از مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس اسلاید جدید. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | لایه برای اسلاید. |

**بازگشت:**  
[ISlide](../../com.aspose.slides/islide) - اسلاید وارد‌شده.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

یک کپی از اسلاید مشخص را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلایدی که باید کلون شود. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | لایه اسلاید برای اسلاید جدید. |

**بازگشت:**  
[ISlide](../../com.aspose.slides/islide) - اسلاید جدید.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

یک کپی از اسلاید مشخص را در موقعیت مشخص شده از مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس اسلاید جدید. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلایدی که باید کلون شود. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | لایه اسلاید برای اسلاید جدید. |

**بازگشت:**  
[ISlide](../../com.aspose.slides/islide) - اسلاید وارد‌شده.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

یک کپی از اسلاید منبع مشخص را به انتهای مجموعه اضافه می‌کند. لایوت مناسب به‌صورت خودکار از master مشخص شده انتخاب می‌شود (لایوت مناسب همان لایوتی است که Type یا Name مشابه لایوت اسلاید منبع داشته باشد). اگر لایوت مناسبی وجود نداشته باشد، لایوت اسلاید منبع کلون می‌شود (اگر allowCloneMissingLayout برابر true باشد) یا استثنای PptxEditException پرتاب می‌شود (اگر برابر false باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلایدی که باید کلون شود. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | master اسلاید برای اسلاید جدید. |
| allowCloneMissingLayout | boolean | اگر در master مشخص شده لایوت مناسبی وجود نداشته باشد، لایوت اسلاید منبع کلون می‌شود (اگر true باشد) یا PptxEditException پرتاب می‌شود (اگر false باشد). |

**بازگشت:**  
[ISlide](../../com.aspose.slides/islide) - اسلاید جدید.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

یک کپی از اسلاید منبع مشخص را در موقعیت مشخص شده از مجموعه وارد می‌کند. لایوت مناسب به‌صورت خودکار از master مشخص شده انتخاب می‌شود (لایوت مناسب همان لایوتی است که Type یا Name مشابه لایوت اسلاید منبع داشته باشد). اگر لایوت مناسبی وجود نداشته باشد، لایوت اسلاید منبع کلون می‌شود (اگر allowCloneMissingLayout برابر true باشد) یا استثنای PptxEditException پرتاب می‌شود (اگر برابر false باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس اسلاید جدید. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلایدی که باید کلون شود. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | master اسلاید برای اسلاید جدید. |
| allowCloneMissingLayout | boolean | اگر در master مشخص شده لایوت مناسبی وجود نداشته باشد، لایوت اسلاید منبع کلون می‌شود (اگر true باشد) یا PptxEditException پرتاب می‌شود (اگر false باشد). |

**بازگشت:**  
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

عنصر موجود در ایندکس مشخص شده را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-پایهٔ عنصری که باید حذف شود. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

یک enumerator که از مجموعه عبور می‌کند را برمی‌گرداند.

**بازگشت:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - یک IGenericEnumerator که می‌تواند برای عبور از مجموعه استفاده شود.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**بازگشت:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - یک java.util.Iterator برای کل مجموعه.

### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

یک آرایه شامل تمام اسلایدها ایجاد و برمی‌گرداند.

**بازگشت:**  
com.aspose.slides.ISlide[] - آرایه‌ای از [Slide](../../com.aspose.slides/slide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

یک آرایه شامل تمام اسلایدهای بازهٔ مشخص‌شده ایجاد و برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | int | ایندکس اولین اسلایدی که باید اضافه شود. |
| count | int | تعداد اسلایدهایی که باید اضافه شوند. |

**بازگشت:**  
com.aspose.slides.ISlide[] - آرایه‌ای از [Slide](../../com.aspose.slides/slide)
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

اسلاید را از مجموعه به موقعیت مشخص شده جابه‌جا می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس هدف. |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلاید برای جابه‌جایی. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

اسلایدها را از مجموعه به موقعیت مشخص شده جابه‌جا می‌کند. اسلایدها از اندیس شروع شده و به ترتیب ظاهر شدن در لیست قرار می‌گیرند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس هدف. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | اسلایدها برای جابه‌جایی. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISSlide-}
```
public final int indexOf(ISlide slide)
```

یک اندیس از اسلاید مشخص‌شده در مجموعه را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلاید برای جستجو. |

**بازگشت:**
int - اندیس یک اسلاید یا -1 اگر اسلاید از این مجموعه نباشد.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```

اسلایدها را از سند PDF ایجاد می‌کند و به انتهای مجموعه اضافه می‌کند.

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

**بازگشت:**
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

اسلایدها را از سند PDF ایجاد می‌کند و با در نظر گرفتن گزینه‌های وارد کردن PDF، به انتهای مجموعه اضافه می‌کند.

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
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | گزینه‌های وارد کردن PDF |

**بازگشت:**
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```

اسلایدها را از سند PDF ایجاد می‌کند و به انتهای مجموعه اضافه می‌کند.

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


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pdfStream | java.io.InputStream | جریانی که به‌عنوان منبع سند PDF استفاده می‌شود. |

**بازگشت:**
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

اسلایدها را از سند PDF ایجاد می‌کند و به انتهای مجموعه اضافه می‌کند.

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pdfStream | java.io.InputStream | جریانی که به‌عنوان منبع سند PDF استفاده می‌شود. |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | گزینه‌های وارد کردن PDF |

**بازگشت:**
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| htmlText | java.lang.String | HTML برای اضافه کردن. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | شیء بازگشتی برای دریافت اشیاء خارجی. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | java.lang.String | یک URI از HTML مشخص‌شده. برای حل لینک‌های نسبی استفاده می‌شود. |

**بازگشت:**
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| htmlText | java.lang.String | HTML برای اضافه کردن. |

**بازگشت:**
com.aspose.slides.ISSlide[] - اسلایدهای اضافه‌شده

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| htmlStream | java.io.InputStream | جریانی که به‌عنوان منبع فایل HTML استفاده می‌شود. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | شیء بازگشتی برای دریافت اشیاء خارجی. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | java.lang.String | یک URI از HTML مشخص‌شده. برای حل لینک‌های نسبی استفاده می‌شود. |

**بازگشت:**
com.aspose.slides.ISSlide[] - اسلایدهای اضافه‌شده.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌کند.

--------------------

> ```
> // یک نمونه از کلاس Presentation ایجاد کنید.
>  Presentation pres = new Presentation();
>  try {
>      String html = new String(Files.readAllBytes(Paths.get("file.html")));
>      // متد AddFromHtml را فراخوانی کنید و فایل HTML را پاس دهید.
>      pres.getSlides().addFromHtml(html);
>      // از متد Save برای ذخیره فایل به عنوان سند PowerPoint استفاده کنید.
>      pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| htmlStream | java.io.InputStream | جریانی که به‌عنوان منبع فایل HTML استفاده می‌شود. |

**بازگشت:**
com.aspose.slides.ISSlide[] - اسلایدهای اضافه‌شده

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیت برای وارد کردن. |
| htmlText | java.lang.String | HTML برای اضافه کردن. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | شیء بازگشتی برای دریافت اشیاء خارجی. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | java.lang.String | یک URI از HTML مشخص‌شده. برای حل لینک‌های نسبی استفاده می‌شود. |

**بازگشت:**
com.aspose.slides.ISSlide[] - اسلایدهای اضافه‌شده.

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیت برای وارد کردن. |
| htmlText | java.lang.String | HTML برای اضافه کردن. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | شیء بازگشتی برای دریافت اشیاء خارجی. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | java.lang.String | یک URI از HTML مشخص‌شده. برای حل لینک‌های نسبی استفاده می‌شود. |
| useSlideWithIndexAsStart | boolean | این پرچم تعیین می‌کند که درج از کجا شروع شود: از یک اسلاید جدید یا از اسلاید با اندیس مشخص‌شده. اگر **true** باشد، درج داده‌ها از یک فضای خالی در اسلاید با اندیس مشخص‌شده آغاز می‌شود. اگر **false** باشد، داده‌ها به اسلایدهای ایجاد شده اضافه می‌شوند. |

**بازگشت:**
com.aspose.slides.ISSlide[] - اسلایدهای اضافه‌شده.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیت برای وارد کردن. |
| htmlText | java.lang.String | HTML برای اضافه کردن. |

**بازگشت:**
com.aspose.slides.ISSlide[] - اسلایدهای اضافه‌شده

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیت برای وارد کردن. |
| htmlText | java.lang.String | HTML برای اضافه کردن. |
| useSlideWithIndexAsStart | boolean | این پرچم تعیین می‌کند که درج از کجا شروع شود: از یک اسلاید جدید یا از اسلاید با اندیس مشخص‌شده. اگر **true** باشد، درج داده‌ها از یک فضای خالی در اسلاید با اندیس مشخص‌شده آغاز می‌شود. اگر **false** باشد، داده‌ها به اسلایدهای ایجاد شده اضافه می‌شوند. |

**بازگشت:**
com.aspose.slides.ISSlide[] - اسلایدهای اضافه‌شده.

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیت برای وارد کردن. |
| htmlStream | java.io.InputStream | جریانی که به‌عنوان منبع فایل HTML استفاده می‌شود. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | شیء بازگشتی برای دریافت اشیاء خارجی. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | java.lang.String | یک URI از HTML مشخص‌شده. برای حل لینک‌های نسبی استفاده می‌شود. |

**بازگشت:**
com.aspose.slides.ISSlide[] - اسلایدهای اضافه‌شده.

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیت برای وارد کردن. |
| htmlStream | java.io.InputStream | جریانی که به‌عنوان منبع فایل HTML استفاده می‌شود. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | شیء بازگشتی برای دریافت اشیاء خارجی. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | java.lang.String | یک URI از HTML مشخص‌شده. برای حل لینک‌های نسبی استفاده می‌شود. |
| useSlideWithIndexAsStart | boolean | این پرچم تعیین می‌کند که درج از کجا شروع شود: از یک اسلاید جدید یا از اسلاید با اندیس مشخص‌شده. اگر **true** باشد، درج داده‌ها از یک فضای خالی در اسلاید با اندیس مشخص‌شده آغاز می‌شود. اگر **false** باشد، داده‌ها به اسلایدهای ایجاد شده اضافه می‌شوند. |

**بازگشت:**
com.aspose.slides.ISSlide[] - اسلایدهای اضافه‌شده.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیت برای وارد کردن. |
| htmlStream | java.io.InputStream | جریانی که به‌عنوان منبع فایل HTML استفاده می‌شود. |

**بازگشت:**
com.aspose.slides.ISSlide[] - اسلایدهای اضافه‌شده

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیت برای وارد کردن. |
| htmlStream | java.io.InputStream | جریانی که به‌عنوان منبع فایل HTML استفاده می‌شود. |
| useSlideWithIndexAsStart | boolean | این پرچم تعیین می‌کند که درج از کجا شروع شود: از یک اسلاید جدید یا از اسلاید با اندیس مشخص‌شده. اگر **true** باشد، درج داده‌ها از یک فضای خالی در اسلاید با اندیس مشخص‌شده آغاز می‌شود. اگر **false** باشد، داده‌ها به اسلایدهای ایجاد شده اضافه می‌شوند. |

**بازگشت:**
com.aspose.slides.ISSlide[] - اسلایدهای اضافه‌شده

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر مجموعه را به آرایه مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف. |
| index | int | اندیس شروع در آرایه هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (ایمن برای چندنخی). بولی فقط-خواندنی.

**بازگشت:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشهٔ همگام‌سازی را برمی‌گرداند. شیء فقط-خواندنی.

**بازگشت:**
java.lang.Object