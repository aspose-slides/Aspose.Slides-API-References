---
title: HyperlinkManager
second_title: Aspose.Slides สำหรับ Java API อ้างอิง
description: ให้การจัดการลิงก์ไฮเปอร์ การเพิ่มและการลบ
type: docs
url: /th/com.aspose.slides/hyperlinkmanager/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

จัดการลิงก์ไฮเปอร์ (เพิ่ม, ลบ)
## Methods

| เมธอด | คำอธิบาย |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | ตั้งค่าลิงก์ไฮเปอร์ภายนอกเมื่อคลิก |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | ตั้งค่าลิงก์ไฮเปอร์ภายในเมื่อคลิก |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | ลบลิงก์ไฮเปอร์เมื่อคลิก |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | ตั้งค่าลิงก์ไฮเปอร์ภายนอกเมื่อเอาเมาส์ไปชี้ |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | ตั้งค่าลิงก์ไฮเปอร์ภายในเมื่อเอาเมาส์ไปชี้ |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | ลบลิงก์ไฮเปอร์เมื่อเอาเมาส์ไปชี้ |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | ตั้งค่าลิงก์ไฮเปอร์แมโครเมื่อคลิก |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```


ตั้งค่าลิงก์ไฮเปอร์ภายนอกเมื่อคลิก

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation ที่เป็นตัวแทนของ PPTX
>  Presentation pres = new Presentation();
>  try {
>      // รับสไลด์แรกในพรีเซนเทชัน
>      ISlide slide = pres.getSlides().get_Item(0);
>      // เพิ่มอ็อบเจ็กต์ AutoShape ที่ประเภทกำหนดเป็น Rectangle
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // แคสต์รูปร่างเป็น AutoShape
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // เข้าถึงคุณสมบัติ ITextFrame ที่เชื่อมโยงกับ AutoShape
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // เพิ่มข้อความบางส่วนลงในเฟรม
>      portion.setText("Aspose.Slides");
>      // ตั้งค่าลิงก์ไฮเปอร์สำหรับข้อความส่วน
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // บันทึกพรีเซนเทชัน PPTX
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| url | java.lang.String | URL ของลิงก์ไฮเปอร์ |

**Returns:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```


ตั้งค่าลิงก์ไฮเปอร์ภายในเมื่อคลิก

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์เป้าหมาย |

**Returns:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```


ลบลิงก์ไฮเปอร์เมื่อคลิก

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```


ตั้งค่าลิงก์ไฮเปอร์ภายนอกเมื่อเอาเมาส์ไปชี้

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| url | java.lang.String | URL ของลิงก์ไฮเปอร์ |

**Returns:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```


ตั้งค่าลิงก์ไฮเปอร์ภายในเมื่อเอาเมาส์ไปชี้

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์เป้าหมาย |

**Returns:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```


ลบลิงก์ไฮเปอร์เมื่อเอาเมาส์ไปชี้

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```


ตั้งค่าลิงก์ไฮเปอร์แมโครเมื่อคลิก

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

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| macroName | java.lang.String | ชื่อของแมโคร |

**Returns:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


ส่งกลับอ็อบเจ็กต์ Parent_Immediate อ่านอย่างเดียว IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject