---
title: IFontsManager
second_title: Aspose.Slides for Java API Reference
description: مدیریت فونت‌ها در سراسر ارائه.
type: docs
url: /fa/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

فونت‌ها را در سراسر ارائه مدیریت می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | جایگزینی فونت‌ها برای استفاده هنگام رندرینگ خواندن/نوشتن [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | جایگزینی فونت‌ها برای استفاده هنگام رندرینگ خواندن/نوشتن [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | نمایانگر مجموعه‌ای از قواعد FontFallBack کاربر برای مدیریت مجموعه‌های فونت به منظور جایگزینی صحیح توسط عملکرد fallback خواندن/نوشتن [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | نمایانگر مجموعه‌ای از قواعد FontFallBack کاربر برای مدیریت مجموعه‌های فونت به منظور جایگزینی صحیح توسط عملکرد fallback خواندن/نوشتن [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | فونت‌های مورد استفاده در ارائه را برمی‌گرداند |
| [getSubstitutions()](#getSubstitutions--) | اطلاعات درباره فونت‌هایی که در رندرینگ ارائه جایگزین خواهند شد را دریافت می‌کند. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | دریافت اطلاعات درباره فونت‌هایی که در هنگام رندرینگ اسلایدهای مشخص‌شده جایگزین خواهند شد. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | فونت‌های توکار در ارائه را برمی‌گرداند |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | فونت توکار را حذف می‌کند |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | فونت توکار را اضافه می‌کند. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | اضافه کردن فونت توکار |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | تعویض فونت در ارائه |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | تعویض فونت در ارائه با استفاده از اطلاعات ارائه شده در [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | تعویض فونت در ارائه با استفاده از اطلاعات ارائه شده در مجموعهٔ [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | آرایه بایتی که داده‌های فونت برای یک سبک فونت مشخص و داده‌های فونت را نشان می‌دهد، بازیابی می‌کند. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | تعیین سطح امبدینگ یک فونت از آرایه بایت داده‌شده و نام فونت |
| [getPreferRegisteredFontsOverEmbedded()](#getPreferRegisteredFontsOverEmbedded--) | مشخص می‌کند که آیا فونت‌های ثبت‌شده باید بر فونت‌های توکار با همان نام و سبک فونت ترجیح داده شوند یا خیر. |
| [setPreferRegisteredFontsOverEmbedded(boolean value)](#setPreferRegisteredFontsOverEmbedded-boolean-) | مشخص می‌کند که آیا فونت‌های ثبت‌شده باید بر فونت‌های توکار با همان نام و سبک فونت ترجیح داده شوند یا خیر. |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

جایگزینی فونت‌ها برای استفاده هنگام رندرینگ خواندن/نوشتن [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**بازگرداندن:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

جایگزینی فونت‌ها برای استفاده هنگام رندرینگ خواندن/نوشتن [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

نمایانگر مجموعه‌ای از قواعد FontFallBack کاربر برای مدیریت مجموعه‌های فونت به منظور جایگزینی صحیح توسط عملکرد fallback خواندن/نوشتن [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

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
>      // ایجاد یک نمونه جدید از مجموعه قوانین
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


**بازگرداندن:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)

### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

نمایانگر مجموعه‌ای از قواعد FontFallBack کاربر برای مدیریت مجموعه‌های فونت به منظور جایگزینی صحیح توسط عملکرد fallback خواندن/نوشتن [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ``` 
> Presentation pres = new Presentation();
>  try
>  {
>      // دریافت مجموعه قوانین خالی یا پیش‌تنظیم‌شده از FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // افزودن قوانین به مجموعه
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // یا 
>      // ایجاد یک نمونه جدید از مجموعه قوانین
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
public abstract IFontData[] getFonts()
```

فونت‌های مورد استفاده در ارائه را برمی‌گرداند

**بازگرداندن:**
com.aspose.slides.IFontData[] - آرایه‌ای از فونت‌ها

### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

دریافت اطلاعات درباره فونت‌هایی که در رندرینگ ارائه جایگزین خواهند شد.

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


**بازگرداندن:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - مجموعه‌ای از تمام جایگزینی‌های فونت [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

دریافت اطلاعات درباره فونت‌هایی که در هنگام رندرینگ اسلایدهای مشخص‌شده جایگزین خواهند شد.

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
| slides | int[] | آرایه‌ای از ایندکس‌های اسلاید برای دریافت اطلاعات جایگزینی فونت، آغاز از 1. |

**بازگرداندن:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - مجموعه‌ای از تمام جایگزینی‌های فونت ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) برای اسلایدهای مشخص‌شده.

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

فونت‌های توکار در ارائه را برمی‌گرداند

**بازگرداندن:**
com.aspose.slides.IFontData[] - فونت‌های توکار IFontData[]

### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

حذف فونت توکار

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | شی دادهٔ فونت [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

افزودن فونت توکار.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | شی دادهٔ فونت [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | قانون فونت توکار [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

در هنگام کپی کردن هر فونتی به‌خاطر داشته باشید که اکثر فونت‌ها دارای حق کپی‌رایت هستند. پیش از هر کار، مجوز فونت را پیدا کنید و اطمینان حاصل کنید که می‌توانند به‌صورت آزاد به ماشین دیگری منتقل شوند. |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

اضافه کردن فونت توکار

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontData | byte[] | دادهٔ فونت  byte[]  |
| embedFontRule | int | قانون فونت توکار [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

در هنگام افزودن هر فونتی به‌خاطر داشته باشید که اکثر فونت‌ها دارای حق کپی‌رایت هستند. پیش از هر کار، مجوز فونت را پیدا کنید و اطمینان حاصل کنید که می‌توانند به‌صورت آزاد به ماشین دیگری منتقل شوند. |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

تعویض فونت در ارائه

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | فونت منبع |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | فونت مقصد |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```

تعویض فونت در ارائه با استفاده از اطلاعات ارائه شده در [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | اطلاعات جایگزینی فونت |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

تعویض فونت در ارائه با استفاده از اطلاعات ارائه شده در مجموعهٔ [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | مجموعهٔ اطلاعات جایگزینی فونت |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

آرایه بایتی که داده‌های فونت برای یک سبک فونت مشخص و داده‌های فونت را نشان می‌دهد، بازیابی می‌کند.

--------------------

> ``` 
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // تمام فونت‌های مورد استفاده در ارائه را بازیابی کنید
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // آرایه بایتی که نمایانگر سبک عادی اولین فونت در ارائه است را دریافت کنید
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | شی دادهٔ فونت حاوی اطلاعات دربارهٔ فونت [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | سبک فونت که داده‌های آن باید بازیابی شود [FontStyleType](../../com.aspose.slides/fontstyletype). |

**بازگرداندن:**
byte[] - آرایه بایت شامل دادهٔ فونت برای سبک فونت مشخص‌شده. اگر دادهٔ فونت یا سبک یافت نشود، مقدار null برگردانده می‌شود.

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

تعیین سطح امبدینگ یک فونت از آرایه بایت داده‌شده و نام فونت.

--------------------

> ``` 
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // تمام فونت‌های مورد استفاده در ارائه را بازیابی کنید
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // آرایه بایتی که نمایانگر سبک عادی اولین فونت در ارائه است را دریافت کنید
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // سطح امبدینگ فونت را تعیین کنید
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontBytes | byte[] | آرایه بایت حاوی دادهٔ فونت. |
| fontName | java.lang.String | نام فونت. |

**بازگرداندن:**
int - سطح امبدینگ فونت مشخص‌شده.

### getPreferRegisteredFontsOverEmbedded() {#getPreferRegisteredFontsOverEmbedded--}
```
public abstract boolean getPreferRegisteredFontsOverEmbedded()
```

مشخص می‌کند که آیا فونت‌های ثبت‌شده باید بر فونت‌های توکار با همان نام و سبک فونت ترجیح داده شوند. هنگام فعال بودن، فونت‌های توکار مطابقت‌دار به‌طور موقت با فونت‌های ثبت‌شدهٔ متناظر جایگزین می‌شوند.

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

به‌طور پیش‌فرض **false** است.

**بازگرداندن:**
boolean

### setPreferRegisteredFontsOverEmbedded(boolean value) {#setPreferRegisteredFontsOverEmbedded-boolean-}
```
public abstract void setPreferRegisteredFontsOverEmbedded(boolean value)
```

مشخص می‌کند که آیا فونت‌های ثبت‌شده باید بر فونت‌های توکار با همان نام و سبک فونت ترجیح داده شوند. هنگام فعال بودن، فونت‌های توکار مطابقت‌دار به‌طور موقت با فونت‌های ثبت‌شدهٔ متناظر جایگزین می‌شوند.

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

به‌طور پیش‌فرض **false** است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |