---
title: IBaseSlide
second_title: Aspose.Slides لمرجع API لجافا
description: يمثّل البيانات العامة لجميع أنواع الشرائح.
type: docs
url: /ar/com.aspose.slides/ibaseslide/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

يمثِّل البيانات العامة لجميع أنواع الشرائح.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getShapes()](#getShapes--) | يعيد الأشكال لشريحة. |
| [getControls()](#getControls--) | يعيد مجموعة عناصر تحكم ActiveX على شريحة. |
| [getName()](#getName--) | يعيد أو يضع اسم الشريحة. |
| [setName(String value)](#setName-java.lang.String-) | يعيد أو يضع اسم الشريحة. |
| [getSlideId()](#getSlideId--) | يعيد معرِّف الشريحة. |
| [getCustomData()](#getCustomData--) | يعيد البيانات المخصَّصة للشفرة. |
| [getTimeline()](#getTimeline--) | يعيد كائن جدول الزمن للرسوم المتحركة. |
| [getSlideShowTransition()](#getSlideShowTransition--) | يعيد كائن TransitionEx الذي يحتوي على معلومات حول كيفية تقدم الشريحة المحددة أثناء عرض الشرائح. |
| [getBackground()](#getBackground--) | يعيد خلفية الشريحة. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | يوفر وصولًا سهلاً إلى الروابط التشعبية المتضمنة. |
| [getShowMasterShapes()](#getShowMasterShapes--) | يحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية في الشرائح أم لا. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | يحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية في الشرائح أم لا. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | يجد أول ظهور لشكل يحتوي على النص البديل المحدد. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | يقوم بدمج المقاطع ذات التنسيق نفسه في جميع الفقرات في جميع الأشكال القابلة للقبول. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | يحدد ما إذا كانت مثيلتا IBaseSlide متساويتين. |

### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```

يعيد الأشكال لشريحة. قراءة فقط [IShapeCollection](../../com.aspose.slides/ishapecollection).

**الإرجاع:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)

### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```

يعيد مجموعة عناصر تحكم ActiveX على شريحة. قراءة فقط [IControlCollection](../../com.aspose.slides/icontrolcollection).

**الإرجاع:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)

### getName() {#getName--}
```
public abstract String getName()
```

يعيد أو يضع اسم الشريحة. قراءة/كتابة String.

**الإرجاع:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

يعيد أو يضع اسم الشريحة. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```

يعيد معرِّف الشريحة. قراءة فقط long.

**الإرجاع:**
long

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

يعيد البيانات المخصَّصة للشفرة. قراءة فقط [ICustomData](../../com.aspose.slides/icustomdata).

**الإرجاع:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```

يعيد كائن جدول الزمن للرسوم المتحركة. قراءة فقط [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**الإرجاع:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)

### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```

يعيد كائن TransitionEx الذي يحتوي على معلومات حول كيفية تقدم الشريحة المحددة أثناء عرض الشرائح. قراءة فقط [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**الإرجاع:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)

### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```

يعيد خلفية الشريحة. قراءة فقط [IBackground](../../com.aspose.slides/ibackground).

**الإرجاع:**
[IBackground](../../com.aspose.slides/ibackground)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

يوفر وصولًا سهلاً إلى الروابط التشعبية المتضمنة. قراءة فقط [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**الإرجاع:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

يحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية في الشرائح أم لا. بالنسبة للشريحة الرئيسية نفسها هذه الخاصية دائمًا ما تعيد false. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

يحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية في الشرائح أم لا. بالنسبة للشريحة الرئيسية نفسها هذه الخاصية دائمًا ما تعيد false. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public abstract IShape findShapeByAltText(String altText)
```

يجد أول ظهور لشكل يحتوي على النص البديل المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| altText | java.lang.String | النص البديل. |

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape) - ShapeEx object أو null.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

يقوم بدمج المقاطع ذات التنسيق نفسه في جميع الفقرات في جميع الأشكال القابلة للقبول.

### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```

يحدد ما إذا كانت مثيلتا IBaseSlide متساويتين. يتم حساب القيمة المرجعة بناءً على بنية الشريحة والمحتوى الثابت. تكون الشرائح متساوية إذا كانت جميع الأشكال والأنماط والنصوص والرسوم المتحركة والإعدادات الأخرى، إلخ، متساوية. لا تأخذ المقارنة في الاعتبار قيم المعرف الفريدة، مثل SlideId، والمحتوى الديناميكي، مثل قيمة التاريخ الحالي في عنصر نائب التاريخ.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | الـ IBaseSlide للمقارنة مع الـ IBaseSlide الحالي. |

**الإرجاع:**
boolean - **true** إذا كان الـ IBaseSlide المحدد متساوٍ مع الـ IBaseSlide الحالي؛ وإلا فإن القيمة **false**.