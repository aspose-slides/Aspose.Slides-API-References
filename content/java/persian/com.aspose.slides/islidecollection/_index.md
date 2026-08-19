---
title: ISlideCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایندهٔ مجموعه‌ای از اسلایدها.
type: docs
url: /fa/com.aspose.slides/islidecollection/
---
**تمام رابط‌های پیاده‌سازی شده:**
com.aspose.slides.IGenericCollection
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

نمایش‌دهنده‌ی مجموعه‌ای از اسلایدها.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصر را در اندیس مشخص دریافت می‌کند. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | یک نسخه از اسلاید مشخص را به انتهای مجموعه اضافه می‌کند. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | یک نسخه از اسلاید مشخص را به انتهای مجموعه اضافه می‌کند. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | یک نسخه از اسلاید مشخص را در موقعیت معین مجموعه وارد می‌کند. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | یک اسلاید خالی جدید را به انتهای مجموعه اضافه می‌کند. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | یک نسخه از اسلاید مشخص را در موقعیت معین مجموعه وارد می‌کند. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | یک نسخه از اسلاید مشخص را به انتهای مجموعه اضافه می‌کند. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | یک نسخه از اسلاید مشخص را در موقعیت معین مجموعه وارد می‌کند. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | یک نسخه از اسلاید منبع مشخص را به انتهای مجموعه اضافه می‌کند. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | یک نسخه از اسلاید منبع مشخص را در موقعیت معین مجموعه وارد می‌کند. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصر را در اندیس مشخص از مجموعه حذف می‌کند. |
| [toArray()](#toArray--) | یک آرایه شامل تمام اسلایدها ایجاد و برمی‌گرداند. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | یک آرایه شامل تمام اسلایدهای بازه‌ی مشخص شده ایجاد و برمی‌گرداند. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | اسلاید را از مجموعه به موقعیت مشخص منتقل می‌کند. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | اسلایدها را از مجموعه به موقعیت مشخص منتقل می‌کند. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | اندیس اسلاید مشخص‌شده در مجموعه را برمی‌گرداند. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | اسلایدها را از سند PDF ایجاد کرده و با در نظر گرفتن گزینه‌های واردات PDF به انتهای مجموعه اضافه می‌کند. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص به مجموعه وارد می‌کند. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص به مجموعه وارد می‌کند. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص به مجموعه وارد می‌کند. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص به مجموعه وارد می‌کند. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) **|** اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص به مجموعه وارد می‌کند. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص به مجموعه وارد می‌کند. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص به مجموعه وارد می‌کند. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص به مجموعه وارد می‌کند. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISlide get_Item(int index)
```

عنصر را در اندیس مشخص دریافت می‌کند. فقط-خواندنی [ISlide](../../com.aspose.slides/islide).

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public abstract ISlide addClone(ISlide sourceSlide)
```

یک نسخه از اسلاید مشخص را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلاید برای تکثیر. |

--------------------

هنگام تکثیر یک اسلاید بین ارائه‌های مختلف، مستر اسلاید نیز می‌تواند تکثیر شود. یک رجیستری داخلی برای ردیابی مسترهای تکثیر شده به‌صورت خودکار استفاده می‌شود تا از ایجاد چندین تکثیر از همان مستر اسلاید جلوگیری شود. تکثیر دستی مستر اسلایدها نه جلوگیری می‌شود و نه ثبت می‌شود. اگر به کنترل بیشتری در فرآیند تکثیر نیاز دارید از \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) یا \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) برای تکثیر اسلایدها، [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) یا [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) برای تکثیر لایوت‌ها و [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) برای تکثیر مسترها استفاده کنید.

