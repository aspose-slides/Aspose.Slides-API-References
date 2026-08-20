---
title: BaseSlide
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل البيانات المشتركة لجميع أنواع الشرائح.
type: docs
url: /ar/com.aspose.slides/baseslide/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

يمثل البيانات المشتركة لجميع أنواع الشرائح.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getShapes()](#getShapes--) | يعيد الأشكال في الشريحة. |
| [getControls()](#getControls--) | يعيد مجموعة عناصر التحكم ActiveX في شريحة. |
| [getName()](#getName--) | يعيد أو يعيّن اسم الشريحة. |
| [setName(String value)](#setName-java.lang.String-) | يعيد أو يعيّن اسم الشريحة. |
| [getSlideId()](#getSlideId--) | يعيد معرّف الشريحة. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | يحدد ما إذا كانت كائني IBaseSlide متساويين. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | ينضمّ القطاعات ذات التنسيق نفسه في جميع الفقرات في جميع الأشكال المقبولة. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | ينضمّ القطاعات ذات التنسيق نفسه في جميع الفقرات في جميع الأشكال المقبولة. |
| [createThemeEffective()](#createThemeEffective--) | يعيد سمة فعالة لهذه الشريحة. |
| [getCustomData()](#getCustomData--) | يعيد البيانات المخصصة للشريحة. |
| [getTimeline()](#getTimeline--) | يعيد كائن خط الزمن للرسوم المتحركة. |
| [getSlideShowTransition()](#getSlideShowTransition--) | يعيد كائن الانتقال الذي يحتوي على معلومات حول كيفية تقدم الشريحة المحددة أثناء عرض الشرائح. |
| [getBackground()](#getBackground--) | يعيد خلفية الشريحة. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | يوفر وصولًا سهلاً إلى الروابط التشعبية المضمنة. |
| [getShowMasterShapes()](#getShowMasterShapes--) | يحدد ما إذا كان يجب إظهار الأشكال على الشريحة الرئيسية على الشرائح أم لا. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | يحدد ما إذا كان يجب إظهار الأشكال على الشريحة الرئيسية على الشرائح أم لا. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | يجد أول ظهور لشكل بالنص البديل المحدد. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | يعيد واجهة IPresentation. |
| [getSlide()](#getSlide--) |  |

### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

يعيد الأشكال في شريحة. قراءة فقط [IShapeCollection](../../com.aspose.slides/ishapecollection).

**الإرجاع:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```

يعيد مجموعة عناصر التحكم ActiveX في شريحة. قراءة فقط [IControlCollection](../../com.aspose.slides/icontrolcollection).

**الإرجاع:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public String getName()
```

يعيد أو يعيّن اسم الشريحة. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

يعيد أو يعيّن اسم الشريحة. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```

يعيد معرّف الشريحة. قراءة فقط long.

**الإرجاع:**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```

يحدد ما إذا كانت كائنتا IBaseSlide متساويتين. تُحسب القيمة المرجعة بناءً على بنية الشريحة والمحتوى الثابت. تكون الشريحتان متساويتين إذا كانت جميع الأشكال والأنماط والنصوص والرسوم المتحركة والإعدادات الأخرى ... متساوية. لا تأخذ المقارنة في الاعتبار قيم المعرف الفريدة، مثل SlideId، والمحتوى الديناميكي، مثل قيمة التاريخ الحالية في Date Placeholder.

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
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | شريحة IBaseSlide للمقارنة مع الـ IBaseSlide الحالي. |

**الإرجاع:**
boolean -  **true**  إذا كان الـ IBaseSlide المحدد يساوي الـ IBaseSlide الحالي؛ وإلا **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

ينضمّ القطاعات ذات التنسيق نفسه في جميع الفقرات في جميع الأشكال المقبولة.

### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```

ينضمّ القطاعات ذات التنسيق نفسه في جميع الفقرات في جميع الأشكال المقبولة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

يعيد سمة فعالة لهذه الشريحة.

**الإرجاع:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

يعيد البيانات المخصصة للشريحة. قراءة فقط [ICustomData](../../com.aspose.slides/icustomdata).

**الإرجاع:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```

يعيد كائن خط الزمن للرسوم المتحركة. قراءة فقط [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**الإرجاع:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```

يعيد كائن الانتقال الذي يحتوي على معلومات حول كيفية تقدم الشريحة المحددة أثناء عرض الشرائح. قراءة فقط [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**الإرجاع:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```

يعيد خلفية الشريحة. قراءة فقط [IBackground](../../com.aspose.slides/ibackground).

**الإرجاع:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

يوفر وصولًا سهلاً إلى الروابط التشعبية المضمنة. قراءة فقط [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**الإرجاع:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

يحدد ما إذا كان يجب إظهار الأشكال على الشريحة الرئيسية على الشرائح أم لا. بالنسبة للشريحة الرئيسية نفسها تُعيد هذه الخاصية دائمًا false. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

يحدد ما إذا كان يجب إظهار الأشكال على الشريحة الرئيسية على الشرائح أم لا. بالنسبة للشريحة الرئيسية نفسها تُعيد هذه الخاصية دائمًا false. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```

يجد أول ظهور لشكل بالنص البديل المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| altText | java.lang.String | النص البديل. |

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape) - Shape object أو null.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يعيد كائن Parent_Immediate. قراءة فقط IDOMObject.

**الإرجاع:**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يعيد واجهة IPresentation. قراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**الإرجاع:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يعيد الشريحة الأساس. قراءة فقط [IBaseSlide](../../com.aspose.slides/ibaseslide).

**الإرجاع:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)