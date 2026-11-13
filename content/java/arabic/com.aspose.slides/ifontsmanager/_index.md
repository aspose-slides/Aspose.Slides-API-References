---
title: IFontsManager
second_title: Aspose.Slides لـ Java دليل API
description: يدير الخطوط عبر العرض التقديمي.
type: docs
url: /ar/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

يدير الخطوط عبر العرض التقديمي.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | استبدالات الخط للاستخدام عند العرض قراءة/كتابة [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | استبدالات الخط للاستخدام عند العرض قراءة/كتابة [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | تمثّل مجموعة المستخدم من قواعد FontFallBack لإدارة مجموعات الخطوط للاستبدالات الصحيحة عبر وظيفة fallback قراءة/كتابة [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | تمثّل مجموعة المستخدم من قواعد FontFallBack لإدارة مجموعات الخطوط للاستبدالات الصحيحة عبر وظيفة fallback قراءة/كتابة [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | إرجاع الخطوط المستخدمة في العرض التقديمي |
| [getSubstitutions()](#getSubstitutions--) | الحصول على معلومات حول الخطوط التي سيتم استبدالها عند عرض الشرائح. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | الحصول على معلومات حول الخطوط التي سيتم استبدالها أثناء عرض الشرائح المحددة. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | إرجاع الخطوط المدمجة في العرض التقديمي |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | إزالة الخط المدمج |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | إضافة الخط المدمج. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | إضافة الخط المدمج |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | استبدال الخط في العرض التقديمي |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | استبدال الخط في العرض التقديمي باستخدام المعلومات المقدمة في [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | استبدال الخط في العرض التقديمي باستخدام المعلومات المقدمة في مجموعة [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | استرجاع مصفوفة البايت التي تمثّل بيانات الخط لنمط خط محدد وبيانات الخط. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | تحديد مستوى تضمين الخط من مصفوفة البايت واسم الخط المعطى. |
| [getPreferRegisteredFontsOverEmbedded()](#getPreferRegisteredFontsOverEmbedded--) | تحديد ما إذا كان يجب تفضيل الخطوط المسجلة على الخطوط المدمجة ذات الاسم والنمط نفسه. |
| [setPreferRegisteredFontsOverEmbedded(boolean value)](#setPreferRegisteredFontsOverEmbedded-boolean-) | تحديد ما إذا كان يجب تفضيل الخطوط المسجلة على الخطوط المدمجة ذات الاسم والنمط نفسه. |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

استبدالات الخط للاستخدام عند العرض قراءة/كتابة [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**الإرجاع:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

استبدالات الخط للاستخدام عند العرض قراءة/كتابة [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

تمثّل مجموعة المستخدم من قواعد FontFallBack لإدارة مجموعات الخطوط للاستبدالات الصحيحة عبر وظيفة fallback قراءة/كتابة [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // الحصول على مجموعة القواعد الفارغة أو المبدئية من FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // إضافة القواعد إلى المجموعة
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // أو 
>      // تهيئة نسخة جديدة من مجموعة القواعد
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // إضافة القواعد إلى المجموعة
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // واستبدال المجموعة الحالية بالجديدة في FontsManager 
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
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

تمثّل مجموعة المستخدم من قواعد FontFallBack لإدارة مجموعات الخطوط للاستبدالات الصحيحة عبر وظيفة fallback قراءة/كتابة [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // جلب مجموعة القواعد الفارغة أو المبدئية من FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // إضافة القواعد إلى المجموعة
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // أو 
>      // تهيئة نسخة جديدة من مجموعة القواعد
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // إضافة القواعد إلى المجموعة
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // و استبدال المجموعة الحالية بالجديدة في FontsManager 
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
public abstract IFontData[] getFonts()
```

إرجاع الخطوط المستخدمة في العرض التقديمي

**الإرجاع:**
com.aspose.slides.IFontData[] - مصفوفة من الخطوط

### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

الحصول على معلومات حول الخطوط التي سيتم استبدالها عند عرض الشرائح.

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
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - مجموعة جميع استبدالات الخطوط [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

الحصول على معلومات حول الخطوط التي سيتم استبدالها أثناء عرض الشرائح المحددة.

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
| slides | int[] | مصفوفة من فهارس الشرائح التي يجب استرجاع معلومات استبدال الخط لها، تبدأ من 1. |

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - مجموعة جميع استبدالات الخط ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) للشرائح المحددة.

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

إرجاع الخطوط المدمجة في العرض التقديمي

**الإرجاع:**
com.aspose.slides.IFontData[] - الخطوط المدمجة IFontData[]

### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

إزالة الخط المدمج

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | كائن بيانات الخط [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

إضافة الخط المدمج.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | كائن بيانات الخط [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | قاعدة الخط المدمج [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

ضع في اعتبارك عند نسخ أي خطوط أن معظم الخطوط محمية بحقوق الطبع والنشر. ابحث أولاً عن ترخيص الخط وتأكد من إمكانية نقلها بحرية إلى جهاز آخر. |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

إضافة الخط المدمج

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontData | byte[] | بيانات الخط byte[] |
| embedFontRule | int | قاعدة الخط المدمج [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

ضع في اعتبارك عند إضافة أي خطوط أن معظم الخطوط محمية بحقوق الطبع والنشر. ابحث أولاً عن ترخيص الخط وتأكد من إمكانية نقلها بحرية إلى جهاز آخر. |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

استبدال الخط في العرض التقديمي

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | الخط المصدر |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | الخط الهدف |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```

استبدال الخط في العرض التقديمي باستخدام المعلومات المقدمة في [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | معلومات استبدال الخط |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

استبدال الخط في العرض التقديمي باستخدام المعلومات المقدمة في مجموعة [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | مجموعة معلومات استبدال الخط |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

استرجاع مصفوفة البايت التي تمثّل بيانات الخط لنمط خط محدد وبيانات الخط.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // استرجاع جميع الخطوط المستخدمة في العرض التقديمي
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // الحصول على مصفوفة البايت التي تمثل النمط العادي للخط الأول في العرض التقديمي
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | كائن بيانات الخط الذي يحتوي على معلومات الخط [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | نمط الخط الذي يجب استرجاع بياناته [FontStyleType](../../com.aspose.slides/fontstyletype). |

**الإرجاع:**
byte[] - مصفوفة بايت تحتوي على بيانات الخط للنمط المحدد. إذا لم يُعثر على بيانات الخط أو النمط، تُرجع null.

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

تحديد مستوى تضمين الخط من مصفوفة البايت واسم الخط المعطى.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // استرجاع جميع الخطوط المستخدمة في العرض التقديمي
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // الحصول على مصفوفة البايت التي تمثل النمط العادي للخط الأول في العرض التقديمي
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // تحديد مستوى تضمين الخط
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
int - مستوى تضمين الخط المحدد.

### getPreferRegisteredFontsOverEmbedded() {#getPreferRegisteredFontsOverEmbedded--}
```
public abstract boolean getPreferRegisteredFontsOverEmbedded()
```

تحديد ما إذا كان يجب تفضيل الخطوط المسجلة على الخطوط المدمجة ذات الاسم والنمط نفسه. عند التفعيل، تُستبدل الخطوط المدمجة المتطابقة مؤقتًا بالخطوط المسجلة المقابلة أثناء التصدير.

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
public abstract void setPreferRegisteredFontsOverEmbedded(boolean value)
```

تحديد ما إذا كان يجب تفضيل الخطوط المسجلة على الخطوط المدمجة ذات الاسم والنمط نفسه. عند التفعيل، تُستبدل الخطوط المدمجة المتطابقة مؤقتًا بالخطوط المسجلة المقابلة أثناء التصدير.

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