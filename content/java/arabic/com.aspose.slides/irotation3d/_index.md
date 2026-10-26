---
title: IRotation3D
second_title: Aspose.Slides for Java API Reference
description: يمثل دوران ثلاثي الأبعاد لمخطط.
type: docs
url: /ar/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

يمثل دوران ثلاثي الأبعاد لمخطط.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getRotationX()](#getRotationX--) | تُعيد أو تُعيّن درجة الدوران حول المحور X، أي |
| [setRotationX(byte value)](#setRotationX-byte-) | تُعيد أو تُعيّن درجة الدوران حول المحور X، أي |
| [getRotationY()](#getRotationY--) | تُعيد أو تُعيّن درجة الدوران حول المحور Y، أي |
| [setRotationY(int value)](#setRotationY-int-) | تُعيد أو تُعيّن درجة الدوران حول المحور Y، أي |
| [getPerspective()](#getPerspective--) | تُعيد أو تُعيّن قيمة المنظور (زاوية مجال الرؤية) للمخططات ثلاثية الأبعاد (بين 0 و 100). |
| [setPerspective(byte value)](#setPerspective-byte-) | تُعيد أو تُعيّن قيمة المنظور (زاوية مجال الرؤية) للمخططات ثلاثية الأبعاد (بين 0 و 100). |
| [getRightAngleAxes()](#getRightAngleAxes--) | يحدد ما إذا كانت محاور المخطط قائمة بزاوية 90 درجة، بدلاً من رسمها بمنظور. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | يحدد ما إذا كانت محاور المخطط قائمة بزاوية 90 درجة، بدلاً من رسمها بمنظور. |
| [getDepthPercents()](#getDepthPercents--) | تُعيد أو تُعيّن عمق المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 20 و 2000 بالمئة). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | تُعيد أو تُعيّن عمق المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 20 و 2000 بالمئة). |
| [getHeightPercents()](#getHeightPercents--) | تحدد ارتفاع المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 5 و 500 بالمئة). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | تحدد ارتفاع المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 5 و 500 بالمئة). |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

تُعيد أو تُعيّن درجة الدوران حول المحور X، أي في اتجاه Y للمخططات ثلاثية الأبعاد (بين -90 و 90 درجة). تتطابق الخاصية مع العنصر rotX (X Rotation) في ECMA-376 ومع خيار "Y Rotation" في PowerPoint 2007+. قراءة/كتابة byte.

**القيمة المرجعة:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

تُعيد أو تُعيّن درجة الدوران حول المحور X، أي في اتجاه Y للمخططات ثلاثية الأبعاد (بين -90 و 90 درجة). تتطابق الخاصية مع العنصر rotX (X Rotation) في ECMA-376 ومع خيار "Y Rotation" في PowerPoint 2007+. قراءة/كتابة byte.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

تُعيد أو تُعيّن درجة الدوران حول المحور Y، أي في اتجاه X للمخططات ثلاثية الأبعاد (بين 0 و 360 درجة). تتطابق الخاصية مع العنصر rotY (Y Rotation) في ECMA-376 ومع خيار "X Rotation" في PowerPoint 2007+. قراءة/كتابة int.

**القيمة المرجعة:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

تُعيد أو تُعيّن درجة الدوران حول المحور Y، أي في اتجاه X للمخططات ثلاثية الأبعاد (بين 0 و 360 درجة). تتطابق الخاصية مع العنصر rotY (Y Rotation) في ECMA-376 ومع خيار "X Rotation" في PowerPoint 2007+. قراءة/كتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

تُعيد أو تُعيّن قيمة المنظور (زاوية مجال الرؤية) للمخططات ثلاثية الأبعاد (بين 0 و 100). يتم التجاهل إذا كانت قيمة الخاصية RightAngleAxes صحيحة. قراءة/كتابة byte.

**القيمة المرجعة:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

تُعيد أو تُعيّن قيمة المنظور (زاوية مجال الرؤية) للمخططات ثلاثية الأبعاد (بين 0 و 100). يتم التجاهل إذا كانت قيمة الخاصية RightAngleAxes صحيحة. قراءة/كتابة byte.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

يحدد ما إذا كانت محاور المخطط قائمة بزاوية 90 درجة، بدلاً من رسمها بمنظور. بمعنى آخر يحدد ما إذا كانت زوايا محاور المخطط مستقلة عن دوران أو ارتفاع المخطط. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

يحدد ما إذا كانت محاور المخطط قائمة بزاوية 90 درجة، بدلاً من رسمها بمنظور. بمعنى آخر يحدد ما إذا كانت زوايا محاور المخطط مستقلة عن دوران أو ارتفاع المخطط. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

تُعيد أو تُعيّن عمق المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 20 و 2000 بالمئة). قراءة/كتابة int.

**القيمة المرجعة:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

تُعيد أو تُعيّن عمق المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 20 و 2000 بالمئة). قراءة/كتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

تحدد ارتفاع المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 5 و 500 بالمئة). قراءة/كتابة int.

**القيمة المرجعة:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

تحدد ارتفاع المخطط ثلاثي الأبعاد كنسبة مئوية من عرض المخطط (بين 5 و 500 بالمئة). قراءة/كتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |