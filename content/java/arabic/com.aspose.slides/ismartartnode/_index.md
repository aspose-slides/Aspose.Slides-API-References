---
title: ISmartArtNode
second_title: Aspose.Slides for Java API Reference
description: تمثّل عقدة من مخطط SmartArt.
type: docs
url: /ar/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

تمثّل عقدة من مخطط SmartArt.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | يُعيد مجموعات جميع العقد الفرعية للعقدة الحالية. |
| [getShapes()](#getShapes--) | يُعيد مجموعات جميع الأشكال المرتبطة بالعقدة. |
| [getTextFrame()](#getTextFrame--) | يُعيد أو يعيّن نص العقدة. |
| [isAssistant()](#isAssistant--) | يُعيد أو يعيّن العقدة كمساعد. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | يُعيد أو يعيّن العقدة كمساعد. |
| [getLevel()](#getLevel--) | يُعيد مستوى التعشيق للعقدة. |
| [getBulletFillFormat()](#getBulletFillFormat--) | يُعيد كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة لنقطة التعداد الخاصة بالعقدة. |
| [getPosition()](#getPosition--) | يُعيد أو يعيّن موضع الصفر الأساسي للعقدة بين العقد الشقيقة. |
| [setPosition(int value)](#setPosition-int-) | يُعيد أو يعيّن موضع الصفر الأساسي للعقدة بين العقد الشقيقة. |
| [isHidden()](#isHidden--) | يُعيد true إذا كانت هذه العقدة عقدة مخفية في نموذج البيانات. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | يُعيد أو يعيّن نوع تخطيط مخطط المنظمة المرتبط بالعقدة الحالية. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | يُعيد أو يعيّن نوع تخطيط مخطط المنظمة المرتبط بالعقدة الحالية. |
| [remove()](#remove--) | إزالة العقدة الحالية. |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```

يُعيد مجموعات جميع العقد الفرعية للعقدة الحالية. للقراءة فقط [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**القيمة المرجعة:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```

يُعيد مجموعات جميع الأشكال المرتبطة بالعقدة. للقراءة فقط [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**القيمة المرجعة:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

يُعيد أو يعيّن نص العقدة. للقراءة فقط [ITextFrame](../../com.aspose.slides/itextframe).

**القيمة المرجعة:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```

يُعيد أو يعيّن العقدة كمساعد. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```

يُعيد أو يعيّن العقدة كمساعد. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```

يُعيد مستوى التعشيق للعقدة. للقراءة فقط int.

**القيمة المرجعة:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```

يُعيد كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة لنقطة التعداد الخاصة بالعقدة. ملاحظة: قد يُعيد null لأنواع معينة من تخطيط SmartArt التي لا توفر نقاط تعداد للعقد. للقراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

**القيمة المرجعة:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

يُعيد أو يعيّن موضع الصفر الأساسي للعقدة بين العقد الشقيقة. قراءة/كتابة int.

**القيمة المرجعة:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

يُعيد أو يعيّن موضع الصفر الأساسي للعقدة بين العقد الشقيقة. قراءة/كتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

يُعيد true إذا كانت هذه العقدة عقدة مخفية في نموذج البيانات. للقراءة فقط boolean.

**القيمة المرجعة:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```

يُعيد أو يعيّن نوع تخطيط مخطط المنظمة المرتبط بالعقدة الحالية. قراءة/كتابة [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**القيمة المرجعة:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```

يُعيد أو يعيّن نوع تخطيط مخطط المنظمة المرتبط بالعقدة الحالية. قراءة/كتابة [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```

إزالة العقدة الحالية.

**القيمة المرجعة:**
boolean - true إذا تم الإزالة بنجاح، وإلا false.