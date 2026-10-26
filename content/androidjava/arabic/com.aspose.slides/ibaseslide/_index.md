---
title: IBaseSlide
second_title: Aspose.Slides للـ Android عبر مرجع واجهة برمجة التطبيقات Java
description: يمثل البيانات العامة لجميع أنواع الشرائح.
type: docs
url: /ar/com.aspose.slides/ibaseslide/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

يمثل البيانات العامة لجميع أنواع الشرائح.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getShapes()](#getShapes--) | يعرض الأشكال في الشريحة. |
| [getControls()](#getControls--) | يعرض مجموعة عناصر التحكم ActiveX في الشريحة. |
| [getName()](#getName--) | يعرض أو يعيّن اسم الشريحة. |
| [setName(String value)](#setName-java.lang.String-) | يعرض أو يعيّن اسم الشريحة. |
| [getSlideId()](#getSlideId--) | يعرض معرف (ID) الشريحة. |
| [getCustomData()](#getCustomData--) | يعرض البيانات المخصصة للشريحة. |
| [getTimeline()](#getTimeline--) | يعرض كائن جدول زمني للرسوم المتحركة. |
| [getSlideShowTransition()](#getSlideShowTransition--) | يعرض كائن TransitionEx الذي يحتوي على معلومات حول كيفية تقدم الشريحة المحددة أثناء عرض الشرائح. |
| [getBackground()](#getBackground--) | يعرض خلفية الشريحة. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | يوفر وصولًا سهلاً إلى الروابط التشعبية المضمنة. |
| [getShowMasterShapes()](#getShowMasterShapes--) | يحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية في الشرائح أم لا. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | يحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية في الشرائح أم لا. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | يبحث عن أول ظهور لشكل يحتوي على النص البديل المحدد. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | يجمع المقاطع ذات التنسيق المتطابق في جميع الفقرات بجميع الأشكال القابلة للاستخدام. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | يحدد ما إذا كان مثليا IBaseSlide المتاين متساويين. |

### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```

يعرض الأشكال في الشريحة. للقراءة فقط [IShapeCollection](../../com.aspose.slides/ishapecollection).

**القيمة المرجعة:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```

يعرض مجموعة عناصر التحكم ActiveX في الشريحة. للقراءة فقط [IControlCollection](../../com.aspose.slides/icontrolcollection).

**القيمة المرجعة:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public abstract String getName()
```

يعرض أو يعيّن اسم الشريحة. للقراءة والكتابة String.

**القيمة المرجعة:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

يعرض أو يعيّن اسم الشريحة. للقراءة والكتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```

يعرض معرف (ID) الشريحة. للقراءة فقط long.

**القيمة المرجعة:**
long
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

يعرض البيانات المخصصة للشريحة. للقراءة فقط [ICustomData](../../com.aspose.slides/icustomdata).

**القيمة المرجعة:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```

يعرض كائن جدول زمني للرسوم المتحركة. للقراءة فقط [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**القيمة المرجعة:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```

يعرض كائن TransitionEx الذي يحتوي على معلومات حول كيفية تقدم الشريحة المحددة أثناء عرض الشرائح. للقراءة فقط [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**القيمة المرجعة:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```

يعرض خلفية الشريحة. للقراءة فقط [IBackground](../../com.aspose.slides/ibackground).

**القيمة المرجعة:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

يوفر وصولًا سهلاً إلى الروابط التشعبية المضمنة. للقراءة فقط [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**القيمة المرجعة:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

يحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية في الشرائح أم لا. بالنسبة إلى الشريحة الرئيسية نفسها، هذه الخاصية دائمًا تُعيد false. للقراءة والكتابة boolean.

**القيمة المرجعة:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

يحدد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية في الشرائح أم لا. بالنسبة إلى الشريحة الرئيسية نفسها، هذه الخاصية دائمًا تُعيد false. للقراءة والكتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public abstract IShape findShapeByAltText(String altText)
```

يبحث عن أول ظهور لشكل يحتوي على النص البديل المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| altText | java.lang.String | النص البديل. |

**القيمة المرجعة:**
[IShape](../../com.aspose.slides/ishape) - كائن ShapeEx أو null.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

يجمع المقاطع ذات التنسيق المتطابق في جميع الفقرات بجميع الأشكال القابلة للاستخدام.

### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```

يحدد ما إذا كان مثليا IBaseSlide المتاين متساويين. يتم حساب القيمة المرجعة بناءً على بنية الشريحة والمحتوى الثابت. تكون الشريحتان متساويتين إذا كانت جميع الأشكال والأنماط والنصوص والرسوم المتحركة والإعدادات الأخرى، إلخ، متساوية. لا تأخذ المقارنة في الاعتبار قيم المعرف الفريدة، مثل SlideId، والمحتوى الديناميكي، مثل قيمة التاريخ الحالي في العنصر النائب Date Placeholder.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | IBaseSlide للمقارنة مع IBaseSlide الحالي. |

**القيمة المرجعة:**
boolean - **true** إذا كان IBaseSlide المحدد مساويًا لـ IBaseSlide الحالي؛ وإلا **false**.