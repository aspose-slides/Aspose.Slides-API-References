---
title: ISlideCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงคอลเลกชันของสไลด์
type: docs
url: /th/com.aspose.slides/islidecollection/
---
**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

แสดงคอลเลกชันของสไลด์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบที่ตำแหน่งที่ระบุ. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของส่วนที่ระบุ. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | แทรกสำเนาของสไลด์ที่ระบุในตำแหน่งที่ระบุของคอลเลกชัน. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | เพิ่มสไลด์เปล่าใหม่ไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | แทรกสำเนาของสไลด์ที่ระบุในตำแหน่งที่ระบุของคอลเลกชัน. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | แทรกสำเนาของสไลด์ที่ระบุในตำแหน่งที่ระบุของคอลเลกชัน. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | เพิ่มสำเนาของสไลด์ต้นฉบับที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | แทรกสำเนาของสไลด์ต้นฉบับที่ระบุในตำแหน่งที่ระบุของคอลเลกชัน. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | ลบการเกิดขึ้นครั้งแรกของอ็อบเจกต์ที่ระบุจากคอลเลกชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบองค์ประกอบที่ตำแหน่งที่ระบุของคอลเลกชัน. |
| [toArray()](#toArray--) | สร้างและส่งกลับอาเรย์ที่มีสไลด์ทั้งหมด. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | สร้างและส่งกลับอาเรย์ที่มีสไลด์ทั้งหมดจากช่วงที่ระบุ. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | คืนค่าดัชนีของสไลด์ที่ระบุในคอลเลกชัน. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | สร้างสไลด์จากเอกสาร PDF และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | สร้างสไลด์จากเอกสาร PDF และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันโดยคำนึงถึงตัวเลือกการนำเข้า PDF. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | สร้างสไลด์จากเอกสาร PDF และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | สร้างสไลด์จากเอกสาร PDF และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | สร้างสไลด์จากข้อความ HTML และแทรกเข้าคอลเลกชันในตำแหน่งที่ระบุ. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | สร้างสไลด์จากข้อความ HTML และแทรกเข้าคอลเลกชันในตำแหน่งที่ระบุ. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | สร้างสไลด์จากข้อความ HTML และแทรกเข้าคอลเลกชันในตำแหน่งที่ระบุ. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | สร้างสไลด์จากข้อความ HTMLและแทรกเข้าคอลเลกชันในตำแหน่งที่ระบุ. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | สร้างสไลด์จากข้อความ HTMLและแทรกเข้าคอลเลกชันในตำแหน่งที่ระบุ. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | สร้างสไลด์จากข้อความ HTMLและแทรกเข้าคอลเลกชันในตำแหน่งที่ระบุ. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | สร้างสไลด์จากข้อความ HTMLและแทรกเข้าคอลเลกชันในตำแหน่งที่ระบุ. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | สร้างสไลด์จากข้อความ HTMLและแทรกเข้าคอลเลกชันในตำแหน่งที่ระบุ. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISlide get_Item(int index)
```

รับองค์ประกอบที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [ISlide](../../com.aspose.slides/islide).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ค่าที่ส่งคืน:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public abstract ISlide addClone(ISlide sourceSlide)
```

เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะโคลน. |

--------------------

เมื่อทำการโคลนสไลด์ระหว่างพรีเซนเทชั่นที่แตกต่างกัน หน้ากระดาษมาสเตอร์ของสไลด์อาจถูกโคลนด้วย ระบบทะเบียนภายในใช้เพื่อติดตามมาสเตอร์ที่ถูกโคลนอัตโนมัติเพื่อป้องกันการสร้างโคลนหลายตัวของมาสเตอร์สไลด์เดียวกัน การโคลนมาสเตอร์สไลด์ด้วยตนเองจะไม่ได้รับการป้องกันหรือบันทึก หากคุณต้องการควบคุมการโคลนมากขึ้น ให้ใช้ \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) หรือ \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) สำหรับการโคลนสไลด์, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) หรือ [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) สำหรับการโคลนเลเอาต์และ [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) สำหรับการโคลนมาสเตอร์. 

