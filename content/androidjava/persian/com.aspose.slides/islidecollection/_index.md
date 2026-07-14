---
title: ISlideCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش یک مجموعه از اسلایدها.
type: docs
url: /fa/com.aspose.slides/islidecollection/
---
**تمام رابط‌های پیاده‌سازی شده:**
com.aspose.slides.IGenericCollection
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

نمایش یک مجموعه از اسلایدها.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصری را که در ایندکس مشخص شده قرار دارد، دریافت می‌کند. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | یک نسخه از اسلاید مشخص را به انتهای مجموعه اضافه می‌کند. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | یک نسخه از اسلاید مشخص را به انتهای بخش مشخص شده اضافه می‌کند. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | یک نسخه از اسلاید مشخص را در موقعیت تعیین‌شدهٔ مجموعه وارد می‌کند. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | یک اسلاید خالی جدید را به انتهای مجموعه اضافه می‌کند. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | یک نسخه از اسلاید مشخص را در موقعیت تعیین‌شدهٔ مجموعه وارد می‌کند. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | یک نسخه از اسلاید مشخص را به انتهای مجموعه اضافه می‌کند. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | یک نسخه از اسلاید مشخص را در موقعیت تعیین‌شدهٔ مجموعه وارد می‌کند. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | یک نسخه از اسلاید منبع مشخص را به انتهای مجموعه اضافه می‌کند. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | یک نسخه از اسلاید منبع مشخص را در موقعیت تعیین‌شدهٔ مجموعه وارد می‌کند. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | اولین وقوع یک شیء خاص را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصری که در ایندکس مشخص شدهٔ مجموعه قرار دارد را حذف می‌کند. |
| [toArray()](#toArray--) | یک آرایه شامل تمام اسلایدها ایجاد و بازمی‌گرداند. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | یک آرایه شامل تمام اسلایدهای بازهٔ مشخص شده ایجاد و بازمی‌گرداند. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | اسلاید را از مجموعه به موقعیت مشخص شده منتقل می‌کند. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | اسلایدها را از مجموعه به موقعیت مشخص شده منتقل می‌کند. اسلایدها از ایندکس شروع شده و به ترتیب ظاهر شدن در لیست قرار می‌گیرند. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | اندیس اسلاید مشخص شده را در مجموعه برمی‌گرداند. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | اسلایدهایی را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | اسلایدهایی را از سند PDF ایجاد کرده و با در نظر گرفتن گزینه‌های واردسازی PDF به انتهای مجموعه اضافه می‌کند. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | اسلایدهایی را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | اسلایدهایی را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | اسلایدهایی را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | اسلایدهایی را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | اسلایدهایی را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | اسلایدهایی را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | اسلایدهایی را از متن HTML ایجاد کرده و در موقعیت مشخص شدهٔ مجموعه وارد می‌کند. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | اسلایدهایی را از متن HTML ایجاد کرده و در موقعیت مشخص شدهٔ مجموعه وارد می‌کند. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | اسلایدهایی را از متن HTML ایجاد کرده و در موقعیت مشخص شدهٔ مجموعه وارد می‌کند. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | اسلایدهایی را از متن HTML ایجاد کرده و در موقعیت مشخص شدهٔ مجموعه وارد می‌کند. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | اسلایدهایی را از متن HTML ایجاد کرده و در موقعیت مشخص شدهٔ مجموعه وارد می‌کند. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | اسلایدهایی را از متن HTML ایجاد کرده و در موقعیت مشخص شدهٔ مجموعه وارد می‌کند. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | اسلایدهایی را از متن HTML ایجاد کرده و در موقعیت مشخص شدهٔ مجموعه وارد می‌کند. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | اسلایدهایی را از متن HTML ایجاد کرده و در موقعیت مشخص شدهٔ مجموعه وارد می‌کند. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISlide get_Item(int index)
```

عنصری را که در ایندکس مشخص شده قرار دارد، دریافت می‌کند. فقط-خواندنی [ISlide](../../com.aspose.slides/islide).

**پارامترها:**
| پارامتر | نوع | توضیح |
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
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلایدی برای کلون کردن. |

--------------------

هنگام کلون کردن یک اسلاید بین ارائه‌های مختلف، مستر اسلاید نیز می‌تواند کلون شود. رجیستری داخلی برای ردیابی مسترهای کلون‌شده به‌صورت خودکار استفاده می‌شود تا از ایجاد چندین کلون از همان مستر اسلاید جلوگیری شود. کلون کردن دستی مستر اسلایدها نه منع می‌شود و نه ثبت می‌شود. اگر نیاز به کنترل بیشتر بر فرآیند کلون دارید از \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) یا \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) برای کلون کردن اسلایدها، [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) یا [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) برای کلون کردن لایه‌ها و [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) برای کلون کردن مسترها استفاده کنید. |

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
>      // اکنون بخش دوم شامل یک نسخه از اسلاید اول است.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلایدی برای کلون کردن. |
| section | [ISection](../../com.aspose.slides/isection) | بخش برای اسلاید جدید. |

**بازگشت:**
[ISlide](../../com.aspose.slides/islide) - اسلاید جدید.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

یک نسخه از اسلاید مشخص را در موقعیت تعیین‌شدهٔ مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس اسلاید جدید. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلایدی برای کلون کردن. |

--------------------

هنگام کلون کردن یک اسلاید بین ارائه‌های مختلف، مستر اسلاید نیز می‌تواند کلون شود. رجیستری داخلی برای ردیابی مسترهای کلون‌شده به‌صورت خودکار استفاده می‌شود تا از ایجاد چندین کلون از همان مستر اسلاید جلوگیری شود. کلون کردن دستی مستر اسلایدها نه منع می‌شود و نه ثبت می‌شود. اگر نیاز به کنترل بیشتر بر فرآیند کلون دارید از \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) یا \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) برای کلون کردن اسلایدها و [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) برای کلون کردن مسترها استفاده کنید. |

**بازگشت:**
[ISlide](../../com.aspose.slides/islide) - اسلاید وارد‌شده.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addEmptySlide(ILayoutSlide layout)
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
public abstract ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

یک نسخه از اسلاید مشخص را در موقعیت تعیین‌شدهٔ مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس اسلاید جدید. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | لایه برای اسلاید. |

**بازگشت:**
[ISlide](../../com.aspose.slides/islide) - اسلاید وارد‌شده.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

یک نسخه از اسلاید مشخص را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلایدی برای کلون کردن. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | لایه اسلاید برای اسلاید جدید. |

**بازگشت:**
[ISlide](../../com.aspose.slides/islide) - اسلاید جدید.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

یک نسخه از اسلاید مشخص را در موقعیت تعیین‌شدهٔ مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس اسلاید جدید. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلایدی برای کلون کردن. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | لایه اسلاید برای اسلاید جدید. |

**بازگشت:**
[ISlide](../../com.aspose.slides/islide) - اسلاید وارد‌شده.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

یک نسخه از اسلاید منبع مشخص را به انتهای مجموعه اضافه می‌کند. لایه مناسب به‌صورت خودکار از مستر مشخص شده انتخاب می‌شود (لایه مناسب همان لایه‌ای است که نوع یا نامش با لایهٔ اسلاید منبع یکسان باشد). اگر لایهٔ مناسبی وجود نداشته باشد، لایهٔ اسلاید منبع کلون می‌شود (اگر allowCloneMissingLayout برابر true باشد) یا PptxEditException پرتاب می‌شود (اگر برابر false باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلایدی برای کلون کردن. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | مستر اسلاید برای اسلاید جدید. |
| allowCloneMissingLayout | boolean | اگر در مستر مشخص شده لایهٔ مناسبی وجود نداشته باشد، لایهٔ اسلاید منبع کلون می‌شود (اگر true باشد) یا PptxEditException پرتاب می‌شود (اگر false باشد). |

**بازگشت:**
[ISlide](../../com.aspose.slides/islide) - اسلاید جدید.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

یک نسخه از اسلاید منبع مشخص را در موقعیت تعیین‌شدهٔ مجموعه وارد می‌کند. لایه مناسب به‌صورت خودکار از مستر مشخص شده انتخاب می‌شود (لایه مناسب همان لایه‌ای است که نوع یا نامش با لایهٔ اسلاید منبع یکسان باشد). اگر لایهٔ مناسبی وجود نداشته باشد، لایهٔ اسلاید منبع کلون می‌شود (اگر allowCloneMissingLayout برابر true باشد) یا PptxEditException پرتاب می‌شود (اگر برابر false باشد).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس اسلاید جدید. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | اسلایدی برای کلون کردن. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | مستر اسلاید برای اسلاید جدید. |
| allowCloneMissingLayout | boolean | اگر در مستر مشخص شده لایهٔ مناسبی وجود نداشته باشد، لایهٔ اسلاید منبع کلون می‌شود (اگر true باشد) یا PptxEditException پرتاب می‌شود (اگر false باشد). |

**بازگشت:**
[ISlide](../../com.aspose.slides/islide) - اسلاید وارد‌شده.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

اولین وقوع یک شیء خاص را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | اسلایدی که باید از مجموعه حذف شود. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

عنصری که در ایندکس مشخص شدهٔ مجموعه قرار دارد را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-آبشاری عنصری که باید حذف شود. |

### toArray() {#toArray--}
```
public abstract ISlide[] toArray()
```

یک آرایه شامل تمام اسلایدها ایجاد و بازمی‌گرداند.

**بازگشت:**
com.aspose.slides.ISlide[] - آرایهٔ [ISlide](../../com.aspose.slides/islide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract ISlide[] toArray(int startIndex, int count)
```

یک آرایه شامل تمام اسلایدهای بازهٔ مشخص شده ایجاد و بازمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | int | ایندکس اولین اسلایدی که باید اضافه شود. |
| count | int | تعداد اسلایدهایی که باید اضافه شوند. |

**بازگشت:**
com.aspose.slides.ISlide[] - آرایهٔ [ISlide](../../com.aspose.slides/islide)

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public abstract void reorder(int index, ISlide slide)
```

اسلاید را از مجموعه به موقعیت مشخص شده منتقل می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس هدف. |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلایدی که باید منتقل شود. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public abstract void reorder(int index, ISlide[] slides)
```

اسلایدها را از مجموعه به موقعیت مشخص شده منتقل می‌کند. اسلایدها از ایندکس شروع شده و به ترتیب ظاهر شدن در لیست قرار می‌گیرند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس هدف. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | اسلایدهایی که باید منتقل شوند. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public abstract int indexOf(ISlide slide)
```

اندیس اسلاید مشخص شده را در مجموعه برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلایدی که باید پیدا شود. |

**بازگشت:**
int - اندیس اسلاید یا -1 اگر اسلاید متعلق به این مجموعه نباشد.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public abstract ISlide[] addFromPdf(String path)
```

اسلایدهایی را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند.

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
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

اسلایدهایی را از سند PDF ایجاد کرده و با در نظر گرفتن گزینه‌های واردسازی PDF به انتهای مجموعه اضافه می‌کند.

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
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | گزینه‌های واردسازی PDF |

**بازگشت:**
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

اسلایدهایی را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند.

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
>   } catch (IOException e) {
>   } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pdfStream | java.io.InputStream | جریانی که به عنوان منبع سند PDF استفاده می‌شود |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | گزینه‌های واردسازی PDF |

