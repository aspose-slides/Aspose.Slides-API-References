---
title: SmartArtNode
second_title: Aspose.Slides للـ Java مرجع API
description: يمثل عقدة لكائن SmartArt
type: docs
url: /ar/com.aspose.slides/smartartnode/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُنفذة:**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

يمثل عقدة لكائن SmartArt
## الأساليب

| Method | Description |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | يرجع مجموعة من جميع عقد الأطفال للعقدة الحالية. |
| [getShapes()](#getShapes--) | يرجع مجموعة من جميع الأشكال المرتبطة بالعقدة. |
| [getTextFrame()](#getTextFrame--) | يرجع إطار النص للعقدة. |
| [isAssistant()](#isAssistant--) | يرجع أو يحدد العقدة كمساعد. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | يرجع أو يحدد العقدة كمساعد. |
| [getLevel()](#getLevel--) | يرجع مستوى التعشيق للعقدة. |
| [getBulletFillFormat()](#getBulletFillFormat--) | يرجع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة لنقطة القائمة في العقدة. |
| [getPosition()](#getPosition--) | يرجع أو يحدد الموقع الصفري للعقدة بين العقد الشقيقة. |
| [setPosition(int value)](#setPosition-int-) | يرجع أو يحدد الموقع الصفري للعقدة بين العقد الشقيقة. |
| [isHidden()](#isHidden--) | يرجع true إذا كانت هذه العقدة عقدة مخفية في نموذج البيانات. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | يرجع أو يحدد نوع تخطيط مخطط التنظيم المرتبط بالعقدة الحالية. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | يرجع أو يحدد نوع تخطيط مخطط التنظيم المرتبط بالعقدة الحالية. |
| [remove()](#remove--) | إزالة العقدة الحالية. |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```


يرجع مجموعة من جميع عقد الأطفال للعقدة الحالية. للقراية فقط [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**الإرجاع:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```


يرجع مجموعة من جميع الأشكال المرتبطة بالعقدة. للقراية فقط [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**الإرجاع:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


يرجع إطار النص للعقدة. للقراية فقط [ITextFrame](../../com.aspose.slides/itextframe).

**الإرجاع:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```


يرجع أو يحدد العقدة كمساعد. قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```


يرجع أو يحدد العقدة كمساعد. قابل للقراءة والكتابة boolean.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLevel() {#getLevel--}
```
public final int getLevel()
```


يرجع مستوى التعشيق للعقدة. للقراية فقط int.

**الإرجاع:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```


يرجع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة لنقطة القائمة في العقدة. ملاحظة: قد يرجع null لبعض أنواع تخطيطات SmartArt التي لا توفر نقاطًا للعقد. للقراية فقط [IFillFormat](../../com.aspose.slides/ifillformat).

**الإرجاع:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


يرجع أو يحدد الموقع الصفري للعقدة بين العقد الشقيقة. قابل للقراءة والكتابة int.

**الإرجاع:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


يرجع أو يحدد الموقع الصفري للعقدة بين العقد الشقيقة. قابل للقراءة والكتابة int.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isHidden() {#isHidden--}
```
public final boolean isHidden()
```


يرجع true إذا كانت هذه العقدة عقدة مخفية في نموذج البيانات. للقراية فقط boolean.

**الإرجاع:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```


يرجع أو يحدد نوع تخطيط مخطط التنظيم المرتبط بالعقدة الحالية. قابل للقراءة والكتابة [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**الإرجاع:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```


يرجع أو يحدد نوع تخطيط مخطط التنظيم المرتبط بالعقدة الحالية. قابل للقراءة والكتابة [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### remove() {#remove--}
```
public final boolean remove()
```


إزالة العقدة الحالية.

**الإرجاع:**
boolean - true إذا تم الإزالة بنجاح، وإلا false