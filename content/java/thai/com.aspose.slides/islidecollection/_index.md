---
title: ISlideCollection
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงคอลเลกชันของสไลด์
type: docs
url: /th/com.aspose.slides/islidecollection/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

เป็นคอลเลกชันของสไลด์.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Adds a copy of a specified slide to the end of the collection. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Adds a copy of a specified slide to the end of the specified section. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Inserts a copy of a specified slide to specified position of the collection. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Adds a new empty slide to the end of the collection. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Inserts a copy of a specified slide to specified position of the collection. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Adds a copy of a specified slide to the end of the collection. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Inserts a copy of a specified slide to specified position of the collection. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Adds a copy of a specified source slide to the end of the collection. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Inserts a copy of a specified source slide to specified position of the collection. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Removes the first occurrence of a specific object from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index of the collection. |
| [toArray()](#toArray--) | Creates and returns an array with all slides in it. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Creates and returns an array with all slides from the specified range in it. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Moves slide from the collection to the specified position. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ สไลด์จะถูกวางเริ่มจากตำแหน่งที่กำหนดตามลำดับที่ปรากฏในรายการ. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Returns an index of the specified slide in the collection. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Creates slides from the PDF document and adds them to the end of the collection. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Creates slides from the PDF document and adds them to the end of the collection considering the pdf import options. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Creates slides from the PDF document and adds them to the end of the collection. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Creates slides from the PDF document and adds them to the end of the collection. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Creates slides from HTML text and adds them to the end of the collection. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Creates slides from HTML text and adds them to the end of the collection. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Creates slides from HTML text and adds them to the end of the collection. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Creates slides from HTML text and adds them to the end of the collection. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Creates slides from HTML text and inserts them to the collection at the specified position. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISlide get_Item(int index)
```

ดึงอิลิเมนต์ที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [ISlide](../../com.aspose.slides/islide).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ค่าที่ส่งกลับ:**
[ISlide](../../com.aspose.slides/islide)
### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public abstract ISlide addClone(ISlide sourceSlide)
```

เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่ต้องทำสำเนา.

--------------------

เมื่อทำการสำเนาสไลด์ระหว่างงานนำเสนอที่ต่างกันมาสไลด์มาสเตอร์อาจถูกสำเนาเช่นกัน คลังภายในจะใช้เพื่อติดตามมาสเตอร์ที่ถูกสำเนาโดยอัตโนมัติเพื่อป้องกันการสร้างสำเนาซ้ำของมาสเตอร์สไลด์เดียวกัน การสำเนามาสเตอร์สไลด์ด้วยตนเองจะไม่ถูกป้องกันหรือบันทึก หากต้องการควบคุมกระบวนการสำเนาเพิ่มเติมให้ใช้ \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) หรือ \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) สำหรับการสำเนาสไลด์, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) หรือ [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) สำหรับการสำเนาเลเอาต์และ [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) สำหรับการสำเนามาสเตอร์. |

**ค่าที่ส่งกลับ:**
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
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่ต้องทำสำเนา. |
| section | [ISection](../../com.aspose.slides/isection) | ส่วนสำหรับสไลด์ใหม่. |

**ค่าที่ส่งกลับ:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ใหม่.
### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของสไลด์ใหม่. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่ต้องทำสำเนา.

--------------------

เมื่อทำการสำเนาสไลด์ระหว่างงานนำเสนอที่ต่างกันมาสไลด์มาสเตอร์อาจถูกสำเนาเช่นกัน คลังภายในจะใช้เพื่อติดตามมาสเตอร์ที่ถูกสำเนาโดยอัตโนมัติเพื่อป้องกันการสร้างสำเนาซ้ำของมาสเตอร์สไลด์เดียวกัน การสำเนามาสเตอร์สไลด์ด้วยตนเองจะไม่ถูกป้องกันหรือบันทึก หากต้องการควบคุมกระบวนการสำเนาเพิ่มเติมให้ใช้ \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) หรือ \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) สำหรับการสำเนาสไลด์และ [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) สำหรับการสำเนามาสเตอร์. |

**ค่าที่ส่งกลับ:**
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

**ค่าที่ส่งกลับ:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ที่เพิ่ม.
### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของสไลด์ใหม่. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | เลเอาต์สำหรับสไลด์. |

