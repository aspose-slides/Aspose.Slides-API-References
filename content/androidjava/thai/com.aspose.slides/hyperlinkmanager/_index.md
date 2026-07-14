---
title: HyperlinkManager
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: จัดการไฮเปอร์ลิงก์โดยการเพิ่มและลบ
type: docs
url: /th/com.aspose.slides/hyperlinkmanager/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**  
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject  
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

จัดการไฮเปอร์ลิงก์ (เพิ่ม, ลบ)  
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | ตั้งค่าไฮเปอร์ลิงก์ภายนอกเมื่อคลิก |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | ตั้งค่าไฮเปอร์ลิงก์ภายในเมื่อคลิก |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | ลบไฮเปอร์ลิงก์เมื่อคลิก |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | ตั้งค่าไฮเปอร์ลิงก์ภายนอกเมื่อเมาส์อยู่เหนือ |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | ตั้งค่าไฮเปอร์ลิงก์ภายในเมื่อเมาส์อยู่เหนือ |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | ลบไฮเปอร์ลิงก์เมื่อเมาส์อยู่เหนือ |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | ตั้งค่าไฮเปอร์ลิงก์แมโครเมื่อคลิก |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```

ตั้งค่าไฮเปอร์ลิงก์ภายนอกเมื่อคลิก

--------------------

> ```
> ตัวอย่างโค้ดต่อไปนี้แสดงวิธีเพิ่มกล่องข้อความพร้อมไฮเปอร์ลิงก์.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation ที่แสดงถึงไฟล์ PPTX
>  Presentation pres = new Presentation();
>  try {
>      // ดึงสไลด์แรกในงานนำเสนอ
>      ISlide slide = pres.getSlides().get_Item(0);
>      // เพิ่มอ็อบเจ็กต์ AutoShape โดยกำหนดประเภทเป็น Rectangle
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // แคสต์รูปทรงเป็น AutoShape
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // เข้าถึงคุณสมบัติ ITextFrame ที่เชื่อมกับ AutoShape
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // เพิ่มข้อความบางส่วนลงในเฟรม
>      portion.setText("Aspose.Slides");
>      // ตั้งค่าไฮเปอร์ลิงก์สำหรับข้อความส่วน
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // บันทึกงานนำเสนอ PPTX
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| url | java.lang.String | URL ของไฮเปอร์ลิงก์ |

**คืนค่า:**  
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

ตั้งค่าไฮเปอร์ลิงก์ภายในเมื่อคลิก

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์เป้าหมาย |

**คืนค่า:**  
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```

ลบไฮเปอร์ลิงก์เมื่อคลิก

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```

ตั้งค่าไฮเปอร์ลิงก์ภายนอกเมื่อเมาส์อยู่เหนือ

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| url | java.lang.String | URL ของไฮเปอร์ลิงก์ |

**คืนค่า:**  
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

ตั้งค่าไฮเปอร์ลิงก์ภายในเมื่อเมาส์อยู่เหนือ

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์เป้าหมาย |

**คืนค่า:**  
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```

ลบไฮเปอร์ลิงก์เมื่อเมาส์อยู่เหนือ

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```

ตั้งค่าไฮเปอร์ลิงก์แมโครเมื่อคลิก

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.BlankButton, 20, 20, 80, 30);
>      shape.getHyperlinkManager().setMacroHyperlinkClick("MacroName");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| macroName | java.lang.String | ชื่อของแมโคร |

**คืนค่า:**  
[IHyperlink](../../com.aspose.slides/ihyperlink) - อ็อบเจ็กต์ Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่าอ็อบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**  
com.aspose.slides.IDOMObject