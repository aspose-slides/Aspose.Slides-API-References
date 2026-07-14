---
title: IMasterLayoutSlideCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงคอลเลกชันของสไลด์เลเอาต์ทั้งหมดที่กำหนดไว้ในมาสเตอร์สไลด์.
type: docs
url: /th/com.aspose.slides/imasterlayoutslidecollection/
---
**อินเทอร์เฟซที่ทำการ implements ทั้งหมด:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

แทนชุดของสไลด์เลเอาต์ทั้งหมดของมาสเตอร์สไลด์ที่กำหนดไว้. ขยายอินเทอร์เฟซ ILayoutSlideCollection ด้วยเมธอดสำหรับการเพิ่ม/แทรก/ลบ/โคลนสไลด์เลเอาต์ในบริบทของคอลเลกชันสไลด์เลเอาต์ของมาสเตอร์แต่ละอัน.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | เพิ่มสำเนาของสไลด์เลเอาต์ที่ระบุไปที่ตำแหน่งสุดท้ายของคอลเลกชัน. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | แทรกสำเนาของสไลด์เลเอาต์ที่ระบุไปยังตำแหน่งที่กำหนดของคอลเลกชัน. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | เพิ่มสไลด์เลเอาต์ใหม่ไปที่ตำแหน่งสุดท้ายของคอลเลกชัน. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | แทรกสไลด์เลเอาต์ใหม่ไปยังตำแหน่งที่กำหนดของคอลเลกชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบองค์ประกอบที่ตำแหน่งตามดัชนีที่ระบุจากคอลเลกชัน. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | ย้ายสไลด์เลเอาต์จากคอลเลกชันไปยังตำแหน่งที่กำหนด. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

เพิ่มสำเนาของสไลด์เลเอาต์ที่ระบุไปที่ตำแหน่งสุดท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | สไลด์ที่จะโคลน. |

--------------------
1) เลเอาต์ใหม่จะถูกเชื่อมโยงกับมาสเตอร์สไลด์พ่อแม่สำหรับคอลเลกชันสไลด์เลเอาต์นี้ ดังนั้นจึงเป็นลักษณะคล้ายการคัดลอก/วางโดยใช้ตัวเลือก "Use Destination Theme" ใน PowerPoint. 2) วิธีการที่คล้ายกับเมธอดนี้คือเมธอด [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) ที่เข้าถึงผ่านคุณสมบัติ [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**ผลลัพธ์:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - สไลด์ที่เพิ่ม.

### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

แทรกสำเนาของสไลด์เลเอาต์ที่ระบุไปยังตำแหน่งที่กำหนดของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของสไลด์ใหม่. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | สไลด์ที่จะโคลน. |

--------------------
เลเอาต์ใหม่จะถูกเชื่อมโยงกับมาสเตอร์สไลด์พ่อแม่สำหรับคอลเลกชันสไลด์เลเอาต์นี้ ดังนั้นจึงเป็นลักษณะคล้ายการคัดลอก/วางโดยใช้ตัวเลือก "Use Destination Theme" ใน PowerPoint.

**ผลลัพธ์:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - สไลด์ที่แทรก.

### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```

เพิ่มสไลด์เลเอาต์ใหม่ไปที่ตำแหน่งสุดท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| layoutType | byte | ชนิดเลเอาต์สำหรับเลเอาต์ใหม่. ชนิดเลเอาต์ที่รองรับ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. ชนิดเลเออต์อื่นๆ ไม่รองรับในขณะนี้: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | ชื่อสำหรับเลเอาต์ใหม่. หากชื่อที่ระบุมีการใช้แล้วจะเกิด ArgumentException. หากพารามิเตอร์เป็น null จะสร้างชื่อโดยอัตโนมัติตามชนิดเลเอาต์ที่ระบุ (เช่น "Title Slide" หรือ "1_Title Slide", "2_.." เป็นต้น). |

--------------------
1) เพิ่มเลเอาต์สำหรับค่า SlideLayoutType.Custom ของ layoutType โดยไม่มีตัวแทนและรูปทรงใดๆ. 2) วิธีการที่คล้ายกับเมธอดนี้คือเมธอด [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) ที่เข้าถึงผ่านคุณสมบัติ [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**ผลลัพธ์:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - สไลด์ที่เพิ่ม.

### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

แทรกสไลด์เลเอาต์ใหม่ไปยังตำแหน่งที่กำหนดของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของสไลด์ใหม่. |
| layoutType | byte | ชนิดเลเอาต์สำหรับเลเอาต์ใหม่. ชนิดเลเอาต์ที่รองรับ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. ชนิดเลเอาต์อื่นๆ ไม่รองรับในขณะนี้: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | ชื่อสำหรับเลเอาต์ใหม่. หากชื่อที่ระบุมีการใช้แล้วจะเกิด ArgumentException. หากพารามิเตอร์เป็น null จะสร้างชื่อโดยอัตโนมัติตามชนิดเลเออต์ที่ระบุ (เช่น "Title Slide" หรือ "1_Title Slide", "2_.." เป็นต้น). |

--------------------
เลเอาต์ที่แทรกสำหรับค่า SlideLayoutType.Custom ของ layoutType โดยไม่มีตัวแทนและรูปทรงใดๆ.

**ผลลัพธ์:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - สไลด์ที่แทรก.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบองค์ประกอบที่ตำแหน่งตามดัชนีที่ระบุจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มต้นจากศูนย์ขององค์ประกอบที่ต้องการลบ. |

--------------------
1) เพื่อหลีกเลี่ยงการโยน PptxEditException ให้ตรวจสอบคุณสมบัติ HasDependingSlides ของเลเอ็ตก่อน. 2) คุณสามารถใช้เมธอด [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) เพื่อทำให้โค้ดง่ายขึ้น.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```

ย้ายสไลด์เลเอาต์จากคอลเลกชันไปยังตำแหน่งที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเป้าหมาย. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | สไลด์ที่จะย้าย. |