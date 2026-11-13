---
title: FontsManager
second_title: مرجع Aspose.Slides لواجهة برمجة تطبيقات جافا
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
>      // تحميل الخط المصدر لاستبداله
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
> ```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | بدائل الخطوط لاستخدامها عند التصيير. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | بدائل الخطوط لاستخدامها عند التصيير. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | يمثل مجموعة المستخدم لقواعد FontFallBack لإدارة مجموعات الخطوط للاستبدالات المناسبة عبر وظيفة fallback. قراءة/كتابة [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | يمثل مجموعة المستخدم لقواعد FontFallBack لإدارة مجموعات الخطوط للاستبدالات المناسبة عبر وظيفة fallback. قراءة/كتابة [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | تُرجع الخطوط المستخدمة في العرض التقديمي |
| [getSubstitutions()](#getSubstitutions--) | يحصل على المعلومات عن الخطوط التي سيتم استبدالها عند تصيير العرض التقديمي. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | يحصل على المعلومات عن الخطوط التي سيتم استبدالها أثناء تصيير الشرائح المحددة. |
| [getPreferRegisteredFontsOverEmbedded()](#getPreferRegisteredFontsOverEmbedded--) | يحدد ما إذا كان يجب تفضيل الخطوط المسجلة على الخطوط المدمجة التي لها نفس اسم الخط والنمط. |
| [setPreferRegisteredFontsOverEmbedded(boolean value)](#setPreferRegisteredFontsOverEmbedded-boolean-) | يحدد ما إذا كان يجب تفضيل الخطوط المسجلة على الخطوط المدمجة التي لها نفس اسم الخط والنمط. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | تُرجع الخطوط المدمجة في العرض التقديمي |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | يزيل الخط المدمج |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | يضيف الخط المدمج |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | يضيف الخط المدمج |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | استبدال الخط في العرض التقديمي |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | استبدال الخط في العرض التقديمي باستخدام المعلومات المقدمة في [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | استبدال الخط في العرض التقديمي باستخدام المعلومات المقدمة في مجموعة [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | يسترجع مصفوفة البايت التي تمثل بيانات الخط لنمط خط محدد وبيانات الخط. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | يحدد مستوى دمج الخط من مصفوفة البايت المعطاة واسم الخط. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```

بدائل الخطوط لاستخدامها عند التصيير. قراءة/كتابة [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**الإرجاع:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```

بدائل الخطوط لاستخدامها عند التصيير. قراءة/كتابة [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

يمثل مجموعة المستخدم لقواعد FontFallBack لإدارة مجموعات الخطوط للاستبدالات المناسبة عبر وظيفة fallback. قراءة/كتابة [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // الحصول على مجموعة قواعد فارغة أو مبدئية من FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // إضافة قواعد إلى المجموعة
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // أو 
>      // تهيئة نسخة جديدة من مجموعة القواعد
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // إضافة قواعد إلى المجموعة
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // واستبدال المجموعة الموجودة بالجديدة في FontsManager 
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

يمثل مجموعة المستخدم لقواعد FontFallBack لإدارة مجموعات الخطوط للاستبدالات المناسبة عبر وظيفة fallback. قراءة/كتابة [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // الحصول على مجموعة قواعد فارغة أو مبدئية من FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // إضافة قواعد إلى المجموعة
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // أو 
>      // تهيئة نسخة جديدة من مجموعة القواعد
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // إضافة قواعد إلى المجموعة
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // واستبدال المجموعة الموجودة بالجديدة في FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public final IFontData[] getFonts()
```

تُرجع الخطوط المستخدمة في العرض التقديمي

**الإرجاع:**
com.aspose.slides.IFontData[] - مصفوفة من الخطوط
### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

يحصل على المعلومات عن الخطوط التي سيتم استبدالها عند تصيير العرض التقديمي.

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

يحصل على المعلومات عن الخطوط التي سيتم استبدالها أثناء تصيير الشرائح المحددة.

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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| slides | int[] | مصفوفة من فهارس الشرائح التي يجب استرجاع معلومات استبدال الخطوط لها، بدءاً من 1. |

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - مجموعة من جميع استبدالات الخطوط ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) للشرائح المحددة.
### getPreferRegisteredFontsOverEmbedded() {#getPreferRegisteredFontsOverEmbedded--}
```
public final boolean getPreferRegisteredFontsOverEmbedded()
```

يحدد ما إذا كان يجب تفضيل الخطوط المسجلة على الخطوط المدمجة التي لها نفس اسم الخط والنمط. عندما يكون مفعلاً، يتم استبدال الخطوط المدمجة المتطابقة مؤقتًا بالخطوط المسجلة المقابلة أثناء التصدير.

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

القيمة الافتراضية هي **false**.

**الإرجاع:**
boolean
### setPreferRegisteredFontsOverEmbedded(boolean value) {#setPreferRegisteredFontsOverEmbedded-boolean-}
```
public final void setPreferRegisteredFontsOverEmbedded(boolean value)
```

يحدد ما إذا كان يجب تفضيل الخطوط المسجلة على الخطوط المدمجة التي لها نفس اسم الخط والنمط. عندما يكون مفعلاً، يتم استبدال الخطوط المدمجة المتطابقة مؤقتًا بالخطوط المسجلة المقابلة أثناء التصدير.

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

القيمة الافتراضية هي **false**.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```

تُرجع الخطوط المدمجة في العرض التقديمي

**الإرجاع:**
com.aspose.slides.IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```

يزيل الخط المدمج

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

يضيف الخط المدمج

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

يضيف الخط المدمج

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```

استبدال الخط في العرض التقديمي

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | الخط المصدر |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | الخط الوجهة |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```

استبدال الخط في العرض التقديمي باستخدام المعلومات المقدمة في [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | معلومات استبدال الخط |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```

استبدال الخط في العرض التقديمي باستخدام المعلومات المقدمة في مجموعة [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | مجموعة قواعد استبدال الخط |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```

يسترجع مصفوفة البايت التي تمثل بيانات الخط لنمط خط محدد وبيانات الخط.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // استرجاع جميع الخطوط المستخدمة في العرض التقديمي
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // احصل على مصفوفة البايت التي تمثل النمط العادي لأول خط في العرض التقديمي
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | كائن بيانات الخط الذي يحتوي على المعلومات حول الخط [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | نمط الخط الذي يجب استرجاع البيانات له [FontStyleType](../../com.aspose.slides/fontstyletype). |

**الإرجاع:**
byte[] - مصفوفة بايت تحتوي على بيانات الخط للنمط المحدد. إذا لم يتم العثور على بيانات الخط أو النمط، تُرجع null.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

يحدد مستوى دمج الخط من مصفوفة البايت المعطاة واسم الخط.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // استرجاع جميع الخطوط المستخدمة في العرض التقديمي
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // احصل على مصفوفة البايت التي تمثل النمط العادي للخط الأول في العرض التقديمي
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
>      // تحديد مستوى دمج الخط
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontBytes | byte[] | مصفوفة البايت التي تحتوي على بيانات الخط. |
| fontName | java.lang.String | اسم الخط. |

**الإرجاع:**
int - مستوى دمج الخط المحدد.