**بازگشت:**
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
```

اسلایدهایی را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند.

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

**بازگشت:**
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

اسلایدهایی را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| htmlText | java.lang.String | Html برای اضافه‌کردن. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | شیء فراخوانی برای دریافت اشیای خارجی. اگر این پارامتر null باشد همهٔ اشیای خارجی نادیده گرفته می‌شوند. |
| uri | java.lang.String | URI متن HTML مشخص شده. برای حل لینک‌های نسبی استفاده می‌شود. |

**بازگشت:**
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
```

اسلایدهایی را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| htmlText | java.lang.String | Html برای اضافه‌کردن. |

**بازگشت:**
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

اسلایدهایی را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| htmlStream | java.io.InputStream | شیء جریانی که به عنوان منبع یک فایل HTML استفاده می‌شود. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | شیء فراخوانی برای دریافت اشیای خارجی. اگر این پارامتر null باشد همهٔ اشیای خارجی نادیده گرفته می‌شوند. |
| uri | java.lang.String | URI متن HTML مشخص شده. برای حل لینک‌های نسبی استفاده می‌شود. |

**بازگشت:**
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```

اسلایدهایی را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| htmlStream | java.io.InputStream | شیء جریانی که به عنوان منبع یک فایل HTML استفاده می‌شود. |

**بازگشت:**
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

اسلایدهایی را از متن HTML ایجاد کرده و در موقعیت مشخص شدهٔ مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیتی که باید وارد شود. |
| htmlText | java.lang.String | Html برای اضافه‌کردن. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | شیء فراخوانی برای دریافت اشیای خارجی. اگر این پارامتر null باشد همهٔ اشیای خارجی نادیده گرفته می‌شوند. |
| uri | java.lang.String | URI متن HTML مشخص شده. برای حل لینک‌های نسبی استفاده می‌شود. |

**بازگشت:**
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```

