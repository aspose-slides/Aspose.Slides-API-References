---
title: FontsManager
second_title: Aspose.Slides برای مرجع API جاوا
description: فونت‌ها را در سرتاسر ارائه مدیریت می‌کند.
type: docs
url: /fa/com.aspose.slides/fontsmanager/
---
**وارثی:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IFontsManager](../../com.aspose.slides/ifontsmanager)
```
public class FontsManager implements IFontsManager
```

فونت‌ها را در سرتاسر ارائه مدیریت می‌کند.

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // بارگذاری ارائه
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // بارگذاری فونت منبع برای جایگزینی
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
>      // ذخیره ارائه
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
```
## متدها

| متد | توضیح |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | جایگزین‌های فونت برای استفاده هنگام رندرینگ. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | جایگزین‌های فونت برای استفاده هنگام رندرینگ. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | مجموعه‌ای از قوانین FontFallBack کاربر برای مدیریت مجموعه‌های فونت برای جایگزینی صحیح توسط عملکرد fallback. خواندنی/نوشتنی [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | مجموعه‌ای از قوانین FontFallBack کاربر برای مدیریت مجموعه‌های فونت برای جایگزینی صحیح توسط عملکرد fallback. خواندنی/نوشتنی [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | فونت‌های استفاده شده در ارائه را باز می‌گرداند |
| [getSubstitutions()](#getSubstitutions--) | اطلاعات درباره فونت‌هایی که در رندرینگ ارائه جایگزین خواهند شد را دریافت می‌کند. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | اطلاعات درباره فونت‌هایی که در رندرینگ اسلایدهای مشخص شده جایگزین خواهند شد را دریافت می‌کند. |
| [getPreferRegisteredFontsOverEmbedded()](#getPreferRegisteredFontsOverEmbedded--) | مشخص می‌کند آیا فونت‌های ثبت‌شده نسبت به فونت‌های توکار با همان نام و سبک ترجیح داده شوند. |
| [setPreferRegisteredFontsOverEmbedded(boolean value)](#setPreferRegisteredFontsOverEmbedded-boolean-) | مشخص می‌کند آیا فونت‌های ثبت‌شده نسبت به فونت‌های توکار با همان نام و سبک ترجیح داده شوند. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | فونت‌های توکار در ارائه را باز می‌گرداند |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | فونت توکار را حذف می‌کند |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | فونت توکار را اضافه می‌کند |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | فونت توکار را اضافه می‌کند |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | فونت را در ارائه جایگزین می‌کند |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | فونت را در ارائه با استفاده از اطلاعات ارائه شده در [FontSubstRule](../../com.aspose.slides/fontsubstrule) جایگزین می‌کند |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | فونت را در ارائه با استفاده از اطلاعات ارائه شده در مجموعه‌ای از [FontSubstRule](../../com.aspose.slides/fontsubstrule) جایگزین می‌کند |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | آرایه بایت نمایانگر داده‌های فونت برای یک سبک فونت مشخص و داده‌های فونت را بازیابی می‌کند. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | سطح توکار شدن یک فونت را از آرایه بایت و نام فونت داده‌شده تعیین می‌کند. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```


