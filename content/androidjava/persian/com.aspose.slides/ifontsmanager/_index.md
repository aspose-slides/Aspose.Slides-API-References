---
title: IFontsManager
second_title: Aspose.Slides for Android via Java API Reference
description: فونت‌ها را در سراسر ارائه مدیریت می‌کند.
type: docs
url: /fa/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

فونت‌ها را در سراسر ارائه مدیریت می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | جایگزینی‌های قلم برای استفاده هنگام رندر کردن Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | جایگزینی‌های قلم برای استفاده هنگام رندر کردن Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | نمایش مجموعه‌ای از قوانین FontFallBack کاربر برای مدیریت مجموعه‌های قلم برای جایگزینی صحیح توسط عملکرد fallback Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | نمایش مجموعه‌ای از قوانین FontFallBack کاربر برای مدیریت مجموعه‌های قلم برای جایگزینی صحیح توسط عملکرد fallback Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | فونت‌های استفاده‌شده در ارائه را برمی‌گرداند |
| [getSubstitutions()](#getSubstitutions--) | اطلاعاتی درباره قلم‌هایی که در رندر ارائه جایگزین خواهند شد را دریافت می‌کند. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | اطلاعاتی درباره قلم‌هایی که در رندر اسلایدهای مشخص شده جایگزین خواهند شد را دریافت می‌کند. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | فونت‌های جاسازی‌شده در ارائه را برمی‌گرداند |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | قلم جاسازی‌شده را حذف می‌کند |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | قلم جاسازی‌شده را اضافه می‌کند. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | قلم جاسازی‌شده را اضافه می‌کند |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | جایگزینی قلم در ارائه |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | جایگزینی قلم در ارائه با استفاده از اطلاعات ارائه‌شده در [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | جایگزینی قلم در ارائه با استفاده از اطلاعات ارائه‌شده در مجموعه‌ای از [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | آرایه بایت نمایانگر داده‌های قلم برای سبک قلم مشخص و داده‌های قلم را باز می‌گرداند. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | سطح جاسازی یک قلم را از آرایه بایت و نام قلم داده‌شده تعیین می‌کند. |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

جایگزینی‌های قلم برای استفاده هنگام رندر کردن Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**بازمی‌گردد:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

جایگزینی‌های قلم برای استفاده هنگام رندر کردن Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

نمایش مجموعه‌ای از قوانین FontFallBack کاربر برای مدیریت مجموعه‌های قلم برای جایگزینی صحیح توسط عملکرد fallback Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```  
> Presentation pres = new Presentation();
>  try
>  {
>      // دریافت مجموعه قوانین خالی یا پیش‌راه‌اندازی‌شده از FontsManager
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


**بازمی‌گردد:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)

### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

نمایش مجموعه‌ای از قوانین FontFallBack کاربر برای مدیریت مجموعه‌های قلم برای جایگزینی صحیح توسط عملکرد fallback Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // دریافت مجموعه قوانین خالی یا پیش‌راه‌اندازی‌شده از FontsManager
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
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public abstract IFontData[] getFonts()
```

فونت‌های استفاده‌شده در ارائه را برمی‌گرداند

**بازمی‌گردد:**
com.aspose.slides.IFontData[] - یک آرایه از قلم‌ها

### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

اطلاعاتی درباره قلم‌هایی که در رندر ارائه جایگزین خواهند شد را دریافت می‌کند.

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


**بازمی‌گردد:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - مجموعه‌ای از تمام جایگزینی‌های قلم [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

اطلاعاتی درباره قلم‌هایی که در رندر اسلایدهای مشخص شده جایگزین خواهند شد را دریافت می‌کند.

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
| slides | int[] | آرایه‌ای از ایندکس‌های اسلاید که برای آنها اطلاعات جایگزینی قلم بازیابی می‌شود، از ۱ شروع می‌شود. |

**بازمی‌گردد:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - یک مجموعه از تمام جایگزینی‌های قلم ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) برای اسلایدهای مشخص‌شده

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

قلم‌های جاسازی‌شده در ارائه را برمی‌گرداند

**بازمی‌گردد:**
com.aspose.slides.IFontData[] - قلم‌های جاسازی‌شده IFontData[]

### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

قلم جاسازی‌شده را حذف می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | شیء داده قلم [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

قلم جاسازی‌شده را اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | شیء داده قلم [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | قانون قلم جاسازی [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

در نظر داشته باشید هنگام کپی کردن هر قلمی، اکثر قلم‌ها تحت حق تکثیر هستند. ابتدا مجوز یک قلم را پیدا کنید و اطمینان حاصل کنید که می‌توان آن را به‌صورت آزاد به دستگاه دیگری منتقل کرد. |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

قلم جاسازی‌شده را اضافه می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontData | byte[] | داده قلم byte[] |
| embedFontRule | int | قانون قلم جاسازی [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

در نظر داشته باشید هنگام اضافه کردن هر قلمی، اکثر قلم‌ها تحت حق تکثیر هستند. ابتدا مجوز یک قلم را پیدا کنید و اطمینان حاصل کنید که می‌توان آن را به‌صورت آزاد به دستگاه دیگری منتقل کرد. |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

جایگزینی قلم در ارائه

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | قلم منبع |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | قلم مقصد |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```

جایگزینی قلم در ارائه با استفاده از اطلاعات ارائه‌شده در [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | اطلاعات جایگزینی قلم |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

جایگزینی قلم در ارائه با استفاده از اطلاعات ارائه‌شده در مجموعه‌ای از [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | مجموعه اطلاعات جایگزینی قلم |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

آرایه بایت نمایانگر داده‌های قلم برای سبک قلم مشخص و داده‌های قلم را باز می‌گرداند.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // دریافت تمام قلم‌های استفاده‌شده در ارائه
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // دریافت آرایه بایت که نمایانگر سبک معمولی اولین قلم در ارائه است
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | شیء داده قلم حاوی اطلاعات درباره قلم [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | سبک قلم که داده‌های آن باید بازیابی شود [FontStyleType](../../com.aspose.slides/fontstyletype). |

**بازمی‌گردد:**
byte[] - یک آرایه بایت حاوی داده‌های قلم برای سبک قلم مشخص. اگر داده قلم یا سبک یافت نشد، null برمی‌گرداند.

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

سطح جاسازی یک قلم را از آرایه بایت و نام قلم داده‌شده تعیین می‌کند.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // دریافت تمام قلم‌های استفاده‌شده در ارائه
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // دریافت آرایه بایت که نمایانگر سبک معمولی اولین قلم در ارائه است
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // تعیین سطح جاسازی قلم
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضحیح |
| --- | --- | --- |
| fontBytes | byte[] | آرایه بایتی حاوی داده‌های قلم. |
| fontName | java.lang.String | نام قلم. |

**بازمی‌گردد:**
int - سطح جاسازی قلم مشخص‌شده.