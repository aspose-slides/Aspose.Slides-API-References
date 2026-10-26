---
title: ISmartArtNode
second_title: Aspose.Slides for Android via Java API Reference
description: تمثّل عقدة في مخطط SmartArt.
type: docs
url: /ar/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

تمثّل عقدة في مخطط SmartArt.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | إرجاع مجموعة من جميع العقد الفرعية للعقدة الحالية. |
| [getShapes()](#getShapes--) | إرجاع مجموعة من جميع الأشكال المرتبطة بالعقدة. |
| [getTextFrame()](#getTextFrame--) | إرجاع أو تعيين نص العقدة. |
| [isAssistant()](#isAssistant--) | إرجاع أو تعيين ما إذا كانت العقدة مساعدة. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | إرجاع أو تعيين ما إذا كانت العقدة مساعدة. |
| [getLevel()](#getLevel--) | إرجاع مستوى التعشيق للعقدة. |
| [getBulletFillFormat()](#getBulletFillFormat--) | إرجاع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة لنقطة قائمة العقدة. |
| [getPosition()](#getPosition--) | إرجاع أو تعيين الموضع الصفري القائم على الفهرس للعقدة بين العقود الشقيقة. |
| [setPosition(int value)](#setPosition-int-) | إرجاع أو تعيين الموضع الصفري القائم على الفهرس للعقدة بين العقود الشقيقة. |
| [isHidden()](#isHidden--) | إرجاع true إذا كانت هذه العقدة عقدة مخفيّة في نموذج البيانات. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | إرجاع أو تعيين نوع تخطيط مخطط المؤسسة المرتبط بالعقدة الحالية. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | إرجاع أو تعيين نوع تخطيط مخطط المؤسسة المرتبط بالعقدة الحالية. |
| [remove()](#remove--) | إزالة العقدة الحالية. |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```

إرجاع مجموعة من جميع العقد الفرعية للعقدة الحالية. قراءة فقط [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**القيمة المرجعة:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```

إرجاع مجموعة من جميع الأشكال المرتبطة بالعقدة. قراءة فقط [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**القيمة المرجعة:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

إرجاع أو تعيين نص العقدة. قراءة فقط [ITextFrame](../../com.aspose.slides/itextframe).

**القيمة المرجعة:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```

إرجاع أو تعيين ما إذا كانت العقدة مساعدة. قراءة/كتابة منطقية.

**القيمة المرجعة:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```

إرجاع أو تعيين ما إذا كانت العقدة مساعدة. قراءة/كتابة منطقية.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```

إرجاع مستوى التعشيق للعقدة. قراءة فقط int.

**القيمة المرجعة:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```

إرجاع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة لنقطة قائمة العقدة. ملاحظة: قد يُرجع null لأنواع معينة من تخطيطات SmartArt التي لا توفر نقاطًا للعقد. قراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

**القيمة المرجعة:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

إرجاع أو تعيين الموضع الصفري القائم على الفهرس للعقدة بين العقود الشقيقة. قراءة/كتابة int.

**القيمة المرجعة:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

إرجاع أو تعيين الموضع الصفري القائم على الفهرس للعقدة بين العقود الشقيقة. قراءة/كتابة int.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

إرجاع true إذا كانت هذه العقدة عقدة مخفيّة في نموذج البيانات. قراءة فقط منطقية.

**القيمة المرجعة:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```

إرجاع أو تعيين نوع تخطيط مخطط المؤسسة المرتبط بالعقدة الحالية. قراءة/كتابة [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**القيمة المرجعة:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```

إرجاع أو تعيين نوع تخطيط مخطط المؤسسة المرتبط بالعقـدة الحالية. قراءة/كتابة [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```

إزالة العقدة الحالية.

**القيمة المرجعة:**
boolean - true إذا تم الإزالة بنجاح، وإلا false.