اسلایدهایی را از متن HTML ایجاد کرده و در موقعیت مشخص شدهٔ مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیتی که باید وارد شود. |
| htmlText | java.lang.String | Html برای اضافه‌کردن. |

**بازگشت:**
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

اسلایدهایی را از متن HTML ایجاد کرده و در موقعیت مشخص شدهٔ مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیتی که باید وارد شود. |
| htmlStream | java.io.InputStream | شیء جریانی که به عنوان منبع یک فایل HTML استفاده می‌شود. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | شیء فراخوانی برای دریافت اشیای خارجی. اگر این پارامتر null باشد همهٔ اشیای خارجی نادیده گرفته می‌شوند. |
| uri | java.lang.String | URI متن HTML مشخص شده. برای حل لینک‌های نسبی استفاده می‌شود. |

**بازگشت:**
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

اسلایدهایی را از متن HTML ایجاد کرده و در موقعیت مشخص شدهٔ مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیتی که باید وارد شود. |
| htmlStream | java.io.InputStream | شیء جریانی که به عنوان منبع یک فایل HTML استفاده می‌شود. |

**بازگشت:**
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

اسلایدهایی را از متن HTML ایجاد کرده و در موقعیت مشخص شدهٔ مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیتی که باید وارد شود. |
| htmlText | java.lang.String | Html برای اضافه‌کردن. |
| useSlideWithIndexAsStart | boolean | این پرچم مشخص می‌کند که واردسازی از اسلاید جدید یا از اسلاید با ایندکس مشخص شروع شود. اگر **true** باشد، واردسازی از فضای خالی در اسلاید با ایندکس مشخص شروع می‌شود. اگر **false** باشد، داده‌ها به اسلایدهای ایجادشده اضافه می‌شوند. |

