---
title: SlideCollection
second_title: Aspose.Slides สำหรับ Java API อ้างอิง
description: เป็นตัวแทนของคอลเลกชันของสไลด์
type: docs
url: /th/com.aspose.slides/slidecollection/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

เป็นคอลเลกชันของสไลด์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | รับจำนวนขององค์ประกอบที่จริง ๆ อยู่ในคอลเลกชัน |
| [get_Item(int index)](#get-Item-int-) | รับอิลเมนต์ที่ตำแหน่งดัชนีที่ระบุ |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของส่วนที่ระบุ |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | เพิ่มสไลด์เปล่าใหม่ไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | เพิ่มสำเนาของสไลด์ต้นฉบับที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | แทรกสำเนาของสไลด์ต้นฉบับที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | ลบการปรากฏตัวครั้งแรกของอ็อบเจ็กต์ที่ระบุจากคอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบอิลเมนต์ที่ตำแหน่งดัชนีที่ระบุของคอลเลกชัน |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด |
| [toArray()](#toArray--) | สร้างและคืนค่าอาร์เรย์ที่มีสไลด์ทั้งหมด |
| [toArray(int startIndex, int count)](#toArray-int-int-) | สร้างและคืนค่าอาร์เรย์ที่มีสไลด์ทั้งหมดจากช่วงที่ระบุ |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | คืนค่าดัชนีของสไลด์ที่ระบุในคอลเลกชัน |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | สร้างสไลด์จากไฟล์ PDF และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | สร้างสไลด์จากไฟล์ PDF และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันโดยคำนึงถึงตัวเลือกการนำเข้า PDF |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | สร้างสไลด์จากไฟล์ PDF และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | สร้างสไลด์จากไฟล์ PDF และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกทุกอิลเมนต์จากคอลเลกชันไปยังอาร์เรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่แสดงว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด) หรือไม่ |
| [getSyncRoot()](#getSyncRoot--) | คืนค่ารากของการซิงโครไนซ์ |

### size() {#size--}
```
public final int size()
```


รับจำนวนขององค์ประกอบที่จริง ๆ อยู่ในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**
int

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```


รับอิลเมนต์ที่ตำแหน่งดัชนีที่ระบุ. อ่านอย่างเดียว [Slide](../../com.aspose.slides/slide).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```


เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะโคลน.

--------------------

เมื่อทำการโคลนสไลด์ระหว่างการนำเสนอที่ต่างกัน master ของสไลด์อาจถูกโคลนด้วยเช่นกัน. เรจิสทรีภายในใช้เพื่อติดตาม master ที่ถูกโคลนอัตโนมัติเพื่อป้องกันการสร้างสำเนาซ้ำของ master สไลด์เดียวกัน. การโคลน master สไลด์ด้วยมือจะไม่ถูกป้องกันหรือบันทึก. หากคุณต้องการควบคุมกระบวนการโคลนมากขึ้นให้ใช้ \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) หรือ \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) สำหรับการโคลนสไลด์, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) หรือ [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) สำหรับการโคลนเลเอาต์และ [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) สำหรับการโคลน master. |

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ใหม่.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
```


เพิ่มสำเนของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของส่วนที่ระบุ.

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

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ใหม่.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```


แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน.

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation ที่แสดงถึงไฟล์งานนำเสนอ
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // คัดลอกสไลด์ที่ต้องการไปที่ส่วนท้ายของคอลเลกชันสไลด์ในงานนำเสนอเดียวกัน
>      ISlideCollection slds = pres.getSlides();
>      // คัดลอกสไลด์ที่ต้องการไปยังตำแหน่งที่กำหนดในงานนำเสนอเดียวกัน
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // บันทึกงานนำเสนอที่แก้ไขแล้วลงดิสก์
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation เพื่อโหลดไฟล์งานนำเสนอต้นฉบับ
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // สร้างอินสแตนซ์ของคลาส Presentation สำหรับไฟล์ PPTX ปลายทาง (ที่สไลด์จะถูกคัดลอกไป)
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // บันทึกงานนำเสนอปลายทางลงดิสก์
>          destPres.save("Aspose2_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของสไลด์ใหม่. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะโคลน.

--------------------

เมื่อทำการโคลนสไลด์ระหว่างการนำเสนอที่ต่างกัน master ของสไลด์อาจถูกโคลนด้วยเช่นกัน. เรจิสทรีภายในใช้เพื่อติดตาม master ที่ถูกโคลนอัตโนมัติเพื่อป้องกันการสร้างสำเนาซ้ำของ master สไลด์เดียวกัน. การโคลน master สไลด์ด้วยมือจะไม่ถูกป้องกันหรือบันทึก. หากคุณต้องการควบคุมกระบวนการโคลนมากขึ้นให้ใช้ \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) หรือ \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) สำหรับการโคลนสไลด์และ [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) สำหรับการโคลน master. |

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ที่แทรกเข้ามา.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```


เพิ่มสไลด์เปล่าใหม่ไปยังตำแหน่งสุดท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | เลเอาต์สำหรับสไลด์. |

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ที่เพิ่ม.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```


แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของสไลด์ใหม่. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | เลเอาต์สำหรับสไลด์. |

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ที่แทรกเข้ามา.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```


เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะโคลน. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | เลเอาต์สไลด์สำหรับสไลด์ใหม่. |

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ใหม่.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```


แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของสไลด์ใหม่. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะโคลน. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | เลเอาต์สไลด์สำหรับสไลด์ใหม่. |

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ที่แทรกเข้ามา.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```


เพิ่มสำเนาของสไลด์ต้นฉบับที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน. เลเอาต์ที่เหมาะสมจะถูกเลือกโดยอัตโนมัติจาก master ที่ระบุ (เลเอาต์ที่เหมาะสมคือเลเอาต์ที่มี Type หรือ Name เหมือนกับเลเอาต์ของสไลด์ต้นฉบับ). หากไม่มีเลเอาต์ที่เหมาะสม เลเอาต์ของสไลด์ต้นฉบับจะถูกโคลน (หาก allowCloneMissingLayout เป็น true) หรือจะเกิด PptxEditException (หาก allowCloneMissingLayout เป็น false).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะโคลน. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide สำหรับสไลด์ใหม่. |
| allowCloneMissingLayout | boolean | หากไม่มีเลเอาต์ที่เหมาะสมใน master ที่ระบุ เลเอาต์ของสไลด์ต้นฉบับจะถูกโคลน (หาก allowCloneMissingLayout เป็น true) หรือจะเกิด PptxEditException (หาก allowCloneMissingLayout เป็น false). |

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ใหม่.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```


แทรกสำเนาของสไลด์ต้นฉบับที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน. เลเอาต์ที่เหมาะสมจะถูกเลือกโดยอัตโนมัติจาก master ที่ระบุ (เลเอาต์ที่เหมาะสมคือเลเอาต์ที่มี Type หรือ Name เหมือนกับเลเอาต์ของสไลด์ต้นฉบับ). หากไม่มีเลเอาต์ที่เหมาะสม เลเอาต์ของสไลด์ต้นฉบับจะถูกโคลน (หาก allowCloneMissingLayout เป็น true) หรือจะเกิด PptxEditException (หาก allowCloneMissingLayout เป็น false).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของสไลด์ใหม่. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะโคลน. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide สำหรับสไลด์ใหม่. |
| allowCloneMissingLayout | boolean | หากไม่มีเลเอาต์ที่เหมาะสมใน master ที่ระบุ เลเอาต์ของสไลด์ต้นฉบับจะถูกโคลน (หาก allowCloneMissingLayout เป็น true) หรือจะเกิด PptxEditException (หาก allowCloneMissingLayout เป็น false). |

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ที่แทรกเข้ามา.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```


ลบการปรากฏตัวครั้งแรกของอ็อบเจ็กต์ที่ระบุจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะลบจากคอลเลกชัน. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


ลบอิลเมนต์ที่ตำแหน่งดัชนีที่ระบุของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ของอิลเมนต์ที่จะลบ. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```


คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - IGenericEnumerator ที่สามารถใช้วนซ้ำผ่านคอลเลกชันได้.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```


คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด.

### toArray() {#toArray--}
```
public final ISlide[] toArray()
```


สร้างและคืนค่าอาร์เรย์ที่มีสไลด์ทั้งหมด

**คืนค่า:**
com.aspose.slides.ISlide[] - อาร์เรย์ของ [Slide](../../com.aspose.slides/slide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```


สร้างและคืนค่าอาร์เรย์ที่มีสไลด์ทั้งหมดจากช่วงที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| startIndex | int | ดัชนีของสไลด์แรกที่จะเพิ่ม. |
| count | int | จำนวนสไลด์ที่จะเพิ่ม. |

