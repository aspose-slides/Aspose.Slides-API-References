---
title: FontsManager
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: จัดการแบบอักษรทั่วทั้งงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/fontsmanager/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IFontsManager](../../com.aspose.slides/ifontsmanager)
```
public class FontsManager implements IFontsManager
```

จัดการแบบอักษรทั่วทั้งงานนำเสนอ.

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // โหลดงานนำเสนอ
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // โหลดแบบอักษรต้นฉบับที่ต้องการแทนที่
>      IFontData sourceFont = new FontData("Arial");
>      IFontData[] allFonts = pres.getFontsManager().getFonts();
>      for (IFontData font : allFonts)
>      {
>          boolean fontAlreadyEmbedded = false;
>          IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>          for (int i = 0; i < embeddedFonts.length; i++)
>          {
>              if (embeddedFonts[i].equals(font))
>              {
>                  fontAlreadyEmbedded = true;
>                  break;
>              }
>          }
>          if (!fontAlreadyEmbedded) {
>              pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>          }
>      }
>      // บันทึกงานนำเสนอ
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | การแทนที่แบบอักษรที่ใช้เมื่อแสดงผล. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | การแทนที่แบบอักษรที่ใช้เมื่อแสดงผล. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | แสดงถึงคอลเลกชันของผู้ใช้สำหรับกฎ FontFallBack เพื่อจัดการคอลเลกชันของแบบอักษรเพื่อการแทนที่ที่เหมาะสมโดยฟังก์ชัน fallback อ่าน/เขียน [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | แสดงถึงคอลเลกชันของผู้ใช้สำหรับกฎ FontFallBack เพื่อจัดการคอลเลกชันของแบบอักษรเพื่อการแทนที่ที่เหมาะสมโดยฟังก์ชัน fallback อ่าน/เขียน [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | ส่งคืนแบบอักษรที่ใช้ในงานนำเสนอ |
| [getSubstitutions()](#getSubstitutions--) | รับข้อมูลเกี่ยวกับแบบอักษรที่จะแทนที่ในการแสดงผลของงานนำเสนอ |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | รับข้อมูลเกี่ยวกับแบบอักษรที่จะถูกแทนที่ระหว่างการแสดงผลของสไลด์ที่ระบุ |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | ส่งคืนแบบอักษรที่ฝังในงานนำเสนอ |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | ลบแบบอักษรที่ฝังไว้ |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | เพิ่มแบบอักษรที่ฝังไว้ |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | เพิ่มแบบอักษรที่ฝังไว้ |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | แทนที่แบบอักษรในงานนำเสนอ |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | แทนที่แบบอักษรในงานนำเสนอโดยใช้ข้อมูลที่ให้ไว้ใน [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | แทนที่แบบอักษรในงานนำเสนอโดยใช้ข้อมูลที่ให้ไว้ในคอลเลกชันของ [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | ดึงอาร์เรย์ไบต์ที่เป็นตัวแทนของข้อมูลแบบอักษรสำหรับสไตล์แบบอักษรและข้อมูลแบบอักษรที่ระบุ |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | กำหนดระดับการฝังของแบบอักษรจากอาร์เรย์ไบต์และชื่อแบบอักษรที่ให้มา |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```

การแทนที่แบบอักษรที่ใช้เมื่อแสดงผล. อ่าน/เขียน [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**ส่งคืน:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```

การแทนที่แบบอักษรที่ใช้เมื่อแสดงผล. อ่าน/เขียน [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

แสดงถึงคอลเลกชันของผู้ใช้สำหรับกฎ FontFallBack เพื่อจัดการคอลเลกชันของแบบอักษรเพื่อการแทนที่ที่เหมาะสมโดยฟังก์ชัน fallback อ่าน/เขียน [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // รับคอลเลกชันของกฎที่ว่างหรือที่กำหนดค่าไว้ล่วงหน้าได้จาก FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // เพิ่มกฎลงในคอลเลกชัน
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // หรือ 
>      // การสร้างอินสแตนซ์ใหม่ของคอลเลกชันกฎ
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // เพิ่มกฎลงในคอลเลกชัน
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // และแทนที่คอลเลกชันเดิมด้วยคอลเลกชันใหม่ใน FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**ส่งคืน:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public final void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

แสดงถึงคอลเลกชันของผู้ใช้สำหรับกฎ FontFallBack เพื่อจัดการคอลเลกชันของแบบอักษรเพื่อการแทนที่ที่เหมาะสมโดยฟังก์ชัน fallback อ่าน/เขียน [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // รับคอลเลกชันของกฎที่ว่างหรือที่เตรียมค่าไว้ล่วงหน้าจาก FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // เพิ่มกฎลงในคอลเลกชัน
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // หรือ 
>      // การสร้างอินสแตนซ์ใหม่ของคอลเลกชันกฎ
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // เพิ่มกฎลงในคอลเลกชัน
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // และแทนที่คอลเลกชันที่มีอยู่ด้วยคอลเลกชันใหม่ใน FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public final IFontData[] getFonts()
```

ส่งคืนแบบอักษรที่ใช้ในงานนำเสนอ

**ส่งคืน:**
com.aspose.slides.IFontData[] - อาร์เรย์ของแบบอักษร
### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

รับข้อมูลเกี่ยวกับแบบอักษรที่จะแทนที่ในการแสดงผลของงานนำเสนอ

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions())
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ส่งคืน:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - คอลเลกชันของการแทนที่แบบอักษรทั้งหมด [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

รับข้อมูลเกี่ยวกับแบบอักษรที่จะถูกแทนที่ระหว่างการแสดงผลของสไลด์ที่ระบุ

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      int[] targetSlides = { 1, 2, 5 };
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions(targetSlides))
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| slides | int[] | อาร์เรย์ของดัชนีสไลด์ที่ต้องการรับข้อมูลการแทนที่แบบอักษร เริ่มจาก 1. |

**ส่งคืน:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - คอลเลกชันของการแทนที่แบบอักษรทั้งหมด ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) สำหรับสไลด์ที่ระบุ
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```

ส่งคืนแบบอักษรที่ฝังในงานนำเสนอ

**ส่งคืน:**
com.aspose.slides.IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```

ลบแบบอักษรที่ฝังไว้

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

เพิ่มแบบอักษรที่ฝังไว้

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

เพิ่มแบบอักษรที่ฝังไว้

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```

แทนที่แบบอักษรในงานนำเสนอ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | แบบอักษรต้นทาง |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | แบบอักษรปลายทาง |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```

แทนที่แบบอักษรในงานนำเสนอโดยใช้ข้อมูลที่ให้ไว้ใน [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | ข้อมูลการแทนที่แบบอักษร |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```

แทนที่แบบอักษรในงานนำเสนอโดยใช้ข้อมูลที่ให้ไว้ในคอลเลกชันของ [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | คอลเลกชันของกฎการแทนที่แบบอักษร |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```

ดึงอาร์เรย์ไบต์ที่เป็นตัวแทนของข้อมูลแบบอักษรสำหรับสไตล์แบบอักษรและข้อมูลแบบอักษรที่ระบุ

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // ดึงแบบอักษรทั้งหมดที่ใช้ในงานนำเสนอ
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // รับอาร์เรย์ไบต์ที่เป็นตัวแทนของสไตล์ปกติของแบบอักษรแรกในงานนำเสนอ
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | อ็อบเจกต์ข้อมูลแบบอักษรที่มีข้อมูลเกี่ยวกับแบบอักษร [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | สไตล์ของแบบอักษรที่ต้องการดึงข้อมูล [FontStyleType](../../com.aspose.slides/fontstyletype). |

**ส่งคืน:**
byte[] - อาร์เรย์ไบต์ที่มีข้อมูลแบบอักษรสำหรับสไตล์แบบอักษรที่ระบุ หากไม่พบข้อมูลแบบอักษรหรือสไตล์ จะส่งคืน null.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

กำหนดระดับการฝังของแบบอักษรจากอาร์เรย์ไบต์และชื่อแบบอักษรที่ให้มา

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // ดึงแบบอักษรทั้งหมดที่ใช้ในงานนำเสนอ
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // รับอาร์เรย์ไบต์ที่เป็นตัวแทนของสไตล์ปกติของแบบอักษรแรกในงานนำเสนอ
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
>      // กำหนดระดับการฝังของแบบอักษร
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontBytes | byte[] | อาร์เรย์ไบต์ที่มีข้อมูลแบบอักษร. |
| fontName | java.lang.String | ชื่อของแบบอักษร. |

**ส่งคืน:**
int - ระดับการฝังของแบบอักษรที่ระบุ.