---
title: IFontsManager
second_title: Aspose.Slides for Java API Reference
description: مدیریت فونت‌ها در سراسر ارائه.
type: docs
url: /fa/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

مدیریت فونت‌ها در سراسر ارائه.
## متدها

| متد | توضیح |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | جایگزینی فونت‌ها برای استفاده هنگام رندر کردن خواندن/نوشتن [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | جایگزینی فونت‌ها برای استفاده هنگام رندر کردن خواندن/نوشتن [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | مجموعه‌ای از قوانین FontFallBack کاربر برای مدیریت مجموعه‌های فونت برای جایگزینی صحیح توسط عملکرد fallback خواندن/نوشتن [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | مجموعه‌ای از قوانین FontFallBack کاربر برای مدیریت مجموعه‌های فونت برای جایگزینی صحیح توسط عملکرد fallback خواندن/نوشتن [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | فونت‌های استفاده شده در ارائه را برمی‌گرداند |
| [getSubstitutions()](#getSubstitutions--) | اطلاعات درباره فونت‌هایی که در رندر ارائه جایگزین می‌شوند را دریافت می‌کند. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | اطلاعات درباره فونت‌هایی که در رندر اسلایدهای مشخص شده جایگزین می‌شوند را دریافت می‌کند. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | فونت‌های تعبیه‌شده در ارائه را برمی‌گرداند |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | فونت تعبیه‌شده را حذف می‌کند |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | فونت تعبیه‌شده را اضافه می‌کند. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | فونت تعبیه‌شده را اضافه می‌کند |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | فونت را در ارائه جایگزین می‌کند |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | فونت را در ارائه با استفاده از اطلاعات موجود در [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) جایگزین می‌کند |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | فونت را در ارائه با استفاده از اطلاعات موجود در مجموعهٔ [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) جایگزین می‌کند |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | آرایهٔ بایت نمایانگر دادهٔ فونت برای سبک و دادهٔ فونت مشخص شده را بازیابی می‌کند. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | سطح تعبیهٔ یک فونت را از آرایهٔ بایت و نام فونت داده‌شده تعیین می‌کند. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

جایگزینی فونت‌ها برای استفاده هنگام رندر کردن خواندن/نوشتن [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**بازگشت:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

جایگزینی فونت‌ها برای استفاده هنگام رندر کردن خواندن/نوشتن [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

مجموعه‌ای از قوانین FontFallBack کاربر برای مدیریت مجموعه‌های فونت برای جایگزینی صحیح توسط عملکرد fallback خواندن/نوشتن [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // دریافت مجموعه قوانین خالی یا پیش‌مقداردهی شده از FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // افزودن قوانین به مجموعه
>      // یا 
>      // راه‌اندازی نمونه جدید از مجموعه قوانین
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
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

مجموعه‌ای از قوانین FontFallBack کاربر برای مدیریت مجموعه‌های فونت برای جایگزینی صحیح توسط عملکرد fallback خواندن/نوشتن [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

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
>      // راه‌اندازی یک نمونه جدید از مجموعه قوانین
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public abstract IFontData[] getFonts()
```

فونت‌های استفاده شده در ارائه را برمی‌گرداند

**بازگشت:**
com.aspose.slides.IFontData[] - آرایه‌ای از فونت‌ها
### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

اطلاعات درباره فونت‌هایی که در رندر ارائه جایگزین می‌شوند را دریافت می‌کند.

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
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - مجموعه‌ای از تمام جایگزینی‌های فونت [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

اطلاعات درباره فونت‌هایی که در رندر اسلایدهای مشخص شده جایگزین می‌شوند را دریافت می‌کند.

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
| Parameter | Type | Description |
| --- | --- | --- |
| slides | int[] | آرایه‌ای از ایندکس‌های اسلایدها که اطلاعات جایگزینی فونت برای آنها دریافت می‌شود، از 1 شروع می‌شود. |

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - مجموعه‌ای از تمام جایگزینی‌های فونت ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) برای اسلایدهای مشخص شده.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

فونت‌های تعبیه‌شده در ارائه را برمی‌گرداند

**بازگشت:**
com.aspose.slides.IFontData[] - فونت‌های تعبیه‌شده IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

فونت تعبیه‌شده را حذف می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | شیء دادهٔ فونت [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

فونت تعبیه‌شده را اضافه می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | شیء دادهٔ فونت [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | قانون فونت تعبیه‌شده [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

به‌خاطر داشته باشید هنگام کپی کردن هر فونت، بیشتر فونت‌ها حق تکثیر دارند. پیش از آن مجوز فونت را بررسی کنید و اطمینان حاصل کنید که می‌توانند به‌صورت آزاد به ماشین دیگری منتقل شوند. |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

فونت تعبیه‌شده را اضافه می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontData | byte[] | دادهٔ فونت byte[] |
| embedFontRule | int | قانون فونت تعبیه‌شده [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

به‌خاطر داشته باشید هنگام افزودن هر فونت، بیشتر فونت‌ها حق تکثیر دارند. پیش از آن مجوز فونت را بررسی کنید و اطمینان حاصل کنید که می‌توانند به‌صورت آزاد به ماشین دیگری منتقل شوند. |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

جایگزینی فونت در ارائه

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | فونت منبع |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | فونت مقصد |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```

جایگزینی فونت در ارائه با استفاده از اطلاعات موجود در [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | اطلاعات جایگزینی فونت |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

جایگزینی فونت در ارائه با استفاده از اطلاعات موجود در مجموعهٔ [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | مجموعهٔ اطلاعات جایگزینی فونت |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

آرایهٔ بایت نمایانگر دادهٔ فونت برای سبک و دادهٔ فونت مشخص شده را بازیابی می‌کند.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // دریافت تمام فونت‌های استفاده شده در ارائه
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // دریافت آرایهٔ بایت که سبک معمولی اولین فونت در ارائه را نشان می‌دهد
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | شیء دادهٔ فونت حاوی اطلاعات دربارهٔ فونت [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | سبک فونت که دادهٔ آن باید بازیابی شود [FontStyleType](../../com.aspose.slides/fontstyletype). |

**بازگشت:**
byte[] - آرایهٔ بایت حاوی دادهٔ فونت برای سبک مشخص شده. در صورت عدم یافتن دادهٔ فونت یا سبک، مقدار null برگردانده می‌شود.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

سطح تعبیهٔ یک فونت را از آرایهٔ بایت و نام فونت داده‌شده تعیین می‌کند.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // دریافت تمام فونت‌های استفاده شده در ارائه
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // دریافت آرایهٔ بایت که سبک معمولی اولین فونت در ارائه را نشان می‌دهد
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // تعیین سطح تعبیهٔ فونت
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontBytes | byte[] | آرایهٔ بایت حاوی دادهٔ فونت. |
| fontName | java.lang.String | نام فونت. |

**بازگشت:**
int - سطح تعبیهٔ فونت مشخص شده.