**ค่าที่ส่งคืน:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ใหม่.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public abstract ISlide addClone(ISlide sourceSlide, ISection section)
```

เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของส่วนที่ระบุ.

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
>      // ตอนนี้ส่วนที่สองมีสำเนาของสไลด์แรก.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะโคลน. |
| section | [ISection](../../com.aspose.slides/isection) | ส่วนสำหรับสไลด์ใหม่. |

**ค่าที่ส่งคืน:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ใหม่.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

แทรกสำเนาของสไลด์ที่ระบุในตำแหน่งที่ระบุของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของสไลด์ใหม่. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะโคลน. |

--------------------

เมื่อทำการโคลนสไลด์ระหว่างพรีเซนเทชั่นที่แตกต่างกัน หน้ากระดาษมาสเตอร์ของสไลด์อาจถูกโคลนด้วย ระบบทะเบียนภายในใช้เพื่อติดตามมาสเตอร์ที่ถูกโคลนอัตโนมัติเพื่อป้องกันการสร้างโคลนหลายตัวของมาสเตอร์สไลด์เดียวกัน การโคลนมาสเตอร์สไลด์ด้วยตนเองจะไม่ได้รับการป้องกันหรือบันทึก หากคุณต้องการควบคุมการโคลนมากขึ้น ให้ใช้ \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) หรือ \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) สำหรับการโคลนสไลด์และ [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) สำหรับการโคลนมาสเตอร์. 

**ค่าที่ส่งคืน:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ที่แทรก.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addEmptySlide(ILayoutSlide layout)
```

เพิ่มสไลด์เปล่าใหม่ไปยังตำแหน่งสุดท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | เลเอาต์สำหรับสไลด์. |

**ค่าที่ส่งคืน:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ที่เพิ่ม.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

แทรกสำเนาของสไลด์ที่ระบุในตำแหน่งที่ระบุของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของสไลด์ใหม่. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | เลเอาต์สำหรับสไลด์. |

**ค่าที่ส่งคืน:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ที่แทรก.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะโคลน. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | เลเอาต์สไลด์สำหรับสไลด์ใหม่. |

**ค่าที่ส่งคืน:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ใหม่.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

แทรกสำเนาของสไลด์ที่ระบุในตำแหน่งที่ระบุของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของสไลด์ใหม่. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะโคลน. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | เลเอาต์สไลด์สำหรับสไลด์ใหม่. |

**ค่าที่ส่งคืน:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ที่แทรก.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

เพิ่มสำเนาของสไลด์ต้นฉบับที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน เลเอาต์ที่เหมาะสมจะถูกเลือกโดยอัตโนมัติจากมาสเตอร์ที่ระบุ (เลเอาต์ที่เหมาะสมคือเลเอาต์ที่มี Type หรือ Name เหมือนกับเลเอาต์ของสไลด์ต้นฉบับ) หากไม่มีเลเอาต์ที่เหมาะสม เลเอาต์ของสไลด์ต้นฉบับจะถูกโคลน (หาก allowCloneMissingLayout เป็น true) หรือจะโยน PptxEditException (หาก allowCloneMissingLayout เป็น false).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะโคลน. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | มาสเตอร์สไลด์สำหรับสไลด์ใหม่. |
| allowCloneMissingLayout | boolean | หากไม่มีเลเอาต์ที่เหมาะสมในมาสเตอร์ที่ระบุ เลเอาต์ของสไลด์ต้นฉบับจะถูกโคลน (ถ้า allowCloneMissingLayout เป็น true) หรือจะโยน PptxEditException (ถ้า allowCloneMissingLayout เป็น false). |

**ค่าที่ส่งคืน:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ใหม่.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

แทรกสำเนาของสไลด์ต้นฉบับที่ระบุในตำแหน่งที่ระบุของคอลเลกชัน เลเอาต์ที่เหมาะสมจะถูกเลือกโดยอัตโนมัติจากมาสเตอร์ที่ระบุ (เลเอาต์ที่เหมาะสมคือเลเอ็ตที่มี Type หรือ Name เหมือนกับเลเอ็ตของสไลด์ต้นฉบับ) หากไม่มีเลเอ็ตที่เหมาะสม เลเอ็ตของสไลด์ต้นฉบับจะถูกโคลน (หาก allowCloneMissingLayout เป็น true) หรือจะโยน PptxEditException (หาก allowCloneMissingLayout เป็น false).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของสไลด์ใหม่. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะโคลน. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | มาสเตอร์สไลด์สำหรับสไลด์ใหม่. |
| allowCloneMissingLayout | boolean | หากไม่มีเลเอ็ตที่เหมาะสมในมาสเตอร์ที่ระบุ เลเอ็ตของสไลด์ต้นฉบับจะถูกโคลน (ถ้า allowCloneMissingLayout เป็น true) หรือจะโยน PptxEditException (ถ้า allowCloneMissingLayout เป็น false). |

