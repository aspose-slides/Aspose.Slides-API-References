---
title: FontsManager
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يدير الخطوط عبر العرض التقديمي.
type: docs
url: /ar/com.aspose.slides/fontsmanager/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IFontsManager](../../com.aspose.slides/ifontsmanager)
```
public class FontsManager implements IFontsManager
```

يدير الخطوط عبر العرض التقديمي.

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // تحميل العرض التقديمي
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // تحميل الخط المصدر الذي سيتم استبداله
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
>      // حفظ العرض التقديمي
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
```
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | استبدالات الخط لتُستخدم أثناء التصيير. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | استبدالات الخط لتُستخدم أثناء التصيير. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | يمثل مجموعة المستخدم لقواعد FontFallBack لإدارة مجموعات الخطوط للاستبدالات الصحيحة عبر وظيفة fallback. قراءة/كتابة [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | يمثل مجموعة المستخدم لقواعد FontFallBack لإدارة مجموعات الخطوط للاستبدالات الصحيحة عبر وظيفة fallback. قراءة/كتابة [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | يعيد الخطوط المستخدمة في العرض التقديمي |
| [getSubstitutions()](#getSubstitutions--) | يحصل على المعلومات حول الخطوط التي سيتم استبدالها عند تصيير العرض التقديمي. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | يحصل على المعلومات حول الخطوط التي سيتم استبدالها عند تصيير العرض التقديمي. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | يعيد الخطوط المتضمنة في العرض التقديمي |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | يزيل الخط المتضمن |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | يضيف الخط المتضمن |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | يضيف الخط المتضمن |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | استبدال الخط في العرض التقديمي |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | استبدال الخط في العرض التقديمي باستخدام المعلومات المقدمة في [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | استبدال الخط في العرض التقديمي باستخدام المعلومات المقدمة في مجموعة [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | يسترجع المصفوفة البايتية التي تمثل بيانات الخط لنمط خط محدد وبيانات الخط. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | يحدد مستوى تضمين الخط من مصفوفة البايت المعطاة واسم الخط. |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```

استبدالات الخط لتُستخدم أثناء التصيير. قراءة/كتابة [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**الإرجاع:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```

استبدالات الخط لتُستخدم أثناء التصيير. قراءة/كتابة [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**المعلمات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

يمثل مجموعة المستخدم لقواعد FontFallBack لإدارة مجموعات الخطوط للاستبدالات الصحيحة عبر وظيفة fallback. قراءة/كتابة [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // جلب مجموعة القواعد الفارغة أو المُهيأة مسبقًا من FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // إضافة القواعد إلى المجموعة
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // أو
>      // تهيئة كائن جديد لمجموعة القواعد
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // إضافة القواعد إلى المجموعة
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // واستبدال المجموعة الحالية بالأخرى الجديدة في FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public final void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

يمثل مجموعة المستخدم لقواعد FontFallBack لإدارة مجموعات الخطوط للاستبدالات الصحيحة عبر وظيفة fallback. قراءة/كتابة [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // جلب مجموعة القواعد الفارغة أو المُهيأة مسبقًا من FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // إضافة القواعد إلى المجموعة
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // أو
>      // تهيئة كائن جديد لمجموعة القواعد
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // إضافة القواعد إلى المجموعة
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // واستبدال المجموعة الحالية بالأخرى الجديدة في FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public final IFontData[] getFonts()
```

يعيد الخطوط المستخدمة في العرض التقديمي

**الإرجاع:**
com.aspose.slides.IFontData[] - مصفوفة من الخطوط
### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

يحصل على المعلومات حول الخطوط التي سيتم استبدالها عند تصيير العرض التقديمي.

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

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - مجموعة من جميع استبدالات الخطوط [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

يحصل على المعلومات حول الخطوط التي سيتم استبدالها عند تصيير الشرائح المحددة.

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

**المعلمات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| slides | int[] | مصفوفة من مؤشرات الشرائح التي يُراد استرجاع معلومات استبدال الخطوط لها، بدءًا من 1. |

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - مجموعة من جميع استبدالات الخطوط ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) للشرائح المحددة.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```

يعيد الخطوط المتضمنة في العرض التقديمي

**الإرجاع:**
com.aspose.slides.IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```

يزيل الخط المتضمن

**المعلمات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

يضيف الخط المتضمن

**المعلمات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

يضيف الخط المتضمن

**المعلمات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```

استبدال الخط في العرض التقديمي

**المعلمات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | خط المصدر |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | خط الوجهة |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```

استبدال الخط في العرض التقديمي باستخدام المعلومات المقدمة في [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**المعلمات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | معلومات استبدال الخط |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```

استبدال الخط في العرض التقديمي باستخدام المعلومات المقدمة في مجموعة [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**المعلمات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | مجموعة قواعد استبدال الخطوط |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```

يسترجع المصفوفة البايتية التي تمثل بيانات الخط لنمط خط محدد وبيانات الخط.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // استرجاع جميع الخطوط المستخدمة في العرض التقديمي
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // الحصول على مصفوفة البايت تمثل النمط العادي للخط الأول في العرض التقديمي
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | كائن بيانات الخط الذي يحتوي على المعلومات حول الخط [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | نمط الخط الذي يُراد استرجاع البيانات له [FontStyleType](../../com.aspose.slides/fontstyletype). |

**الإرجاع:**
byte[] - مصفوفة بايتية تحتوي على بيانات الخط للنمط المحدد. إذا لم توجد بيانات الخط أو النمط، يرجع null.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

يحدد مستوى تضمين الخط من مصفوفة البايت المعطاة واسم الخط.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // استرجاع جميع الخطوط المستخدمة في العرض التقديمي
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // الحصول على مصفوفة البايت التي تمثل النمط العادي للخط الأول في العرض التقديمي
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
>      // تحديد مستوى تضمين الخط
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| fontBytes | byte[] | المصفوفة البايتية التي تحتوي على بيانات الخط. |
| fontName | java.lang.String | اسم الخط. |

**الإرجاع:**
int - مستوى التضمين للخط المحدد.