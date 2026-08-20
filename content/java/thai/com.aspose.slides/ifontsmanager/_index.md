---
title: IFontsManager
second_title: Aspose.Slides for Java API Reference
description: จัดการแบบอักษรทั่วทั้งงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

จัดการแบบอักษรทั่วทั้งงานนำเสนอ.
## เมธอด

| Method | Description |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | การแทนที่แบบอักษรที่จะใช้เมื่อตอนการเรนเดอร์ อ่าน/เขียน [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | การแทนที่แบบอักษรที่จะใช้เมื่อตอนการเรนเดอร์ อ่าน/เขียน [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | แสดงคอลเลกชันของผู้ใช้สำหรับกฎ FontFallBack เพื่อจัดการคอลเลกชันของแบบอักษรสำหรับการแทนที่ที่เหมาะสมโดยฟังก์ชัน fallback อ่าน/เขียน [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | แสดงคอลเลกชันของผู้ใช้สำหรับกฎ FontFallBack เพื่อจัดการคอลเลกชันของแบบอักษรสำหรับการแทนที่ที่เหมาะสมโดยฟังก์ชัน fallback อ่าน/เขียน [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | คืนค่าแบบอักษรที่ใช้ในงานนำเสนอ |
| [getSubstitutions()](#getSubstitutions--) | รับข้อมูลเกี่ยวกับแบบอักษรที่จะถูกแทนที่ในการเรนเดอร์ของงานนำเสนอ |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | รับข้อมูลเกี่ยวกับแบบอักษรที่จะถูกแทนที่ระหว่างการเรนเดอร์ของสไลด์ที่ระบุ |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | คืนค่าแบบอักษรที่ฝังในงานนำเสนอ |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | ลบแบบอักษรที่ฝังไว้ |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | เพิ่มแบบอักษรที่ฝังไว้ |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | เพิ่มแบบอักษรที่ฝังไว้ |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | แทนที่แบบอักษรในงานนำเสนอ |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | แทนที่แบบอักษรในงานนำเสนอโดยใช้ข้อมูลที่ให้ไว้ใน [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | แทนที่แบบอักษรในงานนำเสนอโดยใช้ข้อมูลที่ให้ไว้ในคอลเลกชันของ [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | ดึงอาเรย์ไบต์ที่เป็นตัวแทนข้อมูลแบบอักษรสำหรับสไตล์แบบอักษรและข้อมูลแบบอักษรที่ระบุ |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | กำหนดระดับการฝังของแบบอักษรจากอาเรย์ไบต์และชื่อแบบอักษรที่ให้มา |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

การแทนที่แบบอักษรที่จะใช้เมื่อตอนการเรนเดอร์ อ่าน/เขียน [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**คืนค่า:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

การแทนที่แบบอักษรที่จะใช้เมื่อตอนการเรนเดอร์ อ่าน/เขียน [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

แสดงคอลเลกชันของผู้ใช้สำหรับกฎ FontFallBack เพื่อจัดการคอลเลกชันของแบบอักษรสำหรับการแทนที่ที่เหมาะสมโดยฟังก์ชัน fallback อ่าน/เขียน [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // การดึงคอลเลกชันกฎที่ว่างหรือกำหนดค่าไว้ล่วงหน้าจาก FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // การเพิ่มกฎลงในคอลเลกชัน
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // หรือ 
>      // การกำหนดค่าอินสแตนซ์ใหม่ของคอลเลกชันกฎ
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // การเพิ่มกฎลงในคอลเลกชัน
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // และการแทนที่คอลเลกชันที่มีอยู่ด้วยคอลเลกชันใหม่ใน FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)

### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

แสดงคอลเลกชันของผู้ใช้สำหรับกฎ FontFallBack เพื่อจัดการคอลเลกชันของแบบอักษรสำหรับการแทนที่ที่เหมาะสมโดยฟังก์ชัน fallback อ่าน/เขียน [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // ดึงคอลเลกชันของกฎที่ว่างหรือกำหนดค่าไว้ล่วงหน้าจาก FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // การเพิ่มกฎลงในคอลเลกชัน
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // หรือ
>      // การกำหนดค่าอินสแตนซ์ใหม่ของคอลเลกชันกฎ
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // การเพิ่มกฎลงในคอลเลกชัน
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // และการแทนที่คอลเลกชันที่มีอยู่ด้วยคอลเลกชันใหม่ใน FontsManager
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
public abstract IFontData[] getFonts()
```

คืนค่าแบบอักษรที่ใช้ในงานนำเสนอ

**คืนค่า:**
com.aspose.slides.IFontData[] - อาเรย์ของแบบอักษร

### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

รับข้อมูลเกี่ยวกับแบบอักษรที่จะถูกแทนที่ในการเรนเดอร์ของงานนำเสนอ

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


**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - คอลเลกชันของการแทนที่แบบอักษรทั้งหมด [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

รับข้อมูลเกี่ยวกับแบบอักษรที่จะถูกแทนที่ระหว่างการเรนเดอร์ของสไลด์ที่ระบุ

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
| slides | int[] | อาเรย์ของดัชนีสไลด์ที่ต้องการดึงข้อมูลการแทนที่แบบอักษร เริ่มที่ 1 |

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - คอลเลกชันของการแทนที่แบบอักษรทั้งหมด ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) สำหรับสไลด์ที่ระบุ

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

คืนค่าแบบอักษรที่ฝังในงานนำเสนอ

**คืนค่า:**
com.aspose.slides.IFontData[] - แบบอักษรที่ฝัง IFontData[]

### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

ลบแบบอักษรที่ฝังไว้

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | วัตถุข้อมูลแบบอักษร [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

เพิ่มแบบอักษรที่ฝังไว้

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | วัตถุข้อมูลแบบอักษร [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | กฎการฝังแบบอักษร [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

โปรดจำว่าเมื่อคัดลอกแบบอักษรใด ๆ ส่วนใหญ่แบบอักษรมีลิขสิทธิ์ ควรตรวจสอบลิขสิทธิ์ของแบบอักษรก่อนและยืนยันว่ามีการอนุญาตให้โอนย้ายไปยังเครื่องอื่นได้อย่างอิสระ

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

เพิ่มแบบอักษรที่ฝังไว้

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontData | byte[] | ข้อมูลแบบอักษร byte[] |
| embedFontRule | int | กฎการฝังแบบอักษร [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

โปรดจำว่าเมื่อเพิ่มแบบอักษรใด ๆ ส่วนใหญ่แบบอักษรมีลิขสิทธิ์ ควรตรวจสอบลิขสิทธิ์ของแบบอักษรก่อนและยืนยันว่ามีการอนุญาตให้โอนย้ายไปยังเครื่องอื่นได้อย่างอิสระ

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

แทนที่แบบอักษรในงานนำเสนอ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | แบบอักษรต้นฉบับ |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | แบบอักษรปลายทาง |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```

แทนที่แบบอักษรในงานนำเสนอโดยใช้ข้อมูลที่ให้ไว้ใน [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | ข้อมูลการแทนที่แบบอักษร |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

แทนที่แบบอักษรในงานนำเสนอโดยใช้ข้อมูลที่ให้ไว้ในคอลเลกชันของ [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | คอลเลกชันของข้อมูลการแทนที่แบบอักษร |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

ดึงอาเรย์ไบต์ที่เป็นตัวแทนข้อมูลแบบอักษรสำหรับสไตล์แบบอักษรและข้อมูลแบบอักษรที่ระบุ

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // ดึงแบบอักษรทั้งหมดที่ใช้ในงานนำเสนอ
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // ดึงอาเรย์ไบต์ที่เป็นตัวแทนสไตล์ปกติของแบบอักษรแรกในงานนำเสนอ
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | วัตถุข้อมูลแบบอักษรที่บรรจุข้อมูลเกี่ยวกับแบบอักษร [IFontData](../../com.aspose.slides/ifontdata) |
| fontStyle | int | สไตล์ของแบบอักษรที่ต้องการดึงข้อมูล [FontStyleType](../../com.aspose.slides/fontstyletype) |

**คืนค่า:**
byte[] - อาเรย์ไบต์ที่บรรจุข้อมูลแบบอักษรสำหรับสไตล์ที่ระบุ หากไม่พบข้อมูลแบบอักษรหรือสไตล์ จะคืนค่า null

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

กำหนดระดับการฝังของแบบอักษรจากอาเรย์ไบต์และชื่อแบบอักษรที่ให้มา

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // ดึงแบบอักษรทั้งหมดที่ใช้ในงานนำเสนอ
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // ดึงอาเรย์ไบต์ที่เป็นตัวแทนสไตล์ปกติของแบบอักษรแรกในงานนำเสนอ
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // กำหนดระดับการฝังของแบบอักษร
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontBytes | byte[] | อาเรย์ไบต์ที่บรรจุข้อมูลแบบอักษร |
| fontName | java.lang.String | ชื่อของแบบอักษร |

**คืนค่า:**
int - ระดับการฝังของแบบอักษรที่ระบุ