**بازگشت:**
[ISlide](../../com.aspose.slides/islide) - اسلاید جدید.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public abstract ISlide addClone(ISlide sourceSlide, ISection section)
```

یک نسخه از اسلاید مشخص را به انتهای بخش مشخص شده اضافه می‌کند.

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
>      // اکنون بخش دوم حاوی یک کپی از اسلاید اول است.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلاید برای تکثیر. |
| section | [ISection](../../com.aspose.slides/isection) | بخش برای اسلاید جدید. |

**بازگشت:**
[ISlide](../../com.aspose.slides/islide) - اسلاید جدید.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

یک نسخه از اسلاید مشخص را در موقعیت معین مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| index | int | اندیس اسلاید جدید. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلاید برای تکثیر. |

--------------------

هنگام تکثیر یک اسلاید بین ارائه‌های مختلف، مستر اسلاید نیز می‌تواند تکثیر شود. یک رجیستری داخلی برای ردیابی مسترهای تکثیر شده به‌صورت خودکار استفاده می‌شود تا از ایجاد چندین تکثیر از همان مستر اسلاید جلوگیری شود. تکثیر دستی مستر اسلایدها نه جلوگیری می‌شود و نه ثبت می‌شود. اگر به کنترل بیشتری در فرآیند تکثیر نیاز دارید از \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) یا \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) برای تکثیر اسلایدها و [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) برای تکثیر مسترها استفاده کنید.

**بازگشت:**
[ISlide](../../com.aspose.slides/islide) - اسلاید وارد‌شده.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addEmptySlide(ILayoutSlide layout)
```

یک اسلاید خالی جدید را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | لایوت برای اسلاید. |

**بازگشت:**
[ISlide](../../com.aspose.slides/islide) - اسلاید اضافه‌شده.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

یک نسخه از اسلاید مشخص را در موقعیت معین مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| index | int | اندیس اسلاید جدید. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | لایوت برای اسلاید. |

**بازگشت:**
[ISlide](../../com.aspose.slides/islide) - اسلاید وارد‌شده.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

یک نسخه از اسلاید مشخص را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلاید برای تکثیر. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | لایوت اسلاید برای اسلاید جدید. |

**بازگشت:**
[ISlide](../../com.aspose.slides/islide) - اسلاید جدید.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

یک نسخه از اسلاید مشخص را در موقعیت معین مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| index | int | اندیس اسلاید جدید. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلاید برای تکثیر. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | لایوت اسلاید برای اسلاید جدید. |

**بازگشت:**
[ISlide](../../com.aspose.slides/islide) - اسلاید وارد‌شده.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

یک نسخه از اسلاید منبع مشخص را به انتهای مجموعه اضافه می‌کند. لایوت مناسب به‌صورت خودکار از مستر مشخص شده انتخاب می‌شود (لایوت مناسب همان لایوتی است که نوع یا نام آن با لایوت اسلاید منبع مطابقت دارد). اگر لایوت مناسب وجود نداشته باشد، لایوت اسلاید منبع تکثیر می‌شود (اگر allowCloneMissingLayout برابر true باشد) یا PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout برابر false باشد).

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلاید برای تکثیر. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | مستر اسلاید برای اسلاید جدید. |
| allowCloneMissingLayout | boolean | اگر در مستر مشخص شده لایوت مناسب وجود نداشته باشد، لایوت اسلاید منبع تکثیر می‌شود (اگر این مقدار true باشد) یا PptxEditException پرتاب می‌شود (اگر این مقدار false باشد). |

**بازگشت:**
[ISlide](../../com.aspose.slides/islide) - اسلاید جدید.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

یک نسخه از اسلاید منبع مشخص را در موقعیت معین مجموعه وارد می‌کند. لایوت مناسب به‌صورت خودکار از مستر مشخص شده انتخاب می‌شود (لایوت مناسب همان لایوتی است که نوع یا نام آن با لایوت اسلاید منبع مطابقت دارد). اگر لایوت مناسب وجود نداشته باشد، لایوت اسلاید منبع تکثیر می‌شود (اگر allowCloneMissingLayout برابر true باشد) یا PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout برابر false باشد).

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| index | int | اندیس اسلاید جدید. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلاید برای تکثیر. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | مستر اسلاید برای اسلاید جدید. |
| allowCloneMissingLayout | boolean | اگر در مستر مشخص شده لایوت مناسب وجود نداشته باشد، لایوت اسلاید منبع تکثیر می‌شود (اگر این مقدار true باشد) یا PptxEditException پرتاب می‌شود (اگر این مقدار false باشد). |

**بازگشت:**
[ISlide](../../com.aspose.slides/islide) - اسلاید وارد‌شده.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | اسلایدی که باید از مجموعه حذف شود. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

عنصر را در اندیس مشخص از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| index | int | اندیس صفر-محور عنصر برای حذف. |

