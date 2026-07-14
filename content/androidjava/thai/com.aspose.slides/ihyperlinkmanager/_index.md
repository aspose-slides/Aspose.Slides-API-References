---
title: IHyperlinkManager
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: จัดการไฮเปอร์ลิงก์ (เพิ่มและลบ)
type: docs
url: /th/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

จัดการไฮเปอร์ลิงก์ (เพิ่มและลบ).
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | ตั้งค่าไฮเปอร์ลิงก์ภายนอกเมื่อคลิก |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | ตั้งค่าไฮเปอร์ลิงก์ภายในเมื่อคลิก |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | ลบไฮเปอร์ลิงก์เมื่อคลิก |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | ตั้งค่าไฮเปอร์ลิงก์ภายนอกเมื่อเมาส์อยู่เหนือ |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | ตั้งค่าไฮเปอร์ลิงก์ภายในเมื่อเมาส์อยู่เหนือ |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | ลบไฮเปอร์ลิงก์เมื่อเมาส์อยู่เหนือ |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | ตั้งค่าไฮเปอร์ลิงก์แมโครเมื่อคลิก |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

ตั้งค่าไฮเปอร์ลิงก์ภายนอกเมื่อคลิก

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| url | java.lang.String | URL ของไฮเปอร์ลิงก์ |

**ผลลัพธ์:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - อ็อบเจ็กต์ Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

ตั้งค่าไฮเปอร์ลิงก์ภายในเมื่อคลิก

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์เป้าหมาย |

**ผลลัพธ์:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```

ลบไฮเปอร์ลิงก์เมื่อคลิก

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

ตั้งค่าไฮเปอร์ลิงก์ภายนอกเมื่อเมาส์อยู่เหนือ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| url | java.lang.String | URL ของไฮเปอร์ลิงก์ |

**ผลลัพธ์:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

ตั้งค่าไฮเปอร์ลิงก์ภายในเมื่อเมาส์อยู่เหนือ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์เป้าหมาย |

**ผลลัพธ์:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```

ลบไฮเปอร์ลิงก์เมื่อเมาส์อยู่เหนือ

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
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

**ผลลัพธ์:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - อ็อบเจ็กต์ Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)