**بازگشت:**
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

اسلایدهایی را از متن HTML ایجاد کرده و در موقعیت مشخص شدهٔ مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیتی که باید وارد شود. |
| htmlText | java.lang.String | Html برای اضافه‌کردن. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | شیء فراخوانی برای دریافت اشیای خارجی. اگر این پارامتر null باشد همهٔ اشیای خارجی نادیده گرفته می‌شوند. |
| uri | java.lang.String | URI متن HTML مشخص شده. برای حل لینک‌های نسبی استفاده می‌شود. |
| useSlideWithIndexAsStart | boolean | این پرچم مشخص می‌کند که واردسازی از اسلاید جدید یا از اسلاید با ایندکس مشخص شروع شود. اگر **true** باشد، واردسازی از فضای خالی در اسلاید با ایندکس مشخص شروع می‌شود. اگر **false** باشد، داده‌ها به اسلایدهای ایجادشده اضافه می‌شوند. |

**بازگشت:**
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده.

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

اسلایدهایی را از متن HTML ایجاد کرده و در موقعیت مشخص شدهٔ مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیتی که باید وارد شود. |
| htmlStream | java.io.InputStream | شیء جریانی که به عنوان منبع یک فایل HTML استفاده می‌شود. |
| useSlideWithIndexAsStart | boolean | این پرچم مشخص می‌کند که واردسازی از اسلاید جدید یا از اسلاید با ایندکس مشخص شروع شود. اگر **true** باشد، واردسازی از فضای خالی در اسلاید با ایندکس مشخص شروع می‌شود. اگر **false** باشد، داده‌ها به اسلایدهای ایجادشده اضافه می‌شوند. |

**بازگشت:**
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

اسلایدهایی را از متن HTML ایجاد کرده و در موقعیت مشخص شدهٔ مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیتی که باید وارد شود. |
| htmlStream | java.io.InputStream | شیء جریانی که به عنوان منبع یک فایل HTML استفاده می‌شود. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | شیء فراخوانی برای دریافت اشیای خارجی. اگر این پارامتر null باشد همهٔ اشیای خارجی نادیده گرفته می‌شوند. |
| uri | java.lang.String | URI متن HTML مشخص شده. برای حل لینک‌های نسبی استفاده می‌شود. |
| useSlideWithIndexAsStart | boolean | این پرچم مشخص می‌کند که واردسازی از اسلاید جدید یا از اسلاید با ایندکس مشخص شروع شود. اگر **true** باشد، واردسازی از فضای خالی در اسلاید با ایندکس مشخص شروع می‌شود. اگر **false** باشد، داده‌ها به اسلایدهای ایجادشده اضافه می‌شوند. |

**بازگشت:**
com.aspose.slides.ISlide[] - اسلایدهای اضافه‌شده.