**คืนค่า:**
com.aspose.slides.ISlide[] - อาร์เรย์ของ [Slide](../../com.aspose.slides/slide)
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีเป้าหมาย |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะย้าย |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ สไลด์จะถูกวางเริ่มจากดัชนีตามลำดับที่ปรากฏในรายการ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีเป้าหมาย |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | สไลด์ที่จะย้าย |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```

คืนดัชนีของสไลด์ที่ระบุในคอลเลกชัน.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่ต้องการหา |

**ผลลัพธ์:**
int - ดัชนีของสไลด์หรือ -1 หากสไลด์ไม่อยู่ในคอลเลกชันนี้

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```

สร้างสไลด์จากเอกสาร PDF และเพิ่มลงในส่วนท้ายของคอลเลกชัน.

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
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | เส้นทางไปยังเอกสาร PDF |

**ผลลัพธ์:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

สร้างสไลด์จากเอกสาร PDF และเพิ่มลงในส่วนท้ายของคอลเลกชันโดยพิจณาตัวเลือกการนำเข้า PDF.

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
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | เส้นทางไปยังเอกสาร PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | ตัวเลือกสำหรับการนำเข้า PDF |

**ผลลัพธ์:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```

สร้างสไลด์จากเอกสาร PDF และเพิ่มลงในส่วนท้ายของคอลเลกชัน.

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
| Parameter | Type | Description |
| --- | --- | --- |
| pdfStream | java.io.InputStream | สตรีมที่ใช้เป็นแหล่งที่มาของเอกสาร PDF |

**ผลลัพธ์:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

สร้างสไลด์จากเอกสาร PDF และเพิ่มลงในส่วนท้ายของคอลเลกชัน.

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
| Parameter | Type | Description |
| --- | --- | --- |
| pdfStream | java.io.InputStream | สตรีมที่ใช้เป็นแหล่งที่มาของเอกสาร PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | ตัวเลือกสำหรับการนำเข้า PDF |

**ผลลัพธ์:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

สร้างสไลด์จากข้อความ HTML และเพิ่มลงในส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | java.lang.String | HTML ที่จะเพิ่ม |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | ออบเจ็กต์ callback ที่ใช้ดึงข้อมูลวัตถุภายนอก หากพารามิเตอร์นี้เป็น null วัตถุภายนอกทั้งหมดจะถูกละเว้น |
| uri | java.lang.String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์สัมพัทธ์ |

**ผลลัพธ์:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

สร้างสไลด์จากข้อความ HTML และเพิ่มลงในส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | java.lang.String | HTML ที่จะเพิ่ม |

**ผลลัพธ์:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

สร้างสไลด์จากข้อความ HTML และเพิ่มลงในส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | java.io.InputStream | ออบเจ็กต์ Stream ที่จะใช้เป็นแหล่งที่มาของไฟล์ HTML |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | ออบเจ็กต์ callback ที่ใช้ดึงข้อมูลวัตถุภายนอก หากพารามิเตอร์นี้เป็น null วัตถุภายนอกทั้งหมดจะถูกละเว้น |
| uri | java.lang.String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์สัมพัทธ์ |

**ผลลัพธ์:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

สร้างสไลด์จากข้อความ HTML และเพิ่มลงในส่วนท้ายของคอลเลกชัน.

--------------------

> ```
> // สร้างอินสแตนซ์ของคลาส Presentation.
>  Presentation pres = new Presentation();
>  try {
>      String html = new String(Files.readAllBytes(Paths.get("file.html")));
>      // เรียกเมธอด AddFromHtml และส่งไฟล์ HTML.
>      pres.getSlides().addFromHtml(html);
>      // ใช้เมธอด Save เพื่อบันทึกไฟล์เป็นเอกสาร PowerPoint.
>      pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | java.io.InputStream | ออบเจ็กต์ Stream ที่จะใช้เป็นแหล่งที่มาของไฟล์ HTML |

**ผลลัพธ์:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ตำแหน่งเพื่อแทรก |
| htmlText | java.lang.String | HTML ที่จะเพิ่ม |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | ออบเจ็กต์ callback ที่ใช้ดึงข้อมูลวัตถุภายนอก หากพารามิเตอร์นี้เป็น null วัตถุภายนอกทั้งหมดจะถูกละเว้น |
| uri | java.lang.String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์สัมพัทธ์ |

**ผลลัพธ์:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ตำแหน่งเพื่อแทรก |
| htmlText | java.lang.String | HTML ที่จะเพิ่ม |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | ออบเจ็กต์ callback ที่ใช้ดึงข้อมูลวัตถุภายนอก หากพารามิเตอร์นี้เป็น null วัตถุภายนอกทั้งหมดจะถูกละเว้น |
| uri | java.lang.String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์สัมพัทธ์ |
| useSlideWithIndexAsStart | boolean | ธงนี้กำหนดวิธีเริ่มการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่ระบุ หาก **true** การแทรกข้อมูลจะเริ่มจากพื้นที่ว่างบนสไลด์ที่มีดัชนีที่ระบุ หาก **false** ข้อมูลจะถูกเพิ่มไปยังสไลด์ที่สร้างขึ้น |

**ผลลัพธ์:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ตำแหน่งเพื่อแทรก |
| htmlText | java.lang.String | HTML ที่จะเพิ่ม |

**ผลลัพธ์:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ตำแหน่งเพื่อแทรก |
| htmlText | java.lang.String | HTML ที่จะเพิ่ม |
| useSlideWithIndexAsStart | boolean | ธงนี้กำหนดวิธีเริ่มการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่ระบุ หาก **true** การแทรกข้อมูลจะเริ่มจากพื้นที่ว่างบนสไลด์ที่มีดัชนีที่ระบุ หาก **false** ข้อมูลจะถูกเพิ่มไปยังสไลด์ที่สร้างขึ้น |

**ผลลัพธ์:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ตำแหน่งเพื่อแทรก |
| htmlStream | java.io.InputStream | ออบเจ็กต์ Stream ที่จะใช้เป็นแหล่งที่มาของไฟล์ HTML |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | ออบเจ็กต์ callback ที่ใช้ดึงข้อมูลวัตถุภายนอก หากพารามิเตอร์นี้เป็น null วัตถุภายนอกทั้งหมดจะถูกละเว้น |
| uri | java.lang.String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์สัมพัทธ์ |

**ผลลัพธ์:**
com.aspose.slides.ISSlide[] - สไลด์ที่เพิ่ม

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ตำแหน่งเพื่อแทรก |
| htmlStream | java.io.InputStream | ออบเจ็กต์ Stream ที่จะใช้เป็นแหล่งที่มาของไฟล์ HTML |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | ออบเจ็กต์ callback ที่ใช้ดึงข้อมูลวัตถุภายนอก หากพารามิเตอร์นี้เป็น null วัตถุภายนอกทั้งหมดจะถูกละเว้น |
| uri | java.lang.String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์สัมพัทธ์ |
| useSlideWithIndexAsStart | boolean | ธงนี้กำหนดวิธีเริ่มการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่ระบุ หาก **true** การแทรกข้อมูลจะเริ่มจากพื้นที่ว่างบนสไลด์ที่มีดัชนีที่ระบุ หาก **false** ข้อมูลจะถูกเพิ่มไปยังสไลด์ที่สร้างขึ้น |

**ผลลัพธ์:**
com.aspose.slides.ISSlide[] - สไลด์ที่เพิ่ม

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ตำแหน่งเพื่อแทรก |
| htmlStream | java.io.InputStream | ออบเจ็กต์ Stream ที่จะใช้เป็นแหล่งที่มาของไฟล์ HTML |

**ผลลัพธ์:**
com.aspose.slides.ISSlide[] - สไลด์ที่เพิ่ม

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ตำแหน่งเพื่อแทรก |
| htmlStream | java.io.InputStream | ออบเจ็กต์ Stream ที่จะใช้เป็นแหล่งที่มาของไฟล์ HTML |
| useSlideWithIndexAsStart | boolean | ธงนี้กำหนดวิธีเริ่มการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่ระบุ หาก **true** การแทรกข้อมูลจะเริ่มจากพื้นที่ว่างบนสไลด์ที่มีดัชนีที่ระบุ หาก **false** ข้อมูลจะถูกเพิ่มไปยังสไลด์ที่สร้างขึ้น |

**ผลลัพธ์:**
com.aspose.slides.ISSlide[] - สไลด์ที่เพิ่ม

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์เป้าหมาย |
| index | int | ดัชนีเริ่มต้นในอาร์เรย์เป้าหมาย |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันนั้นถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด) หรือไม่ บูลีนแบบอ่านอย่างเดียว.

**ผลลัพธ์:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนรูทของการซิงโครไนซ์. Object แบบอ่านอย่างเดียว.

**ผลลัพธ์:**
java.lang.Object