**ค่าที่ส่งกลับ:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ที่แทรก.
### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่ต้องทำสำเนา. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | เลเอาต์สไลด์สำหรับสไลด์ใหม่. |

**ค่าที่ส่งกลับ:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ใหม่.
### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของสไลด์ใหม่. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่ต้องทำสำเนา. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | เลเอาต์สไลด์สำหรับสไลด์ใหม่. |

**ค่าที่ส่งกลับ:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ที่แทรก.
### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

เพิ่มสำเนาของสไลด์ต้นฉบับที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน เลเอาต์ที่เหมาะสมจะถูกเลือกโดยอัตโนมัติจากมาสเตอร์ที่ระบุ (เลเอาต์ที่เหมาะสมคือเลเอาต์ที่มี Type หรือ Name เดียวกับเลเอาต์ของสไลด์ต้นฉบับ) หากไม่มีเลเอาต์ที่เหมาะสมเลเอาต์ของสไลด์ต้นฉบับจะถูกสำเนา (หาก allowCloneMissingLayout เป็น true) หรือจะเกิด PptxEditException (หาก allowCloneMissingLayout เป็น false).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่ต้องทำสำเนา. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | มาสเตอร์สไลด์สำหรับสไลด์ใหม่. |
| allowCloneMissingLayout | boolean | หากไม่มีเลเอาต์ที่เหมาะสมในมาสเตอร์ที่ระบุเลเอาต์ของสไลด์ต้นฉบับจะถูกสำเนา (หาก allowCloneMissingLayout เป็น true) หรือจะเกิด PptxEditException (หาก allowCloneMissingLayout เป็น false). |

**ค่าที่ส่งกลับ:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ใหม่.
### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

แทรกสำเนาของสไลด์ต้นฉบับที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน เลเอาต์ที่เหมาะสมจะถูกเลือกโดยอัตโนมัติจากมาสเตอร์ที่ระบุ (เลเอาต์ที่เหมาะสมคือเลเอาต์ที่มี Type หรือ Name เดียวกับเลเอาต์ของสไลด์ต้นฉบับ) หากไม่มีเลเอาต์ที่เหมาะสมเลเอาต์ของสไลด์ต้นฉบับจะถูกสำเนา (หาก allowCloneMissingLayout เป็น true) หรือจะเกิด PptxEditException (หาก allowCloneMissingLayout เป็น false).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของสไลด์ใหม่. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่ต้องทำสำเนา. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | มาสเตอร์สไลด์สำหรับสไลด์ใหม่. |
| allowCloneMissingLayout | boolean | หากไม่มีเลเอาต์ที่เหมาะสมในมาสเตอร์ที่ระบุเลเอาต์ของสไลด์ต้นฉบับจะถูกสำเนา (หาก allowCloneMissingLayout เป็น true) หรือจะเกิด PptxEditException (หาก allowCloneMissingLayout เป็น false). |

**ค่าที่ส่งกลับ:**
[ISlide](../../com.aspose.slides/islide) - สไลด์ที่แทรก.
### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

ลบการปรากฏครั้งแรกของอ็อบเจกต์ที่ระบุจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่ต้องลบจากคอลเลกชัน. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบอิลิเมนต์ที่ตำแหน่งที่ระบุจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ของอิลิเมนต์ที่ต้องลบ. |

### toArray() {#toArray--}
```
public abstract ISlide[] toArray()
```

สร้างและส่งกลับอาร์เรย์ที่มีสไลด์ทั้งหมดอยู่ในนั้น.

**ค่าที่ส่งกลับ:**
com.aspose.slides.ISlide[] - อาร์เรย์ของ [ISlide](../../com.aspose.slides/islide)
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract ISlide[] toArray(int startIndex, int count)
```

สร้างและส่งกลับอาร์เรย์ที่มีสไลด์ทั้งหมดจากช่วงที่ระบุอยู่ในนั้น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| startIndex | int | ดัชนีของสไลด์แรกที่ต้องเพิ่ม. |
| count | int | จำนวนสไลด์ที่ต้องเพิ่ม. |

**ค่าที่ส่งกลับ:**
com.aspose.slides.ISlide[] - อาร์เรย์ของ [ISlide](../../com.aspose.slides/islide)
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public abstract void reorder(int index, ISlide slide)
```

ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเป้าหมาย. |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่ต้องย้าย. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public abstract void reorder(int index, ISlide[] slides)
```

ย้ายสไลด์หลายรายการจากคอลเลกชันไปยังตำแหน่งที่ระบุ สไลด์จะถูกวางเริ่มจากดัชนีเป้าหมายตามลำดับที่ปรากฏในรายการ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเป้าหมาย. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | สไลด์ที่ต้องย้าย. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public abstract int indexOf(ISlide slide)
```

