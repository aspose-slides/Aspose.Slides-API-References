---
title: IHyperlinkManager
second_title: Aspose.Slides สำหรับ Java API Reference
description: ให้บริการการจัดการไฮเปอร์ลิงก์ (เพิ่มและลบ)
type: docs
url: /th/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

ให้บริการการจัดการไฮเปอร์ลิงก์ (เพิ่มและลบ)

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | ตั้งค่าการเชื่อมโยงภายนอกเมื่อคลิก |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | ตั้งค่าการเชื่อมโยงภายในเมื่อคลิก |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | ลบการเชื่อมโยงเมื่อคลิก |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | ตั้งค่าการเชื่อมโยงภายนอกเมื่อเมาส์อยู่เหนือ |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | ตั้งค่าการเชื่อมโยงภายในเมื่อเมาส์อยู่เหนือ |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | ลบการเชื่อมโยงเมื่อเมาส์อยู่เหนือ |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | ตั้งค่าการเชื่อมโยงมาโครเมื่อคลิก |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

ตั้งค่าการเชื่อมโยงภายนอกเมื่อคลิก

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| url | java.lang.String | URL ของไฮเปอร์ลิงก์ |

**ค่าที่ส่งคืน:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - วัตถุ Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

ตั้งค่าการเชื่อมโยงภายในเมื่อคลิก

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์เป้าหมาย |

**ค่าที่ส่งคืน:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```

ลบการเชื่อมโยงเมื่อคลิก

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

ตั้งค่าการเชื่อมโยงภายนอกเมื่อเมาส์อยู่เหนือ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| url | java.lang.String | URL ของไฮเปอร์ลิงก์ |

**ค่าที่ส่งคืน:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - วัตถุ Hyperlink
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

ตั้งค่าการเชื่อมโยงภายในเมื่อเมาส์อยู่เหนือ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์เป้าหมาย |

**ค่าที่ส่งคืน:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - วัตถุ Hyperlink
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```

ลบการเชื่อมโยงเมื่อเมาส์อยู่เหนือ

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```

ตั้งค่าการเชื่อมโยงมาโครเมื่อคลิก

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
| macroName | java.lang.String | ชื่อของมาโคร |

**ค่าที่ส่งคืน:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - วัตถุ Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)