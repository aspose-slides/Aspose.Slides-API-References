---
title: FontsManager
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: قلم‌ها را در سراسر ارائه مدیریت می‌کند.
type: docs
url: /fa/com.aspose.slides/fontsmanager/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IFontsManager](../../com.aspose.slides/ifontsmanager)
```
public class FontsManager implements IFontsManager
```

قلم‌ها را در سراسر ارائه مدیریت می‌کند.

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // بارگذاری ارائه
>  // بارگذاری قلم منبع برای جایگزینی
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // بارگذاری قلم منبع برای جایگزینی
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
>      // ذخیره‌سازی ارائه
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## متدها

| متد | توضیح |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | جایگزینی‌های قلم برای استفاده هنگام رندر. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | جایگزینی‌های قلم برای استفاده هنگام رندر. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | نمایانگر مجموعه‌ای از قوانین FontFallBack کاربر برای مدیریت مجموعه‌های قلم‌ها به منظور جایگزینی صحیح با عملکرد fallback. خواندنی/نوشتنی [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | نمایانگر مجموعه‌ای از قوانین FontFallBack کاربر برای مدیریت مجموعه‌های قلم‌ها به منظور جایگزینی صحیح با عملکرد fallback. خواندنی/نوشتنی [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | قلم‌های استفاده‌شده در ارائه را برمی‌گرداند |
| [getSubstitutions()](#getSubstitutions--) | اطلاعات مربوط به قلم‌هایی که در رندر ارائه جایگزین خواهند شد را دریافت می‌کند. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | اطلاعات مربوط به قلم‌هایی که در رندر اسلایدهای مشخص شده جایگزین خواهند شد را دریافت می‌کند. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | قلم‌های تعبیه‌شده در ارائه را برمی‌گرداند |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | قلم تعبیه‌شده را حذف می‌کند |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | قلم تعبیه‌شده را اضافه می‌کند |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | قلم تعبیه‌شده را اضافه می‌کند |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | قلم را در ارائه جایگزین می‌کند |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | قلم را در ارائه با استفاده از اطلاعات ارائه‌شده در [FontSubstRule](../../com.aspose.slides/fontsubstrule) جایگزین می‌کند |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | قلم را در ارائه با استفاده از اطلاعات ارائه‌شده در مجموعه‌ای از [FontSubstRule](../../com.aspose.slides/fontsubstrule) جایگزین می‌کند |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | آرایه بایتی که داده‌های قلم برای یک سبک قلم مشخص و داده‌های قلم را نمایش می‌دهد، بازیابی می‌کند. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | سطح جاسازی یک قلم را از آرایه بایتی داده شده و نام قلم تعیین می‌کند. |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```

جایگزینی‌های قلم برای استفاده هنگام رندر. خواندنی/نوشتنی [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**بازگشت:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```

جایگزینی‌های قلم برای استفاده هنگام رندر. خواندنی/نوشتنی [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

نمایانگر مجموعه‌ای از قوانین FontFallBack کاربر برای مدیریت مجموعه‌های قلم‌ها به منظور جایگزینی صحیح با عملکرد fallback. خواندنی/نوشتنی [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // دریافت مجموعه قوانین خالی یا پیش‌تنظیم‌شده از FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // اضافه کردن قوانین به مجموعه
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // یا
>      // مقداردهی اولیه نمونه جدید مجموعه قوانین
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // اضافه کردن قوانین به مجموعه
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // و جایگزینی مجموعه موجود با مجموعه جدید در FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگشت:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)

### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public final void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

نمایانگر مجموعه‌ای از قوانین FontFallBack کاربر برای مدیریت مجموعه‌های قلم‌ها به منظور جایگزینی صحیح با عملکرد fallback. خواندنی/نوشتنی [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // دریافت مجموعه قوانین خالی یا پیش‌تنظیم‌شده از FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // اضافه‌کردن قوانین به مجموعه
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // یا
>      // مقداردهی اولیه نمونه جدید از مجموعه قوانین
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // اضافه‌کردن قوانین به مجموعه
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // و جایگزینی مجموعه موجود با مجموعه جدید در FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public final IFontData[] getFonts()
```

قلم‌های استفاده‌شده در ارائه را برمی‌گرداند

**بازگشت:**
com.aspose.slides.IFontData[] - آرایه‌ای از قلم‌ها

### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

اطلاعات مربوط به قلم‌هایی که در رندر ارائه جایگزین خواهند شد را دریافت می‌کند.

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


**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - مجموعه‌ای از تمام جایگزینی‌های قلم [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

اطلاعات مربوط به قلم‌هایی که در رندر اسلایدهای مشخص شده جایگزین خواهند شد را دریافت می‌کند.

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


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| slides | int[] | آرایه‌ای از ایندکس‌های اسلایدها برای دریافت اطلاعات جایگزینی قلم، شروع از 1. |

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - مجموعه‌ای از تمام جایگزینی‌های قلم ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) برای اسلایدهای مشخص‌شده.

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```

قلم‌های تعبیه‌شده در ارائه را برمی‌گرداند

**بازگشت:**
com.aspose.slides.IFontData[]

### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```

قلم تعبیه‌شده را حذف می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

قلم تعبیه‌شده را اضافه می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

قلم تعبیه‌شده را اضافه می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```

قلم را در ارائه جایگزین می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | قلم منبع |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | قلم مقصد |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```

قلم را در ارائه با استفاده از اطلاعات ارائه‌شده در [FontSubstRule](../../com.aspose.slides/fontsubstrule) جایگزین می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | اطلاعات جایگزینی قلم |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```

قلم را در ارائه با استفاده از اطلاعات ارائه‌شده در مجموعه‌ای از [FontSubstRule](../../com.aspose.slides/fontsubstrule) جایگزین می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | مجموعه قوانین جایگزینی قلم |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```

آرایه بایتی که داده‌های قلم برای یک سبک قلم مشخص و داده‌های قلم را نمایش می‌دهد، بازیابی می‌کند.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // تمام قلم‌های استفاده‌شده در ارائه را بازیابی کنید
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // دریافت آرایه بایتی که سبک عادی اولین قلم در ارائه را نشان می‌دهد
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | شیء داده قلم که شامل اطلاعات درباره قلم [IFontData](../../com.aspose.slides/ifontdata) است. |
| fontStyle | int | سبک قلم برای داده‌ای که باید بازیابی شود [FontStyleType](../../com.aspose.slides/fontstyletype). |

**بازگشت:**
byte[] - آرایه بایتی حاوی داده‌های قلم برای سبک قلم مشخص. اگر داده‌های قلم یا سبک یافت نشود، مقدار null برمی‌گردد.

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

سطح جاسازی یک قلم را از آرایه بایتی داده شده و نام قلم تعیین می‌کند.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // تمام قلم‌های استفاده‌شده در ارائه را بازیابی کنید
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // دریافت آرایه بایتی که سبک عادی اولین قلم در ارائه را نشان می‌دهد
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
>      // تعیین سطح جاسازی قلم
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontBytes | byte[] | آرایه بایتی حاوی داده‌های قلم. |
| fontName | java.lang.String | نام قلم. |

**بازگشت:**
int - سطح جاسازی قلم مشخص‌شده.