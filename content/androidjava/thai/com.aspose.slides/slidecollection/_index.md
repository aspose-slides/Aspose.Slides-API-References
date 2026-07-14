---
title: SlideCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
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

แสดงถึงคอลเลกชันของสไลด์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | รับจำนวนขององค์ประกอบที่แท้จริงที่อยู่ในคอลเลกชัน |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบที่ตำแหน่งที่กำหนด |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของส่วนที่ระบุ |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่กำหนดของคอลเลกชัน |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | เพิ่มสไลด์เปล่าใหม่ไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่กำหนดของคอลเลกชัน |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่กำหนดของคอลเลกชัน |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | เพิ่มสำเนาของสไลด์แหล่งที่มาที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | แทรกสำเนาของสไลด์แหล่งที่มาที่ระบุไปยังตำแหน่งที่กำหนดของคอลเลกชัน |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | ลบการปรากฏครั้งแรกของอ็อบเจ็กต์ที่ระบุจากคอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบองค์ประกอบที่ตำแหน่งที่ระบุของคอลเลกชัน |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด |
| [toArray()](#toArray--) | สร้างและคืนค่าอาร์เรย์ที่มีสไลด์ทั้งหมด |
| [toArray(int startIndex, int count)](#toArray-int-int-) | สร้างและคืนค่าอาร์เรย์ที่มีสไลด์จากช่วงที่ระบุ |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | คืนค่าตำแหน่งของสไลด์ที่ระบุในคอลเลกชัน |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | สร้างสไลด์จากเอกสาร PDF และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | สร้างสไลด์จากเอกสาร PDF และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันโดยคำนึงถึงตัวเลือกการนำเข้า PDF |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | สร้างสไลด์จากเอกสาร PDF และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | สร้างสไลด์จากเอกสาร PDF และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | สร้างสไลด์จากข้อความ HTML และแทรกไปยังคอลเลกชันที่ตำแหน่งที่ระบุ |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | สร้างสไลด์จากข้อความ HTML และแทรกไปยังคอลเลกชันที่ตำแหน่งที่ระบุ |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | สร้างสไลด์จากข้อความ HTML และแทรกไปยังคอลเลกชันที่ตำแหน่งที่ระบุ |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | สร้างสไลด์จากข้อความ HTML และแทรกไปยังคอลเลกชันที่ตำแหน่งที่ระบุ |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | สร้างสไลด์จากข้อความ HTML และแทรกไปยังคอลเลกชันที่ตำแหน่งที่ระบุ |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | สร้างสไลด์จากข้อความ HTML และแทรกไปยังคอลเลกชันที่ตำแหน่งที่ระบุ |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | สร้างสไลด์จากข้อความ HTML และแทรกไปยังคอลเลกชันที่ตำแหน่งที่ระบุ |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | สร้างสไลด์จากข้อความ HTML และแทรกไปยังคอลเลกชันที่ตำแหน่งที่ระบุ |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | คืนค่าชนิดที่บ่งบอกว่าการเข้าถึงคอลเลกชันทำได้อย่างประสาน (ปลอดภัยต่อเธรด) |
| [getSyncRoot()](#getSyncRoot--) | คืนค่ารากของการประสาน |
### size() {#size--}
```
public final int size()
```

รับจำนวนขององค์ประกอบที่แท้จริงที่อยู่ในคอลเลกชัน อ่านอย่างเดียว int.

**คืนค่า:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

รับองค์ประกอบที่ตำแหน่งที่กำหนด อ่านอย่างเดียว [Slide](../../com.aspose.slides/slide).

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

เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะคัดลอก |

--------------------

เมื่อทำการคัดลอกสไลด์ระหว่างงานนำเสนอที่ต่างกัน มาสเตอร์ของสไลด์อาจถูกคัดลอกด้วย ระบบทะเบียนภายในจะใช้เพื่อติดตามมาสเตอร์ที่ถูกคัดลอกอัตโนมัติเพื่อป้องกันการสร้างสำเนาหลายชุดของมาสเตอร์เดียวกัน การคัดลอกมาสเตอร์แบบมือจะไม่ได้รับการป้องกันหรือบันทึก หากต้องการควบคุมขั้นตอนการคัดลอกเพิ่มเติมให้ใช้ \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) หรือ \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) เพื่อคัดลอกสไลด์, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) หรือ [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) เพื่อคัดลอกเลย์เอาต์และ [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) เพื่อคัดลอกมาสเตอร์ |

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ใหม่
### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
```

เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของส่วนที่ระบุ

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
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะคัดลอก |
| section | [ISection](../../com.aspose.slides/isection) | ส่วนสำหรับสไลด์ใหม่ |

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ใหม่
### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่กำหนดของคอลเลกชัน

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation ที่แทนไฟล์งานนำเสนอ
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // คัดลอกสไลด์ที่ต้องการไปยังตำแหน่งสุดท้ายของคอลเลกชันสไลด์ในงานนำเสนอเดียวกัน
>      ISlideCollection slds = pres.getSlides();
>      // คัดลอกสไลด์ที่ต้องการไปยังตำแหน่งที่ระบุในงานนำเสนอเดียวกัน
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // เขียนงานนำเสนอที่แก้ไขแล้วลงดิสก์
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation เพื่อโหลดไฟล์งานนำแหล่ง
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // สร้างอินสแตนซ์ของคลาส Presentation สำหรับไฟล์ PPTX ปลายทาง (ที่สไลด์จะถูกคัดลอก)
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // เขียนงานนำเสนอปลายทางลงดิสก์
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
| index | int | ตำแหน่งของสไลด์ใหม่ |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะคัดลอก |

--------------------

เมื่อทำการคัดลอกสไลด์ระหว่างงานนำเสนอที่ต่างกัน มาสเตอร์ของสไลด์อาจถูกคัดลอกด้วย ระบบทะเบียนภายในจะใช้เพื่อติดตามมาสเตอร์ที่ถูกคัดลอกอัตโนมัติเพื่อป้องกันการสร้างสำเนาหลายชุดของมาสเตอร์เดียวกัน การคัดลอกมาสเตอร์แบบมือจะไม่ได้รับการป้องกันหรือบันทึก หากต้องการควบคุมขั้นตอนการคัดลอกเพิ่มเติมให้ใช้ \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) หรือ \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) เพื่อคัดลอกสไลด์และ [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) เพื่อคัดลอกมาสเตอร์ |

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ที่แทรก
### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

เพิ่มสไลด์เปล่าใหม่ไปยังตำแหน่งสุดท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | เลย์เอาต์สำหรับสไลด์ |

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ที่เพิ่ม
### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่กำหนดของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งของสไลด์ใหม่ |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | เลย์เอาต์สำหรับสไลด์ |

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ที่แทรก
### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะคัดลอก |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | เลย์เอาต์สไลด์สำหรับสไลด์ใหม่ |

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ใหม่
### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่กำหนดของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งของสไลด์ใหม่ |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะคัดลอก |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | เลย์เอาต์สไลด์สำหรับสไลด์ใหม่ |

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ที่แทรก
### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

เพิ่มสำเนาของสไลด์แหล่งที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน เลย์เอาต์ที่เหมาะสมจะถูกเลือกโดยอัตโนมัติจากมาสเตอร์ที่ระบุ (เลย์เอาต์ที่เหมาะสมคือเลย์เอาต์ที่มี Type หรือ Name เท่ากับของเลย์เอาต์ในสไลด์แหล่ง) หากไม่มีเลย์เอาต์ที่เหมาะสม เลย์เอาต์ของสไลด์แหล่งจะถูกคัดลอก (หาก allowCloneMissingLayout เป็น true) หรือจะเกิดข้อยกเว้น PptxEditException (หาก allowCloneMissingLayout เป็น false)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะคัดลอก |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | มาสเตอร์สไลด์สำหรับสไลด์ใหม่ |
| allowCloneMissingLayout | boolean | หากไม่มีเลย์เอาต์ที่เหมาะสมในมาสเตอร์ที่ระบุ เลย์เอาต์ของสไลด์แหล่งจะถูกคัดลอก (ถ้า allowCloneMissingLayout เป็น true) หรือจะเกิดข้อยกเว้น PptxEditException (ถ้า allowCloneMissingLayout เป็น false) |

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ใหม่
### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

แทรกสำเนาของสไลด์แหล่งที่ระบุไปยังตำแหน่งที่กำหนดของคอลเลกชัน เลย์เอาต์ที่เหมาะสมจะถูกเลือกโดยอัตโนมัติจากมาสเตอร์ที่ระบุ (เลย์เอาต์ที่เหมาะสมคือเลย์เอาต์ที่มี Type หรือ Name เท่ากับของเลย์เอาต์ในสไลด์แหล่ง) หากไม่มีเลย์เอาต์ที่เหมาะสม เลย์เอาต์ของสไลด์แหล่งจะถูกคัดลอก (หาก allowCloneMissingLayout เป็น true) หรือจะเกิดข้อยกเว้น PptxEditException (หาก allowCloneMissingLayout เป็น false)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งของสไลด์ใหม่ |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะคัดลอก |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | มาสเตอร์สไลด์สำหรับสไลด์ใหม่ |
| allowCloneMissingLayout | boolean | หากไม่มีเลย์เอาต์ที่เหมาะสมในมาสเตอร์ที่ระบุ เลย์เอาต์ของสไลด์แหล่งจะถูกคัดลอก (ถ้า allowCloneMissingLayout เป็น true) หรือจะเกิดข้อยกเว้น PptxEditException (ถ้า allowCloneMissingLayout เป็น false) |

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ที่แทรก
### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

ลบการปรากฏครั้งแรกของอ็อบเจ็กต์ที่ระบุจากคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะลบจากคอลเลกชัน |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบองค์ประกอบที่ตำแหน่งที่ระบุของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มต้นตั้งแต่ศูนย์ขององค์ประกอบที่จะลบ |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

คืนค่า enumerator ที่วนผ่านคอลเลกชัน

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - IGenericEnumerator ที่สามารถใช้เพื่อวนผ่านคอลเลกชัน
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด
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
| startIndex | int | ดัชนีของสไลด์แรกที่จะเพิ่ม |
| count | int | จำนวนสไลด์ที่จะเพิ่ม |

**คืนค่า:**
com.aspose.slides.ISlide[] - อาร์เรย์ของ [Slide](../../com.aspose.slides/slide)
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเป้าหมาย |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะย้าย |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ สไลด์จะถูกวางเริ่มจากดัชนีตามลำดับที่ปรากฏในรายการ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเป้าหมาย |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | สไลด์ที่จะย้าย |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```