ส่งกลับดัชนีของสไลด์ที่ระบุในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ที่ต้องค้นหา. |

**ค่าที่ส่งกลับ:**
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
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| path | java.lang.String | พาธไปยังเอกสาร PDF |

**ผลลัพธ์:**  
com.aspose.slides.ISlide[] - Added slides  
### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

สร้างสไลด์จากเอกสาร PDF และเพิ่มลงท้ายคอลเลกชันโดยคำนึงถึงตัวเลือกการนำเข้า PDF.

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
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| path | java.lang.String | พาธไปยังเอกสาร PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | ตัวเลือกสำหรับการนำเข้า PDF |

**ผลลัพธ์:**  
com.aspose.slides.ISlide[] - Added slides  
### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

สร้างสไลด์จากเอกสาร PDF และเพิ่มลงท้ายคอลเลกชัน.

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
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| pdfStream | java.io.InputStream | สตรีมที่ใช้เป็นแหล่งของเอกสาร PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | ตัวเลือกสำหรับการนำเข้า PDF |

**ผลลัพธ์:**  
com.aspose.slides.ISlide[] - Added slides  
### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
```

สร้างสไลด์จากเอกสาร PDF และเพิ่มลงท้ายคอลเลกชัน.

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
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| pdfStream | java.io.InputStream | สตรีมที่ใช้เป็นแหล่งของเอกสาร PDF |

**ผลลัพธ์:**  
com.aspose.slides.ISlide[] - Added slides  
### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

สร้างสไลด์จากข้อความ HTML และเพิ่มลงท้ายคอลเลกชัน.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| htmlText | java.lang.String | HTML ที่จะเพิ่ม. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | อ็อบเจ็กต์ callback ที่ใช้ในการดึงวัตถุต่าง ๆ ภายนอก หากพารามิเตอร์นี้เป็น null วัตถุภายนอกทั้งหมดจะถูกละเว้น. |
| uri | java.lang.String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์แบบ relative. |

**ผลลัพธ์:**  
com.aspose.slides.ISlide[] - Added slides.  
### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
```

สร้างสไลด์จากข้อความ HTML และเพิ่มลงท้ายคอลเลกชัน.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| htmlText | java.lang.String | HTML ที่จะเพิ่ม. |

**ผลลัพธ์:**  
com.aspose.slides.ISlide[] - Added slides  
### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

สร้างสไลด์จากข้อความ HTML และเพิ่มลงท้ายคอลเลกชัน.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| htmlStream | java.io.InputStream | อ็อบเจ็กต์ Stream ที่จะใช้เป็นแหล่งของไฟล์ HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | อ็อบเจ็กต์ callback ที่ใช้ในการดึงวัตถุต่าง ๆ ภายนอก หากพารามิเตอร์นี้เป็น null วัตถุภายนอกทั้งหมดจะถูกละเว้น. |
| uri | java.lang.String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์แบบ relative. |

**ผลลัพธ์:**  
com.aspose.slides.ISlide[] - Added slides.  
### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```

สร้างสไลด์จากข้อความ HTML และเพิ่มลงท้ายคอลเลกชัน.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| htmlStream | java.io.InputStream | อ็อบเจ็กต์ Stream ที่จะใช้เป็นแหล่งของไฟล์ HTML. |

**ผลลัพธ์:**  
com.aspose.slides.ISlide[] - Added slides  
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| index | int | ตำแหน่งที่จะใส่. |
| htmlText | java.lang.String | HTML ที่จะเพิ่ม. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | อ็อบเจ็กต์ callback ที่ใช้ในการดึงวัตถุต่าง ๆ ภายนอก หากพารามิเตอร์นี้เป็น null วัตถุภายนอกทั้งหมดจะถูกละเว้น. |
| uri | java.lang.String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์แบบ relative. |

**ผลลัพธ์:**  
com.aspose.slides.ISlide[] - Added slides.  
### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| index | int | ตำแหน่งที่จะใส่. |
| htmlText | java.lang.String | HTML ที่จะเพิ่ม. |