### toArray() {#toArray--}
```
public abstract ISlide[] toArray()
```

یک آرایه با تمام اسلایدها در آن ایجاد و برمی‌گرداند.

**بازگشت:**
com.aspose.slides.ISlide[] - آرایه‌ای از [ISlide](../../com.aspose.slides/islide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract ISlide[] toArray(int startIndex, int count)
```

یک آرایه با تمام اسلایدهای بازه‌ی مشخص شده در آن ایجاد و برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| startIndex | int | اندیس اولین اسلاید برای افزودن. |
| count | int | تعداد اسلایدهای برای افزودن. |

**بازگشت:**
com.aspose.slides.ISlide[] - آرایه‌ای از [ISlide](../../com.aspose.slides/islide)

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public abstract void reorder(int index, ISlide slide)
```

اسلاید را از مجموعه به موقعیت مشخص منتقل می‌کند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| index | int | اندیس هدف. |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلاید برای جابه‌جایی. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public abstract void reorder(int index, ISlide[] slides)
```

اسلایدها را از مجموعه به موقعیت مشخص منتقل می‌کند. اسلایدها از اندیس هدف به ترتیب ظاهر شدن در لیست قرار می‌گیرند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| index | int | اندیس هدف. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | اسلایدها برای جابه‌جایی. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public abstract int indexOf(ISlide slide)
```

اندیس اسلاید مشخص‌شده در مجموعه را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلاید برای جستجو. |

**بازگشت:**
int - اندیس اسلاید یا -1 اگر اسلاید متعلق به این مجموعه نباشد.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public abstract ISlide[] addFromPdf(String path)
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
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

اسلایدها را از سند PDF ایجاد می‌کند و آنها را با در نظر گرفتن گزینه‌های وارد کردن PDF به انتهای مجموعه اضافه می‌نماید.

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

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده
### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

اسلایدها را از سند PDF ایجاد می‌کند و آنها را به انتهای مجموعه اضافه می‌نماید.

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
| pdfStream | java.io.InputStream | جریانی که به عنوان منبع سند PDF استفاده می‌شود |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | گزینه‌های وارد کردن PDF |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده
### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
```

اسلایدها را از سند PDF ایجاد می‌کند و آنها را به انتهای مجموعه اضافه می‌نماید.

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
| pdfStream | java.io.InputStream | جریانی که به عنوان منبع سند PDF استفاده می‌شود |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده
### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

اسلایدها را از متن HTML ایجاد می‌کند و آنها را به انتهای مجموعه اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| htmlText | java.lang.String | HTML برای اضافه کردن. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | یک شیٔ فراخوانی بازگشتی که برای دریافت اشیاء خارجی استفاده می‌شود. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | java.lang.String | یک URI از HTML مشخص شده. برای حل لینک‌های نسبی استفاده می‌شود. |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده.
### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
```

اسلایدها را از متن HTML ایجاد می‌کند و آنها را به انتهای مجموعه اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| htmlText | java.lang.String | HTML برای اضافه کردن. |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده
### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

اسلایدها را از متن HTML ایجاد می‌کند و آنها را به انتهای مجموعه اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| htmlStream | java.io.InputStream | یک شیٔ Stream که به عنوان منبع یک فایل HTML استفاده می‌شود. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | یک شیٔ فراخوانی بازگشتی که برای دریافت اشیاء خارجی استفاده می‌شود. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | java.lang.String | یک URI از HTML مشخص شده. برای حل لینک‌های نسبی استفاده می‌شود. |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده.
### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```

اسلایدها را از متن HTML ایجاد می‌کند و آنها را به انتهای مجموعه اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| htmlStream | java.io.InputStream | یک شیٔ Stream که به عنوان منبع یک فایل HTML استفاده می‌شود. |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

اسلایدها را از متن HTML ایجاد می‌کند و آنها را در موقعیت مشخص به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیت برای درج. |
| htmlText | java.lang.String | HTML برای اضافه کردن. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | یک شیٔ فراخوانی بازگشتی که برای دریافت اشیاء خارجی استفاده می‌شود. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | java.lang.String | یک URI از HTML مشخص شده. برای حل لینک‌های نسبی استفاده می‌شود. |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده.
### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```

اسلایدها را از متن HTML ایجاد می‌کند و آنها را در موقعیت مشخص به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیت برای درج. |
| htmlText | java.lang.String | HTML برای اضافه کردن. |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

اسلایدها را از متن HTML ایجاد می‌کند و آنها را در موقعیت مشخص به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیت برای درج. |
| htmlStream | java.io.InputStream | یک شیٔ Stream که به عنوان منبع یک فایل HTML استفاده می‌شود. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | یک شیٔ فراخوانی بازگشتی که برای دریافت اشیاء خارجی استفاده می‌شود. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | java.lang.String | یک URI از HTML مشخص شده. برای حل لینک‌های نسبی استفاده می‌شود. |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده.
### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

اسلایدها را از متن HTML ایجاد می‌کند و آنها را در موقعیت مشخص به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیت برای درج. |
| htmlStream | java.io.InputStream | یک شیٔ Stream که به عنوان منبع یک فایل HTML استفاده می‌شود. |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده
### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

اسلایدها را از متن HTML ایجاد می‌کند و آنها را در موقعیت مشخص به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیت برای درج. |
| htmlText | java.lang.String | HTML برای اضافه کردن. |
| useSlideWithIndexAsStart | boolean | این پرچم تعیین می‌کند که درج چگونه شروع شود: از یک اسلاید جدید یا از اسلایدی با ایندکس مشخص. اگر **true** باشد، درج داده‌ها از یک فضای خالی در اسلاید با ایندکس مشخص شروع می‌شود. اگر **false** باشد، داده‌ها به اسلایدهای ایجادشده اضافه می‌شوند. |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

اسلایدها را از متن HTML ایجاد می‌کند و آنها را در موقعیت مشخص به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیت برای درج. |
| htmlText | java.lang.String | HTML برای اضافه کردن. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | یک شیٔ فراخوانی بازگشتی که برای دریافت اشیاء خارجی استفاده می‌شود. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | java.lang.String | یک URI از HTML مشخص شده. برای حل لینک‌های نسبی استفاده می‌شود. |
| useSlideWithIndexAsStart | boolean | این پرچم تعیین می‌کند که درج چگونه شروع شود: از یک اسلاید جدید یا از اسلایدی با ایندکس مشخص. اگر **true** باشد، درج داده‌ها از یک فضای خالی در اسلاید با ایندکس مشخص شروع می‌شود. اگر **false** باشد، داده‌ها به اسلایدهای ایجادشده اضافه می‌شوند. |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده.
### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

اسلایدها را از متن HTML ایجاد می‌کند و آنها را در موقعیت مشخص به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیت برای درج. |
| htmlStream | java.io.InputStream | یک شیٔ Stream که به عنوان منبع یک فایل HTML استفاده می‌شود. |
| useSlideWithIndexAsStart | boolean | این پرچم تعیین می‌کند که درج چگونه شروع شود: از یک اسلاید جدید یا از اسلایدی با ایندکس مشخص. اگر **true** باشد، درج داده‌ها از یک فضای خالی در اسلاید با ایندکس مشخص شروع می‌شود. اگر **false** باشد، داده‌ها به اسلایدهای ایجادشده اضافه می‌شوند. |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

اسلایدها را از متن HTML ایجاد می‌کند و آنها را در موقعیت مشخص به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیت برای درج. |
| htmlStream | java.io.InputStream | یک شیٔ Stream که به عنوان منبع یک فایل HTML استفاده می‌شود. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | یک شیٔ فراخوانی بازگشتی که برای دریافت اشیاء خارجی استفاده می‌شود. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | java.lang.String | یک URI از HTML مشخص شده. برای حل لینک‌های نسبی استفاده می‌شود. |
| useSlideWithIndexAsStart | boolean | این پرچم تعیین می‌کند که درج چگونه شروع شود: از یک اسلاید جدید یا از اسلایدی با ایندکس مشخص. اگر **true** باشد، درج داده‌ها از یک فضای خالی در اسلاید با ایندکس مشخص شروع می‌شود. اگر **false** باشد، داده‌ها به اسلایدهای ایجادشده اضافه می‌شوند. |

**بازگرداندن:**  
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده.