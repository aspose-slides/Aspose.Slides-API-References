---
title: SmartArtNode
second_title: Aspose.Slides لأندرويد عبر مرجع API لجافا
description: يمثل عقدة لكائن SmartArt
type: docs
url: /ar/com.aspose.slides/smartartnode/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)  
```
public final class SmartArtNode implements ISmartArtNode
```

يمثل عقدة لكائن SmartArt object
## Methods

| Method | Description |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | يرجع مجموعة جميع العقد الفرعية للعقدة الحالية. |
| [getShapes()](#getShapes--) | يرجع مجموعة جميع الأشكال المرتبطة بالعقدة. |
| [getTextFrame()](#getTextFrame--) | يرجع إطار النص للعقدة. |
| [isAssistant()](#isAssistant--) | يرجع أو يعيّن العقدة كمساعد. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | يرجع أو يعيّن العقدة كمساعد. |
| [getLevel()](#getLevel--) | يرجع مستوى التداخل للعقدة. |
| [getBulletFillFormat()](#getBulletFillFormat--) | يرجع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة لتعداد النقاط في العقدة. |
| [getPosition()](#getPosition--) | يرجع أو يعيّن موقع العقدة بصفر أساسي بين العقد الشقيقة. |
| [setPosition(int value)](#setPosition-int-) | يرجع أو يعيّن موقع العقدة بصفر أساسي بين العقد الشقيقة. |
| [isHidden()](#isHidden--) | يرجع true إذا كانت هذه العقدة عقدة مخفية في نموذج البيانات. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | يرجع أو يعيّن نوع تخطيط مخطط المؤسسة المرتبط بالعقدة الحالية. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | يرجع أو يعيّن نوع تخطيط مخطط المؤسسة المرتبط بالعقدة الحالية. |
| [remove()](#remove--) | إزالة العقدة الحالية. |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```

يرجع مجموعة جميع العقد الفرعية للعقدة الحالية. للقراءة فقط [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Returns:**  
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```

يرجع مجموعة جميع الأشكال المرتبطة بالعقدة. للقراءة فقط [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Returns:**  
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

يرجع إطار النص للعقدة. للقراءة فقط [ITextFrame](../../com.aspose.slides/itextframe).

**Returns:**  
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```

يرجع أو يعيّن العقدة كمساعد. قابل للقراءة والكتابة boolean.

**Returns:**  
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```

يرجع أو يعيّن العقدة كمساعد. قابل للقراءة والكتابة boolean.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public final int getLevel()
```

يرجع مستوى التداخل للعقدة. للقراءة فقط int.

**Returns:**  
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```

يرجع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة لتعداد النقاط في العقدة. ملاحظة: قد يرجع null لبعض أنواع تخطيط SmartArt التي لا توفر تعداد نقاط للعقد. للقراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**  
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

يرجع أو يعيّن موقع العقدة بصفر أساسي بين العقد الشقيقة. قابل للقراءة والكتابة int.

**Returns:**  
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

يرجع أو يعيّن موقع العقدة بصفر أساسي بين العقد الشقيقة. قابل للقراءة والكتابة int.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

يرجع true إذا كانت هذه العقدة عقدة مخفية في نموذج البيانات. للقراءة فقط boolean.

**Returns:**  
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```

يرجع أو يعيّن نوع تخطيط مخطط المؤسسة المرتبط بالعقدة الحالية. قابل للقراءة والكتابة [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Returns:**  
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```

يرجع أو يعيّن نوع تخطيط مخطط المؤسسة المرتبط بالعقدة الحالية. قابل للقراءة والكتابة [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public final boolean remove()
```

إزالة العقدة الحالية.

**Returns:**  
boolean - true إذا تم الإزالة بنجاح، وإلا false