جایگزین‌های فونت برای استفاده هنگام رندرینگ. خواندنی/نوشتنی [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**بازگشت:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```


جایگزین‌های فونت برای استفاده هنگام رندرینگ. خواندنی/نوشتنی [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```


مجموعه‌ای از قوانین FontFallBack کاربر برای مدیریت مجموعه‌های فونت برای جایگزینی صحیح توسط عملکرد fallback. خواندنی/نوشتنی [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // دریافت مجموعه قوانین خالی یا پیش‌مقداردهی شده از FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // افزودن قوانین به مجموعه
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // یا
>      // مقداردهی اولیهٔ نمونه جدید مجموعه قوانین
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // افزودن قوانین به مجموعه
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


مجموعه‌ای از قوانین FontFallBack کاربر برای مدیریت مجموعه‌های فونت برای جایگزینی صحیح توسط عملکرد fallback. خواندنی/نوشتنی [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // دریافت مجموعه قوانین خالی یا پیش‌مقداردهی شده از FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // افزودن قوانین به مجموعه
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // یا
>      // مقداردهی اولیهٔ نمونه جدید مجموعه قوانین
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // افزودن قوانین به مجموعه
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


فونت‌های استفاده شده در ارائه را باز می‌گرداند

**بازگشت:**
com.aspose.slides.IFontData[] - آرایه‌ای از فونت‌ها
### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```


اطلاعات درباره فونت‌هایی که در رندرینگ ارائه جایگزین خواهند شد را دریافت می‌کند.

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
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - مجموعه‌ای از همه جایگزین‌های فونت [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```


اطلاعات درباره فونت‌هایی که در رندرینگ اسلایدهای مشخص شده جایگزین خواهند شد را دریافت می‌کند.

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
| slides | int[] | آرایه‌ای از شاخص‌های اسلاید برای دریافت اطلاعات جایگزینی فونت، شروع از 1. |

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - مجموعه‌ای از همه جایگزین‌های فونت ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) برای اسلایدهای مشخص شده.
### getPreferRegisteredFontsOverEmbedded() {#getPreferRegisteredFontsOverEmbedded--}
```
public final boolean getPreferRegisteredFontsOverEmbedded()
```


مشخص می‌کند آیا فونت‌های ثبت‌شده نسبت به فونت‌های توکار با همان نام و سبک ترجیح داده شوند. وقتی فعال باشد، فونت‌های توکار مطابق موقتاً با فونت‌های ثبت‌شده جایگزین می‌شوند هنگام خروجی گرفتن.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      pres.getFontsManager().setPreferRegisteredFontsOverEmbedded(true);
>      pres.save("Presentation-out.pdf", SaveFormat.Pdf);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

پیش‌فرض **false** است.

**بازگشت:**
boolean
### setPreferRegisteredFontsOverEmbedded(boolean value) {#setPreferRegisteredFontsOverEmbedded-boolean-}
```
public final void setPreferRegisteredFontsOverEmbedded(boolean value)
```


مشخص می‌کند آیا فونت‌های ثبت‌شده نسبت به فونت‌های توکار با همان نام و سبک ترجیح داده شوند. وقتی فعال باشد، فونت‌های توکار مطابق موقتاً با فونت‌های ثبت‌شده جایگزین می‌شوند هنگام خروجی گرفتن.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      pres.getFontsManager().setPreferRegisteredFontsOverEmbedded(true);
>      pres.save("Presentation-out.pdf", SaveFormat.Pdf);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

پیش‌فرض **false** است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```


فونت‌های توکار در ارائه را باز می‌گرداند

**بازگشت:**
com.aspose.slides.IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```


فونت توکار را حذف می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```


فونت توکار را اضافه می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```


فونت توکار را اضافه می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```


فونت را در ارائه جایگزین می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | فونت منبع |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | فونت مقصد |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```


فونت را در ارائه با استفاده از اطلاعات ارائه شده در [FontSubstRule](../../com.aspose.slides/fontsubstrule) جایگزین می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | اطلاعات جایگزینی فونت |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```


فونت را در ارائه با استفاده از اطلاعات ارائه شده در مجموعه‌ای از [FontSubstRule](../../com.aspose.slides/fontsubstrule) جایگزین می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | مجموعه‌ای از قوانین جایگزینی فونت |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```


آرایه بایت نمایانگر داده‌های فونت برای یک سبک فونت مشخص و داده‌های فونت را بازیابی می‌کند.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // دریافت تمام فونت‌های استفاده شده در ارائه
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // دریافت آرایه بایت نمایانگر سبک معمولی اولین فونت در ارائه
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | شی داده‌های فونت حاوی اطلاعات درباره فونت [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | سبک فونت که داده‌های آن باید بازیابی شود [FontStyleType](../../com.aspose.slides/fontstyletype). |

**بازگشت:**
byte[] - آرایه بایتی شامل داده‌های فونت برای سبک مشخص شده. اگر داده یا سبک فونت یافت نشود، null برمی‌گردد.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```


سطح توکار شدن یک فونت را از آرایه بایت و نام فونت داده‌شده تعیین می‌کند.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // دریافت تمام فونت‌های استفاده شده در ارائه
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // دریافت آرایه بایت نمایانگر سبک معمولی اولین فونت در ارائه
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
>      // تعیین سطح توکار شدن فونت
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontBytes | byte[] | آرایه بایتی حاوی داده‌های فونت. |
| fontName | java.lang.String | نام فونت. |

**بازگشت:**
int - سطح توکار شدن فونت مشخص‌شده.