คืนค่าตำแหน่งของสไลด์ที่ระบุในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่จะค้นหา |

**คืนค่า:**
int - ดัชนีของสไลด์หรือ -1 หากสไลด์ไม่อยู่ในคอลเลกชันนี้
### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```

สร้างสไลด์จากเอกสาร PDF และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน

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

**คืนค่า:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม
### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

สร้างสไลด์จากเอกสาร PDF และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันโดยคำนึงถึงตัวเลือกการนำเข้า PDF

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

**คืนค่า:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม
### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```

สร้างสไลด์จากเอกสาร PDF และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน

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
| pdfStream | java.io.InputStream | สตรีมที่จะใช้เป็นแหล่งของเอกสาร PDF |

**คืนค่า:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม
### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

สร้างสไลด์จากเอกสาร PDF และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน

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
| pdfStream | java.io.InputStream | สตรีมที่จะใช้เป็นแหล่งของเอกสาร PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | ตัวเลือกสำหรับการนำเข้า PDF |

**คืนค่า:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม
### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| htmlText | java.lang.String | HTML ที่จะเพิ่ม |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | วัตถุ callback ที่ใช้ดึงอ็อบเจ็กต์ภายนอก หากค่าเป็น null จะละเว้นอ็อบเจ็กต์ภายนอกทั้งหมด |
| uri | java.lang.String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ลิงก์สัมพันธ์ |

**คืนค่า:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม
### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| htmlText | java.lang.String | HTML ที่จะเพิ่ม |

**คืนค่า:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม
### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| htmlStream | java.io.InputStream | วัตถุ Stream ที่ใช้เป็นแหล่งของไฟล์ HTML |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | วัตถุ callback ที่ใช้ดึงอ็อบเจ็กต์ภายนอก หากค่าเป็น null จะละเว้นอ็อบเจ็กต์ภายนอกทั้งหมด |
| uri | java.lang.String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ลิงก์สัมพันธ์ |

**คืนค่า:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม
### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน

--------------------

> ```
> // สร้างอินสแตนซ์ของคลาส Presentation.
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("file.html");
>          // เรียกเมธอด AddFromHtml และส่งไฟล์ HTML.
>          pres.getSlides().addFromHtml(fos);
>          // ใช้เมธอด Save เพื่อบันทึกไฟล์เป็นเอกสาร PowerPoint.
>          pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| htmlStream | java.io.InputStream | วัตถุ Stream ที่ใช้เป็นแหล่งของไฟล์ HTML |

**คืนค่า:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

สร้างสไลด์จากข้อความ HTML และแทรกไปยังคอลเลกชันที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งที่จะใส่ |
| htmlText | java.lang.String | HTML ที่จะเพิ่ม |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | วัตถุ callback ที่ใช้ดึงอ็อบเจ็กต์ภายนอก หากค่าเป็น null จะละเว้นอ็อบเจ็กต์ภายนอกทั้งหมด |
| uri | java.lang.String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ลิงก์สัมพันธ์ |

**คืนค่า:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

สร้างสไลด์จากข้อความ HTML และแทรกไปยังคอลเลกชันที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งที่จะใส่ |
| htmlText | java.lang.String | HTML ที่จะเพิ่ม |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | วัตถุ callback ที่ใช้ดึงอ็อบเจ็กต์ภายนอก หากค่าเป็น null จะละเว้นอ็อบเจ็กต์ภายนอกทั้งหมด |
| uri | java.lang.String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ลิงก์สัมพันธ์ |
| useSlideWithIndexAsStart | boolean | ธงนี้กำหนดวิธีเริ่มการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่ตำแหน่งที่ระบุ หาก **true** การแทรกข้อมูลจะเริ่มจากพื้นที่ว่างบนสไลด์ที่ตำแหน่งที่ระบุ หาก **false** ข้อมูลจะถูกเพิ่มลงบนสไลด์ที่สร้างขึ้น |

**คืนค่า:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม
### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

สร้างสไลด์จากข้อความ HTML และแทรกไปยังคอลเลกชันที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งที่จะใส่ |
| htmlText | java.lang.String | HTML ที่จะเพิ่ม |

**คืนค่า:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม
### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

สร้างสไลด์จากข้อความ HTML และแทรกไปยังคอลเลกชันที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งที่จะใส่ |
| htmlText | java.lang.String | HTML ที่จะเพิ่ม |
| useSlideWithIndexAsStart | boolean | ธ.Flagsนี้กำหนดวิธีเริ่มการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่ตำแหน่งที่ระบุ หาก **true** การแทรกข้อมูลจะเริ่มจากพื้นที่ว่างบนสไลด์ที่ตำแหน่งที่ระบุ หาก **false** ข้อมูลจะถูกเพิ่มลงบนสไลด์ที่สร้างขึ้น |

**คืนค่า:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

สร้างสไลด์จากข้อความ HTML และแทรกไปยังคอลเลกชันที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งที่จะใส่ |
| htmlStream | java.io.InputStream | วัตถุ Stream ที่ใช้เป็นแหล่งของไฟล์ HTML |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | วัตถุ callback ที่ใช้ดึงอ็อบเจ็กต์ภายนอก หากค่าเป็น null จะละเว้นอ็อบเจ็กต์ภายนอกทั้งหมด |
| uri | java.lang.String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ลิงก์สัมพันธ์ |

**คืนค่า:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

สร้างสไลด์จากข้อความ HTML และแทรกไปยังคอลเลกชันที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งที่จะใส่ |
| htmlStream | java.io.InputStream | วัตถุ Stream ที่ใช้เป็นแหล่งของไฟล์ HTML |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | วัตถุ callback ที่ใช้ดึงอ็อบเจ็กต์ภายนอก หากค่าเป็น null จะละเว้นอ็อบเจ็กต์ภายนอกทั้งหมด |
| uri | java.lang.String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ลิงก์สัมพันธ์ |
| useSlideWithIndexAsStart | boolean | ธ.Flagsนี้กำหนดวิธีเริ่มการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่ตำแหน่งที่ระบุ หาก **true** การแทรกข้อมูลจะเริ่มจากพื้นที่ว่างบนสไลด์ที่ตำแหน่งที่ระบุ หาก **false** ข้อมูลจะถูกเพิ่มลงบนสไลด์ที่สร้างขึ้น |

**คืนค่า:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม
### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

สร้างสไลด์จากข้อความ HTML และแทรกไปยังคอลเลกชันที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งที่จะใส่ |
| htmlStream | java.io.InputStream | วัตถุ Stream ที่ใช้เป็นแหล่งของไฟล์ HTML |

**คืนค่า:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม
### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

สร้างสไลด์จากข้อความ HTML และแทรกไปยังคอลเลกชันที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งที่จะใส่ |
| htmlStream | java.io.InputStream | วัตถุ Stream ที่ใช้เป็นแหล่งของไฟล์ HTML |
| useSlideWithIndexAsStart | boolean | ธ.Flagsนี้กำหนดวิธีเริ่มการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่ตำแหน่งที่ระบุ หาก **true** การแทรกข้อมูลจะเริ่มจากพื้นที่ว่างบนสไลด์ที่ตำแหน่งที่ระบุ หาก **false** ข้อมูลจะถูกเพิ่มลงบนสไลด์ที่สร้างขึ้น |

**คืนค่า:**
com.aspose.slides.ISlide[] - สไลด์ที่เพิ่ม
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์เป้าหมาย |
| index | int | ดัชนีเริ่มต้นในอาร์เรย์เป้าหมาย |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าชนิดที่บ่งบอกว่าการเข้าถึงคอลเลกชันทำได้อย่างประสาน (ปลอดภัยต่อเธรด) อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนค่ารากของการประสาน อ่านอย่างเดียว Object.

**คืนค่า:**
java.lang.Object