**ผลลัพธ์:**  
com.aspose.slides.ISlide[] - Added slides  
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| index | int | ตำแหน่งที่จะใส่. |
| htmlStream | java.io.InputStream | อ็อบเจ็กต์ Stream ที่จะใช้เป็นแหล่งของไฟล์ HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | อ็อบเจ็กต์ callback ที่ใช้ในการดึงวัตถุต่าง ๆ ภายนอก หากพารามิเตอร์นี้เป็น null วัตถุภายนอกทั้งหมดจะถูกละเว้น. |
| uri | java.lang.String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์แบบ relative. |

**ผลลัพธ์:**  
com.aspose.slides.ISlide[] - Added slides.  
### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| index | int | ตำแหน่งที่จะใส่. |
| htmlStream | java.io.InputStream | อ็อบเจ็กต์ Stream ที่จะใช้เป็นแหล่งของไฟล์ HTML. |

**ผลลัพธ์:**  
com.aspose.slides.ISlide[] - Added slides  
### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| index | int | ตำแหน่งที่จะใส่. |
| htmlText | java.lang.String | HTML ที่จะเพิ่ม. |
| useSlideWithIndexAsStart | boolean | ค่าสถานะนี้กำหนดวิธีการเริ่มต้นการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่กำหนด หาก **true** การแทรกข้อมูลจะเริ่มจากพื้นที่ว่างบนสไลด์ที่มีดัชนีนั้น หาก **false** ข้อมูลจะถูกเพิ่มไปยังสไลด์ที่สร้างขึ้น. |

**ผลลัพธ์:**  
com.aspose.slides.ISlide[] - Added slides  
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| index | int | ตำแหน่งที่จะใส่. |
| htmlText | java.lang.String | HTML ที่จะเพิ่ม. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | อ็อบเจ็กต์ callback ที่ใช้ในการดึงวัตถุต่าง ๆ ภายนอก หากพารามิเตอร์นี้เป็น null วัตถุภายนอกทั้งหมดจะถูกละเว้น. |
| uri | java.lang.String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์แบบ relative. |
| useSlideWithIndexAsStart | boolean | ค่าสถานะนี้กำหนดวิธีการเริ่มต้นการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่กำหนด หาก **true** การแทรกข้อมูลจะเริ่มจากพื้นที่ว่างบนสไลด์ที่มีดัชนีนั้น หาก **false** ข้อมูลจะถูกเพิ่มไปยังสไลด์ที่สร้างขึ้น. |

**ผลลัพธ์:**  
com.aspose.slides.ISlide[] - Added slides.  
### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| index | int | ตำแหน่งที่จะใส่. |
| htmlStream | java.io.InputStream | อ็อบเจ็กต์ Stream ที่จะใช้เป็นแหล่งของไฟล์ HTML. |
| useSlideWithIndexAsStart | boolean | ค่าสถานะนี้กำหนดวิธีการเริ่มต้นการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่กำหนด หาก **true** การแทรกข้อมูลจะเริ่มจากพื้นที่ว่างบนสไลด์ที่มีดัชนีนั้น หาก **false** ข้อมูลจะถูกเพิ่มไปยังสไลด์ที่สร้างขึ้น. |

**ผลลัพธ์:**  
com.aspose.slides.ISlide[] - Added slides  
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| index | int | ตำแหน่งที่จะใส่. |
| htmlStream | java.io.InputStream | อ็อบเจ็กต์ Stream ที่จะใช้เป็นแหล่งของไฟล์ HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | อ็อบเจ็กต์ callback ที่ใช้ในการดึงวัตถุต่าง ๆ ภายนอก หากพารามิเตอร์นี้เป็น null วัตถุภายนอกทั้งหมดจะถูกละเว้น. |
| uri | java.lang.String | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์แบบ relative. |
| useSlideWithIndexAsStart | boolean | ค่าสถานะนี้กำหนดวิธีการเริ่มต้นการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่กำหนด หาก **true** การแทรกข้อมูลจะเริ่มจากพื้นที่ว่างบนสไลด์ที่มีดัชนีนั้น หาก **false** ข้อมูลจะถูกเพิ่มไปยังสไลด์ที่สร้างขึ้น. |

**ผลลัพธ์:**  
com.aspose.slides.ISlide[] - Added slides.