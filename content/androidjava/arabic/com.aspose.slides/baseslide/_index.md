---
title: BaseSlide
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل البيانات المشتركة لجميع أنواع الشرائح.
type: docs
url: /ar/com.aspose.slides/baseslide/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المُنفذة:**  
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner  
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

يمثل البيانات المشتركة لجميع أنواع الشرائح.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getShapes()](#getShapes--) | يرجع أشكال الشريحة. |
| [getControls()](#getControls--) | يرجع مجموعة عناصر تحكم ActiveX في الشريحة. |
| [getName()](#getName--) | يرجع أو يضبط اسم الشريحة. |
| [setName(String value)](#setName-java.lang.String-) | يرجع أو يضبط اسم الشريحة. |
| [getSlideId()](#getSlideId--) | يرجع معرف الشريحة. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | يحدد ما إذا كانت كائنتا IBaseSlide متساويتان. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | ينضم أجزاء النص ذات التنسيق نفسه في جميع الفقرات جميع الأشكال المقبولة. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | ينضم أجزاء النص ذات التنسيق نفسه في جميع الفقرات في جميع الأشكال المقبولة. |
| [createThemeEffective()](#createThemeEffective--) | يرجع سمة فعالة لهذه الشريحة. |
| [getCustomData()](#getCustomData--) | يرجع البيانات المخصصة للشريحة. |
| [getTimeline()](#getTimeline--) | يرجع كائن جدول الزمن للرسوم المتحركة. |
| [getSlideShowTransition()](#getSlideShowTransition--) | يرجع كائن Transition الذي يحتوي على معلومات حول كيفية تقدم الشريحة المحددة خلال عرض الشرائح. |
| [getBackground()](#getBackground--) | يرجع خلفية الشريحة. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | يوفر وصولًا سهلاً إلى الروابط التشعبية المحتواة. |
| [getShowMasterShapes()](#getShowMasterShapes--) | يحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسة في الشرائح أم لا. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | يحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسة في الشرائح أم لا. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | يجد أول ظهور لشكل يحتوي على النص البديل المحدد. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | يرجع واجهة IPresentation. |
| [getSlide()](#getSlide--) |  |

### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

يرجع أشكال الشريحة. للقراءة فقط [IShapeCollection](../../com.aspose.slides/ishapecollection).

**القيمة المرجعة:**  
[IShapeCollection](../../com.aspose.slides/ishapecollection)

### getControls() {#getControls--}
```
public final IControlCollection getControls()
```

يرجع مجموعة عناصر تحكم ActiveX في الشريحة. للقراءة فقط [IControlCollection](../../com.aspose.slides/icontrolcollection).

**القيمة المرجعة:**  
[IControlCollection](../../com.aspose.slides/icontrolcollection)

### getName() {#getName--}
```
public String getName()
```

يرجع أو يضبط اسم الشريحة. قراءة/كتابة String.

**القيمة المرجعة:**  
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

يرجع أو يضبط اسم الشريحة. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```

يرجع معرف الشريحة. للقراءة فقط long.

**القيمة المرجعة:**  
long

### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```

يحدد ما إذا كانت كائنتا IBaseSlide متساويتان. يتم حساب القيمة المرجعة بناءً على بنية الشريحة ومحتواها الثابت. تكون الشريحتان متساويتين إذا كانت جميع الأشكال والأنماط والنصوص والرسوم المتحركة والإعدادات الأخرى، إلخ، متساوية. لا تأخذ المقارنة بعين الاعتبار قيم المعرفات الفريدة مثل SlideId والمحتوى الديناميكي مثل قيمة التاريخ الحالية في العنصر النائب Date Placeholder.

--------------------

> ```
> The following example shows how to compare two slides.
>  
>  Presentation presentation1 = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation presentation2 = new Presentation("HelloWorld.pptx");
>      try {
>          for (int i = 0; i < presentation1.getMasters().size(); i++)
>          {
>              for (int j = 0; j < presentation2.getMasters().size(); j++)
>              {
>                  if (presentation1.getMasters().get_Item(i).equals(presentation2.getMasters().get_Item(j)))
>                      System.out.println(String.format("SomePresentation1 MasterSlide#%d is equal to SomePresentation2 MasterSlide#%d", i, j));
>              }
>          }
>      } finally {
>          if (presentation2 != null) presentation2.dispose();
>      }
>  } finally {
>      if (presentation1 != null) presentation1.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | كائن IBaseSlide للمقارنة مع كائن IBaseSlide الحالي. |

**القيمة المرجعة:**  
boolean - **true** إذا كان كائن IBaseSlide المحدد يساوي كائن IBaseSlide الحالي؛ وإلا **false**.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

ينضم أجزاء النص ذات التنسيق نفسه في جميع الفقرات جميع الأشكال المقبولة.

### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```

ينضم أجزاء النص ذات التنسيق نفسه في جميع الفقرات في جميع الأشكال المقبولة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

يرجع سمة فعالة لهذه الشريحة.

**القيمة المرجعة:**  
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

يرجع البيانات المخصصة للشريحة. للقراءة فقط [ICustomData](../../com.aspose.slides/icustomdata).

**القيمة المرجعة:**  
[ICustomData](../../com.aspose.slides/icustomdata)

### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```

يرجع كائن جدول الزمن للرسوم المتحركة. للقراءة فقط [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**القيمة المرجعة:**  
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)

### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```

يرجع كائن Transition الذي يحتوي على معلومات حول كيفية تقدم الشريحة المحددة خلال عرض الشرائح. للقراءة فقط [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**القيمة المرجعة:**  
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)

### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```

يرجع خلفية الشريحة. للقراءة فقط [IBackground](../../com.aspose.slides/ibackground).

**القيمة المرجعة:**  
[IBackground](../../com.aspose.slides/ibackground)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

يوفر وصولًا سهلاً إلى الروابط التشعبية المحتواة. للقراءة فقط [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**القيمة المرجعة:**  
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

يحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسة في الشرائح أم لا. بالنسبة للشريحة الرئيسة نفسها تُعيد هذه الخاصية دائمًا false. قراءة/كتابة boolean.

**القيمة المرجعة:**  
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

يحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسة في الشرائح أم لا. بالنسبة للشريحة الرئيسة نفسها تُعيد هذه الخاصية دائمًا false. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```

يجد أول ظهور لشكل يحتوي على النص البديل المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| altText | java.lang.String | النص البديل. |

**القيمة المرجعة:**  
[IShape](../../com.aspose.slides/ishape) - كائن Shape أو null.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يرجع كائن Parent_Immediate. للقراءة فقط IDOMObject.

**القيمة المرجعة:**  
com.aspose.slides.IDOMObject

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يرجع واجهة IPresentation. للقراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**القيمة المرجعة:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يرجع الشريحة الأساسية. للقراءة فقط [IBaseSlide](../../com.aspose.slides/ibaseslide).

**القيمة المرجعة:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)