**ค่าที่ส่งคืน:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ที่แทรก.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

ลบการเกิดขึ้นครั้งแรกของอ็อบเจกต์ที่ระบุจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะลบจากคอลเลกชัน. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบองค์ประกอบที่ตำแหน่งที่ระบุของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ขององค์ประกอบที่จะลบ. |

### toArray() {#toArray--}
```
public abstract ISlide[] toArray()
```

สร้างและส่งกลับอาเรย์ที่มีสไลด์ทั้งหมด.

**ค่าที่ส่งคืน:**
com.aspose.slides.ISlide[] - อาเรย์ของ [ISlide](../../com.aspose.slides/islide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract ISlide[] toArray(int startIndex, int count)
```

สร้างและส่งกลับอาเรย์ที่มีสไลด์ทั้งหมดจากช่วงที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| startIndex | int | ดัชนีของสไลด์แรกที่จะเพิ่ม. |
| count | int | จำนวนสไลด์ที่จะเพิ่ม. |

**ค่าที่ส่งคืน:**
com.aspose.slides.ISlide[] - อาเรย์ของ [ISlide](../../com.aspose.slides/islide)

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public abstract void reorder(int index, ISlide slide)
```

ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเป้าหมาย. |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะย้าย. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public abstract void reorder(int index, ISlide[] slides)
```

ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ สไลด์จะถูกวางเริ่มจากดัชนีตามลำดับที่ปรากฏในรายการ.

**พารามิเตอร์:**
| พารามิ터 | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเป้าหมาย. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | สไลด์ที่จะย้าย. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public abstract int indexOf(ISlide slide)
```

คืนค่าดัชนีของสไลด์ที่ระบุในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะค้นหา. |

**ค่าที่ส่งคืน:**
int - ดัชนีของสไลด์หรือ -1 หากสไลด์ไม่อยู่ในคอลเลกชันนี้.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public abstract ISlide[] addFromPdf(String path)
```

สร้างสไลด์จากเอกสาร PDF และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน.

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

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| path | java.lang.String | เส้นทางไปยังเอกสาร PDF |

**ค่าที่ส่งคืน:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

สร้างสไลด์จากเอกสาร PDF และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันโดยคำนึงถึงตัวเลือกการนำเข้า PDF.

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

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| path | java.lang.String | เส้นทางไปยังเอกสาร PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | ตัวเลือกสำหรับการนำเข้า PDF |

**ค่าที่ส่งคืน:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

สร้างสไลด์จากเอกสาร PDF และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน.

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


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pdfStream | java.io.InputStream | สตรีมที่ใช้เป็นแหล่งของเอกสาร PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | ตัวเลือกสำหรับการนำเข้า PDF |

**ค่าที่ส่งคืน:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
```

สร้างสไลด์จากเอกสาร PDF และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน.

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

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pdfStream | java.io.InputStream | สตรีมที่ใช้เป็นแหล่งของเอกสาร PDF |

**ค่าที่ส่งคืน:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| htmlText | java.lang.String | HTML ที่จะเพิ่ม. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | อ็อบเจกต์ callback ที่ใช้เพื่อดึงอ็อบเจกต์ภายนอก หากพารามิเตอร์นี้เป็น null จะละเว้นอ็อบเจกต์ภายนอกทั้งหมด. |
| uri | java.lang.String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์สัมพันธ์. |

**ค่าที่ส่งคืน:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
```

สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| htmlText | java.lang.String | HTML ที่จะเพิ่ม. |

**ค่าที่ส่งคืน:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| htmlStream | java.io.InputStream | อ็อบเจกต์ Stream ที่ใช้เป็นแหล่งของไฟล์ HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | อ็อบเจกต์ callback ที่ใช้เพื่อดึงอ็อบเจกต์ภายนอก หากพารามิเตอร์นี้เป็น null จะละเว้นอ็อบเจกต์ภายนอกทั้งหมด. |
| uri | java.lang.String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์สัมพันธ์. |

**ค่าที่ส่งคืน:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```

สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| htmlStream | java.io.InputStream | อ็อบเจกต์ Stream ที่ใช้เป็นแหล่งของไฟล์ HTML. |

**ค่าที่ส่งคืน:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

สร้างสไลด์จากข้อความ HTML และแทรกเข้าคอลเลกชันในตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งที่จะใส่. |
| htmlText | java.lang.String | HTML ที่จะเพิ่ม. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | อ็อบเจกต์ callback ที่ใช้เพื่อดึงอ็อบเจกต์ภายนอก หากพารามิเตอร์นี้เป็น null จะละเว้นอ็อบเจกต์ภายนอกทั้งหมด. |
| uri | java.lang.String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์สัมพันธ์. |

**ค่าที่ส่งคืน:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```

สร้างสไลด์จากข้อความ HTML และแทรกเข้าคอลเลกชันในตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งที่จะใส่. |
| htmlText | java.lang.String | HTML ที่จะเพิ่ม. |

**ค่าที่ส่งคืน:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

สร้างสไลด์จากข้อความ HTML และแทรกเข้าคอลเลกชันในตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งที่จะใส่. |
| htmlStream | java.io.InputStream | อ็อบเจกต์ Stream ที่ใช้เป็นแหล่งของไฟล์ HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | อ็อบเจกต์ callback ที่ใช้เพื่อดึงอ็อบเจกต์ภายนอก หากพารามิเตอร์นี้เป็น null จะละเว้นอ็อบเจกต์ภายนอกทั้งหมด. |
| uri | java.lang.String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์สัมพันธ์. |

**ค่าที่ส่งคืน:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

สร้างสไลด์จากข้อความ HTML และแทรกเข้าคอลเลกชันในตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งที่จะใส่. |
| htmlStream | java.io.InputStream | อ็อบเจกต์ Stream ที่ใช้เป็นแหล่งของไฟล์ HTML. |

**ค่าที่ส่งคืน:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

สร้างสไลด์จากข้อความ HTML และแทรกเข้าคอลเลกชันในตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งที่จะใส่. |
| htmlText | java.lang.String | HTML ที่จะเพิ่ม. |
| useSlideWithIndexAsStart | boolean | ธงนี้กำหนดวิธีการเริ่มการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่ระบุ หาก **true** จะเริ่มจากช่องว่างในสไลด์ที่ระบุ หาก **false** จะเพิ่มข้อมูลลงในสไลด์ที่สร้างใหม่. |

**ค่าที่ส่งคืน:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

สร้างสไลด์จากข้อความ HTML และแทรกเข้าคอลเลกชันในตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งที่จะใส่. |
| htmlText | java.lang.String | HTML ที่จะเพิ่ม. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | อ็อบเจกต์ callback ที่ใช้เพื่อดึงอ็อบเจกต์ภายนอก หากพารามิเตอร์นี้เป็น null จะละเว้นอ็อบเจกต์ภายนอกทั้งหมด. |
| uri | java.lang.String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์สัมพันธ์. |
| useSlideWithIndexAsStart | boolean | ธ旗นี้กำหนดวิธีการเริ่มการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่ระบุ หาก **true** จะเริ่มจากช่องว่างในสไลด์ที่ระบุ หาก **false** จะเพิ่มข้อมูลลงในสไลด์ที่สร้างใหม่. |

**ค่าที่ส่งคืน:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม.

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

สร้างสไลด์จากข้อความ HTML และแทรกเข้าคอลเลกชันในตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งที่จะใส่. |
| htmlStream | java.io.InputStream | อ็อบเจกต์ Stream ที่ใช้เป็นแหล่งของไฟล์ HTML. |
| useSlideWithIndexAsStart | boolean | ธ旗นี้กำหนดวิธีการเริ่มการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่ระบุ หาก **true** จะเริ่มจากช่องว่างในสไลด์ที่ระบุ หาก **false** จะเพิ่มข้อมูลลงในสไลด์ที่สร้างใหม่. |

**ค่าที่ส่งคืน:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

สร้างสไลด์จากข้อความ HTML และแทรกเข้าคอลเลกชันในตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งที่จะใส่. |
| htmlStream | java.io.InputStream | อ็อบเจกต์ Stream ที่ใช้เป็นแหล่งของไฟล์ HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | อ็อบเจกต์ callback ที่ใช้เพื่อดึงอ็อบเจกต์ภายนอก หากพารามิเตอร์นี้เป็น null จะละเว้นอ็อบเจกต์ภายนอกทั้งหมด. |
| uri | java.lang.String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์สัมพันธ์. |
| useSlideWithIndexAsStart | boolean | ธ旗นี้กำหนดวิธีการเริ่มการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่ระบุ หาก **true** จะเริ่มจากช่องว่างในสไลด์ที่ระบุ หาก **false** จะเพิ่มข้อมูลลงในสไลด์ที่สร้างใหม่. |

**ค่าที่ส่งคืน:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม.